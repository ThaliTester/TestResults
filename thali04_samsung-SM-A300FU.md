#### Test 79896569ef47422_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-26 18:20:01.456  1015  1134 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 18:20:01.456  1015  1134 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 18:20:01.456  1015  1134 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 18:20:01.456  1015  1134 D BatteryService: stay LED for fully charged
08-26 18:20:01.456  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 18:20:01.466  1015  1015 I MotionRecognitionService: Plugged
08-26 18:20:01.466  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-26 18:20:01.466  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 18:20:01.466  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 18:20:01.466  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 18:20:01.466  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 18:20:01.476  3158  3158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 18:20:01.476  3158  3270 D HeadsetStateMachine: Disconnected process message: 10
08-26 18:20:01.496  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 18:20:01.496  1178  1178 D SViewCoverView: level :100 plugged : 2
08-26 18:20:01.496  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 18:20:01.496  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 18:20:01.496  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:02.026  6855  6855 D AndroidRuntime: 
08-26 18:20:02.026  6855  6855 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 18:20:02.026  6855  6855 D AndroidRuntime: CheckJNI is OFF
08-26 18:20:02.026  6855  6855 D AndroidRuntime: readGMSProperty: start
08-26 18:20:02.026  6855  6855 D AndroidRuntime: readGMSProperty: already setted!!
08-26 18:20:02.026  6855  6855 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 18:20:02.026  6855  6855 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 18:20:02.026  6855  6855 D AndroidRuntime: readGMSProperty: end
08-26 18:20:02.026  6855  6855 D AndroidRuntime: addProductProperty: start
08-26 18:20:02.176  6855  6855 E AffinityControl: AffinityControl: registerfunction enter
08-26 18:20:02.206  6855  6855 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 18:20:02.226  1015  1216 E PersonaManagerService: inState():  stateMachine is null !!
08-26 18:20:02.226  1015  1216 I PersonaManagerService: PersonaId don't exist
08-26 18:20:02.226  1015  1216 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 18:20:02.236  1015  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 18:20:02.256  1015  1216 W ActivityManager: mDVFSHelper.acquire()
08-26 18:20:02.256   258   258 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-26 18:20:02.266   258   258 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-26 18:20:02.266  1015  1216 D FocusedStackFrame: Set to : 0
08-26 18:20:02.276  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:02.276  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:02.276  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:02.276  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:02.276  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 18:20:02.276  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 18:20:02.286  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 18:20:02.286  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 18:20:02.296   258   258 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-26 18:20:02.296  6866  6866 E Zygote  : MountEmulatedStorage()
08-26 18:20:02.296  6866  6866 E Zygote  : v2
08-26 18:20:02.296  6866  6866 I libpersona: KNOX_SDCARD checking this for 10171
08-26 18:20:02.296  6866  6866 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:02.306  6866  6866 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:02.306  1015  1216 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6866 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 18:20:02.306  1015  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 18:20:02.306  1015  1216 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 18:20:02.306  1015  1216 D InputDispatcher: Focused application set to: xxxx
08-26 18:20:02.306  1015  1216 D InputDispatcher: Focus left window: 1497
08-26 18:20:02.306  6855  6855 D AndroidRuntime: Shutting down VM
08-26 18:20:02.306  6866  6866 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:02.316  6866  6866 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 18:20:02.336  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 18:20:02.336  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 18:20:02.336  6866  6866 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:02.336  6866  6866 D ActivityThread: Added TimaKeyStore provider
08-26 18:20:02.336  1015  1535 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 18:20:02.346  1015  1015 V ActivityManager: Display changed displayId=0
08-26 18:20:02.346  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 18:20:02.356  1015  1535 D PersonaManager: isKioskContainerExistOnDevice
08-26 18:20:02.376  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 18:20:02.386   258  1101 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-26 18:20:02.386   258  2006 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-26 18:20:02.386  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{349c1d7d token=android.os.BinderProxy@f6c9220 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 18:20:02.396  1497  1497 D Launcher: onTrimMemory. Level: 20
08-26 18:20:02.486  6866  6866 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-26 18:20:02.486   288   288 E SMD     : DCD OFF
08-26 18:20:02.506  6866  6866 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7190-7192)
08-26 18:20:02.506  6866  6866 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 18:20:02.516  6855  6855 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 18:20:02.536  6866  6866 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1f71846b},
,08-26 18:20:02.536  6866  6866 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 18:20:02.536  6866  6866 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
,08-26 18:20:02.586  6866  6866 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 18:20:02.586  6866  6866 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:02.586  6866  6866 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 18:20:02.626  6866  6866 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 18:20:02.626  6866  6866 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 18:20:02.626  6866  6866 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 18:20:02.626  6866  6866 I Adreno-EGL: Local Branch: 
08-26 18:20:02.626  6866  6866 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 18:20:02.626  6866  6866 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 18:20:02.626  6866  6866 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 18:20:02.706  6866  6866 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 18:20:02.716  6866  6866 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 18:20:02.716  6866  6866 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-26 18:20:02.726  6866  6866 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 18:20:02.726  6866  6866 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-26 18:20:02.856  6866  6866 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:02.866  6866  6866 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 18:20:02.866  1015  1040 W ActivityManager: Activity pause timeout for ActivityRecord{275361b u0 com.test.thalitest/.MainActivity t2}
,08-26 18:20:02.876  6866  6866 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 18:20:02.876  6866  6866 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 18:20:02.886  6866  6866 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 18:20:02.886  6866  6866 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:02.886  6866  6866 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:02.966  6866  6907 D OpenGLRenderer: Render dirty regions requested: true
,08-26 18:20:02.966  1015  4518 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 18:20:02.976  1015  4518 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 18:20:02.976  1015  4518 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 18:20:02.976  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 18:20:02.976  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 18:20:02.976  6866  6894 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-26 18:20:02.986  6866  6866 V ActivityThread: updateVisibility : ActivityRecord{3ef1944b token=android.os.BinderProxy@3ab1aa3c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 18:20:02.986  6866  6866 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-26 18:20:02.986  6866  6866 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 18:20:02.996   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-26 18:20:03.006  1015  1512 D InputDispatcher: Focus entered window: 6866,
,08-26 18:20:03.016  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 18:20:03.016  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 18:20:03.016  6866  6866 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 18:20:03.016  6866  6907 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 18:20:03.016  6866  6907 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-26 18:20:03.016  6866  6907 D OpenGLRenderer: Enabling debug mode 0
,08-26 18:20:03.036  1015  1319 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 18:20:03.046  1178  1178 I StatusBar: Icon Only
,08-26 18:20:03.046  1178  1178 D PanelView: There is/are notification(s) 
,08-26 18:20:03.046  1015  6911 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 18:20:03.056  1015  1045 I ActivityManager: Displayed Component not be shown by security: +694ms (total +784ms)
,08-26 18:20:03.056  1015  1045 W ActivityManager: mDVFSHelper.release()
08-26 18:20:03.056  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{275361b u0 com.test.thalitest/.MainActivity t2} time:107749
,08-26 18:20:03.066  6866  6866 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 18:20:03.066  6866  6866 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ab1aa3c time:107754
,08-26 18:20:03.066   258   453 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 18:20:03.066   258  2006 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 18:20:03.076  1879  1879 I SamsungIME: getCurrentCandidateView,
,08-26 18:20:03.186  6866  6866 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6866
,08-26 18:20:03.186  1879  1879 D SamsungIME: Dismiss ExpandCandiate
,08-26 18:20:03.346  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 18:20:03.386  1879  1879 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 18:20:03.396  6866  6866 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 18:20:03.396  1879  1879 I SamsungIME: KeybaordView init() : load resources
,08-26 18:20:03.426  1879  1879 I SamsungIME: getCurrentKeyboard
,08-26 18:20:03.426  1879  1879 I SamsungIME: getTextKeyboard
,08-26 18:20:03.446  1879  1879 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 18:20:03.446  1015  1317 E Watchdog: !@Sync 3
,08-26 18:20:03.476  6866  6913 D jxcore_app_log: JniHelper::setJavaVM(0xb7a252b0), pthread_self() = -1208282776
,08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-26 18:20:03.486  6866  6913 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ca5d79 added. We now have 1 listener(s)
,08-26 18:20:03.486  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
08-26 18:20:03.486  6866  6913 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:03.496  6866  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 18:20:03.496  6866  6913 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-26 18:20:03.496  6866  6913 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2bd21a6c added. We now have 1 listener(s)
08-26 18:20:03.496  6866  6913 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 18:20:03.506  6866  6913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:03.516  6866  6913 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-26 18:20:03.516  6866  6913 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:03.516  6866  6913 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:03.516  6866  6913 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 18:20:03.516  6866  6913 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:03.516  6866  6913 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 18:20:03.516  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:03.526  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:03.546  6866  6866 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 18:20:04.086  6866  6920 W jxcore-log: Initializing JXcore engine
08-26 18:20:04.086  6866  6920 W jxcore-log: JXcore engine is ready
,08-26 18:20:04.136  2008  2008 E audit   : type=1400 msg=audit(1472228404.136:205): avc:  denied  { ioctl } for  pid=6920 comm="Thread-1280" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-26 18:20:04.136  2008  2008 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:04.136  2008  2008 E audit   : type=1300 msg=audit(1472228404.136:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8fb8f8 items=0 ppid=306 ppcomm=main pid=6920 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1280" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 18:20:04.136  2008  2008 E audit   : type=1320 msg=audit(1472228404.136:205): 
,08-26 18:20:04.146  6866  6920 W jxcore-log: Starting JXcore engine
,08-26 18:20:04.256  6866  6920 W jxcore-log: Platform android
08-26 18:20:04.256  6866  6920 W jxcore-log: 
08-26 18:20:04.256  6866  6920 W jxcore-log: Process ARCH arm
08-26 18:20:04.256  6866  6920 W jxcore-log: 
,08-26 18:20:04.466  6866  6920 I jxcore-log: JXcore Cordova bridge is ready!
08-26 18:20:04.466  6866  6920 I jxcore-log: 
,08-26 18:20:04.466  6866  6920 W jxcore-log: JXcore engine is started
,08-26 18:20:04.466  6866  6913 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 18:20:04.476  6866  6866 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 18:20:05.136   326   326 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 18:20:05.136   326   326 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 18:20:05.486   288   288 E SMD     : DCD OFF
,08-26 18:20:08.486   288   288 E SMD     : DCD OFF,
,08-26 18:20:08.546  1015  1047 I PowerManagerService: [PWL] Off : 50s ago,
,08-26 18:20:08.736  1015  3374 D SSRM:n  : SIOP:: AP = 350,
,08-26 18:20:10.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:11.086  5721  5721 D FactoryTest: Not factory mode
,08-26 18:20:11.086  5721  5721 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 18:20:11.086  5721  5721 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-26 18:20:11.086  5721  5721 D MTPRx   : still no open session command from host, so toast
,08-26 18:20:11.096  5721  5721 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-26 18:20:11.096  5721  5721 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 18:20:11.096  5721  5721 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115782
,08-26 18:20:11.096  1015  3406 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 18:20:11.096  1015  3406 I PersonaManagerService: PersonaId don't exist
08-26 18:20:11.096  1015  3406 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 18:20:11.096  1015  3406 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 18:20:11.096  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:11.096  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:11.106  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 18:20:11.106  1015  3406 W ActivityManager: mDVFSHelper.acquire()
,08-26 18:20:11.126  1015  3406 D PersonaManager: isKioskContainerExistOnDevice
,08-26 18:20:11.136  1015  3406 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 18:20:11.136  1015  3406 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 18:20:11.136  1015  3406 D InputDispatcher: Focused application set to: xxxx
,08-26 18:20:11.136  1015  3406 D InputDispatcher: Focus left window: 6866
,08-26 18:20:11.136  5721  5721 E MTPRx   : started activity for popup,
08-26 18:20:11.136  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 18:20:11.136  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 18:20:11.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 18:20:11.166  5721  5721 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:11.196  5721  5721 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 18:20:11.196  1015  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 18:20:11.196  1015  1496 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 18:20:11.196  1015  1496 D InputDispatcher: Focused application set to: xxxx
,08-26 18:20:11.196  1015  1496 D InputDispatcher: Focus entered window: 6866
,08-26 18:20:11.206  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 18:20:11.206  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 18:20:11.206  1015  1496 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-26 18:20:11.206  1015  1496 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3d73033a attribute=null, token = android.os.BinderProxy@2822a38a
,08-26 18:20:11.246  5721  5721 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 18:20:11.256  5721  5721 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 18:20:11.256  5721  5721 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 18:20:11.276  6866  6866 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 18:20:11.276  6866  6866 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 18:20:11.276  6866  6866 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 18:20:11.276  6866  6866 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 18:20:11.276  1015  1495 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 18:20:11.276  1015  1495 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-26 18:20:11.276  1015  1495 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 18:20:11.276  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 18:20:11.276  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 18:20:11.296  6866  6866 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-26 18:20:11.296  6866  6866 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 18:20:11.296  6866  6866 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@156a16f8 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@300ba299, 16908290=android.view.AbsSavedState$1@300ba299}, android:focusedViewId=100}]}]
08-26 18:20:11.296  6866  6866 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 18:20:11.296  6866  6866 V ActivityThread: updateVisibility : ActivityRecord{3ef1944b token=android.os.BinderProxy@3ab1aa3c {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 18:20:11.296  6866  6866 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 18:20:11.296  6866  6866 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 18:20:11.296  6866  6866 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ab1aa3c time:115984
,08-26 18:20:11.306  1015  1512 D PersonaManager: isKioskContainerExistOnDevice
,08-26 18:20:11.496   288   288 E SMD     : DCD OFF
,08-26 18:20:11.516  1015  3406 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 18:20:11.516  1015  3406 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 18:20:11.516  1015  3406 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 18:20:11.516  1015  3406 D BatteryService: stay LED for fully charged
08-26 18:20:11.516  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 18:20:11.516  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 18:20:11.516  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 18:20:11.526  1015  1015 I MotionRecognitionService: Plugged
08-26 18:20:11.526  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false,
,08-26 18:20:11.526  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 18:20:11.526  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 18:20:11.536  3158  3158 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 18:20:11.536  3158  3270 D HeadsetStateMachine: Disconnected process message: 10
,08-26 18:20:11.546  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 18:20:11.546  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 18:20:11.546  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 18:20:11.546  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
08-26 18:20:11.546  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:12.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:12.326  1015  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-26 18:20:13.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:14.106  1015  1040 W ActivityManager: mDVFSHelper.release(),
,08-26 18:20:14.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:14.496   288   288 E SMD     : DCD OFF
,08-26 18:20:15.146   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 18:20:15.316  1015  1094 V AlarmManager: waitForAlarm result :4
08-26 18:20:15.316  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 18:20:15.326  1015  1015 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-26 18:20:15.326  1015  1015 V AlarmManagerEXT: <AppSync3 Whitelist>
,08-26 18:20:15.326  1015  1015 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-26 18:20:15.336  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-26 18:20:15.336  1178  1178 D KeyguardUpdateMonitor: handleTimeUpdate
,08-26 18:20:15.346  1178  1178 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-26 18:20:15.346  1178  1178 D SecKeyguardClockView: HomeTimezone(): 1
,08-26 18:20:15.346  1972  1972 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 18:20:15.386  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 18:20:15.386  1178  1178 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-26 18:20:15.386  1178  1178 I KeyguardEffectViewController: *** don't update sliding image ***
,08-26 18:20:15.396  1178  1178 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-26 18:20:15.416  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 18:20:15.426  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:15.426  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 18:20:15.426  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:15.426  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:15.426  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:15.426  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 18:20:15.446  1178  1178 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-26 18:20:15.466  1178  1178 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-26 18:20:15.466  4869  4869 D ConnectivityManager: CallingUid : 10011, CallingPid : 4869
,08-26 18:20:15.466  1015  3406 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 18:20:15.466  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-26 18:20:15.466  1015  1128 D ConnectivityService: apparently satisfied.  currentScore=60
08-26 18:20:15.466  1015  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 18:20:15.466  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 18:20:15.536  4869  6930 W DriveInitializer: Background init thread started
,08-26 18:20:15.576   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 18:20:15.576   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:15.576  4869  6930 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 18:20:15.606  1972  1972 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-26 18:20:15.666  4869  6930 W DriveInitializer: Background init thread ended
,08-26 18:20:15.766  1015  1216 I art     : Explicit concurrent mark sweep GC freed 28653(1699KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 24MB/36MB, paused 2.475ms total 150.839ms
,08-26 18:20:15.766  1972  1983 I art     : Explicit concurrent mark sweep GC freed 57750(3MB) AllocSpace objects, 18(288KB) LOS objects, 40% free, 10MB/17MB, paused 1.345ms total 70.678ms
,08-26 18:20:15.806  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:15.806  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 18:20:15.816  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:15.816  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:15.816  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:15.836  1015  1512 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-26 18:20:15.836  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 18:20:15.856  1015  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:15.856  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 18:20:15.856  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:15.856  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:15.856  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:15.886  4869  6938 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-26 18:20:15.886  4869  6938 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 18:20:15.906  1972  1972 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 18:20:15.946  1015  1040 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:15.946  1015  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:15.946  1015  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.016  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:16.016  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 18:20:16.026  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.026  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.026  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.056  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-26 18:20:16.056  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 18:20:16.056  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:16.056  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.056  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.096  1015  3406 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.106  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.106  1015  3406 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.106  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.126  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.126  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.126  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 18:20:16.126  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.186  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.186  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.186  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.186  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.186  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:16.186  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:16.186  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:16.186  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:16.206  6943  6943 E Zygote  : MountEmulatedStorage()
08-26 18:20:16.206  6943  6943 E Zygote  : v2
08-26 18:20:16.206  6943  6943 I libpersona: KNOX_SDCARD checking this for 10011
,08-26 18:20:16.206  6943  6943 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:16.206  1015  1027 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6943 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-26 18:20:16.206  6943  6943 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 18:20:16.216  6943  6943 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 18:20:16.216  6943  6943 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 18:20:16.236  6943  6943 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:16.236  6943  6943 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:16.256  6943  6943 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 18:20:16.256  6943  6943 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 18:20:16.296  6943  6943 I MultiDex: VM with version 2.1.0 has multidex support
08-26 18:20:16.296  6943  6943 I MultiDex: install
08-26 18:20:16.296  6943  6943 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 18:20:16.336  6943  6943 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 18:20:16.396  6943  6943 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 18:20:16.396  6943  6943 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@14b4eb17: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 18:20:16.396  6943  6943 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 18:20:16.426  6943  6943 D ChimeraCfgMgr: Reading stored module config
,08-26 18:20:16.466  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 18:20:16.486  1015  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.486  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.486  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.486  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.496  1015  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.496  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.496  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.496  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.516  6943  6960 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 18:20:16.546  6943  6943 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 18:20:16.546  6943  6943 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 18:20:16.556  1972  1972 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=9b6d334e-be79-4b9a-8b22-d4f2e1dc571c
,08-26 18:20:16.556  1015  4518 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 18:20:16.556  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 18:20:16.556  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.556  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 18:20:16.556  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.566  1972  1972 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 18:20:16.566  1972  1972 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 18:20:16.586  1015  4518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.586  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.586  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.586  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.636   283   283 D WVCdm   : Instantiating CDM.
,08-26 18:20:16.646   283   670 I WVCdm   : CdmEngine::OpenSession
,08-26 18:20:16.646   283   670 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 18:20:16.666   283   670 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 18:20:16.666  4282  5093 I art     : Explicit concurrent mark sweep GC freed 1379(47KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 702us total 22.068ms
,08-26 18:20:16.686   283   670 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-26 18:20:16.746   283   670 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 18:20:16.746   283   283 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-26 18:20:16.746   283   283 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 18:20:16.746   283   283 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-26 18:20:16.756   283   283 D WVCdm   : PrepareKeyRequest: nonce=3392375747
,08-26 18:20:16.766  6943  6952 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 18:20:16.766  6943  6952 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:16.766  6943  6952 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 18:20:16.766  6943  6952 I System.out: (HTTPLog)-Thread-1256-446357640: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 18:20:16.766  6943  6952 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:16.776   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 18:20:16.776   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 18:20:16.816  1972  2149 W GCoreFlp: No location to return for getLastLocation()
,08-26 18:20:16.816  6943  6952 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 18:20:16.816  6943  6952 I qtaguid : Tagging socket 33 with tag 1000180300000000{268441603,0} for uid -1, pid: 6943, getuid(): 10011
,08-26 18:20:16.856  1015  1512 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.866  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.866  1015  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.866  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.866  1015  1216 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.866  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.866  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 18:20:16.866  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 18:20:16.866  1015  4518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:16.866  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:16.876  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:16.876  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:16.886  1972  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 18:20:16.886  4869  6939 D UdcContextInitService: registered all accounts: true
,08-26 18:20:16.896  1972  2157 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 18:20:17.066  1015  4357 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 18:20:17.066  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 18:20:17.066  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:17.066  1015  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:17.066  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:17.136  6943  6952 I qtaguid : Untagging socket 33
,08-26 18:20:17.216  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 18:20:17.216  6866  6920 I jxcore-log: 
,08-26 18:20:17.226  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 18:20:17.226  6866  6920 I jxcore-log: 
,08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:17.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:17.226  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:17.226  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 18:20:17.226  6866  6920 I jxcore-log: 
,08-26 18:20:17.236  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 18:20:17.236  6866  6920 I jxcore-log: 
,08-26 18:20:17.506   288   288 E SMD     : DCD OFF
,08-26 18:20:17.636  1015  3403 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 18:20:17.836  6972  6972 I dex2oat : ----------------------------------------------------
,08-26 18:20:17.836  6972  6972 I dex2oat : <SS>: S T A R T I N G . . .
08-26 18:20:17.836  6972  6972 I dex2oat : <SS>: Zip is absent. Canceled.
08-26 18:20:17.836  6972  6972 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 18:20:17.886  6972  6972 I dex2oat : dex2oat took 49.103ms (threads: 4)
,08-26 18:20:17.896  6943  6952 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 18:20:17.896  6943  6952 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 18:20:17.896  6943  6952 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 18:20:17.896  6943  6952 I Adreno-EGL: Local Branch: 
08-26 18:20:17.896  6943  6952 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 18:20:17.896  6943  6952 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 18:20:17.896  6943  6952 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 18:20:17.936  6866  6920 D executeNativeTests: Running unit tests
,08-26 18:20:17.966  6943  6952 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 18:20:17.966  6943  6952 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 18:20:17.966  6943  6952 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 18:20:17.966  6943  6952 I Adreno-EGL: Local Branch: 
08-26 18:20:17.966  6943  6952 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 18:20:17.966  6943  6952 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 18:20:17.966  6943  6952 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 18:20:18.036  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:18.036  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e added. We now have 2 listener(s)
,08-26 18:20:18.036  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:18.036  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:18.036  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:18.036  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:18.036  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f added. We now have 2 listener(s)
08-26 18:20:18.036  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:18.036  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:18.036  6943  6952 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 18:20:18.036  6943  6952 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 18:20:18.036  6943  6952 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 18:20:18.036  6943  6952 I Adreno-EGL: Local Branch: 
08-26 18:20:18.036  6943  6952 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 18:20:18.036  6943  6952 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 18:20:18.036  6943  6952 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 18:20:18.036  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.046  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:18.046  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:18.046  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:18.046  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.056  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-26 18:20:18.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 18:20:18.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 18:20:18.056  6866  6920 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 18:20:18.066  6866  6920 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 18:20:18.066  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-26 18:20:18.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 18:20:18.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 18:20:18.066  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:18.066  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:18.066  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 18:20:18.066  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 18:20:18.066  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:18.066  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:18.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e removed from the list
,08-26 18:20:18.066  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f removed from the list
08-26 18:20:18.066  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 18:20:18.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.076  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:18.076  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.076  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.076  6866  6920 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 18:20:18.076  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.076  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.076  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.076  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.076  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.076  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.076  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.076  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.076  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.076  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.076  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.076  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.076  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 18:20:18.086  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.086  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.086  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.086  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.086  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.086  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.086  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.086  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.086  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.086  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.086  6866  6920 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 18:20:18.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.096  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:18.096  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.096  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:18.096  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:18.096  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:18.096  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:18.096  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:18.096  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:18.096  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:18.096  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 18:20:18.106  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:18.106  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 18:20:18.116  1015  1319 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 18:20:18.116  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
08-26 18:20:18.116  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:18.116  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:18.116  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 18:20:18.116  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:18.126  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 18:20:18.126  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 18:20:18.126  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 18:20:18.126  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 18:20:18.126  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 18:20:18.146  1972  6941 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-26 18:20:18.146  1972  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:18.146  1972  6941 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 18:20:18.146  1972  6941 I System.out: (HTTPLog)-Thread-271-705693428: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 18:20:18.146  1972  6941 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:18.146   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 18:20:18.146   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-26 18:20:18.146  1972  6941 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:18.146  1972  6941 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:18.156  3158  3166 D BtGatt.GattService: registerClient() - UUID=9046cd21-9767-4e2b-9089-8a63014fd5e4
,08-26 18:20:18.206  3158  3262 D BtGatt.GattService: onClientRegistered() - UUID=9046cd21-9767-4e2b-9089-8a63014fd5e4, clientIf=6
,08-26 18:20:18.206  6866  6877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 18:20:18.206  3158  3368 D BtGatt.GattService: start scan with filters
,08-26 18:20:18.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 18:20:18.206  3158  3269 D BtGatt.ScanManager: handling starting scan
08-26 18:20:18.206  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 18:20:18.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:18.206  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 18:20:18.216  3158  3269 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:18.216  1972  6941 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:18.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.216  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 18:20:18.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:18.226  3158  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 18:20:18.226  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.226  3158  3269 D BtGatt.ScanManager: allow scan with filters
08-26 18:20:18.226  3158  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 18:20:18.226  3158  3269 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 18:20:18.226  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 18:20:18.226  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.226  3158  3269 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 18:20:18.226  3158  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 18:20:18.226  3158  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 18:20:18.226  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.236  6866  6920 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 18:20:18.236  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 18:20:18.236  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.236  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.236  6866  6920 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 18:20:18.236  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.236  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 18:20:18.236  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 18:20:18.236  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 18:20:18.236  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:18.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:18.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 18:20:18.236  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:18.236  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:18.236  3158  3168 D BtGatt.GattService: stopScan() - queue size =1
,08-26 18:20:18.246  3158  3269 D BtGatt.ScanManager: filter size is 1
08-26 18:20:18.246  3158  3166 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 18:20:18.246  3158  3269 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:18.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:18.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-26 18:20:18.246  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 18:20:18.246  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.246  3158  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:18.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:18.246  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-26 18:20:18.246  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.246  3158  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6,
08-26 18:20:18.246  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.246  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.246  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:18.246  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:18.246  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.246  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.246  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.246  6866  6920 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 18:20:18.256  3158  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 18:20:18.256  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.256  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.256  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:18.256  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:18.256  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:18.266  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:18.266  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:18.266  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:18.266  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:18.266  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 18:20:18.276  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.276  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 18:20:18.276  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.276  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 18:20:18.276  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:18.286  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 18:20:18.286  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 18:20:18.286  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 18:20:18.286  3158  3166 D BtGatt.GattService: registerClient() - UUID=07d3335f-4024-48ec-baad-7529fb7fc0e1
,08-26 18:20:18.316   283   674 I WVCdm   : CdmEngine::CloseSession
,08-26 18:20:18.326   283   674 I WVCdm   : L3 Terminate.
,08-26 18:20:18.326  3158  3262 D BtGatt.GattService: onClientRegistered() - UUID=07d3335f-4024-48ec-baad-7529fb7fc0e1, clientIf=6
,08-26 18:20:18.326  6866  6877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 18:20:18.326  3158  3368 D BtGatt.GattService: start scan with filters
,08-26 18:20:18.326  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 18:20:18.326  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 18:20:18.326  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:18.326  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 18:20:18.326  3158  3269 D BtGatt.ScanManager: handling starting scan
,08-26 18:20:18.336  3158  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 18:20:18.336  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.336  3158  3269 D BtGatt.ScanManager: allow scan with filters
,08-26 18:20:18.336  3158  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 18:20:18.336  3158  3269 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 18:20:18.336  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 18:20:18.336  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.336  3158  3269 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 18:20:18.336  3158  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 18:20:18.336  3158  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 18:20:18.336  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.336  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.336  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.336  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 18:20:18.336  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 18:20:18.346  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.346  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:18.346  6866  6920 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 18:20:18.346  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:18.346  6866  6920 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 18:20:18.346  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:18.346  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 18:20:18.346  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.346  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 18:20:18.346  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 18:20:18.346  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:18.346  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-26 18:20:18.346  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:18.356  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-26 18:20:18.356  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:18.356  3158  3166 D BtGatt.GattService: stopScan() - queue size =1
,08-26 18:20:18.356  3158  3269 D BtGatt.ScanManager: filter size is 1
,08-26 18:20:18.356  3158  3269 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 18:20:18.356  3158  3368 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 18:20:18.356  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:18.356  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:18.356  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:18.356  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:18.356  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 18:20:18.356  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 18:20:18.356  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.356  3158  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-26 18:20:18.356  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:18.366  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 18:20:18.366  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.366  3158  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.366  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:18.366  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.366  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.366  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.366  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.366  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.366  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:18.366  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.366  3158  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 18:20:18.366  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.366  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.366  6866  6920 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 18:20:18.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.376  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:18.376  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:18.386  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:18.386  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:18.386  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:18.386  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:18.386  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:18.386  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 18:20:18.386  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.386  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 18:20:18.386  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 18:20:18.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:18.406  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 18:20:18.406  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 18:20:18.406  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 18:20:18.406  3158  3272 D BtGatt.GattService: registerClient() - UUID=01a5e52e-e279-44c6-957b-c356c5000828
,08-26 18:20:18.446  3158  3262 D BtGatt.GattService: onClientRegistered() - UUID=01a5e52e-e279-44c6-957b-c356c5000828, clientIf=6
,08-26 18:20:18.446  6866  6877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 18:20:18.446  3158  3168 D BtGatt.GattService: start scan with filters
,08-26 18:20:18.446  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 18:20:18.446  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 18:20:18.446  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:18.446  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 18:20:18.446  3158  3269 D BtGatt.ScanManager: handling starting scan
,08-26 18:20:18.456  3158  3262 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 18:20:18.456  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.456  3158  3269 D BtGatt.ScanManager: allow scan with filters
08-26 18:20:18.456  3158  3269 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 18:20:18.456  3158  3269 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 18:20:18.456  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 18:20:18.456  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.456  3158  3269 D BtGatt.ScanManager: Starting BLE batch scan
08-26 18:20:18.456  3158  3269 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 18:20:18.456  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.456  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 18:20:18.456  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:18.456  3158  3262 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 18:20:18.456  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.466  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 18:20:18.466  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.466  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:18.466  6866  6920 I io.jxcore.node.ConnectionHelper: start: OK
08-26 18:20:18.466  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.466  6866  6920 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 18:20:18.466  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.466  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 18:20:18.466  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.466  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 18:20:18.466  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 18:20:18.466  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:18.466  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:18.466  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:18.466  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:18.466  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:18.466  3158  3272 D BtGatt.GattService: stopScan() - queue size =1
,08-26 18:20:18.476  3158  3269 D BtGatt.ScanManager: filter size is 1
,08-26 18:20:18.476  3158  3168 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 18:20:18.476  3158  3269 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 18:20:18.476  3158  3262 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:18.476  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.476  3158  3269 D BtGatt.ScanManager: stopping BLe Batch
,08-26 18:20:18.476  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:18.476  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:18.476  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 18:20:18.476  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:18.476  3158  3262 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 18:20:18.476  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:18.476  3158  3269 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 18:20:18.476  3158  3262 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 18:20:18.476  3158  3262 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:18.476  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.486  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.486  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:18.486  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.486  6866  6920 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 18:20:18.486  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.486  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.486  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.486  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.486  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.486  6866  6920 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-26 18:20:18.486  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.486  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.486  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.486  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.486  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.486  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.486  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.486  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.486  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 18:20:18.486  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.496  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 18:20:18.496  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:18.496  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.496  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.496  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.496  6866  6920 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-26 18:20:18.496  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.496  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.496  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.496  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.496  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.496  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.496  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.496  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.506  6866  6920 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-26 18:20:18.506  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.506  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.506  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.506  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 18:20:18.506  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 18:20:18.506  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 18:20:18.506  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 18:20:18.506  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.506  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.506  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.506  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.506  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.506  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.506  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.506  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.506  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:18.506  6866  6920 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 18:20:18.506  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 18:20:18.516  6866  6920 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:18.516  6866  6920 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:18.516  6866  6920 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 18:20:18.516  6866  6920 E io.jxcore.node.ConnectionHelper: connect: Callback is null,
08-26 18:20:18.516  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.516  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.516  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.516  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.516  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.516  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-26 18:20:18.516  6866  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1344)
08-26 18:20:18.516  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.516  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.516  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop,
08-26 18:20:18.516  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.516  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.516  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.516  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.516  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.516  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.526  6866  6920 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.526  6866  6985 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1344
,08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 18:20:18.526  6866  6920 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 18:20:18.526  6866  6920 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 18:20:18.526  6866  6920 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 18:20:18.526  6866  6920 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 18:20:18.526  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.526  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.526  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.526  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.526  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: ,1 listener(s) left
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.526  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.526  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.536  1972  2157 I art     : Explicit concurrent mark sweep GC freed 60739(3MB) AllocSpace objects, 8(269KB) LOS objects, 39% free, 11MB/18MB, paused 1.348ms total 98.823ms
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.536  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.536  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.536  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.536  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.536  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6984 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 18:20:18.536  6866  6866 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6866 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:18.536  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.536  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.536  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:18.536  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.536  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:18.536  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnecto,rlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.536  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.536  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.536  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.536  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.536  6866  6986 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 18:20:18.536  6866  6986 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 18:20:18.546  6866  6866 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.546  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.546  6866  6920 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 18:20:18.546  6866  6920 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 18:20:18.546  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 18:20:18.546  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.546  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.546  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.546  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.546  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.546  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.546  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.546  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.546  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.546  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.546  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.546  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.546  6866  6984 D BluetoothSocket: connect(): myUserId = 0
08-26 18:20:18.546  6866  6984 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.546  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.546  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.546  3158  3166 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 18:20:18.546  6866  6984 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,08-26 18:20:18.556  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.556  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.556  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.556  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.556  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:18.556  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:18.556  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@584860e not in the list
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
08-26 18:20:18.556  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:18.556  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:18.556  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:18.556  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:18.556  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3719882f not in the list
,08-26 18:20:18.556  6866  6920 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 18:20:18.556  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 18:20:18.556  6866  6920 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 18:20:18.556  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 18:20:18.556  6866  6920 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 18:20:18.556  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-26 18:20:18.566  6866  6920 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 18:20:18.566  6866  6920 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 18:20:18.566  6866  6920 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 18:20:18.566  6866  6920 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-26 18:20:18.566  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:18.566  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d3a6179 added. We now have 2 listener(s)
08-26 18:20:18.566  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:18.566  6866  6920 D BluetoothAdapter: enable()
,08-26 18:20:18.566  6866  6920 D BluetoothAdapter: enable(): BT is already enabled..!
,08-26 18:20:18.576  1015  1495 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 18:20:18.576  1015  1495 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 18:20:18.576  1015  1495 D SecContentProvider2: mCursor = null
,08-26 18:20:18.576  1015  1495 D WifiService: setWifiEnabled: true pid=6866, uid=10171
,08-26 18:20:18.576  1972  2157 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 18:20:18.586  1015  1495 W ActivityManager: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 18:20:18.586  1972  2157 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 18:20:18.586  1015  1495 W WifiService: Failed getting userId using ActivityManagerNative
08-26 18:20:18.586  1015  1495 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 18:20:18.586  1015  1495 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 18:20:18.586  1015  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 18:20:18.586  1015  1495 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 18:20:18.586  1015  1495 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 18:20:18.586  1015  1495 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 18:20:18.586  1015  1495 D SettingsProvider: name = wifi_on
,08-26 18:20:18.586  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:18.586  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8248ebe added. We now have 3 listener(s)
08-26 18:20:18.586  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:18.586  1972  2157 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 18:20:16.990+0200, stopTime=2016-08-26 18:20:18.593+0200, duration=1603ms
,08-26 18:20:18.596  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:18.596  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2db1f added. We now have 4 listener(s)
08-26 18:20:18.596  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:18.596  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:18.596  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@38f4ee6c added. We now have 5 listener(s)
08-26 18:20:18.596  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:18.606  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 18:20:18.606  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 18:20:18.606  1015  1027 D SecContentProvider2: mCursor = null
,08-26 18:20:18.606  1015  1027 D WifiService: setWifiEnabled: false pid=6866, uid=10171
,08-26 18:20:18.606  1015  1027 D SettingsProvider: name = wifi_on
,08-26 18:20:18.606  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:18.606   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 18:20:18.606   277  1010 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-26 18:20:18.606  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 18:20:18.606  1972  6989 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:18.616  6866  6920 D BluetoothAdapter: disable()
,08-26 18:20:18.616  1015  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 18:20:18.616  1384  1384 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 18:20:18.616  1384  1384 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 18:20:18.616  1015  4357 D SettingsProvider: name = bluetooth_on
08-26 18:20:18.626  1384  1384 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-26 18:20:18.626  1384  1384 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 18:20:18.626  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:18.636  3158  3259 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 18:20:18.636  3158  3259 D BluetoothAdapterProperties: Setting state to 13
08-26 18:20:18.636  3158  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 18:20:18.636  3158  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:18.636  3158  3259 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 18:20:18.636  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:18.636  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:18.636  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:18.636  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:18.636  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:18.636  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:18.636  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.636  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:18.636  3158  3158 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 18:20:18.636  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1382b8a5, channel: 19, state: LISTENING
08-26 18:20:18.636  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1382b8a5, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1a0a58ed, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1789147amSocket: android.net.LocalSocket@19f7142b impl:android.net.LocalSocketImpl@1a9ae088 fd:FileDescriptor[74]
08-26 18:20:18.636  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19f7142b impl:android.net.LocalSocketImpl@1a9ae088 fd:FileDescriptor[74]
,08-26 18:20:18.636  3158  3259 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:18.636  3158  3259 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 18:20:18.636  3158  3259 D BluetoothAdapterService: terminating service from this receiver
08-26 18:20:18.636  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:18.636  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.636  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:18.646  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 18:20:18.646  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.646  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:18.646  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:18.646  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:18.646  3158  3259 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 18:20:18.646  3158  3259 D BluetoothAdapterProperties: mDiscovering is false
,08-26 18:20:18.646  1015  1319 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 18:20:18.646  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.646  3158  3259 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 18:20:18.656  4126  4126 D BluetoothPbap: Proxy object disconnected
08-26 18:20:18.656  4126  4126 D PbapServerProfile: Bluetooth service disconnected
,08-26 18:20:18.656  1015  1126 E WifiNative-wlan0: do suspend true
,08-26 18:20:18.656  3158  3262 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 18:20:18.656  3158  3262 D BluetoothAdapterProperties: Scan Mode:20
,08-26 18:20:18.656  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:18.656  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 18:20:18.656  3158  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 18:20:18.656  3158  3259 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-26 18:20:18.656  3158  3259 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 18:20:18.656  3158  5280 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 18:20:18.666  3158  3259 E bt-btif : cmd socket is not created
,08-26 18:20:18.666  3158  3287 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 18:20:18.666  3158  3287 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 18:20:18.666  6866  6984 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@16d8ca, channel: -1, state: INIT
,08-26 18:20:18.666  6866  6984 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@16d8ca, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36040a3b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1f788558mSocket: android.net.LocalSocket@1901c6b1 impl:android.net.LocalSocketImpl@e31b796 fd:FileDescriptor[106]
08-26 18:20:18.666  6866  6984 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1901c6b1 impl:android.net.LocalSocketImpl@e31b796 fd:FileDescriptor[106]
,08-26 18:20:18.666  6866  6984 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1344)
08-26 18:20:18.666  3158  3259 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 18:20:18.666  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:18.666  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 18:20:18.666  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 18:20:18.666  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:18.666  3158  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 18:20:18.676  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.686  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:18.686  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-26 18:20:18.696  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 18:20:18.696  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:18.696  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 18:20:18.696  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-26 18:20:18.696  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:18.696  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 18:20:18.696  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:18.696  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e83fe46, channel: 5, state: LISTENING
08-26 18:20:18.696  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e83fe46, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ce4322, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15d0c807mSocket: android.net.LocalSocket@23417d34 impl:android.net.LocalSocketImpl@140575d fd:FileDescriptor[76]
08-26 18:20:18.696  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@23417d34 impl:android.net.LocalSocketImpl@140575d fd:FileDescriptor[76]
,08-26 18:20:18.696  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 18:20:18.706  1015  1496 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:18.706  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:18.706  1015  1512 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 18:20:18.706  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 18:20:18.706  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.706  3158  3158 I BtOppRfcommListener: stopping Accept Thread
,08-26 18:20:18.716  3158  3158 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@11f1b8d2, channel: 12, state: LISTENING
08-26 18:20:18.716  3158  3158 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@11f1b8d2, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c6f69c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ea7dda3mSocket: android.net.LocalSocket@321338a0 impl:android.net.LocalSocketImpl@19300c59 fd:FileDescriptor[79]
08-26 18:20:18.716  3158  3158 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@321338a0 impl:android.net.LocalSocketImpl@19300c59 fd:FileDescriptor[79]
,08-26 18:20:18.716  3158  5280 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 18:20:18.716  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:18.716  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 18:20:18.716  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:18.716  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:18.716  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:18.716  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:18.716  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 18:20:18.726  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 18:20:18.736  1015  4518 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 18:20:18.736  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 18:20:18.736  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:18.736  1015  4518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:18.736  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 18:20:18.746  3158  3158 V BluetoothOppManager: cleanUp...
,08-26 18:20:18.756  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:18.756  1015  3374 D SSRM:n  : SIOP:: AP = 390
,08-26 18:20:18.756  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:18.756  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:18.756  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 18:20:18.756  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 18:20:18.766  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:18.766  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:18.766  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:18.766  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:18.776  6999  6999 E Zygote  : MountEmulatedStorage()
08-26 18:20:18.776  1015  1134 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6999 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-26 18:20:18.776  6999  6999 E Zygote  : v2
08-26 18:20:18.776  6999  6999 I libpersona: KNOX_SDCARD checking this for 10055
08-26 18:20:18.776  6999  6999 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:18.776  6999  6999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:18.786  6999  6999 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:18.786  6999  6999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:18.806  6999  6999 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:18.806  6999  6999 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:18.836  6999  6999 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 18:20:18.866  3158  3352 I bt_userial_mct: exiting userial_read_thread
08-26 18:20:18.866  3158  3352 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 18:20:18.866  3158  3262 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 18:20:18.866  3158  3289 I bt_vendor: hw_epilog_process
,08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:18.866  3158  3262 D bt_userial_mct: userial_close
,08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-26 18:20:18.866  3158  3287 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:18.866  3158  3287 W bt-btif : ag scb idx 1 not allocated
08-26 18:20:18.866  3158  3287 W bt-btif : ag scb idx 2 not allocated
,08-26 18:20:18.866  3158  3287 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 18:20:18.866  3158  3262 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 18:20:18.876  6999  6999 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-26 18:20:18.876  6999  6999 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 18:20:18.876  6999  6999 D UserAnalysis: Create SecureDbHelper
,08-26 18:20:18.876  6999  6999 D IntelligenceServiceApplication: onCreate()
,08-26 18:20:18.886  1015  1319 I ActivityManager: Killing 6574:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-26 18:20:18.886  6999  6999 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 18:20:18.886  1015  4518 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 18:20:18.896  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:18.896  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:18.896  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:18.896  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:18.906  7018  7018 E Zygote  : MountEmulatedStorage(),
,08-26 18:20:18.906  7018  7018 E Zygote  : v2,
08-26 18:20:18.906  7018  7018 I libpersona: KNOX_SDCARD checking this for 10105
08-26 18:20:18.906  7018  7018 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:18.906  7018  7018 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:18.906  1015  4518 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7018 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-26 18:20:18.916  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 18:20:18.916  6999  6999 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 18:20:18.916  7018  7018 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:18.916  7018  7018 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 18:20:18.926  6999  6999 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 18:20:18.936   306   306 I art     : Explicit concurrent mark sweep GC freed 8697(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 710us total 28.212ms
,08-26 18:20:18.946  7018  7018 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 18:20:18.946  7018  7018 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:18.956   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 579us total 16.858ms
,08-26 18:20:18.966   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.552ms,
,08-26 18:20:19.046  6866  6866 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-26 18:20:19.046   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 18:20:19.046   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:19.046  7018  7037 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 18:20:19.056   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 18:20:19.056   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:19.056  7018  7037 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 18:20:19.146  3158  3262 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 18:20:19.146  3158  3262 I bt_vendor: bluetooth satus is on
08-26 18:20:19.146  3158  3262 I bt_vendor: bt-vendor : resetting BT status
08-26 18:20:19.146  3158  3262 I bt_vendor: Starting hciattach daemon
08-26 18:20:19.146  3158  3262 I bt_vendor: try to set false
,08-26 18:20:19.146  3158  3262 I bt_vendor: Starting hciattach daemon
,08-26 18:20:19.146  3158  3262 I bt_vendor: try to set false
08-26 18:20:19.146  3158  3262 I bt_vendor: cleanup
,08-26 18:20:19.146  3158  3287 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-26 18:20:19.146  3158  3262 I GKI_LINUX: GKI_exit_task 0 done
,08-26 18:20:19.146  3158  3262 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 18:20:19.146  3158  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 18:20:19.146  3158  3259 D BtConfig.SecureMode: isSecureModeOn:false
08-26 18:20:19.146  3158  3259 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 18:20:19.146  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 18:20:19.146  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 18:20:19.146  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 18:20:19.146  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:19.146  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.146  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.146  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.146  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.146  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:19.156  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 18:20:19.156  3158  3158 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 18:20:19.156  3158  3158 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 18:20:19.156  3158  3158 D BtGatt.GattService: stop()
08-26 18:20:19.156  3158  3158 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 18:20:19.156  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 18:20:19.156  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:19.156  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.156  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.156  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.156  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.156  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
08-26 18:20:19.156  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 18:20:19.156  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:19.156  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:19.156  1015  3406 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:19.156  3158  3158 D HeadsetService: Received stop request...Stopping profile...
08-26 18:20:19.156  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.156  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.156  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.156  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.156  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.156  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 18:20:19.156  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 18:20:19.166  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 18:20:19.166  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 18:20:19.166  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:19.166  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.166  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.166  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:19.166  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.166  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 18:20:19.166  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 18:20:19.166  4126  4126 D HeadsetProfile: Bluetooth service disconnected
,08-26 18:20:19.166  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 18:20:19.166  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:19.166  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.166  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.166  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:19.166  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.166  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 18:20:19.176  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 18:20:19.176  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 18:20:19.176  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:19.176  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.176  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.176  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.176  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.176  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:19.176  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:19.176  3158  3259 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:19.176  1015  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:19.176  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.176  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.176  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.176  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 18:20:19.186  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 18:20:19.186  1015  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:19.186  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 18:20:19.186  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.186  1015  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.186  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:19.186  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:19.186  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 18:20:19.186  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 18:20:19.186  3158  3259 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 18:20:19.186  3158  3259 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 18:20:19.186  3158  3259 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 18:20:19.186  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 18:20:19.186  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 18:20:19.186  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:19.186  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 18:20:19.186  3158  3158 D A2dpService: Received stop request...Stopping profile...
08-26 18:20:19.186  3158  3280 D A2dpStateMachine: Exit Disconnected: -1
,08-26 18:20:19.196  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.196  1015  1015 D BluetoothA2dp: Proxy object disconnected
,08-26 18:20:19.196  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 18:20:19.196  4126  4126 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:19.196  4126  4126 D A2dpProfile: Bluetooth service disconnected
,08-26 18:20:19.196  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 18:20:19.196  3158  3158 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 18:20:19.196  3158  3158 D HidService: Received stop request...Stopping profile...
,08-26 18:20:19.196  3158  3158 D HidService: Stopping Bluetooth HidService
08-26 18:20:19.196  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 18:20:19.196  3158  3158 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 18:20:19.196  3158  3158 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 18:20:19.196  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.206  4126  4126 D BluetoothInputDevice: Proxy object disconnected
08-26 18:20:19.206  4126  4126 D HidProfile: Bluetooth service disconnected
,08-26 18:20:19.206  3158  3158 D HealthService: Received stop request...Stopping profile...
,08-26 18:20:19.206  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.206  3158  3158 D PanService: Received stop request...Stopping profile...
,08-26 18:20:19.206  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.206  3158  3158 D BluetoothMapService: Received stop request...Stopping profile...
08-26 18:20:19.206  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 18:20:19.206  4126  4126 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 18:20:19.206  4126  4126 D PanProfile: Bluetooth service disconnected
,08-26 18:20:19.206  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.216  4126  4126 D BluetoothMap: Proxy object disconnected
08-26 18:20:19.216  3158  3158 D SapService: Received stop request...Stopping profile...
08-26 18:20:19.216  4126  4126 D MapProfile: Bluetooth service disconnected
08-26 18:20:19.216  3158  3158 D SapService: Stopping Bluetooth SapService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 18:20:19.216  3158  3158 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  3158  3281 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=129 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  7018  7018 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:19.216  7018  7018 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:19.216  3158  3158 I GKI_LINUX: GKI_exit_task 2 done
08-26 18:20:19.216  3158  3158 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 18:20:19.216  3158  3158 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.216  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 18:20:19.216  3158  3158 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 18:20:19.216  4126  4126 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 18:20:19.216  4126  4126 D SapProfile: Bluetooth service disconnected
08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:19.216  3158  3158 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 18:20:19.216  3158  3158 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 18:20:19.216  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 18:20:19.216  3158  3158 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-26 18:20:19.226  1015  1027 I ActivityManager: Killing 6469:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-26 18:20:19.226  3158  3259 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 18:20:19.226  3158  3259 D BluetoothAdapterProperties: Setting state to 10
08-26 18:20:19.226  3158  3259 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 18:20:19.226  3158  3259 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:19.226  3158  3259 D BluetoothAdapterService: updateAdapterState state is 10
08-26 18:20:19.226  3158  3259 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:19.226  3158  3259 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 18:20:19.226  3158  3259 I BluetoothAdapterState: Entering OffState
08-26 18:20:19.226  4126  4140 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:19.226  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:19.226  4126  4136 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.226  4126  4136 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.226  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 18:20:19.236  4126  4140 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 18:20:19.236  6866  6877 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.236  6866  6877 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.236  6866  6877 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 18:20:19.236  6866  6877 D BluetoothLeAdvertiser: Exit stop advertising
08-26 18:20:19.236  6866  6877 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 18:20:19.236  6866  6877 D BluetoothLeScanner: Exiting stopAllScan
08-26 18:20:19.236  1178  4426 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.236  1178  4426 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.236  1443  1470 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.236  1443  1470 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.236  4126  4136 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 18:20:19.236  4126  4136 D Bluetoothsap: Unbinding service...
08-26 18:20:19.236  3158  3368 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:19.236  4126  4140 D BluetoothPbap: onBluetoothStateChange: up=false
08-26 18:20:19.246  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:19.246  4126  4136 D BluetoothMap: onBluetoothStateChange: up=false
08-26 18:20:19.246  3158  3166 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.246  3158  3166 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.246  1972  1981 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.246  1972  1981 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.246  1456  1478 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.246  1456  1478 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:19.246  1469  1480 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.246  1469  1480 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.246  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:19.246  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:19.256  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-26 18:20:19.256  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 18:20:19.256  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:19.256  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-26 18:20:19.256  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-26 18:20:19.266  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.266  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 18:20:19.266  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:19.266  1178  1178 D BluetoothTile:  getBluetoothState : 10
08-26 18:20:19.266  1178  1743 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.266  1178  1743 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.266  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.266  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.266  1015  1533 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 18:20:19.266  1015  4518 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 18:20:19.266  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 18:20:19.276  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 18:20:19.276  1972  2158 D BluetoothAdapter: 791931807: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.276  1972  2158 D BluetoothAdapter: 791931807: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:19.276  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:19.276  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:19.276  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:19.286  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:19.286  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 18:20:19.286  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 18:20:19.286  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.286  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:19.286  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 18:20:19.286  1015  3406 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 18:20:19.286  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 18:20:19.286  7018  7041 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 18:20:19.286  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.286  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:19.286  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 18:20:19.296  3158  3262 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 18:20:19.296  3158  3158 I GKI_LINUX: GKI_exit_task 1 done
08-26 18:20:19.296  3158  3158 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 18:20:19.296  3158  3158 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 18:20:19.296  3158  3158 I art     : System.exit called, status: 0
08-26 18:20:19.296  3158  3158 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 18:20:19.306  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:19.306  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:19.306  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:19.306  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 18:20:19.316  1015  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:19.316  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.316  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:19.316  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 18:20:19.326  1015  1134 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 18:20:19.326  1015  1134 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 18:20:19.326  1015  1134 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 18:20:19.326  1015  1134 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 18:20:19.326  1015  1134 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 18:20:19.326  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 18:20:19.336  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:19.336  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.336  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.336  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:19.346  7056  7056 E Zygote  : MountEmulatedStorage()
,08-26 18:20:19.346  7056  7056 E Zygote  : v2
08-26 18:20:19.346  7056  7056 I libpersona: KNOX_SDCARD checking this for 1002
08-26 18:20:19.346  7056  7056 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:19.346  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:19.346  1015  1134 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7056 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 18:20:19.346  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:19.346  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:19.366  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:19.366  7056  7056 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:19.386  7056  7056 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 18:20:19.386  7056  7056 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:19.406  7056  7056 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding GattService
,08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding HidService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding HealthService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding PanService
,08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding SapService
,08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding SapClientService
08-26 18:20:19.446  7056  7056 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 18:20:19.446  7056  7056 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 18:20:19.446  1015  4518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 18:20:19.446  1015  4518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.446  1015  4518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.446  1015  4518 D SettingsProvider: selectionArgs: false
,08-26 18:20:19.446  1015  4518 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.446  1015  4518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.446  1015  4518 D SettingsProvider: ret = -1
08-26 18:20:19.446  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:19.446  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.446  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.446  1015  1494 D SettingsProvider: selectionArgs: false
08-26 18:20:19.446  1015  1494 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.446  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.446  1015  1494 D SettingsProvider: ret = -1
08-26 18:20:19.446  1015  4357 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 18:20:19.446  1015  4357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.446  1015  4357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.446  1015  4357 D SettingsProvider: selectionArgs: false
08-26 18:20:19.446  1015  4357 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.446  1015  4357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.446  1015  4357 D SettingsProvider: ret = -1
08-26 18:20:19.456  1015  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 18:20:19.456  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-26 18:20:19.456  1015  1535 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
08-26 18:20:19.456  1015  1535 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 18:20:19.456  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  1535 D SettingsProvider: ret = -1
08-26 18:20:19.456  1015  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 18:20:19.456  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.456  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  1533 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  1533 D SettingsProvider: ret = -1
08-26 18:20:19.456   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:19.456  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 18:20:19.456  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.456  1015  1495 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  1495 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  1495 D SettingsProvider: ret = -1
08-26 18:20:19.456  1015  3406 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 18:20:19.456  1015  3406 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  3406 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.456  1015  3406 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  3406 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  3406 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  3406 D SettingsProvider: ret = -1
08-26 18:20:19.456  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:19.456  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 18:20:19.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.456  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.456  1015  1512 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 18:20:19.456  1015  1512 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  1512 D SettingsProvider,: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.456  1015  1512 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  1512 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  1512 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  1512 D SettingsProvider: ret = -1
08-26 18:20:19.456  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:19.456  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.456  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.456  1015  1216 D SettingsProvider: selectionArgs: false
08-26 18:20:19.456  1015  1216 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.456  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.456  1015  1216 D SettingsProvider: ret = -1
,08-26 18:20:19.456  1972  6989 I qtaguid : Untagging socket 66
08-26 18:20:19.466  1972  3046 V NativeCrypto: Read error: ssl=0xb7ed88e0: I/O error during system call, Connection timed out
08-26 18:20:19.466  1015  1496 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:19.466  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.466  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.466  1015  1496 D SettingsProvider: selectionArgs: false
08-26 18:20:19.466  1015  1496 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.466  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.466  1015  1496 D SettingsProvider: ret = -1
,08-26 18:20:19.466  1015  4518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 18:20:19.466  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 18:20:19.466  1015  4518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 18:20:19.466  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-26 18:20:19.466  1015  4518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 18:20:19.466  1015  4518 D SettingsProvider: selectionArgs: false
08-26 18:20:19.466  1015  4518 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.476  1015  1134 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-26 18:20:19.466  1015  4518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.466  1015  4518 D SettingsProvider: ret = -1
08-26 18:20:19.466  1972  3046 V NativeCrypto: SSL shutdown failed: ssl=0xb7ed88e0: I/O error during system call, Broken pipe
08-26 18:20:19.466  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:19.466  1015  1128 E ConnectivityService: updateNetworkInfo(),
08-26 18:20:19.466  1972  3046 E GCM     : Wifi connection closed with errorCode 20
08-26 18:20:19.466  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.466  1015  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 18:20:19.466  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:19.466  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:19.466  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.466  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:19.466  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:19.466  1015  1533 D SettingsProvider: selectionArgs: 1002
08-26 18:20:19.466  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:19.466  1015  1533 D SettingsProvider: ret = -1
08-26 18:20:19.466  1972  6989 I qtaguid : Untagging socket 47
08-26 18:20:19.476  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 18:20:19.476  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.476  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.476  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.486  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:19.486  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:19.486  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.486  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.486  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.486  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:19.486  1015  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 18:20:19.486  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 18:20:19.486  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:19.486  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-26 18:20:19.486  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:19.496  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-16ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:19.496  1015  1125 D WifiP2pService: InactiveState{ what=131204 }
08-26 18:20:19.496  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-16ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:19.496  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 18:20:19.496  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 18:20:19.496  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:19.496  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-26 18:20:19.496  1015  1796 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:19.496  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 18:20:19.496  1015  1796 I qtaguid : Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-26 18:20:19.496  1015  4518 I ActivityManager: Killing 6605:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-26 18:20:19.506  1015  1796 I qtaguid : Untagging socket 348
,08-26 18:20:19.506  1015  1796 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:19.536  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 18:20:19.536  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-26 18:20:19.536  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer,
08-26 18:20:19.536  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 18:20:19.546  1384  1384 I wpa_supplicant: nl80211: Received scan results (11 BSSes),
,08-26 18:20:19.546  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 18:20:19.556  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 18:20:19.556  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 18:20:19.556  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 18:20:19.556  1015  1045 D WifiDisplayController: disconnect
08-26 18:20:19.556  1015  1045 D WifiDisplayController: updateConnection
08-26 18:20:19.556  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 18:20:19.556  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:19.556  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 18:20:19.556  1015  1125 D WifiP2pService: P2pDisablingState
08-26 18:20:19.556  1015  1125 D WifiP2pService: P2pDisablingState{ what=147461 }
08-26 18:20:19.556  1015  1125 D WifiP2pService: DefaultState{ what=147461 }
08-26 18:20:19.556  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 18:20:19.556  1015  1125 D WifiP2pService: p2p socket connection lost
08-26 18:20:19.556  1015  1125 D WifiP2pService: P2pDisabledState
,08-26 18:20:19.566  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 18:20:19.566  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-26 18:20:19.566  1015  1126 E WifiNative-wlan0: do suspend true,
08-26 18:20:19.566  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 18:20:19.566  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 18:20:19.566  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 18:20:19.566  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-26 18:20:19.576  1015  1512 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:19.576  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:19.576  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-26 18:20:19.576  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:19.576  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.576  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.576  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.576  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:19.586   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 18:20:19.586   277  1010 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-26 18:20:19.586   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:19.586  1972  6989 I qtaguid : Untagging socket 47
08-26 18:20:19.586  1015  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 18:20:19.586  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.586  1015  1128 V NetworkStats: updateIfacesLocked()
08-26 18:20:19.586  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.586  1015  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:19.586  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 18:20:19.586  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:19.586  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:19.586  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:19.586  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.586  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 18:20:19.586  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-26 18:20:19.586  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.586  1384  1384 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 18:20:19.596  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.596  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.596  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.596  1015  1128 V NetworkStats: performPollLocked() took 10ms
,08-26 18:20:19.596  1972  6989 I qtaguid : Untagging socket 47
08-26 18:20:19.596  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:19.596  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:19.596  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:19.596  1015  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 18:20:19.596  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.596  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.596  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:19.596  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:19.596  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 18:20:19.596  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:19.596  1178  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 18:20:19.596  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-26 18:20:19.606  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:19.606  1015  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:19.606  1015  1796 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:19.606  1015  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 18:20:19.606  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 18:20:19.606  1015  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 18:20:19.606  1469  1469 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:19.606  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 18:20:19.606  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:19.606  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 18:20:19.606  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.606  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.606  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.606  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:19.606  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:19.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:19.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.606  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 18:20:19.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:19.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 18:20:19.606  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.606  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.606  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.606  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
08-26 18:20:19.606  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.606  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:19.616  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.616  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.616  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.616  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.616  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.616  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:19.616  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.616  1972  6989 I qtaguid : Untagging socket 47
,08-26 18:20:19.616  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.616  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.616  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.616  1972  6989 I qtaguid : Untagging socket 47
08-26 18:20:19.616  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:19.616  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.616  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.616  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.616  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 18:20:19.616  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.616  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 18:20:19.616  1972  6989 I qtaguid : Untagging socket 47,
08-26 18:20:19.616  1972  6989 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:19.616  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:19.616  1972  6989 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:19.616  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:19.616  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:19.616  1972  6989 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 1972, getuid(): 10011
,08-26 18:20:19.616  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:19.626  1015  1123 V NetworkStats: updateIfacesLocked()
08-26 18:20:19.626  1972  6989 I qtaguid : Untagging socket 47
08-26 18:20:19.626  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:19.626  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.626  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:19.626  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:19.626  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:19.626  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:19.626  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:19.626  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:19.626  1178  1178 D HotspotTile: onReceive : 0, 0
,08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 18:20:19.626  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0,
08-26 18:20:19.626  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.626  1015  1123 V NetworkStats: performPollLocked() took 4ms
,08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:19.626  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:19.626  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:19.716  1015  4357 I art     : Explicit concurrent mark sweep GC freed 36927(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 24MB/36MB, paused 2.662ms total 212.012ms,
,08-26 18:20:19.716  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 18:20:19.716  1015  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 18:20:19.716  1015  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 18:20:19.716  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:19.716  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:19.716  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.726  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 18:20:19.726  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.726  1015  1129 D Tethering: MasterInitialState.processMessage what=3
,08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 18:20:19.726  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.726  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.726  1015  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 18:20:19.776  1384  1384 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:19.786  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.786  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.796  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.796  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.796  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.796  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.796  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.796  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.796  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.806  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:19.806  1015  3406 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:19.806  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:19.806  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.806  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:19.806  1015  3406 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:19.806  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:19.806  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.806  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.816  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 18:20:19.816  1972  1972 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-26 18:20:19.816  1972  1972 E ctxmgr  : com.android.volley.NoConnectionError: java.net.ConnectException: failed to connect to www.googleapis.com/172.217.22.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:151)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at iss.performRequest(:com.google.android.gms:64)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.volley.NetworkDispatcher.run(:com.google.android.gms:113)
08-26 18:20:19.816  1972  1972 E ctxmgr  : Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/172.217.22.74 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at java.net.Socket.connect(Socket.java:882)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.volley.toolbox.HttpClientStack.performRequest(:com.google.android.gms:87)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at isr.performRequest(:com.google.android.gms:63)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:96)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	... 2 more
08-26 18:20:19.816  1972  1972 E ctxmgr  : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at libcore.io.Posix.connect(Native Method)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:122),
08-26 18:20:19.816  1972  1972 E ctxmgr  : 	... 21 more
08-26 18:20:19.816  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.816  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.816  1972  2157 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 18:20:19.816  1972  7085 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 18:20:19.816  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 18:20:19.816  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 18:20:19.816  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.826  1015  1512 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:19.826  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 18:20:19.826  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 18:20:19.826  1384  1384 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-26 18:20:19.826  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:19.826  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:19.826  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:19.826  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.826  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 18:20:19.826  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.826  1015  1512 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:19.826  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:19.826  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.826  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.826  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.826  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.836  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.836  1015  1495 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:19.836  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:19.836  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.836  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:19.836  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 18:20:19.836  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 18:20:19.836  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-26 18:20:19.836  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:19.836  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 18:20:19.836  1611  1611 I Hs20UtilService: Starting #8
,08-26 18:20:19.836  1611  1637 I Hs20UtilService: Message received 5007
,08-26 18:20:19.846  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 18:20:19.846  1384  1384 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 18:20:19.846  1384  1384 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 18:20:19.846  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.846  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.846  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:19.846  1384  1384 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 18:20:19.846  1384  1384 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:19.846  1384  1384 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 18:20:19.846  1015  1129 D Tethering: InitialState.processMessage what=4
,08-26 18:20:19.846  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.846  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.846  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:19.846  1015  1134 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:19.846  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:19.856  1015  1129 E Tethering: No numeric data
,08-26 18:20:19.856  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:19.856  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:19.856  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 18:20:19.856  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:19.856  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.856  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:19.856  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:19.856  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:19.856  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:19.856  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:19.856  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:19.856  1015  1129 D Tethering: clearTetheredNotification()
,08-26 18:20:19.856  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:19.856  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:19.856  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.866  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:19.866  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:19.866  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:19.866  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 18:20:19.866  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:19.866  1015  1123 V NetworkStats: performPollLocked() took 4ms
08-26 18:20:19.866  1972  7085 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 18:20:19.866  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.866  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:19.876  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 18:20:19.876  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:19.876  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:19.876  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 18:20:19.876  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:19.876  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:19.876  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:19.876  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 18:20:19.886  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:19.886  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.886  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:19.886  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:19.896  7096  7096 E Zygote  : MountEmulatedStorage()
08-26 18:20:19.896  1015  1216 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7096 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:19.896  7096  7096 E Zygote  : v2
08-26 18:20:19.896  7096  7096 I libpersona: KNOX_SDCARD checking this for 10064
08-26 18:20:19.896  7096  7096 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:19.896  7096  7096 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:19.896  7096  7096 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:19.896  7096  7096 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:19.906   269   269 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb74547c8
08-26 18:20:19.906   269   269 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-26 18:20:19.906   269   269 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 18:20:19.906   269   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1220196216)
,08-26 18:20:19.936  7096  7096 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-26 18:20:19.936  7096  7096 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:19.946   269   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-26 18:20:19.946   269   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 18:20:19.946   269   338 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1220196216) wakelock released: 1, error no: 0
08-26 18:20:19.946   269   338 I rmt_storage: 
,08-26 18:20:19.946   269   269 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb74547c8,
,08-26 18:20:19.956  7096  7096 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 18:20:19.966  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:19.976  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
,08-26 18:20:19.996  7096  7096 D FileShare-Client: Outbound.stopDelayTimer - ,
08-26 18:20:19.996  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 18:20:19.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:19.996  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.016  7111  7111 E Zygote  : MountEmulatedStorage(),
08-26 18:20:20.016  7111  7111 E Zygote  : v2
,08-26 18:20:20.016  7111  7111 I libpersona: KNOX_SDCARD checking this for 10065
08-26 18:20:20.016  7111  7111 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.016  7111  7111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 18:20:20.016  1015  1028 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7111 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 18:20:20.016  7111  7111 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 18:20:20.016  7111  7111 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.036  7111  7111 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 18:20:20.036  7111  7111 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.066  7111  7111 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:20.076  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.076  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 18:20:20.076  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-26 18:20:20.076  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 18:20:20.076  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 18:20:20.076  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.076  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.076  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.096  7126  7126 E Zygote  : MountEmulatedStorage(),
08-26 18:20:20.096  7126  7126 E Zygote  : v2
08-26 18:20:20.096  7126  7126 I libpersona: KNOX_SDCARD checking this for 10102
08-26 18:20:20.096  7126  7126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:20.096  7126  7126 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:20.096  1384  1384 I wpa_supplicant: Blacklist: Clear (all) 
08-26 18:20:20.096  1015  1134 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7126 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 18:20:20.096  1015  1134 I ActivityManager: Killing 6636:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-26 18:20:20.106  7126  7126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:20.106  7126  7126 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 18:20:20.126  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:20.126  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-26 18:20:20.136  1384  1384 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 18:20:20.136  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
,08-26 18:20:20.136  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:20.136  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:20.136  7126  7126 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 18:20:20.146  7126  7126 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:20.146  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:20.146  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:20.156  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:20.176  7126  7126 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 18:20:20.246  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 18:20:20.246  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 18:20:20.246  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:20.246  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:20.246  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:20.246  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:20.246  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:20.246  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:20.246  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:20.256  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 18:20:20.256  1972  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:20.256  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:20.256  1178  1178 D HotspotTile: onReceive : 1, 0
,08-26 18:20:20.256  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:20.256  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:20.256  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 18:20:20.266  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:20.336  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:20.406  7126  7146 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-26 18:20:20.406  7126  7146 I Babel_SMS: MmsConfig.loadMmsSettings
,08-26 18:20:20.406  7126  7146 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 18:20:20.406  7126  7146 I Babel_SMS: MmsConfig.loadFromDatabase
,08-26 18:20:20.436  7126  7146 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-26 18:20:20.436  7126  7146 I Babel_SMS: MmsConfig.loadFromResources
,08-26 18:20:20.436  7126  7146 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 18:20:20.436  7126  7146 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-26 18:20:20.446  1015  4357 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-26 18:20:20.446  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-26 18:20:20.446  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.446  1015  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:20.446  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 18:20:20.466  7126  7126 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:20.476  7126  7126 I Babel_Crash: startup - clean
,08-26 18:20:20.506   288   288 E SMD     : DCD OFF
,08-26 18:20:20.516  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:20.516  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:20.516  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.516  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.516  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:20.516  1611  1611 I Hs20UtilService: Starting #9
08-26 18:20:20.516  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 18:20:20.516  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:20.516  1611  1637 I Hs20UtilService: Message received 5007
08-26 18:20:20.516  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:20.516  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 18:20:20.516  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:20.526  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:20.526  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:20.526  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:20.526  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:20.536  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.536  7126  7126 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-26 18:20:20.536  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.536  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:20.536  1611  1611 I Hs20UtilService: Starting #10
,08-26 18:20:20.536  7126  7126 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 18:20:20.536  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:20.536  7126  7126 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 18:20:20.536  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:20.536  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:20.536  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 18:20:20.536  7126  7126 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 18:20:20.546  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 18:20:20.546  7126  7126 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 18:20:20.546  7126  7126 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 18:20:20.556  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.556  7126  7126 W AudioCapabilities: Unsupported mime audio/x-ima
08-26 18:20:20.556  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.556  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.556  7126  7126 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 18:20:20.556  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.556  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.556  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.556  7126  7126 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 18:20:20.556  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.556  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.556  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.566  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.566  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.566  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.566  7126  7126 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 18:20:20.566  7126  7126 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 18:20:20.566  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.566  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.566  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.576  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.576  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.576  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.576  7126  7126 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 18:20:20.576  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.576  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.576  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.576  7126  7126 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 18:20:20.576  7126  7126 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 18:20:20.586  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.586  7126  7126 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 18:20:20.586  7126  7126 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 18:20:20.586  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.586  7126  7126 W VideoCapabilities: Unsupported mime video/mp43
,08-26 18:20:20.586  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.586  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.596  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.596  7126  7126 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 18:20:20.596  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.596  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.596  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.596  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.596  7126  7126 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 18:20:20.606  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:20.606  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:20.606  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 18:20:20.606  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 18:20:20.606  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.606  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.606  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.606  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.616  7149  7149 E Zygote  : MountEmulatedStorage()
08-26 18:20:20.616  7149  7149 I libpersona: KNOX_SDCARD checking this for 1000
08-26 18:20:20.616  7149  7149 E Zygote  : v2
08-26 18:20:20.616  7149  7149 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.616  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7149 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 18:20:20.626  7149  7149 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:20.626  7149  7149 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 18:20:20.626  7149  7149 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 18:20:20.626  7126  7126 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 18:20:20.646  7149  7149 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:20.646  7149  7149 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.656  7126  7126 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 18:20:20.656  7126  7126 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 18:20:20.666  7126  7126 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 18:20:20.666  7126  7126 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 18:20:20.666  1015  1134 I ActivityManager: Killing 6686:com.samsung.android.sm/1000 (adj 15): empty #21
,08-26 18:20:20.676  7126  7126 I vclib   : onServiceConnected
,08-26 18:20:20.676  7149  7149 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 18:20:20.676  7149  7149 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 18:20:20.676  7149  7149 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 18:20:20.686  7149  7149 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 18:20:20.686  7149  7149 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 18:20:20.686  7149  7149 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 18:20:20.686  7149  7149 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:20.696  1015  1535 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-26 18:20:20.696  1015  1535 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 18:20:20.696  7149  7164 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 18:20:20.696  1015  1535 I ActivityManager: Killing 6656:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 18:20:20.706  1015  4357 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 18:20:20.706  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.706  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.706  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.706  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.716  1015  4357 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7166 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a,
08-26 18:20:20.726  7166  7166 E Zygote  : MountEmulatedStorage()
08-26 18:20:20.726  7166  7166 E Zygote  : v2
08-26 18:20:20.726  7166  7166 I libpersona: KNOX_SDCARD checking this for 10031
08-26 18:20:20.726  7166  7166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:20.726  7166  7166 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.726  7166  7166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:20.726  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
08-26 18:20:20.726  7166  7166 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.726  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.726  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.726  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.726  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.726  1777  1777 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:20.736  7166  7166 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:20.746  7166  7166 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.756  7182  7182 E Zygote  : MountEmulatedStorage()
,08-26 18:20:20.756  7182  7182 E Zygote  : v2
08-26 18:20:20.756  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7182 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-26 18:20:20.756  7182  7182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:20.756  7182  7182 I libpersona: KNOX_SDCARD checking this for 10121
08-26 18:20:20.756  7182  7182 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.766  7182  7182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:20.766  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 18:20:20.766  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.766  7182  7182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.766  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.766  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.766  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.776  7182  7182 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:20.776  7182  7182 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.786  7196  7196 E Zygote  : MountEmulatedStorage(),
08-26 18:20:20.786  7196  7196 E Zygote  : v2
08-26 18:20:20.786  7196  7196 I libpersona: KNOX_SDCARD checking this for 10001
08-26 18:20:20.786  7196  7196 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.786  7196  7196 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:20.786  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7196 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:20.786  7196  7196 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 18:20:20.796  7196  7196 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 18:20:20.796  1015  1042 D Tethering: interfaceRemoved wlan0
08-26 18:20:20.796  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 18:20:20.806  2468  3277 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-26 18:20:20.806  1777  1777 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 18:20:20.806  1777  1777 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-26 18:20:20.806  1777  1777 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 18:20:20.806  1777  1777 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:20.816  1777  1777 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:20.816  7182  7182 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:20.816  7182  7182 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 18:20:20.816  7182  7182 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:20.816  1777  1777 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 18:20:20.816  7196  7196 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:20.816  7196  7196 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.826  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-26 18:20:20.826  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.826  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.826  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.826  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.836  7182  7182 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:20.836  1972  2157 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-26 18:20:20.836  1972  2157 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1,
,08-26 18:20:20.836  7212  7212 E Zygote  : MountEmulatedStorage(),
08-26 18:20:20.846  7212  7212 E Zygote  : v2
08-26 18:20:20.846  7212  7212 I libpersona: KNOX_SDCARD checking this for 10077
,08-26 18:20:20.846  7212  7212 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.846  1015  1216 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7212 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:20.846  7212  7212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:20.846  7212  7212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:20.846  7212  7212 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.856  7182  7182 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 18:20:20.866  7182  7182 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 18:20:20.866  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-26 18:20:20.866  7166  7166 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 18:20:20.876  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.876  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.876  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.876  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.876  7212  7212 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:20.876  7212  7212 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:20.886  7227  7227 E Zygote  : MountEmulatedStorage(),
08-26 18:20:20.886  7227  7227 E Zygote  : v2
,08-26 18:20:20.886  7227  7227 I libpersona: KNOX_SDCARD checking this for 10141
08-26 18:20:20.886  7227  7227 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:20.896  7227  7227 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:20.896  1015  1216 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7227 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 18:20:20.906  7227  7227 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:20.906  1015  1216 I ActivityManager: Killing 6738:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-26 18:20:20.906  7227  7227 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.926  1015  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 18:20:20.926  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.926  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 18:20:20.926  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:20.926  1015  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:20.936  7227  7227 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:20.936  2799  7241 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-26 18:20:20.936  7227  7227 D ActivityThread: Added TimaKeyStore provider,
,08-26 18:20:20.936  2799  7241 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 18:20:20.936  2799  7241 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-26 18:20:20.936  2799  7241 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 18:20:20.946  2799  7241 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 18:20:20.956  1015  1042 D Tethering: interfaceRemoved p2p0
08-26 18:20:20.956  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 18:20:20.956  7243  7243 E Zygote  : MountEmulatedStorage()
08-26 18:20:20.956  7243  7243 E Zygote  : v2
08-26 18:20:20.956  7243  7243 I libpersona: KNOX_SDCARD checking this for 10032
08-26 18:20:20.956  7243  7243 I libpersona: KNOX_SDCARD not a persona,
,08-26 18:20:20.956  7243  7243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:20.966  7243  7243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 18:20:20.966  7243  7243 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 18:20:20.966  1015  1533 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7243 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:20.986  1015  1496 I ActivityManager: Killing 6746:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21,
,08-26 18:20:20.996   306   306 I art     : Explicit concurrent mark sweep GC freed 8688(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 642us total 24.901ms
,08-26 18:20:20.996  7227  7227 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 18:20:20.996  7227  7227 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:20.996  7227  7227 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 18:20:20.996  7227  7227 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 18:20:21.006  7243  7243 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:21.006  7243  7243 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.016   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 19.802ms
,08-26 18:20:21.016  1015  1512 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 18:20:21.016  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.016  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.016  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.016  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.026   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 573us total 16.617ms
,08-26 18:20:21.046  7260  7260 E Zygote  : MountEmulatedStorage()
08-26 18:20:21.046  7260  7260 E Zygote  : v2
08-26 18:20:21.046  7260  7260 I libpersona: KNOX_SDCARD checking this for 1000
08-26 18:20:21.046  7260  7260 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.046  7260  7260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:21.046  1015  1512 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 18:20:21.046  7260  7260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:21.046  1015  1512 I ActivityManager: Killing 6768:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-26 18:20:21.046  7260  7260 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:21.056  1015  3406 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.076  1015  1216 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.076  7260  7260 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:21.076  7260  7260 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.086  7243  7277 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-26 18:20:21.086  7243  7277 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 18:20:21.096  7243  7277 D SPPClientService: PushLog.txt file is not deleted.
08-26 18:20:21.096  7243  7277 D SPPClientService: PushLog.txt file is not deleted.
08-26 18:20:21.096  7243  7277 D SPPClientService: ============PushLog. stop!
08-26 18:20:21.096  7243  7243 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-26 18:20:21.096  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-26 18:20:21.096  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.096  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.096  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.096  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.106  7281  7281 E Zygote  : MountEmulatedStorage()
08-26 18:20:21.106  7281  7281 I libpersona: KNOX_SDCARD checking this for 10036
08-26 18:20:21.106  7281  7281 E Zygote  : v2
08-26 18:20:21.106  7281  7281 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.106  7281  7281 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:21.126  7281  7281 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:21.126  1015  1027 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7281 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:21.126  7281  7281 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 18:20:21.126  1015  1027 I ActivityManager: Killing 6787:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-26 18:20:21.126  1015  1216 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-26 18:20:21.126  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
08-26 18:20:21.126  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:21.126  1015  1216 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-26 18:20:21.126  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-26 18:20:21.136  1015  1512 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.136  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.146  7260  7260 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
08-26 18:20:21.146  7281  7281 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:21.146  7281  7281 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.146   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:21.166  7243  7294 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-26 18:20:21.206  7281  7281 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2588c9f3
,08-26 18:20:21.216  7281  7281 I SA      : [SSP] onCreated
,08-26 18:20:21.216  1015  4518 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-26 18:20:21.216  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.216  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.216  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.216  1015  4518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.226  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId,
,08-26 18:20:21.236  7303  7303 E Zygote  : MountEmulatedStorage(),
08-26 18:20:21.236  7303  7303 E Zygote  : v2
08-26 18:20:21.236  7303  7303 I libpersona: KNOX_SDCARD checking this for 10068
08-26 18:20:21.236  7303  7303 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.236  7303  7303 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:21.236  7303  7303 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:21.236  7303  7303 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 18:20:21.236  1015  4518 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7303 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-26 18:20:21.246  1015  4357 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.256  7303  7303 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:21.256  7303  7303 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.276  7281  7281 I SA      : [TPM] There is no property file
,08-26 18:20:21.276  7281  7281 I SA      : [SCU] isHaveSA() - false
,08-26 18:20:21.286  7281  7281 I SA      : [TPM] getModelProperty : null
08-26 18:20:21.286  7281  7281 I SA      : [TPM] getCSCProperty : null
,08-26 18:20:21.286  7281  7281 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-26 18:20:21.286  7281  7281 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-26 18:20:21.286  7281  7281 I SA      : [DM] TFT FEATURE: false
,08-26 18:20:21.286  7260  7260 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 18:20:21.296  7260  7260 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 18:20:21.296  7260  7260 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:21.306  7281  7281 I SA      : [DM] init START,
,08-26 18:20:21.306  7260  7260 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 18:20:21.306  7260  7260 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 18:20:21.306  7260  7260 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
08-26 18:20:21.306  1015  4357 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 18:20:21.306  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.306  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.306  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.306  1015  4357 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.306  7281  7281 I SA      : [DM] This device is not a Vodafone
,08-26 18:20:21.316  7323  7323 E Zygote  : MountEmulatedStorage()
08-26 18:20:21.316  7323  7323 E Zygote  : v2
08-26 18:20:21.316  7323  7323 I libpersona: KNOX_SDCARD checking this for 10008
08-26 18:20:21.316  7323  7323 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.326  7303  7303 D BadgeProvider: onCreate
08-26 18:20:21.326  7323  7323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-26 18:20:21.326  7303  7303 D BadgeProvider: DatabaseHelper
,08-26 18:20:21.326  1015  1319 D RCPManagerService: exchangeData() failure , invalid userId,
08-26 18:20:21.326  7323  7323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:21.326  7323  7323 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-26 18:20:21.326  1015  4357 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7323 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:21.326  1015  4357 I ActivityManager: Killing 6185:com.android.mms/u0a41 (adj 15): empty #21
,08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 18:20:21.336  7281  7281 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 18:20:21.346  7323  7323 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 18:20:21.346  7323  7323 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.346  1015  1512 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:21.346  7281  7281 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 18:20:21.346  7281  7281 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-26 18:20:21.356  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 18:20:21.356  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.356  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.356  7281  7281 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-26 18:20:21.356  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.356  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.366  7281  7281 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-26 18:20:21.366  7303  7313 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 18:20:21.376  7339  7339 E Zygote  : MountEmulatedStorage()
08-26 18:20:21.376  7339  7339 I libpersona: KNOX_SDCARD checking this for 10009
08-26 18:20:21.376  7339  7339 E Zygote  : v2
08-26 18:20:21.376  7339  7339 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.376  7339  7339 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:21.376  7281  7281 I SA      : [SCU] isHaveSA() - false
08-26 18:20:21.376  7281  7281 I SA      : support phone number id : false
08-26 18:20:21.376  7281  7281 I SA      : [DM] Supports Ref Jpn : true
,08-26 18:20:21.376  7281  7281 I SA      : [DM] init END
08-26 18:20:21.376  7281  7281 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 18:20:21.376  7339  7339 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:21.376  1015  1495 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7339 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-26 18:20:21.376  7281  7281 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 18:20:21.376  1015  1495 I ActivityManager: Killing 6808:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-26 18:20:21.376  7281  7281 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-26 18:20:21.376  1015  1495 I ActivityManager: Killing 6721:com.android.providers.calendar/u0a37 (adj 15): empty #22
,08-26 18:20:21.386  7339  7339 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 18:20:21.386  1015  4518 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 18:20:21.386  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.396  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:21.396  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:21.396  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 18:20:21.396  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 18:20:21.406  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.406  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.406  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:21.406  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:21.406  7339  7339 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:21.406  7339  7339 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.406  1497  1497 D Launcher.Model: reloadBadges entered.
,08-26 18:20:21.406  7303  7314 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-26 18:20:21.406  7303  7314 D BadgeProvider: sendNotify, [notify] : null
08-26 18:20:21.406  7303  7314 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 18:20:21.406  7303  7314 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 18:20:21.406  7303  7314 D BadgeProvider: update, [UpdateCount] : 1
,08-26 18:20:21.406  1015  1495 D CountryDetector: No listener is left
,08-26 18:20:21.416  7281  7281 I SA      : [SLFUCHKMGR] constructor called
,08-26 18:20:21.416  7356  7356 E Zygote  : MountEmulatedStorage()
08-26 18:20:21.416  7356  7356 E Zygote  : v2
08-26 18:20:21.416  7356  7356 I libpersona: KNOX_SDCARD checking this for 10110
08-26 18:20:21.416  7356  7356 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:21.416  7356  7356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:21.426  7356  7356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:21.426  7356  7356 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 18:20:21.426  7281  7281 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-26 18:20:21.446  7281  7281 I SA      : [OR] == isSIMCardReady false ==
,08-26 18:20:21.446  7281  7281 I SA      : [SCU] == networkStateCheck == false,
08-26 18:20:21.446  7281  7281 I SA      : [OR] onReceive END
08-26 18:20:21.446  1015  1134 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7356 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 18:20:21.446  7356  7356 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:21.446  7356  7356 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:21.456  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 18:20:21.456  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.456  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:21.456  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:21.456  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 18:20:21.466  7126  7353 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-26 18:20:21.476  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:21.476  1015  4518 I ActivityManager: Killing 6825:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-26 18:20:21.496  1015  4518 I ActivityManager: Killing 6645:com.android.calendar/u0a131 (adj 15): empty #21
,08-26 18:20:21.506  1015  1216 I ActivityManager: Killing 6130:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-26 18:20:21.516  2920  2920 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 18:20:21 GMT+02:00 2016
,08-26 18:20:21.526  1015  4518 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 18:20:21.526  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.526  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:21.526  1015  4518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:21.526  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 18:20:21.536  1015  1495 I ActivityManager: Killing 5932:com.android.vending/u0a26 (adj 15): empty #21
08-26 18:20:21.536  2920  2920 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 18:20:21.536  1015  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:21.536  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.536  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:21.536  1015  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 18:20:21.546  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:21.546  2920  2920 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 18:20:21.556  2920  2920 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 18:20:21.556  2920  2920 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 18:20:21.556  4869  7374 I iu.SyncManager: SYNC; picasa accounts
,08-26 18:20:21.566  2920  7373 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 18:20:21.566  2920  7373 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:21.576  2920  7373 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-26 18:20:21.576  4869  4869 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-26 18:20:21.576  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-26 18:20:21.576  1015  1216 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 18:20:21.576  2920  7373 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-26 18:20:21.576  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.576  1015  4518 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-26 18:20:21.576  1015  4518 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 18:20:21.576  1015  4518 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 18:20:21.576  1015  4518 D BatteryService: stay LED for fully charged
08-26 18:20:21.576  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 18:20:21.586  2920  2920 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-26 18:20:21.586  1015  1015 I MotionRecognitionService: Plugged
,08-26 18:20:21.586  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 18:20:21.586  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 18:20:21.586  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 18:20:21.596  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 18:20:21.596  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 18:20:21.596  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 18:20:21.606  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 18:20:21.616  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 18:20:21.616  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 18:20:21.616  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-26 18:20:21.616  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:21.616  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:21.636  1015  1494 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 18:20:21.636  1015  1494 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 18:20:21.636  1015  1494 D SecContentProvider2: mCursor = null
,08-26 18:20:21.646  1015  1494 D WifiService: setWifiEnabled: true pid=6866, uid=10171
,08-26 18:20:21.646  1015  1494 W ActivityManager: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 18:20:21.646  1015  1494 W WifiService: Failed getting userId using ActivityManagerNative
08-26 18:20:21.646  1015  1494 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 18:20:21.646  1015  1494 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 18:20:21.646  1015  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 18:20:21.646  1015  1494 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 18:20:21.646  1015  1494 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 18:20:21.646  1015  1494 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 18:20:21.646  1015  1494 D SettingsProvider: name = wifi_on
,08-26 18:20:21.696  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 18:20:21.736  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 18:20:21.866   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 18:20:21.866   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:21.866  7356  7380 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 18:20:21.866   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 18:20:21.866   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:21.876  7356  7380 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 18:20:21.876   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 18:20:21.876   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:21.876  7356  7381 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 18:20:21.886   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 18:20:21.886   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:21.886  7356  7381 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 18:20:21.916  7356  7356 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-26 18:20:21.916  7356  7356 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-26 18:20:21.916  7356  7356 I GAv4    :   adb logcat -s GAv4
,08-26 18:20:21.936  7356  7356 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-26 18:20:21.936  1015  1533 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 18:20:21.946  7356  7356 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-26 18:20:21.956  7356  7389 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-26 18:20:22.046  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 18:20:22.046  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:22.046  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:22.046  1015  1042 D Tethering: interfaceAdded wlan0
,08-26 18:20:22.046  1015  1129 E Tethering: No numeric data
,08-26 18:20:22.046  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 18:20:22.046  1015  1129 D Tethering: clearTetheredNotification()
08-26 18:20:22.056  1015  1042 D Tethering: interfaceAdded p2p0
,08-26 18:20:22.056  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 18:20:22.056  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:22.056  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:22.056   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 18:20:22.056  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:22.056  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:22.056   277  1014 D SoftapController: Softap fwReload - Ok
08-26 18:20:22.056  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:22.056  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:22.056  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-26 18:20:22.056  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:22.056  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 18:20:22.056   277  1014 D CommandListener: Setting iface cfg
08-26 18:20:22.056   277  1014 D CommandListener: Trying to bring down wlan0
,08-26 18:20:22.056  1015  1123 V NetworkStats: performPollLocked() took 6ms
08-26 18:20:22.056  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:22.066   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 18:20:22.066  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:22.066  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:22.076  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 18:20:22.076  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 18:20:22.076  1015  1126 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-26 18:20:22.076  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:22.076  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:22.076  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:22.076  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:22.076  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:22.076  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:22.076  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:22.076  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 18:20:22.086  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 18:20:22.086  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:22.086  1178  1178 D HotspotTile: onReceive : 2, 0
,08-26 18:20:22.086  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:22.086  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:22.096  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:22.126  7393  7393 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 18:20:22.126  7393  7393 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 18:20:22.126  7393  7393 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 18:20:22.146  7393  7393 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 18:20:22.146   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7393,
08-26 18:20:22.146   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-26 18:20:22.146  7393  7393 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-26 18:20:22.146  7393  7393 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:22.146  7393  7393 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 18:20:22.146  7393  7393 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 18:20:22.146   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7393
08-26 18:20:22.146   402   402 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-26 18:20:22.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:22.226  1015  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:22.226  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:22.226  1015  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:22.226  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 18:20:22.266  7356  7356 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-26 18:20:22.286  7356  7356 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6973-6975)
,08-26 18:20:22.286  7356  7356 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-26 18:20:22.296  7356  7356 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1789147a},
08-26 18:20:22.296  7356  7356 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-26 18:20:22.296  7356  7356 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 18:20:22.316  7356  7356 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-26 18:20:22.316  7356  7356 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 18:20:22.316  7356  7356 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 18:20:22.326   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-26 18:20:22.326  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-26 18:20:22.336  7356  7356 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 18:20:22.336  7356  7356 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 18:20:22.336  7356  7356 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 18:20:22.336  7356  7356 I Adreno-EGL: Local Branch: 
08-26 18:20:22.336  7356  7356 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 18:20:22.336  7356  7356 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 18:20:22.336  7356  7356 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 18:20:22.376  7393  7393 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 18:20:22.376  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 18:20:22.396  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 18:20:22.396   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7393
08-26 18:20:22.396   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 18:20:22.396  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,08-26 18:20:22.396  7393  7393 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:22.396  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 18:20:22.396  7393  7393 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:22.396  7393  7393 E wpa_supplicant: SIM READ ERROR
08-26 18:20:22.396  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:22.396  7393  7393 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:22.396  7393  7393 E wpa_supplicant: SIM READ ERROR
08-26 18:20:22.396  7393  7393 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:22.396  7393  7393 I wpa_supplicant: wpa_default_ap_write_once
08-26 18:20:22.396  7393  7393 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 18:20:22.396  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:22.396  7393  7393 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 18:20:22.396  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:22.396  7393  7393 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 18:20:22.396  7393  7393 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 18:20:22.396  7356  7421 W cr.media: Requires BLUETOOTH permission
,08-26 18:20:22.396  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:22.396  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:22.396  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:22.396  1015  1129 D Tethering: InitialState.processMessage what=4
,08-26 18:20:22.406  1015  1129 E Tethering: No numeric data
,08-26 18:20:22.406  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
08-26 18:20:22.406  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:22.406  1015  1129 D Tethering: clearTetheredNotification()
08-26 18:20:22.406  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:22.406  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:22.406  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 18:20:22.406  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 18:20:22.406  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:22.406  1015  1123 V NetworkStats: performPollLocked() took 3ms
08-26 18:20:22.406  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:22.406  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:22.406  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:22.416  7356  7356 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-26 18:20:22.426  7356  7356 I NSApplication: Starting up...
,08-26 18:20:22.426  1015  1216 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 18:20:22.426  1015  1533 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-26 18:20:22.426  1015  3406 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 18:20:22.436  1015  3406 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:22.436  1015  3406 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:22.436  1015  3406 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:22.436  1015  3406 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:22.446  7393  7393 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-26 18:20:22.446  7426  7426 E Zygote  : MountEmulatedStorage()
08-26 18:20:22.446  7426  7426 E Zygote  : v2
08-26 18:20:22.446  7426  7426 I libpersona: KNOX_SDCARD checking this for 10117
,08-26 18:20:22.446  7426  7426 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:22.446  7426  7426 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:22.446  1015  3406 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7426 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,08-26 18:20:22.446  7426  7426 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 18:20:22.446  7426  7426 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
08-26 18:20:22.446  1015  3406 I ActivityManager: Killing 6999:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-26 18:20:22.466  7426  7426 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:22.466  7426  7426 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:22.476  7426  7426 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 18:20:22.576  7393  7393 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-26 18:20:22.576  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 18:20:22.586  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-26 18:20:22.586   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7393
08-26 18:20:22.586   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 18:20:22.586  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running,
08-26 18:20:22.586  7393  7393 I wpa_supplicant: ssSupport state is = 1
,08-26 18:20:22.586  7393  7393 I wpa_supplicant: Ctrl_iface: loading cred from phone,
,08-26 18:20:22.586  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-26 18:20:22.606  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-26 18:20:22.606   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7393
08-26 18:20:22.606   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
,08-26 18:20:22.606  7393  7393 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-26 18:20:22.606  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:22.606  7393  7393 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:22.606  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 18:20:22.606  7393  7393 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:22.606  7393  7393 E wpa_supplicant: SIM READ ERROR
08-26 18:20:22.606  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-26 18:20:22.606  7393  7393 I wpa_supplicant: wpa_default_ap_write_once
08-26 18:20:22.606  7393  7393 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-26 18:20:22.606  7393  7393 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 18:20:22.606  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:22.606  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-26 18:20:22.606  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:22.606  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:22.666  7393  7393 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 18:20:22.666  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 18:20:22.776  7393  7393 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-26 18:20:22.776  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-26 18:20:22.776  7393  7393 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 18:20:22.836  1015  1496 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 18:20:22.836  1015  1496 I ActivityManager: Killing 7056:com.android.bluetooth/1002 (adj 15): empty #21
,08-26 18:20:22.846  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:22.846  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:22.846  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:22.846  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:22.846  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:22.846  1611  1611 I Hs20UtilService: Starting #11
,08-26 18:20:22.846  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 18:20:22.846  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:22.846  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
08-26 18:20:22.846  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 18:20:22.856  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:22.856  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:22.866  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:22.866  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:22.866  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:22.866  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:22.866  1611  1611 I Hs20UtilService: Starting #12
,08-26 18:20:22.866  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:22.866  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:22.866  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:22.866  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
08-26 18:20:22.866  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 18:20:23.046  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 18:20:23.046  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:23.046  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:23.076  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 18:20:23.086  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 18:20:23.086  7393  7393 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 18:20:23.086  7393  7393 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 18:20:23.086  7393  7393 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:23.086  7393  7393 E wpa_supplicant: SIM READ ERROR
08-26 18:20:23.086  7393  7393 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:23.096  1015  1535 I ActivityManager: Killing 7018:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-26 18:20:23.126  7393  7393 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 18:20:23.136  7393  7393 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-26 18:20:23.136  1015  1126 D WifiConfigStore: Loading config and enabling all networks ,
08-26 18:20:23.146  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:23.146  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:23.146  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:23.146  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:23.146  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:23.146  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 18:20:23.146  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:23.146  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:23.146  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:23.146  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 18:20:23.146  1178  1178 D HotspotTile: onReceive : 3, 0
,08-26 18:20:23.146  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:23.156  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:23.156  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:23.156  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:23.156  1015  1126 E WifiConfigStore: Not a HS20
,08-26 18:20:23.156  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 18:20:23.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:23.156  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:23.156  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:23.156  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:23.156  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:23.156  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 18:20:23.156  1015  4518 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:23.156  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:23.156  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:23.166  1015  4518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:23.166  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:23.166  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 18:20:23.166  7393  7393 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 18:20:23.166  7393  7393 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 18:20:23.166  7393  7393 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 18:20:23.166  7393  7393 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 18:20:23.166  7393  7393 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 18:20:23.166  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 18:20:23.166  7393  7393 I wpa_supplicant: First Scan Start
,08-26 18:20:23.166  7393  7393 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 18:20:23.166  1611  1611 I Hs20UtilService: Starting #13
,08-26 18:20:23.166  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:23.166  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:23.166  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:23.166  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 18:20:23.166  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-26 18:20:23.166  7126  7126 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 18:20:23.166  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 18:20:23.166  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:23.166  1015  1126 I WifiNative-HAL: startHal
,08-26 18:20:23.166  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ee0f88c
08-26 18:20:23.166  1015  1126 I WifiNative-HAL: Could not start hal
,08-26 18:20:23.176  1015  1126 E WifiNative-wlan0: do suspend true
,08-26 18:20:23.176  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 },
,08-26 18:20:23.176   277  1014 D CommandListener: Setting iface cfg
08-26 18:20:23.176   277  1014 D CommandListener: Trying to bring up p2p0
08-26 18:20:23.176  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 18:20:23.176  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 18:20:23.176  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 18:20:23.176  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:23.176  1015  1125 D WifiP2pService: P2pEnablingState
08-26 18:20:23.176  1015  1149 I WifiNative-HAL: startHal
08-26 18:20:23.176  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 18:20:23.176  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x993ab9bc
08-26 18:20:23.176  1015  1125 D WifiP2pService: P2p socket connection successful
08-26 18:20:23.176  1015  1149 I WifiNative-HAL: Could not start hal
08-26 18:20:23.176  1015  1125 D WifiP2pService: P2pEnabledState
,08-26 18:20:23.176  1015  1149 E WifiScanningService: could not start HAL
08-26 18:20:23.176  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-26 18:20:23.176  1015  1150 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:23.186  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 18:20:23.186  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 18:20:23.186  1015  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 18:20:23.186  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 18:20:23.186  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 18:20:23.186  1015  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 18:20:23.186  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 18:20:23.186  1015  1128 E ConnectivityService: updateNetworkInfo()
,08-26 18:20:23.186  7393  7393 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 18:20:23.186  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 18:20:23.186  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 18:20:23.186  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 18:20:23.186  1015  1045 D WifiDisplayController: disconnect
08-26 18:20:23.186  7393  7393 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 18:20:23.186  1015  1045 D WifiDisplayController: updateConnection
08-26 18:20:23.186  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 18:20:23.186  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:23.186  7393  7393 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-26 18:20:23.186  1015  1126 E WifiStateMachine: Failed to set frequency band 0
,08-26 18:20:23.186  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:23.186  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:23.196  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:23.196  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-26 18:20:23.196  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 18:20:23.196  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 18:20:23.196  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 18:20:23.196  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-26 18:20:23.196  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 18:20:23.196  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 18:20:23.196  1015  1125 D WifiP2pService: DeviceAddress: 0a:76:28
08-26 18:20:23.196  1015  4357 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:23.196  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 18:20:23.196  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 18:20:23.196  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:23.196  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  secondary type: null
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  wps: 0
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  grpcapab: 0
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  devcapab: 0
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  status: 3
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  wfdInfo: null
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-26 18:20:23.196  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-26 18:20:23.196  1015  1126 D SecContentProvider2: mCursor = null
08-26 18:20:23.196  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:23.206  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 18:20:23.206  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:23.206  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:23.206  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:23.206  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:23.206  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 18:20:23.206  7096  7096 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 18:20:23.216  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 18:20:23.216  1015  1125 D WifiP2pService: InactiveState
,08-26 18:20:23.216  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
08-26 18:20:23.216  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 18:20:23.216  7111  7111 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:23.216  7393  7393 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 18:20:23.216  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-26 18:20:23.216  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 18:20:23.506   288   288 E SMD     : DCD OFF,
,08-26 18:20:24.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:24.396  7393  7393 I wpa_supplicant: nl80211: Received scan results (30 BSSes),
,08-26 18:20:24.396  7393  7393 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 18:20:24.396  7393  7393 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-26 18:20:24.396  7393  7393 I wpa_supplicant: Trying to associate with  'G700'
08-26 18:20:24.396  7393  7393 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-26 18:20:24.396  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-26 18:20:24.406  1015  7452 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 18:20:24.416  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-26 18:20:24.416  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.506  7393  7393 E wpa_supplicant: Cmd 35605 not handled
,08-26 18:20:24.516  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:24.516  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:24.516  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:24.516  7393  7393 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 18:20:24.516  7393  7393 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-26 18:20:24.516  7393  7393 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 18:20:24.516  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-26 18:20:24.516  7393  7393 I wpa_supplicant: Associated with F4.99.3E
,08-26 18:20:24.516  7393  7393 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 18:20:24.516  7393  7393 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 18:20:24.516  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:24.516  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:24.516  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:24.516  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:24.516  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 18:20:24.516  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 18:20:24.516  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-26 18:20:24.516  1015  1129 E Tethering: No numeric data
08-26 18:20:24.526  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 18:20:24.526  1015  1129 D Tethering: clearTetheredNotification()
,08-26 18:20:24.526  7393  7393 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 18:20:24.526  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:24.526  7393  7393 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 18:20:24.526  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.526  7393  7393 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 18:20:24.526  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 18:20:24.526  7393  7393 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:24.526  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-26 18:20:24.526  7393  7393 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 18:20:24.526  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 18:20:24.526  7393  7393 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 18:20:24.526  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-26 18:20:24.526  7393  7393 I wpa_supplicant: Blacklist: Clear (temp) 
,08-26 18:20:24.526  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 18:20:24.526  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
08-26 18:20:24.536  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:24.536  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:24.536  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:24.536  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-26 18:20:24.536  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.536  1015  1123 V NetworkStats: performPollLocked() took 15ms
,08-26 18:20:24.536  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:24.546  1015  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 18:20:24.546  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.546  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.546  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 18:20:24.546  1015  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 18:20:24.546  1015  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 18:20:24.546  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:24.546  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 18:20:24.556  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:24.556  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.556  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.556  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.556  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.556  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.556  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:24.556  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:24.556  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:24.556  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:24.556  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 18:20:24.556  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:24.566  1611  1611 I Hs20UtilService: Starting #14,
,08-26 18:20:24.566  1611  1637 I Hs20UtilService: Message received 5007
,08-26 18:20:24.566  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 18:20:24.566  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:24.566  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:24.566  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 18:20:24.566  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:24.566  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:24.576  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:24.576  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:24.586   277  1014 D CommandListener: Setting iface cfg
,08-26 18:20:24.586  1015  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 18:20:24.586  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 18:20:24.586  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.596  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 18:20:24.596  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.606  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-26 18:20:24.606  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.606  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.606  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 18:20:24.606  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.616  1015  1126 E WifiNative-wlan0: do suspend false,
,08-26 18:20:24.616  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
08-26 18:20:24.616  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 18:20:24.696  1015  4518 D SecContentProvider: uri = 18 selection = isWifiEnabled,
08-26 18:20:24.696  1015  4518 D WifiService: setWifiEnabled: false pid=6866, uid=10171,
,08-26 18:20:24.696  1015  4518 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed,
08-26 18:20:24.696  1015  4518 D SecContentProvider2: mCursor = null
08-26 18:20:24.696  1015  4518 D SettingsProvider: name = wifi_on
,08-26 18:20:24.706  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:24.716  1015  1126 E WifiNative-wlan0: do suspend true,
,08-26 18:20:24.736  1015  1125 D WifiP2pService: InactiveState{ what=143375 },
08-26 18:20:24.736  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 18:20:24.736  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:24.736  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.746  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.746  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.746  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.746  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.746   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 18:20:24.746  1015  1128 E ConnectivityService: updateNetworkInfo(),
08-26 18:20:24.746  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:24.746  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-26 18:20:24.756  1015  1125 D WifiP2pService: InactiveState{ what=131204 },
08-26 18:20:24.756  1015  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-26 18:20:24.756  1015  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 18:20:24.756   277  1014 E Netd    : no such netId 503
,08-26 18:20:24.756  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED,
,08-26 18:20:24.756  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-26 18:20:24.756  1015  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
08-26 18:20:24.756  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.756  1015  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-26 18:20:24.756  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:24.756  1015  1128 V NetworkStats: updateIfacesLocked()
08-26 18:20:24.756  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:24.756  1015  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 18:20:24.766  1015  1128 V NetworkStats: performPollLocked() took 9ms
08-26 18:20:24.766  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:24.766  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.766  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.766  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.766  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.766  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.766  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.766  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 18:20:24.766  1015  1149 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:24.766  1015  1015 D RttService: SCAN_AVAILABLE : 1
08-26 18:20:24.766  1015  1150 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:24.776  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:24.776  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 18:20:24.776  1015  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-26 18:20:24.776  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:24.776  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:24.776  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 18:20:24.776  1015  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 18:20:24.776  1015  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 18:20:24.776  1015  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 18:20:24.776  1611  1611 I Hs20UtilService: Starting #15
08-26 18:20:24.776  1611  1637 I Hs20UtilService: Message received 5007
08-26 18:20:24.776  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:24.776  1015  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,08-26 18:20:24.776  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 18:20:24.786  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-26 18:20:24.786  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 18:20:24.786  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 18:20:24.786  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:24.786  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:24.786  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:24.786  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 18:20:24.786  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 18:20:24.786  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 18:20:24.786  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 18:20:24.786  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 18:20:24.786  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 18:20:24.786  1015  1045 D WifiDisplayController: disconnect
08-26 18:20:24.786  1015  1045 D WifiDisplayController: updateConnection
08-26 18:20:24.786  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 18:20:24.796  1015  1125 D WifiP2pService: P2pDisablingState
08-26 18:20:24.796  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 18:20:24.796  1015  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 18:20:24.796  1015  1125 D WifiP2pService: p2p socket connection lost
,08-26 18:20:24.796  1015  1125 D WifiP2pService: P2pDisabledState
08-26 18:20:24.796  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:24.796  1015  1126 E WifiNative-wlan0: do suspend true
08-26 18:20:24.796  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:24.796  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:24.796  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 18:20:24.796  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:24.796  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-26 18:20:24.796  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-26 18:20:24.796  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 18:20:24.796  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 18:20:24.806  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 18:20:24.806  1015  1027 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:24.806  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 18:20:24.806  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 18:20:24.806  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:24.816  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:24.816  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 18:20:24.816  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:24.816  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:24.816  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:24.816  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
08-26 18:20:24.816  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 18:20:24.816  7096  7096 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 18:20:24.826   277  1014 D CommandListener: Clearing all IP addresses on wlan0
08-26 18:20:24.826  1015  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-26 18:20:24.826  1015  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-26 18:20:24.836  7111  7111 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:24.836  7459  7459 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
08-26 18:20:24.836  7459  7459 I dhcpcd  : version 5.5.6 starting
08-26 18:20:24.836  7393  7393 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 18:20:24.836  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:24.836  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.846  7459  7459 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:24.846  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.846  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.856  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 18:20:24.856  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:24.866  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:24.866  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:24.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:24.866  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:24.866  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:24.866  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:24.866  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0),
08-26 18:20:24.866  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 18:20:24.866  1178  1178 D HotspotTile: onReceive : 0, 0
,08-26 18:20:24.876  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:24.876  1015  1494 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:24.876  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:24.876  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:24.876  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:24.876  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:24.876  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:24.876  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:24.876  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 18:20:24.876  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:24.876  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 18:20:24.876  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:24.876  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:24.876  1611  1611 I Hs20UtilService: Starting #16
08-26 18:20:24.876  1611  1637 I Hs20UtilService: Message received 5007
,08-26 18:20:24.876  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 18:20:24.876  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:24.886  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:24.886  1015  4518 I ActivityManager: Killing 7149:com.sec.pcw.device/1000 (adj 15): empty #21
,08-26 18:20:24.886  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:24.886  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:24.886  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 18:20:24.886  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:24.896  7459  7459 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-26 18:20:24.896  7459  7459 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 18:20:24.896  7459  7459 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 18:20:24.896  7459  7459 I dhcpcd  : bssid match
08-26 18:20:24.896  7459  7459 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 18:20:24.906  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:24.906  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:24.906  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:24.906  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:24.906  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:24.906  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:24.906  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:24.906  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 18:20:24.906  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 18:20:24.906  1611  1611 I Hs20UtilService: Starting #17
,08-26 18:20:24.906  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:24.976  7393  7393 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:24.986  7459  7459 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-26 18:20:25.036  7459  7459 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 18:20:25.036  7393  7393 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 18:20:25.036  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:25.036  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:25.036  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:25.056  7393  7393 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 18:20:25.066  7393  7393 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 18:20:25.066  7393  7393 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-26 18:20:25.066  7393  7393 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:25.066  7393  7393 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 18:20:25.066  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 18:20:25.066  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.066  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:25.066  1015  1129 D Tethering: InitialState.processMessage what=4
08-26 18:20:25.066  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 18:20:25.066  1015  1129 E Tethering: No numeric data
,08-26 18:20:25.066  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-26 18:20:25.076  1015  1129 D Tethering: clearTetheredNotification()
08-26 18:20:25.076  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 18:20:25.076  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:25.076  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.076  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.076  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:25.076  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 18:20:25.076  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:25.076  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 18:20:25.076  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-26 18:20:25.076  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:25.076  1178  1178 D HotspotTile: updateTetherState():false, false
,08-26 18:20:25.086  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 18:20:25.086  1015  1123 V NetworkStats: performPollLocked() took 7ms
,08-26 18:20:25.086  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:25.086  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:25.156   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 18:20:25.306  7393  7393 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:25.406  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.406  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.406  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:25.406  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.406  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:25.406  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:25.406  7393  7393 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-26 18:20:25.416  1015  1040 W ProcessCpuTracker: Skipping unknown process pid 7393
,08-26 18:20:25.516  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-26 18:20:25.516  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 18:20:25.516  7126  7126 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:25.526  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:25.526  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:25.526  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:25.526  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:25.526  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:25.526  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:25.526  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:25.526  1972  2158 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:25.526  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 18:20:25.526  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:25.526  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:25.526  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 18:20:25.526  1178  1178 D HotspotTile: onReceive : 1, 0
,08-26 18:20:25.536  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 18:20:25.536  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-26 18:20:25.536  1015  1496 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:25.536  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:25.536  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:25.536  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:25.536  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:25.546  1611  1611 I Hs20UtilService: Starting #18
,08-26 18:20:25.546  1611  1637 I Hs20UtilService: Message received 5011
08-26 18:20:25.546  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:25.546  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:25.546  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
08-26 18:20:25.546  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 18:20:26.216   277  1008 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-26 18:20:26.216  1015  1042 D Tethering: interfaceRemoved wlan0
,08-26 18:20:26.216  1015  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 18:20:26.346  1015  1042 D Tethering: interfaceRemoved p2p0
,08-26 18:20:26.346  1015  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 18:20:26.506   288   288 E SMD     : DCD OFF,
,08-26 18:20:27.166  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 18:20:27.706  6866  6920 D BluetoothAdapter: enable()
,08-26 18:20:27.706  1015  1216 W ActivityManager: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 18:20:27.706  1015  1216 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-26 18:20:27.706  1015  1216 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 18:20:27.706  1015  1216 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 18:20:27.706  1015  1216 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 18:20:27.706  1015  1216 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
,08-26 18:20:27.706  1015  1216 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 18:20:27.706  1015  1216 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 18:20:27.706  1015  1216 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 18:20:27.706  1015  1216 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:27.716  1015  1216 D SettingsProvider: name = bluetooth_on
,08-26 18:20:27.716  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-26 18:20:27.716  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:27.726  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-26 18:20:27.726  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 18:20:27.726  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 18:20:27.726  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 18:20:27.726  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-26 18:20:27.726  1015  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:27.746  7490  7490 E Zygote  : MountEmulatedStorage()
,08-26 18:20:27.746  7490  7490 E Zygote  : v2
08-26 18:20:27.746  7490  7490 I libpersona: KNOX_SDCARD checking this for 1002
08-26 18:20:27.746  7490  7490 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:27.746  7490  7490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:27.746  1015  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7490 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-26 18:20:27.746  7490  7490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-26 18:20:27.756  7490  7490 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 18:20:27.776  7490  7490 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:27.776  7490  7490 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:27.796  7490  7490 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 18:20:27.796  7490  7490 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:27.826  7490  7490 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding GattService
,08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding A2dpService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding HidService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding HealthService
,08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding PanService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding SapService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding SapClientService
08-26 18:20:27.856  7490  7490 D BtSettings.ProfileConfig: Adding HidDevService
,08-26 18:20:27.856  7490  7490 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 18:20:27.866  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 18:20:27.866  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  1134 D SettingsProvider: selectionArgs: false
08-26 18:20:27.866  1015  1134 D SettingsProvider: selectionArgs: 1002,
08-26 18:20:27.866  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  1134 D SettingsProvider: ret = -1
,08-26 18:20:27.866  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:27.866  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  1495 D SettingsProvider: selectionArgs: false
08-26 18:20:27.866  1015  1495 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.866  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  1495 D SettingsProvider: ret = -1
,08-26 18:20:27.866  1015  4518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:27.866  1015  4518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  4518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  4518 D SettingsProvider: selectionArgs: false
08-26 18:20:27.866  1015  4518 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.866  1015  4518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  4518 D SettingsProvider: ret = -1
08-26 18:20:27.866  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 18:20:27.866  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  1028 D SettingsProvider: selectionArgs: false
08-26 18:20:27.866  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.866  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  1028 D SettingsProvider: ret = -1
08-26 18:20:27.866  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 18:20:27.866  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  1319 D SettingsProvider: selectionArgs: false
08-26 18:20:27.866  1015  1319 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.866  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  1319 D SettingsProvider: ret = -1
08-26 18:20:27.866  1015  1512 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-26 18:20:27.866  1015  1512 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1512 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 18:20:27.866  1015  1512 D SettingsProvider: selectionArgs: false
,08-26 18:20:27.866  1015  1512 D SettingsProvider: selectionArgs: 1002
08-26 18:20:27.866  1015  1512 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 18:20:27.866  1015  1512 D SettingsProvider: ret = -1
08-26 18:20:27.866  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-26 18:20:27.866  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.866  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.866  1015  1027 D SettingsProvider: selectionArgs: false
,08-26 18:20:27.866  1015  1027 D SettingsProvider: selectionArgs: 1002
08-26 18:20:27.866  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.866  1015  1027 D SettingsProvider: ret = -1
08-26 18:20:27.876  1015  1496 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 18:20:27.876  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.876  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 18:20:27.876  1015  1496 D SettingsProvider: selectionArgs: false
08-26 18:20:27.876  1015  1496 D SettingsProvider: selectionArgs: 1002
08-26 18:20:27.876  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.876  1015  1496 D SettingsProvider: ret = -1
08-26 18:20:27.876  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:27.876  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.876  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.876  1015  1494 D SettingsProvider: selectionArgs: false
08-26 18:20:27.876  1015  1494 D SettingsProvider: selectionArgs: 1002
08-26 18:20:27.876  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.876  1015  1494 D SettingsProvider: ret = -1
,08-26 18:20:27.876  1015  4357 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:27.876  1015  4357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.876  1015  4357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.876  1015  4357 D SettingsProvider: selectionArgs: false
08-26 18:20:27.876  1015  4357 D SettingsProvider: selectionArgs: 1002
08-26 18:20:27.876  1015  4357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 18:20:27.876  1015  4357 D SettingsProvider: ret = -1
08-26 18:20:27.876  1015  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 18:20:27.876  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.876  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.876  1015  1535 D SettingsProvider: selectionArgs: false
08-26 18:20:27.876  1015  1535 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.876  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.876  1015  1535 D SettingsProvider: ret = -1
08-26 18:20:27.876  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 18:20:27.876  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:27.876  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:27.876  1015  1216 D SettingsProvider: selectionArgs: false
08-26 18:20:27.876  1015  1216 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:27.876  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:27.876  1015  1216 D SettingsProvider: ret = -1
,08-26 18:20:27.886  7490  7490 D BluetoothAdapterState: make
,08-26 18:20:27.896  7490  7490 I bluedroid: init
,08-26 18:20:27.896  7490  7505 I BluetoothAdapterState: Entering OffState,
08-26 18:20:27.896  7490  7490 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 18:20:27.896  7490  7490 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 18:20:27.896  7490  7490 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 18:20:27.896  7490  7490 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 18:20:27.896  7490  7490 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 18:20:27.896  7490  7490 I bluedroid: get_profile_interface socket
08-26 18:20:27.896  7490  7490 I bluedroid: get_profile_interface map_client
08-26 18:20:27.896  7490  7508 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 18:20:27.896  7490  7490 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 18:20:27.906  7490  7508 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 18:20:27.906  7490  7508 E BluetoothServiceJni: populateRssiValuesNative
08-26 18:20:27.906  7490  7508 I bluedroid: getModelRssiValues
08-26 18:20:27.906  7490  7508 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 18:20:27.906  7490  7508 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 18:20:27.906  1015  1015 D SettingsProvider: name = bluetooth_name
08-26 18:20:27.906  7490  7508 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 18:20:27.916  7490  7490 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:27.916  1015  4357 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 18:20:27.916  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:27.916  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:27.916  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:27.916  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:27.916  7490  7498 I bluedroid: config_hci_snoop_log
,08-26 18:20:27.916  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-26 18:20:27.916  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-26 18:20:27.916  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 18:20:27.916  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 18:20:27.916  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 18:20:27.926  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:27.926  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:27.926  7490  7490 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 18:20:27.926  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 18:20:27.926  7490  7505 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-26 18:20:27.926  7490  7505 D BluetoothAdapterProperties: Setting state to 11
08-26 18:20:27.926  7490  7505 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 18:20:27.926  7490  7505 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:27.926  7490  7505 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 18:20:27.936  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 18:20:27.936  7490  7505 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:27.936  7490  7505 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 18:20:27.936  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:27.936  7490  7505 D BluetoothSecureManager: getInstant: null
08-26 18:20:27.936  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
08-26 18:20:27.936  7490  7505 D BluetoothSecureManager: calling getMethod for getService
08-26 18:20:27.936  7490  7505 D BluetoothSecureManager: calling getService
,08-26 18:20:27.936  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 18:20:27.946  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:27.946  1178  1178 D BluetoothTile:  getBluetoothState : 11
08-26 18:20:27.946  7490  7505 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@45eabe0
,08-26 18:20:27.946  1015  1494 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 18:20:27.946  1015  1494 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 18:20:27.946  7490  7505 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 18:20:27.946  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 18:20:27.946  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 18:20:27.946  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:27.946  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 18:20:27.946  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 18:20:27.946  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
08-26 18:20:27.946  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 18:20:27.946  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 18:20:27.946  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 18:20:27.946  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 18:20:27.946  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 18:20:27.946  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 18:20:27.946  1015  1134 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:27.946  1015  1216 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 18:20:27.956  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 18:20:27.956  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 18:20:27.956  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:27.956  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 18:20:27.956  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 18:20:27.956  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:27.956  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 18:20:27.956  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 18:20:27.966  7490  7505 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 18:20:27.966  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:27.966  7490  7505 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:27.966  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 18:20:27.966  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:27.966  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:27.976  7490  7505 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:27.976  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 18:20:27.976  7490  7505 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:27.976  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 18:20:27.976  7490  7505 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 18:20:27.986  7490  7505 D BluetoothBondStateMachine: make
,08-26 18:20:27.986  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 18:20:27.986  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 18:20:27.986  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 18:20:27.986  7490  7510 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 18:20:28.116  1015  1496 I art     : Explicit concurrent mark sweep GC freed 80166(4MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.501ms total 170.010ms
,08-26 18:20:28.126  1015  1319 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:28.126  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.126  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.126  1015  1319 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:28.126  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:28.126  1015  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.126  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.126  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.126  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.126  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.126  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 18:20:28.126  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 18:20:28.126  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:28.126  7490  7490 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 18:20:28.136  7490  7490 D BtGatt.GattService: Received start request. Starting profile...
,08-26 18:20:28.136  7490  7490 D BtGatt.GattService: start()
08-26 18:20:28.136  7490  7490 D BtGatt.GattService: start()
08-26 18:20:28.136  7490  7490 I bluedroid: get_profile_interface gatt
,08-26 18:20:28.136  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
08-26 18:20:28.136  7490  7490 D BtGatt.AdvertiseManager: advertise manager created
08-26 18:20:28.136  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.136  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.136  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.136  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:28.136  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.136  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:28.146  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:28.146  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 18:20:28.146  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:28.146  7490  7490 D BtGatt.GattService: mStartError = false
08-26 18:20:28.146  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:28.156  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:28.156  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-26 18:20:28.156  7490  7490 D HeadsetService: Received start request. Starting profile...
08-26 18:20:28.156  1015  1495 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-26 18:20:28.156  7490  7490 D HeadsetService: start()
08-26 18:20:28.156  7490  7490 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-26 18:20:28.156  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:28.156  7490  7490 D HeadsetStateMachine: make
08-26 18:20:28.156  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:28.156  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:28.156  1015  1495 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:28.166  7490  7490 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 18:20:28.176  7515  7515 E Zygote  : MountEmulatedStorage()
08-26 18:20:28.176  7515  7515 I libpersona: KNOX_SDCARD checking this for 10055
08-26 18:20:28.176  7515  7515 E Zygote  : v2
08-26 18:20:28.176  7515  7515 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:28.176  7515  7515 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:28.176  7515  7515 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:28.186  7515  7515 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 18:20:28.186  1015  1495 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7515 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-26 18:20:28.186  1015  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.186  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.186  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.186  1015  1494 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 18:20:28.186  1015  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.186  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-26 18:20:28.186  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.186  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.186  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.186  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 18:20:28.196  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 18:20:28.196  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:28.196  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 18:20:28.196  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:28.196  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 18:20:28.196  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.196  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.196  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.196  1015  4357 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 18:20:28.196  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 18:20:28.196  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 18:20:28.196  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 18:20:28.196  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.196  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.196  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.196  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 18:20:28.196  7490  7490 I bluedroid: get_profile_interface handsfree
,08-26 18:20:28.196  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.196  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-26 18:20:28.206  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.206  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.206  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.206  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 18:20:28.206  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 18:20:28.206  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 18:20:28.206  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.206  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.206  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.216  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.216  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.216  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 18:20:28.216  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:28.216  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:28.216  1015  4518 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.216  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.216  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.216  1015  4518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.216  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:28.216  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 18:20:28.216  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:28.216  7490  7505 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 18:20:28.226  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.226  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.226  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.226  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.226  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:28.226  7515  7515 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:28.226  7515  7515 D ActivityThread: Added TimaKeyStore provider
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:28.226  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:28.226  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 18:20:28.226  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 18:20:28.226  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 18:20:28.226  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 18:20:28.226  7490  7505 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 18:20:28.226  7490  7490 I DualScoManager: Instantiating Dual Sco Manager
08-26 18:20:28.226  7490  7490 I DualScoManager: Set HeadsetServiceHelper
,08-26 18:20:28.236  7490  7490 D BluetoothAtMessage: createCMTIContentObservers
,08-26 18:20:28.236  1015  1533 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-26 18:20:28.236  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:28.236  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:28.236  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:28.236  1015  1533 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:28.236  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:28.236  1015  1533 D SettingsProvider: ret = -1
,08-26 18:20:28.236  7490  7514 D HeadsetStateMachine: Enter Disconnected: -2
08-26 18:20:28.236  7490  7490 D HeadsetService: mStartError = false
08-26 18:20:28.236  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:28.236  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 18:20:28.236  7490  7490 D A2dpService: Received start request. Starting profile...
08-26 18:20:28.236  7490  7490 D A2dpService: start()
,08-26 18:20:28.236  7490  7514 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 18:20:28.246  7490  7514 D HeadsetStateMachine: map size, before remove : 0
,08-26 18:20:28.246  7490  7514 D HeadsetStateMachine: map size, after remove: 0
08-26 18:20:28.246  7490  7490 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 18:20:28.246  7490  7490 I bluedroid: get_profile_interface avrcp
,08-26 18:20:28.246  7490  7490 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 18:20:28.246  7490  7490 D Avrcp   : Initialize Media Controller
08-26 18:20:28.246  7490  7490 D Avrcp   : Get the Context Package Name: com.android.bluetooth
08-26 18:20:28.246  7490  7490 E Avrcp   : getActiveSessions
08-26 18:20:28.246  7490  7490 D Avrcp   : pick active media Controller
08-26 18:20:28.246  7490  7490 D Avrcp   : Get the active Media Controller 
,08-26 18:20:28.256  7515  7515 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 18:20:28.266  7490  7490 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 18:20:28.266  7490  7533 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,08-26 18:20:28.266  7490  7490 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 18:20:28.266  7490  7490 D A2dpStateMachine: make
,08-26 18:20:28.276  7490  7490 I bluedroid: get_profile_interface a2dp
,08-26 18:20:28.276  7490  7535 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 18:20:28.276  7490  7490 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 18:20:28.276  7490  7490 D A2dpService: mStartError = false
08-26 18:20:28.276  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:28.276  7490  7490 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 18:20:28.276  7490  7534 D A2dpStateMachine: Enter Disconnected: -2
,08-26 18:20:28.276  1443  1458 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 18:20:28.276  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 18:20:28.276  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 18:20:28.276  1443  1458 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 18:20:28.276  7490  7490 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 18:20:28.276  7490  7490 D HeadsetStateMachine: Proxy object connected
,08-26 18:20:28.286  7490  7490 D HidService: Received start request. Starting profile...
08-26 18:20:28.286  7490  7490 D HidService: start()
08-26 18:20:28.286  7490  7490 I bluedroid: get_profile_interface hidhost
08-26 18:20:28.286  7490  7490 D HidService: setHidService(): set to: null
08-26 18:20:28.286  7490  7490 D HidService: mStartError = false
08-26 18:20:28.286  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:28.286  7490  7490 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 18:20:28.286  7490  7490 I BluetoothHealthServiceJni: classInitNative: succeeds
08-26 18:20:28.286  7490  7514 D HeadsetStateMachine: Disconnected process message: 11
,08-26 18:20:28.286  7490  7490 D HealthService: Received start request. Starting profile...
08-26 18:20:28.286  7490  7490 D HealthService: start()
,08-26 18:20:28.286  7490  7490 I bluedroid: get_profile_interface health
08-26 18:20:28.286  7490  7490 D HealthService: mStartError = false
08-26 18:20:28.286  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:28.286  7490  7490 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 18:20:28.286  7515  7515 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 18:20:28.286  7490  7490 D PanService: Received start request. Starting profile...
08-26 18:20:28.286  7490  7490 D PanService: start()
08-26 18:20:28.286  7490  7490 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 18:20:28.286  7490  7490 I bluedroid: get_profile_interface pan
,08-26 18:20:28.286  7515  7515 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 18:20:28.286  7515  7515 D UserAnalysis: Create SecureDbHelper
08-26 18:20:28.286  7490  7490 D PanService: mStartError = false
08-26 18:20:28.286  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba,
,08-26 18:20:28.296  7490  7533 D BluetoothMediaBrowser: no now playing list
08-26 18:20:28.296  7490  7490 D BluetoothMapService: Received start request. Starting profile...
08-26 18:20:28.296  7490  7490 D BluetoothMapService: start()
,08-26 18:20:28.296  7490  7490 D BluetoothMapService: mStartError = false
08-26 18:20:28.296  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
08-26 18:20:28.296  7490  7490 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-26 18:20:28.296  7490  7490 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 18:20:28.296  7490  7514 D HeadsetStateMachine: Disconnected process message: 18
08-26 18:20:28.296  7490  7533 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-26 18:20:28.296  7490  7490 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 18:20:28.296  7490  7490 D SapService: Received start request. Starting profile...
08-26 18:20:28.296  7490  7490 D SapService: start()
08-26 18:20:28.296  7490  7490 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 18:20:28.296  7490  7490 I bluedroid: get_profile_interface sap
08-26 18:20:28.296  7490  7490 D SapService: mStartError = false
08-26 18:20:28.296  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
08-26 18:20:28.296  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 18:20:28.296  7490  7490 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 18:20:28.296  7490  7490 D BluetoothA2dp: Proxy object connected
08-26 18:20:28.296  7490  7490 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 18:20:28.296  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 18:20:28.296  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 18:20:28.296  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-26 18:20:28.296  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 18:20:28.296  7490  7514 D HeadsetStateMachine: Disconnected process message: 10
,08-26 18:20:28.296  7490  7514 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 18:20:28.296  7490  7514 D HeadsetStateMachine: Disconnected process message: 11
,08-26 18:20:28.306  7515  7515 D IntelligenceServiceApplication: onCreate(),
,08-26 18:20:28.306  1015  1216 I ActivityManager: Killing 7182:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-26 18:20:28.316  7515  7515 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 18:20:28.316  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 18:20:28.316  7515  7515 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 18:20:28.326  7515  7515 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 18:20:28.336  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 18:20:28.336  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 18:20:28.336  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 18:20:28.336  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:28.336  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:28.336  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:28.336  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:28.346  7541  7541 E Zygote  : MountEmulatedStorage(),
08-26 18:20:28.346  7541  7541 I libpersona: KNOX_SDCARD checking this for 10105
08-26 18:20:28.346  7541  7541 E Zygote  : v2
,08-26 18:20:28.346  7541  7541 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:28.346  1015  1028 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7541 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-26 18:20:28.356  7541  7541 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:28.356  7541  7541 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:28.356  7490  7505 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 18:20:28.356  7490  7505 I bluedroid: enable
,08-26 18:20:28.356  7541  7541 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 18:20:28.366  7490  7505 I bt_hci_bdroid: init,
,08-26 18:20:28.366  7490  7550 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
,08-26 18:20:28.366  7490  7505 I bt_vendor: bt-vendor : init
08-26 18:20:28.366  7490  7505 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 18:20:28.366  7490  7505 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 18:20:28.366  7490  7505 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 18:20:28.366  7490  7505 D bt_userial_mct: userial_init
,08-26 18:20:28.366  7490  7505 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 18:20:28.366  7490  7505 I bt_vendor: Starting hciattach daemon
08-26 18:20:28.366  7490  7505 I bt_vendor: try to set false
08-26 18:20:28.366  7490  7505 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-26 18:20:28.366  7490  7505 I bt_vendor: Starting hciattach daemon
08-26 18:20:28.366  7490  7505 I bt_vendor: try to set true
,08-26 18:20:28.376  7541  7541 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:28.376  7541  7541 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:28.386  7560  7560 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 18:20:28.436  7566  7566 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-26 18:20:28.446  7567  7567 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 18:20:28.466  7570  7570 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 18:20:28.466  7571  7571 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-26 18:20:28.476  7573  7573 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 18:20:28.486  7574  7574 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 18:20:28.526   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 18:20:28.526   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:28.526  7541  7578 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 18:20:28.526   257   527 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-26 18:20:28.526   257   527 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 18:20:28.536  7541  7578 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=133 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.v.a(PG,:1161)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.k.d(PG:583)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.e.b(PG:170)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a,(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.666  7541  7541 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:28.666  7541  7541 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:28.676  1015  1533 I ActivityManager: Killing 7166:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-26 18:20:28.676  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 18:20:28.686  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 18:20:28.716  7589  7589 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-26 18:20:28.726  7590  7590 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-26 18:20:28.746  7541  7588 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-26 18:20:28.766  1015  4518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:28.766  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.766  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:28.766  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 18:20:28.766  7490  7505 I bt_vendor: bluetooth satus is on
,08-26 18:20:28.766  7490  7552 D bt_userial_mct: userial_open(port:0)
,08-26 18:20:28.776  7490  7552 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 18:20:28.776  7490  7552 I bt_vendor: Done intiailizing UART
,08-26 18:20:28.776  7490  7552 I bt_vendor: Done intiailizing UART
08-26 18:20:28.776  7490  7552 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 18:20:28.776  7490  7552 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-26 18:20:28.786  7490  7594 D bt_userial_mct: Entering userial_read_thread()
,08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_HCI
,08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 18:20:28.786  1015  3374 D SSRM:n  : SIOP:: AP = 380
,08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_A2D
,08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 18:20:28.786  7490  7550 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 18:20:28.876  7490  7550 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 18:20:28.886  7490  7550 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa430ded1 
,08-26 18:20:28.886  7490  7550 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa430ded1 
,08-26 18:20:28.896  7490  7508 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 18:20:28.906  7490  7508 E bt-btif : Calling BTA_HhEnable
,08-26 18:20:28.906  7490  7508 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 18:20:28.906  7490  7508 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 18:20:28.906  7490  7508 E BluetoothServiceJni: populateRssiValuesNative
08-26 18:20:28.906  7490  7508 I bluedroid: getModelRssiValues
,08-26 18:20:28.906  7490  7508 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 18:20:28.906  7490  7508 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 18:20:28.916  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 18:20:28.916  7490  7508 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 18:20:28.926  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:28.926  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:28.926  7490  7508 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 18:20:28.926  7490  7508 D BluetoothAdapterProperties: Scan Mode:20
,08-26 18:20:28.926  7490  7508 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 18:20:28.926  7490  7508 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-26 18:20:28.926  7490  7508 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-26 18:20:28.926  7490  7508 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 18:20:28.936  7490  7508 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 18:20:28.936  7490  7508 E bt-btif : btif_sock_init: !vhci_init
,08-26 18:20:28.936  7490  7508 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-26 18:20:28.936  7490  7594 E bt_mct  : hci lib postload completed
,08-26 18:20:28.936  7490  7508 D IOP_DB_BT: db_open: db_open : handle 3028549648l, read 13894 bytes onto local cache
,08-26 18:20:28.936  7490  7508 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 18:20:28.936  7490  7508 D IOP_DB_BT: db_query: result 1
,08-26 18:20:28.936  7490  7508 I         : iop_db_open: iop_db_open status 0
,08-26 18:20:28.936  7490  7508 D bte_conf: Device ID record 1 : primary
,08-26 18:20:28.936  7490  7508 D bte_conf:   vendorId            = 0075
08-26 18:20:28.936  7490  7508 D bte_conf:   vendorIdSource      = 0001
,08-26 18:20:28.936  7490  7508 D bte_conf:   product             = 0100
08-26 18:20:28.946  7490  7508 D bte_conf:   version             = 0200
08-26 18:20:28.946  7490  7508 D bte_conf:   clientExecutableURL = 
08-26 18:20:28.946  7490  7508 D bte_conf:   serviceDescription  = 
08-26 18:20:28.946  7490  7508 D bte_conf:   documentationURL    = 
08-26 18:20:28.946  7490  7508 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 18:20:28.946  7490  7508 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 18:20:28.946  7490  7505 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-26 18:20:28.946  7490  7505 D BluetoothAdapterProperties: ScanMode =  20
,08-26 18:20:28.946  7490  7505 D BluetoothAdapterProperties: State =  11
,08-26 18:20:28.946  1015  1535 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 18:20:28.946  7490  7505 D BluetoothAdapterProperties: Setting state to 12
,08-26 18:20:28.946  7490  7505 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 18:20:28.946  7490  7508 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 18:20:28.946  7490  7508 D BluetoothAdapterProperties: Scan Mode:21
,08-26 18:20:28.946  7490  7508 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:28.956  1015  1533 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-26 18:20:28.956  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:28.956  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:28.956  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:28.956  1015  1533 D SettingsProvider: selectionArgs: 1002
08-26 18:20:28.956  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:28.956  1015  1533 D SettingsProvider: ret = -1
08-26 18:20:28.956  7490  7505 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:28.956  7490  7505 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 18:20:28.956  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.956  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.956  1015  1494 W ActivityManager: userId = 0, bbcId = -10000,
08-26 18:20:28.956  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.956  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
,08-26 18:20:28.966  7490  7505 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:28.966  7490  7505 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 18:20:28.966  7490  7505 D BluetoothAdapterService: starting service from this receiver
,08-26 18:20:28.966  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:28.966  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.966  4126  4140 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 18:20:28.966  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.966  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.966  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.966  7490  7505 I BluetoothAdapterState: Entering On State from state = 11
,08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:28.966  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:28.976  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:28.976  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:28.976  4126  4140 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:28.976  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 18:20:28.976  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:28.986  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:28.986  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:28.986  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:28.986  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.986  7490  7490 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12,
,08-26 18:20:28.996  4126  4140 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:28.996  4126  4140 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:28.996  4126  4126 D BluetoothA2dp: Proxy object connected
08-26 18:20:28.996  4126  4126 D A2dpProfile: Bluetooth service connected
,08-26 18:20:28.996  4126  4136 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 18:20:28.996  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 18:20:28.996  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 18:20:28.996  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:28.996  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:28.996  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:28.996  7490  7490 I BluetoothPbapService: Handler(): got msg=1
,08-26 18:20:28.996  1015  4357 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-26 18:20:28.996  1443  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:28.996  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 18:20:28.996  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:29.006  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.006  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.006  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.006  1443  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.006  4126  4126 D BluetoothInputDevice: Proxy object connected
08-26 18:20:29.006  4126  4126 D HidProfile: Bluetooth service connected
,08-26 18:20:29.006  1015  1044 D BluetoothPan: Binding service...
,08-26 18:20:29.006  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 18:20:29.006  7490  7599 V BluetoothPbapService: PBAP Service initSocket try: 0
08-26 18:20:29.006  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.006  6866  6877 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.006  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 18:20:29.006  6866  6877 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:29.006  7490  7498 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 18:20:29.016  1178  1802 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:29.016  1178  1802 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:29.016  7490  7599 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 18:20:29.016  7490  7599 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:29.016  7490  7599 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-26 18:20:29.016  7490  7599 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:29.016  7490  7599 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:29.016  7490  7599 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b734b04
,08-26 18:20:29.016  7490  7599 D BluetoothSocket: channel: 19
08-26 18:20:29.016  7490  7599 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 18:20:29.016  1443  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:29.016  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 18:20:29.016  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:29.016  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.016  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:29.016  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.016  1443  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.026  1443  7600 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.026  1443  7600 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:29.026  4126  7598 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 18:20:29.026  4126  7598 D Bluetoothsap: Binding service...
,08-26 18:20:29.026  4126  7598 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 18:20:29.026  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-26 18:20:29.026  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.026  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.026  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.026  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.026  4126  7598 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 18:20:29.026  4126  4136 D BluetoothPbap: onBluetoothStateChange: up=true
08-26 18:20:29.026  4126  4126 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 18:20:29.026  4126  4126 D SapProfile: Bluetooth service connected
08-26 18:20:29.026  4126  4126 D Bluetoothsap: getConnectedDevices()
,08-26 18:20:29.036  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 18:20:29.036  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.036  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.036  1469  1864 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:29.036  4126  4126 D BluetoothPbap: Proxy object connected
08-26 18:20:29.036  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:29.036  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:29.036  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.036  4126  4126 D PbapServerProfile: Bluetooth service connected
08-26 18:20:29.036  1469  1864 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.036  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 18:20:29.036  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 18:20:29.036  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 18:20:29.036  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.036  1015  1015 D BluetoothA2dp: Proxy object connected
,08-26 18:20:29.036  1443  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:29.036  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:29.036  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:29.036  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.036  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 18:20:29.036  1443  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.046  4126  7598 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 18:20:29.046  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 18:20:29.046  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.046  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:29.046  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.046  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.046  7541  7549 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.046  7541  7549 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:29.046  4126  4126 D BluetoothMap: Proxy object connected
08-26 18:20:29.046  4126  4126 D MapProfile: Bluetooth service connected
08-26 18:20:29.046  4126  4126 D BluetoothMap: getConnectedDevices()
08-26 18:20:29.046  7490  7499 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:29.046  7490  7499 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:29.046  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:29.046  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:29.046  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 18:20:29.046  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.046  4126  4136 D BluetoothPan: Binding service...
,08-26 18:20:29.046  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 18:20:29.046  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.056  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.056  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.056  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.056  1972  1983 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.056  1972  1983 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:29.056  1456  1492 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.056  1456  1492 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:29.056  4126  4126 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 18:20:29.056  4126  4126 D PanProfile: Bluetooth service connected
,08-26 18:20:29.056  4126  4140 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:29.056  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:29.056  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:29.056  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.056  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.056  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.056  4126  4140 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:29.056  1469  1768 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 18:20:29.056  1469  1768 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:29.056  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:29.056  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:29.056  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 18:20:29.056  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-26 18:20:29.056  4126  4126 D HeadsetProfile: Bluetooth service connected
,08-26 18:20:29.066  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:29.066  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-26 18:20:29.066  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 18:20:29.066  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3f8d9a40, true
,08-26 18:20:29.066  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 18:20:29.076  1443  1443 D BluetoothHeadset: registerMessageListener
,08-26 18:20:29.076  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 18:20:29.076  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.076  1178  1178 D BluetoothTile:  getBluetoothState : 12
,08-26 18:20:29.076  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 18:20:29.076  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:29.076  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 18:20:29.076  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:29.076  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:29.086  7490  7509 D HeadsetService: registerMessageListener
,08-26 18:20:29.086  1015  3406 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:29.086  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.086  7490  7509 D HeadsetService: registerMessageListener
,08-26 18:20:29.086  7490  7514 D HeadsetStateMachine: Disconnected process message: 70
08-26 18:20:29.086  7490  7514 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1a0a58ed
,08-26 18:20:29.086  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
08-26 18:20:29.086  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.086  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-26 18:20:29.086  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.086  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 18:20:29.086  1015  3406 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:29.086  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:29.086  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:29.096  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:29.096  4126  4126 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 18:20:29.096  4126  4126 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 18:20:29.096  4126  4126 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 18:20:29.096  4126  4126 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 18:20:29.096  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:29.096  7490  7604 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 18:20:29.096  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 18:20:29.096  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-26 18:20:29.106  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 18:20:29.106  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 18:20:29.106  1015  3406 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 18:20:29.106  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 18:20:29.106  7490  7514 D HeadsetStateMachine: Disconnected process message: 9
,08-26 18:20:29.106  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.106  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:29.106  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 18:20:29.106  7490  7514 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 18:20:29.116  7490  7604 D BluetoothSocket: bindListen(): myUserId = 0
08-26 18:20:29.116  7490  7604 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:29.116  7490  7604 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 18:20:29.116  7490  7604 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:29.116  7490  7604 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:29.116  7490  7604 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ce4322
08-26 18:20:29.116  7490  7604 D BluetoothSocket: channel: 5
,08-26 18:20:29.116  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:29.126  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:29.126   283   674 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 18:20:29.126   283   674 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 18:20:29.126   283   674 V voice   : voice_set_parameters: exit with code(-2)
08-26 18:20:29.126   283   674 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 18:20:29.126   283   674 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 18:20:29.126   283   674 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 18:20:29.126   283   674 V audio_hw_primary: adev_set_parameters: exit
08-26 18:20:29.126  7490  7514 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 18:20:29.126  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:29.126  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 18:20:29.136  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:29.136  7490  7490 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 18:20:29.136  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:29.136  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.136  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:29.136  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:29.136  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:29.156  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:29.156  1015  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:29.156  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:29.156  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:29.156  1015  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:29.156  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:29.166  1972  7610 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 18:20:29.166  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 18:20:29.166  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:29.176  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:29.176  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:29.176  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:29.176  1015  4357 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 18:20:29.186  1015  4357 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:29.186  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:29.186  1015  4357 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:29.186  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:29.196  7490  7614 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 18:20:29.196  7490  7614 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:29.196  7490  7614 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-26 18:20:29.196  7490  7614 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:29.196  7490  7614 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:29.196  7490  7614 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c6f69c
,08-26 18:20:29.196  1972  7610 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
08-26 18:20:29.196  7490  7614 D BluetoothSocket: channel: 12
,08-26 18:20:29.196  7490  7614 I BtOppRfcommListener: Accept thread started.
,08-26 18:20:29.506   288   288 E SMD     : DCD OFF,
,08-26 18:20:30.716  6866  6920 D BluetoothAdapter: disable()
,08-26 18:20:30.726  1015  1512 D SettingsProvider: name = bluetooth_on
,08-26 18:20:30.736  7490  7505 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 18:20:30.736  7490  7505 D BluetoothAdapterProperties: Setting state to 13
08-26 18:20:30.736  7490  7505 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 18:20:30.736  7490  7505 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:30.736  7490  7505 D BluetoothAdapterService: updateAdapterState state is 13
,08-26 18:20:30.736  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:30.736  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:30.736  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:30.736  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:30.736  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:30.736  7490  7505 D BluetoothAdapterService: Autoconnection is available 
,08-26 18:20:30.736  7490  7505 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-26 18:20:30.736  7490  7505 D BluetoothAdapterService: terminating service from this receiver
08-26 18:20:30.746  7490  7490 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-26 18:20:30.746  7490  7490 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1382b8a5, channel: 19, state: LISTENING
08-26 18:20:30.746  7490  7490 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1382b8a5, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1b734b04, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1789147amSocket: android.net.LocalSocket@19f7142b impl:android.net.LocalSocketImpl@1a9ae088 fd:FileDescriptor[74]
08-26 18:20:30.746  7490  7490 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@19f7142b impl:android.net.LocalSocketImpl@1a9ae088 fd:FileDescriptor[74]
,08-26 18:20:30.746  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:30.746  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-26 18:20:30.746  1178  1178 D BluetoothTile:  onBluetoothStateChange:
,08-26 18:20:30.756  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 18:20:30.756  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:30.756  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 18:20:30.756  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:30.756  1178  1178 D BluetoothTile:  getBluetoothState : 13
,08-26 18:20:30.756  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 18:20:30.766  1879  1879 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 18:20:30.766  1015  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:30.766  1015  1319 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 18:20:30.766  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:30.766  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 18:20:30.766  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:30.766  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 18:20:30.776  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:30.776  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:30.776  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:30.776  7490  7505 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 18:20:30.776  7490  7505 D BluetoothAdapterProperties: mDiscovering is false
,08-26 18:20:30.776  1015  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:30.776  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 18:20:30.776  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:30.776  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:30.776  1015  1533 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 18:20:30.776  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:30.776  7490  7505 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 18:20:30.776  1015  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:30.776  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:30.776  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 18:20:30.776  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:30.786  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 18:20:30.786  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:30.786  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:30.786  6866  6866 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 18:20:30.786  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:30.786  1015  1533 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 18:20:30.786  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 18:20:30.786  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:30.786  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:30.786  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 18:20:30.796  7490  7508 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 18:20:30.796  7490  7508 D BluetoothAdapterProperties: Scan Mode:20
,08-26 18:20:30.796  4126  4126 D BluetoothPbap: Proxy object disconnected
08-26 18:20:30.796  4126  4126 D PbapServerProfile: Bluetooth service disconnected
,08-26 18:20:30.806  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:30.806  7490  7505 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 18:20:30.806  7490  7505 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 18:20:30.806  7490  7505 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 18:20:30.806  7490  7505 E bt-btif : cmd socket is not created
08-26 18:20:30.806  7490  7614 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-26 18:20:30.806  7490  7550 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 18:20:30.806  7490  7550 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 18:20:30.806  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:30.806  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:30.806  7490  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:30.806  7490  7505 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 18:20:30.806  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:30.816  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:30.816  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:30.816  7490  7490 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@358b3a21, channel: 5, state: LISTENING
,08-26 18:20:30.816  7490  7490 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@358b3a21, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ce4322, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@e83fe46mSocket: android.net.LocalSocket@15d0c807 impl:android.net.LocalSocketImpl@23417d34 fd:FileDescriptor[76]
08-26 18:20:30.816  7490  7490 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15d0c807 impl:android.net.LocalSocketImpl@23417d34 fd:FileDescriptor[76]
08-26 18:20:30.816  7490  7490 I BtOppRfcommListener: stopping Accept Thread
08-26 18:20:30.816  7490  7490 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@140575d, channel: 12, state: LISTENING
08-26 18:20:30.816  7490  7490 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@140575d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c6f69c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11f1b8d2mSocket: android.net.LocalSocket@ea7dda3 impl:android.net.LocalSocketImpl@321338a0 fd:FileDescriptor[79]
08-26 18:20:30.816  7490  7490 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@ea7dda3 impl:android.net.LocalSocketImpl@321338a0 fd:FileDescriptor[79]
,08-26 18:20:30.816  7490  7614 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 18:20:30.816  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:30.816  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 18:20:30.826  7490  7490 V BluetoothOppManager: cleanUp...
,08-26 18:20:30.846  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:30.846  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 18:20:31.006  7490  7550 W bt-btif : ag scb idx 1 not allocated
08-26 18:20:31.006  7490  7550 W bt-btif : ag scb idx 2 not allocated
08-26 18:20:31.006  7490  7550 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 18:20:31.006  7490  7594 I bt_userial_mct: exiting userial_read_thread
08-26 18:20:31.006  7490  7594 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 18:20:31.006  7490  7508 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 18:20:31.006  7490  7552 I bt_vendor: hw_epilog_process
08-26 18:20:31.006  7490  7508 D bt_userial_mct: userial_close
08-26 18:20:31.006  7490  7508 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 18:20:31.636  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 18:20:31.636  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-26 18:20:31.636  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-26 18:20:31.636  1015  1027 D BatteryService: stay LED for fully charged
08-26 18:20:31.636  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 18:20:31.646  1015  1015 I MotionRecognitionService: Plugged
,08-26 18:20:31.646  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 18:20:31.646  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 18:20:31.646  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 18:20:31.646  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 18:20:31.646  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-26 18:20:31.666  7490  7490 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
08-26 18:20:31.666  7490  7514 D HeadsetStateMachine: Disconnected process message: 10
,08-26 18:20:31.676  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-26 18:20:31.676  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 18:20:31.676  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:31.676  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:31.676  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:31.816  7490  7508 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 18:20:31.816  7490  7508 I bt_vendor: bluetooth satus is on
08-26 18:20:31.816  7490  7508 I bt_vendor: bt-vendor : resetting BT status
08-26 18:20:31.816  7490  7508 I bt_vendor: Starting hciattach daemon
08-26 18:20:31.816  7490  7508 I bt_vendor: try to set false
,08-26 18:20:31.816  7490  7508 I bt_vendor: Starting hciattach daemon,
08-26 18:20:31.816  7490  7508 I bt_vendor: try to set false
08-26 18:20:31.816  7490  7508 I bt_vendor: cleanup
,08-26 18:20:31.816  7490  7550 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-26 18:20:31.816  7490  7508 I GKI_LINUX: GKI_exit_task 0 done
,08-26 18:20:31.816  7490  7508 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 18:20:31.816  7490  7505 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-26 18:20:31.816  1015  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.816  7490  7505 D BtConfig.SecureMode: isSecureModeOn:false
08-26 18:20:31.816  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 18:20:31.816  7490  7505 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 18:20:31.816  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 18:20:31.816  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 18:20:31.816  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 18:20:31.816  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.816  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.816  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:31.826  7490  7490 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 18:20:31.826  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 18:20:31.826  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 18:20:31.826  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.826  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 18:20:31.826  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-26 18:20:31.826  7490  7490 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 18:20:31.826  7490  7490 D BtGatt.GattService: stop()
08-26 18:20:31.826  7490  7490 D BtGatt.AdvertiseManager: advertise clients cleared
08-26 18:20:31.826  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.826  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.826  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:31.826  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.826  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 18:20:31.826  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 18:20:31.826  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:31.826  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.826  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:31.836  7490  7490 D HeadsetService: Received stop request...Stopping profile...,
08-26 18:20:31.836  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.836  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.836  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:31.836  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 18:20:31.836  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:31.836  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 18:20:31.836  1015  4357 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.836  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
08-26 18:20:31.836  1015  4357 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 18:20:31.836  1015  4357 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.836  1015  4357 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.836  1015  4357 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:31.836  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 18:20:31.836  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 18:20:31.836  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 18:20:31.836  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 18:20:31.836  4126  4126 D HeadsetProfile: Bluetooth service disconnected
,08-26 18:20:31.846  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:31.846  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 18:20:31.846  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:31.846  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:31.846  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:31.846  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 18:20:31.846  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 18:20:31.846  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-26 18:20:31.846  1015  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.846  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:31.846  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.846  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.846  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:31.846  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.846  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.846  7490  7505 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:31.846  1015  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.846  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-26 18:20:31.846  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:31.846  1015  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.846  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 18:20:31.856  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 18:20:31.856  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:31.856  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 18:20:31.856  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:31.856  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.856  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:31.856  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:31.856  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 18:20:31.856  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 18:20:31.856  7490  7505 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 18:20:31.856  7490  7505 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 18:20:31.856  7490  7505 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 18:20:31.856  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-26 18:20:31.856  7490  7490 D A2dpService: Received stop request...Stopping profile...
08-26 18:20:31.856  7490  7534 D A2dpStateMachine: Exit Disconnected: -1
,08-26 18:20:31.856  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.856  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:31.856  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-26 18:20:31.856  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 18:20:31.856  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:31.856  7490  7490 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 18:20:31.866  7490  7490 D HidService: Received stop request...Stopping profile...
08-26 18:20:31.866  7490  7490 D HidService: Stopping Bluetooth HidService
08-26 18:20:31.866  7490  7490 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 18:20:31.866  7490  7490 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 18:20:31.866  7490  7490 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 18:20:31.866  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.866  4126  4126 D BluetoothA2dp: Proxy object disconnected
,08-26 18:20:31.866  7490  7490 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 18:20:31.866  4126  4126 D A2dpProfile: Bluetooth service disconnected
08-26 18:20:31.866  7490  7490 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 18:20:31.866  7490  7490 D HealthService: Received stop request...Stopping profile...
08-26 18:20:31.866  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.866  4126  4126 D BluetoothInputDevice: Proxy object disconnected
08-26 18:20:31.866  4126  4126 D HidProfile: Bluetooth service disconnected
,08-26 18:20:31.866  7490  7490 D PanService: Received stop request...Stopping profile...
,08-26 18:20:31.866  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.866  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 18:20:31.866  4126  4126 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 18:20:31.866  4126  4126 D PanProfile: Bluetooth service disconnected
,08-26 18:20:31.866  7490  7490 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 18:20:31.876  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.876  7490  7490 D SapService: Received stop request...Stopping profile...
,08-26 18:20:31.876  7490  7490 D SapService: Stopping Bluetooth SapService
08-26 18:20:31.876  7490  7490 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4221dba
,08-26 18:20:31.876  4126  4126 D BluetoothMap: Proxy object disconnected
08-26 18:20:31.876  4126  4126 D MapProfile: Bluetooth service disconnected
,08-26 18:20:31.876  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-26 18:20:31.876  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:31.876  7490  7490 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 18:20:31.876  7490  7490 D BluetoothA2dp: Proxy object disconnected
08-26 18:20:31.876  7490  7490 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-26 18:20:31.886  7490  7535 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 18:20:31.886  7490  7490 I GKI_LINUX: GKI_exit_task 2 done
08-26 18:20:31.886  7490  7490 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 18:20:31.886  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-26 18:20:31.886  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.886  7490  7490 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.886  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 18:20:31.886  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.886  7490  7490 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:31.886  7490  7490 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 18:20:31.886  7490  7490 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-26 18:20:31.886  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 18:20:31.886  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.886  7490  7490 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:31.886  7490  7490 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...,
08-26 18:20:31.886  7490  7490 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 18:20:31.886  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 18:20:31.886  7490  7490 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:31.886  7490  7490 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 18:20:31.886  7490  7490 E BluetoothAdapterService(69344698): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-26 18:20:31.886  7490  7490 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 18:20:31.886  7490  7490 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 18:20:31.886  7490  7505 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 18:20:31.886  4126  4126 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 18:20:31.886  7490  7505 D BluetoothAdapterProperties: Setting state to 10
08-26 18:20:31.886  7490  7505 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 18:20:31.886  7490  7505 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:31.886  7490  7505 D BluetoothAdapterService: updateAdapterState state is 10
,08-26 18:20:31.886  7490  7505 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:31.886  7490  7505 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 18:20:31.886  7490  7505 I BluetoothAdapterState: Entering OffState
08-26 18:20:31.886  4126  4140 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 18:20:31.886  4126  4126 D SapProfile: Bluetooth service disconnected
,08-26 18:20:31.886  4126  7598 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:31.886  4126  7598 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.886  4126  4136 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 18:20:31.896  6866  6875 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.896  6866  6875 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:31.896  6866  6875 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,08-26 18:20:31.896  6866  6875 D BluetoothLeAdvertiser: Exit stop advertising
08-26 18:20:31.896  6866  6875 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 18:20:31.896  6866  6875 D BluetoothLeScanner: Exiting stopAllScan
,08-26 18:20:31.896  7490  7601 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 18:20:31.896  1178  3253 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.896  1178  3253 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.896  1443  7600 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.896  1443  7600 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.896  4126  4140 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 18:20:31.896  4126  4140 D Bluetoothsap: Unbinding service...
,08-26 18:20:31.896  4126  7598 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 18:20:31.896  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 18:20:31.896  4126  4136 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 18:20:31.906  7541  7553 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.906  7541  7553 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.906  7490  7602 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:31.906  7490  7602 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.906  1972  4839 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.906  1972  4839 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.906  1456  1492 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 18:20:31.906  1456  1492 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.906  1469  1480 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.906  1469  1480 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 18:20:31.906  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 18:20:31.906  1015  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 18:20:31.906  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-26 18:20:31.906  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 18:20:31.916  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:31.916  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-26 18:20:31.916  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 18:20:31.926  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
,08-26 18:20:31.926  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 18:20:31.926  1178  1743 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
,08-26 18:20:31.926  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:31.926  1178  1178 D BluetoothTile:  getBluetoothState : 10
,08-26 18:20:31.926  1178  1743 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
,08-26 18:20:31.926  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:31.926  1178  1178 D BluetoothAdapter: 674301957: getState() :  mService = null. Returning STATE_OFF
,08-26 18:20:31.926  1015  1028 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:31.926  1015  1495 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 18:20:31.926  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:31.926  1879  1879 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 18:20:31.926  7490  7508 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-26 18:20:31.936  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:31.936  7490  7490 I GKI_LINUX: GKI_exit_task 1 done
08-26 18:20:31.936  7490  7490 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 18:20:31.936  1972  2158 D BluetoothAdapter: 791931807: getState() :  mService = null. Returning STATE_OFF
08-26 18:20:31.936  7490  7490 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 18:20:31.936  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:31.936  1972  2158 D BluetoothAdapter: 791931807: getState() :  mService = null. Returning STATE_OFF
,08-26 18:20:31.936  1015  4518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:31.936  1015  4518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 18:20:31.936  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:31.936  1015  4518 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:31.936  1015  4518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:31.936  1015  4518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:31.936  7490  7490 I art     : System.exit called, status: 0
,08-26 18:20:31.936  7490  7490 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 18:20:31.936  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 18:20:31.936  1015  1495 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 18:20:31.936  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 18:20:31.936  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:31.936  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:31.946  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 18:20:31.946  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:31.946  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 18:20:31.946  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:31.966  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:31.966  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 18:20:31.976  1015  1512 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 18:20:31.976  1015  1512 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 18:20:31.976  1015  1512 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-26 18:20:31.976  1015  1512 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-26 18:20:31.976  1015  1512 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 18:20:31.976  1015  1512 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 18:20:31.976  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:31.976  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:31.976  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:31.976  1015  1512 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:31.986  7630  7630 E Zygote  : MountEmulatedStorage()
08-26 18:20:31.986  7630  7630 E Zygote  : v2
08-26 18:20:31.986  7630  7630 I libpersona: KNOX_SDCARD checking this for 1002
08-26 18:20:31.986  7630  7630 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:31.996  1015  1512 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7630 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-26 18:20:31.996  7630  7630 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:31.996  7630  7630 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:31.996  7630  7630 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:32.016   306   306 I art     : Explicit concurrent mark sweep GC freed 8689(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 21.292ms
,08-26 18:20:32.016  7630  7630 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:32.016  7630  7630 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:32.026  7630  7630 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 18:20:32.026  7630  7630 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:32.026   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 723us total 17.521ms
,08-26 18:20:32.046   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 564us total 16.371ms
,08-26 18:20:32.056  7630  7630 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding GattService
,08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding HidService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding HealthService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding PanService
,08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding SapService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding SapClientService
08-26 18:20:32.086  7630  7630 D BtSettings.ProfileConfig: Adding HidDevService
08-26 18:20:32.086  7630  7630 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 18:20:32.086  1015  4518 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 18:20:32.086  1015  4518 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.086  1015  4518 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.086  1015  4518 D SettingsProvider: selectionArgs: false
,08-26 18:20:32.086  1015  4518 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.086  1015  4518 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.086  1015  4518 D SettingsProvider: ret = -1
,08-26 18:20:32.086  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 18:20:32.086  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.086  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 18:20:32.086  1015  1216 D SettingsProvider: selectionArgs: false
08-26 18:20:32.086  1015  1216 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.086  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.086  1015  1216 D SettingsProvider: ret = -1
,08-26 18:20:32.086  1015  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 18:20:32.086  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 18:20:32.086  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.086  1015  1535 D SettingsProvider: selectionArgs: false
08-26 18:20:32.086  1015  1535 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.086  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.086  1015  1535 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  3406 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 18:20:32.096  1015  3406 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 18:20:32.096  1015  3406 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.096  1015  3406 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  3406 D SettingsProvider: selectionArgs: 1002
,08-26 18:20:32.096  1015  3406 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.096  1015  3406 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 18:20:32.096  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 18:20:32.096  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.096  1015  1028 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  1028 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.096  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.096  1015  1028 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 18:20:32.096  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.096  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 18:20:32.096  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  1533 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.096  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 18:20:32.096  1015  1533 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  1494 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 18:20:32.096  1015  1494 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.096  1015  1494 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.096  1015  1494 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  1494 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.096  1015  1494 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 18:20:32.096  1015  1494 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  1496 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 18:20:32.096  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.096  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.096  1015  1496 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  1496 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.096  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.096  1015  1496 D SettingsProvider: ret = -1
,08-26 18:20:32.096  1015  1495 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:32.096  1015  1495 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.096  1015  1495 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.096  1015  1495 D SettingsProvider: selectionArgs: false
08-26 18:20:32.096  1015  1495 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.096  1015  1495 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.096  1015  1495 D SettingsProvider: ret = -1
,08-26 18:20:32.106  1015  1319 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:32.106  1015  1319 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.106  1015  1319 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.106  1015  1319 D SettingsProvider: selectionArgs: false
08-26 18:20:32.106  1015  1319 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.106  1015  1319 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.106  1015  1319 D SettingsProvider: ret = -1
,08-26 18:20:32.106  1015  4357 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 18:20:32.106  1015  4357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.106  1015  4357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.106  1015  4357 D SettingsProvider: selectionArgs: false
08-26 18:20:32.106  1015  4357 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.106  1015  4357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.106  1015  4357 D SettingsProvider: ret = -1
,08-26 18:20:32.106  1015  1134 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 18:20:32.106  1015  1134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:32.106  1015  1134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:32.106  1015  1134 D SettingsProvider: selectionArgs: false
,08-26 18:20:32.106  1015  1134 D SettingsProvider: selectionArgs: 1002
08-26 18:20:32.106  1015  1134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:32.106  1015  1134 D SettingsProvider: ret = -1
,08-26 18:20:32.116  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:32.116  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:32.116  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:32.116  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:32.116  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:32.116  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:32.126  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 18:20:32.126  1972  7647 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 18:20:32.136  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:32.136  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:32.136  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:32.136  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:32.146  1972  7647 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 18:20:32.516   288   288 E SMD     : DCD OFF
,08-26 18:20:33.446  1015  1317 E Watchdog: !@Sync 4
,08-26 18:20:33.546  1015  1047 I PowerManagerService: [PWL] Off : 75s ago
,08-26 18:20:33.546  1015  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-26 18:20:33.546  1015  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-26 18:20:33.546  1015  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=13824)
,08-26 18:20:33.726  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 18:20:33.726  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:35.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:35.516   288   288 E SMD     : DCD OFF
,08-26 18:20:36.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 18:20:36.736  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:36.736  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@51f0f17 added. We now have 6 listener(s),
08-26 18:20:36.736  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:36.736  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:36.736  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@279c9f04 added. We now have 7 listener(s)
08-26 18:20:36.736  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:36.736  6866  6920 I System.out: IsBluetoothEnabled
,08-26 18:20:36.736  6866  6920 D BluetoothAdapter: disable(),
08-26 18:20:36.736  1015  1319 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 18:20:36.746  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 18:20:36.746  6866  6920 D BluetoothAdapter: enable()
,08-26 18:20:36.746  1015  3406 W ActivityManager: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-26 18:20:36.746  1015  3406 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-26 18:20:36.746  1015  3406 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 18:20:36.746  1015  3406 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 18:20:36.746  1015  3406 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:36.756  1015  3406 D SettingsProvider: name = bluetooth_on
,08-26 18:20:36.766  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 18:20:36.766  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:36.766  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 18:20:36.766  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 18:20:36.796  7630  7630 D BluetoothAdapterState: make
,08-26 18:20:36.796  7630  7630 I bluedroid: init
08-26 18:20:36.796  7630  7653 I BluetoothAdapterState: Entering OffState
,08-26 18:20:36.796  7630  7630 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 18:20:36.796  7630  7630 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 18:20:36.796  7630  7630 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 18:20:36.796  7630  7630 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 18:20:36.796  7630  7630 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 18:20:36.796  7630  7630 I bluedroid: get_profile_interface socket
08-26 18:20:36.796  7630  7630 I bluedroid: get_profile_interface map_client
08-26 18:20:36.796  7630  7656 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 18:20:36.806  7630  7630 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-26 18:20:36.806  7630  7656 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 18:20:36.806  7630  7656 E BluetoothServiceJni: populateRssiValuesNative
08-26 18:20:36.806  7630  7656 I bluedroid: getModelRssiValues
08-26 18:20:36.806  7630  7656 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 18:20:36.806  7630  7656 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 18:20:36.806  7630  7656 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 18:20:36.806  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 18:20:36.816  7630  7630 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:36.816  1015  1496 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 18:20:36.816  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.816  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:36.816  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.816  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.816  7630  7638 I bluedroid: config_hci_snoop_log
,08-26 18:20:36.816  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-26 18:20:36.826  1015  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-26 18:20:36.826  1015  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 18:20:36.826  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 18:20:36.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 18:20:36.826  7630  7630 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 18:20:36.826  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 18:20:36.826  1015  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 18:20:36.846  1015  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 18:20:36.846  1015  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 18:20:36.846  7630  7653 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 18:20:36.846  7630  7653 D BluetoothAdapterProperties: Setting state to 11
08-26 18:20:36.846  7630  7653 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-26 18:20:36.846  7630  7653 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:36.846  7630  7653 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 18:20:36.846  7630  7653 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:36.846  7630  7653 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 18:20:36.856  7630  7653 D BluetoothSecureManager: getInstant: null
,08-26 18:20:36.856  7630  7653 D BluetoothSecureManager: calling getMethod for getService
08-26 18:20:36.856  7630  7653 D BluetoothSecureManager: calling getService
,08-26 18:20:36.856  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:36.856  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-26 18:20:36.856  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 18:20:36.856  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:36.856  1178  1178 D BluetoothTile:  getBluetoothState : 11
,08-26 18:20:36.866  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null,
08-26 18:20:36.866  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 18:20:36.866  1879  1879 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 18:20:36.866  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:36.866  7630  7653 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@15d5555e
,08-26 18:20:36.866  1015  4357 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 18:20:36.866  1015  1496 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:36.866  1015  4357 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-26 18:20:36.866  7630  7653 D BtConfig.SecureMode: isSecureModeOn:false
08-26 18:20:36.866  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 18:20:36.866  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.866  1015  1535 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 18:20:36.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 18:20:36.876  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 18:20:36.876  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 18:20:36.876  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:36.876  1015  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:36.876  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 18:20:36.876  7630  7653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:36.876  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 18:20:36.886  7630  7653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:36.886  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 18:20:36.886  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:36.886  7630  7653 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 18:20:36.886  7630  7653 D BluetoothBondStateMachine: make
,08-26 18:20:36.886  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 18:20:36.886  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 18:20:36.886  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-26 18:20:36.886  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:36.886  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 18:20:36.886  7630  7658 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 18:20:36.886  1015  3406 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 18:20:36.886  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.886  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-26 18:20:36.886  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.886  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:36.896  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 18:20:36.896  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 18:20:36.896  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 18:20:36.896  7630  7630 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 18:20:36.896  7630  7630 D BtGatt.GattService: Received start request. Starting profile...
08-26 18:20:36.896  7630  7630 D BtGatt.GattService: start()
08-26 18:20:36.896  7630  7630 D BtGatt.GattService: start()
08-26 18:20:36.896  7630  7630 I bluedroid: get_profile_interface gatt
08-26 18:20:36.896  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
08-26 18:20:36.896  7630  7630 D BtGatt.AdvertiseManager: advertise manager created
,08-26 18:20:36.896  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:36.896  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.896  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:36.896  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.896  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.906  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 18:20:36.906  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 18:20:36.906  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 18:20:36.906  1015  1134 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:36.906  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.906  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.906  7630  7630 D BtGatt.GattService: mStartError = false
08-26 18:20:36.906  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
08-26 18:20:36.906  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.906  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.906  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-26 18:20:36.906  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 18:20:36.906  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 18:20:36.906  7630  7630 D HeadsetService: Received start request. Starting profile...
08-26 18:20:36.906  7630  7630 D HeadsetService: start()
,08-26 18:20:36.906  7630  7630 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 18:20:36.906  7630  7630 D HeadsetStateMachine: make
,08-26 18:20:36.916  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:36.916  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 18:20:36.916  7630  7630 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 18:20:36.926  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.926  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.926  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.926  1015  1319 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone,
08-26 18:20:36.926  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
08-26 18:20:36.926  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.926  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.926  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 18:20:36.926  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 18:20:36.926  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 18:20:36.926  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 18:20:36.936  1015  1495 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 18:20:36.936  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.936  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.936  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.936  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 18:20:36.936  7630  7630 I bluedroid: get_profile_interface handsfree
,08-26 18:20:36.936  1015  3406 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:36.936  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.936  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.936  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:36.936  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.936  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-26 18:20:36.946  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 18:20:36.946  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 18:20:36.946  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.946  1015  1319 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:36.946  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.946  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-26 18:20:36.946  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 18:20:36.946  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:36.946  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:36.946  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 18:20:36.946  7630  7653 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 18:20:36.956  7630  7630 I DualScoManager: Instantiating Dual Sco Manager
08-26 18:20:36.956  7630  7630 I DualScoManager: Set HeadsetServiceHelper
,08-26 18:20:36.956  7630  7630 D BluetoothAtMessage: createCMTIContentObservers
,08-26 18:20:36.956  1015  1533 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 18:20:36.956  1015  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:36.956  1015  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:36.956  1015  1533 D SettingsProvider: selectionArgs: false
08-26 18:20:36.956  1015  1533 D SettingsProvider: selectionArgs: 1002
08-26 18:20:36.956  1015  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:36.956  1015  1533 D SettingsProvider: ret = -1
,08-26 18:20:36.956  7630  7661 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 18:20:36.956  1015  1494 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:36.956  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.956  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:36.956  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 18:20:36.956  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.956  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.966  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 18:20:36.966  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 18:20:36.966  7630  7653 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 18:20:36.966  7630  7630 D HeadsetService: mStartError = false
08-26 18:20:36.966  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:36.966  1015  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:36.966  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 18:20:36.966  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:36.966  1015  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:36.966  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:36.976  7630  7661 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 18:20:36.976  7630  7661 D HeadsetStateMachine: map size, before remove : 0
08-26 18:20:36.976  7630  7661 D HeadsetStateMachine: map size, after remove: 0
,08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:36.976  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:36.976  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-26 18:20:36.976  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-26 18:20:36.976  7630  7653 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 18:20:36.976  7630  7653 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 18:20:36.976  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 18:20:36.976  7630  7630 D A2dpService: Received start request. Starting profile...
,08-26 18:20:36.976  7630  7630 D A2dpService: start()
,08-26 18:20:36.986  7630  7653 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 18:20:36.986  7630  7630 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 18:20:36.986  7630  7630 I bluedroid: get_profile_interface avrcp
,08-26 18:20:36.986  7630  7630 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-26 18:20:36.986  7630  7630 D Avrcp   : Initialize Media Controller
08-26 18:20:36.986  7630  7630 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-26 18:20:36.996  7630  7630 E Avrcp   : getActiveSessions
,08-26 18:20:36.996  7630  7630 D Avrcp   : pick active media Controller
08-26 18:20:36.996  7630  7630 D Avrcp   : Get the active Media Controller 
,08-26 18:20:37.006  7630  7630 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 18:20:37.006  7630  7665 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 18:20:37.006  7630  7630 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 18:20:37.006  7630  7630 D A2dpStateMachine: make
,08-26 18:20:37.006  7630  7630 I bluedroid: get_profile_interface a2dp
,08-26 18:20:37.006  7630  7667 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 18:20:37.006  7630  7630 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 18:20:37.016  7630  7630 D A2dpService: mStartError = false
08-26 18:20:37.016  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:37.016  7630  7630 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 18:20:37.016  7630  7666 D A2dpStateMachine: Enter Disconnected: -2
08-26 18:20:37.016  7630  7630 D HidService: Received start request. Starting profile...
08-26 18:20:37.016  7630  7630 D HidService: start()
08-26 18:20:37.016  7630  7630 I bluedroid: get_profile_interface hidhost
08-26 18:20:37.016  7630  7630 D HidService: setHidService(): set to: null
08-26 18:20:37.016  7630  7630 D HidService: mStartError = false
08-26 18:20:37.016  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:37.016  7630  7630 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 18:20:37.016  1443  7600 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 18:20:37.016  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 18:20:37.016  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 18:20:37.016  1443  7600 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 18:20:37.016  7630  7630 D HeadsetStateMachine: Proxy object connected
,08-26 18:20:37.016  7630  7630 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 18:20:37.026  7630  7630 D HealthService: Received start request. Starting profile...
08-26 18:20:37.026  7630  7630 D HealthService: start()
,08-26 18:20:37.026  7630  7630 I bluedroid: get_profile_interface health
,08-26 18:20:37.026  7630  7630 D HealthService: mStartError = false
08-26 18:20:37.026  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
08-26 18:20:37.026  7630  7630 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 18:20:37.026  7630  7630 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 18:20:37.026  7630  7630 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 18:20:37.026  7630  7661 D HeadsetStateMachine: Disconnected process message: 11
08-26 18:20:37.026  7630  7630 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 18:20:37.026  7630  7661 D HeadsetStateMachine: Disconnected process message: 18
,08-26 18:20:37.026  7630  7630 D PanService: Received start request. Starting profile...
08-26 18:20:37.026  7630  7630 D PanService: start()
08-26 18:20:37.026  7630  7630 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 18:20:37.026  7630  7630 I bluedroid: get_profile_interface pan
,08-26 18:20:37.026  7630  7665 D BluetoothMediaBrowser: no now playing list
08-26 18:20:37.026  7630  7665 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 18:20:37.026  7630  7630 D PanService: mStartError = false
08-26 18:20:37.026  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:37.036  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-26 18:20:37.036  7630  7630 D BluetoothMapService: Received start request. Starting profile...
,08-26 18:20:37.036  7630  7630 D BluetoothMapService: start()
,08-26 18:20:37.036  7630  7630 D BluetoothMapService: mStartError = false
08-26 18:20:37.036  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:37.036  7630  7630 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 18:20:37.036  7630  7661 D HeadsetStateMachine: Disconnected process message: 10
08-26 18:20:37.036  7630  7630 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 18:20:37.036  7630  7661 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-26 18:20:37.036  7630  7661 D HeadsetStateMachine: Disconnected process message: 11
,08-26 18:20:37.036  7630  7630 D SapService: Received start request. Starting profile...
,08-26 18:20:37.036  7630  7630 D SapService: start()
08-26 18:20:37.036  7630  7630 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 18:20:37.036  7630  7630 I bluedroid: get_profile_interface sap
08-26 18:20:37.036  7630  7630 D SapService: mStartError = false
08-26 18:20:37.036  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
08-26 18:20:37.036  7630  7630 D BluetoothA2dp: Proxy object connected
08-26 18:20:37.036  7630  7630 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 18:20:37.036  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true,
08-26 18:20:37.036  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 18:20:37.036  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-26 18:20:37.046  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 18:20:37.056  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 18:20:37.066  7630  7630 E BluetoothAdapterService(259009480): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 18:20:37.066  7630  7653 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-26 18:20:37.066  7630  7653 I bluedroid: enable
,08-26 18:20:37.066  7630  7653 I bt_hci_bdroid: init
,08-26 18:20:37.066  7630  7671 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 18:20:37.066  7630  7653 I bt_vendor: bt-vendor : init
,08-26 18:20:37.066  7630  7653 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 18:20:37.066  7630  7653 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-26 18:20:37.066  7630  7653 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-26 18:20:37.066  7630  7653 D bt_userial_mct: userial_init
,08-26 18:20:37.066  7630  7653 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 18:20:37.066  7630  7653 I bt_vendor: Starting hciattach daemon
08-26 18:20:37.066  7630  7653 I bt_vendor: try to set false
,08-26 18:20:37.066  7630  7653 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 18:20:37.076  7630  7653 I bt_vendor: Starting hciattach daemon
08-26 18:20:37.076  7630  7653 I bt_vendor: try to set true
,08-26 18:20:37.086  7675  7675 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 18:20:37.126  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 18:20:37.136  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 18:20:37.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...,
08-26 18:20:37.156  7684  7684 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-26 18:20:37.166  7685  7685 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 18:20:37.176  7686  7686 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 18:20:37.186  7687  7687 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 18:20:37.376  7690  7690 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-26 18:20:37.386  7691  7691 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 18:20:37.426  7630  7653 I bt_vendor: bluetooth satus is on
,08-26 18:20:37.426  7630  7673 D bt_userial_mct: userial_open(port:0)
08-26 18:20:37.426  7630  7673 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 18:20:37.426  7630  7673 I bt_vendor: Done intiailizing UART
,08-26 18:20:37.436  7630  7673 I bt_vendor: Done intiailizing UART,
08-26 18:20:37.436  7630  7673 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-26 18:20:37.436  7630  7673 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_AVDT
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 18:20:37.436  7630  7671 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_PAN
,08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_SAP
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_SMP
,08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 18:20:37.446  7630  7671 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 18:20:37.446  7630  7694 D bt_userial_mct: Entering userial_read_thread()
,08-26 18:20:37.536  7630  7671 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 18:20:37.546  7630  7671 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4215ed1 
,08-26 18:20:37.546  7630  7671 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4215ed1 
,08-26 18:20:37.556  7630  7656 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 18:20:37.556  7630  7656 E bt-btif : Calling BTA_HhEnable
,08-26 18:20:37.556  7630  7656 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 18:20:37.566  7630  7656 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-26 18:20:37.566  7630  7656 E BluetoothServiceJni: populateRssiValuesNative
08-26 18:20:37.566  7630  7656 I bluedroid: getModelRssiValues
,08-26 18:20:37.566  7630  7656 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 18:20:37.566  7630  7656 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 18:20:37.566  1015  1015 D SettingsProvider: name = bluetooth_name
,08-26 18:20:37.566  7630  7656 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-26 18:20:37.576  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:37.576  7630  7656 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 18:20:37.576  7630  7656 D BluetoothAdapterProperties: Scan Mode:20
08-26 18:20:37.576  7630  7656 D BluetoothAdapterProperties: Discoverable Timeout:120
08-26 18:20:37.576  7630  7656 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-26 18:20:37.576  7630  7656 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 18:20:37.576  7630  7656 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 18:20:37.576  7630  7656 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-26 18:20:37.576  7630  7656 E bt-btif : btif_sock_init: !vhci_init
,08-26 18:20:37.576  7630  7656 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-26 18:20:37.576  7630  7656 D IOP_DB_BT: db_open: db_open : handle 3028582416l, read 13894 bytes onto local cache
08-26 18:20:37.576  7630  7656 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 18:20:37.576  7630  7656 D IOP_DB_BT: db_query: result 1
,08-26 18:20:37.576  7630  7656 I         : iop_db_open: iop_db_open status 0
08-26 18:20:37.576  7630  7656 D bte_conf: Device ID record 1 : primary
,08-26 18:20:37.576  7630  7656 D bte_conf:   vendorId            = 0075
08-26 18:20:37.576  7630  7656 D bte_conf:   vendorIdSource      = 0001
08-26 18:20:37.576  7630  7656 D bte_conf:   product             = 0100
08-26 18:20:37.576  7630  7656 D bte_conf:   version             = 0200
08-26 18:20:37.576  7630  7656 D bte_conf:   clientExecutableURL = 
08-26 18:20:37.576  7630  7656 D bte_conf:   serviceDescription  = 
08-26 18:20:37.576  7630  7656 D bte_conf:   documentationURL    = 
08-26 18:20:37.576  7630  7656 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 18:20:37.576  7630  7653 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 18:20:37.576  7630  7653 D BluetoothAdapterProperties: ScanMode =  20
,08-26 18:20:37.576  7630  7653 D BluetoothAdapterProperties: State =  11
,08-26 18:20:37.586  1015  1134 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 18:20:37.576  7630  7656 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 18:20:37.586  7630  7653 D BluetoothAdapterProperties: Setting state to 12
,08-26 18:20:37.586  7630  7653 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 18:20:37.586  7630  7694 E bt_mct  : hci lib postload completed
,08-26 18:20:37.586  7630  7656 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 18:20:37.586  7630  7656 D BluetoothAdapterProperties: Scan Mode:21
08-26 18:20:37.586  7630  7656 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 18:20:37.586  1015  4357 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 18:20:37.586  1015  4357 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 18:20:37.586  1015  4357 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:37.586  1015  4357 D SettingsProvider: selectionArgs: false
08-26 18:20:37.586  1015  4357 D SettingsProvider: selectionArgs: 1002
08-26 18:20:37.586  1015  4357 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:37.586  1015  4357 D SettingsProvider: ret = -1
,08-26 18:20:37.596  7630  7653 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 18:20:37.596  7630  7653 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 18:20:37.596  1015  1496 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 18:20:37.596  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.596  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.596  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:37.596  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:37.606  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:37.606  7630  7653 D BluetoothAdapterService: Autoconnection is available 
08-26 18:20:37.606  7630  7653 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 18:20:37.606  7630  7653 D BluetoothAdapterService: starting service from this receiver
,08-26 18:20:37.606  4126  7598 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 18:20:37.606  1015  1495 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:37.606  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.616  4126  7598 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:37.616  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.616  1015  1495 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.616  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.616  7630  7653 I BluetoothAdapterState: Entering On State from state = 11
,08-26 18:20:37.626  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:37.636  7630  7630 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 18:20:37.636  1015  3403 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:37.766  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:37.766  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:37.776  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:37.776  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@173b1ced added. We now have 8 listener(s)
08-26 18:20:37.776  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:37.776  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 18:20:37.776  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 18:20:37.776  1015  1027 D SecContentProvider2: mCursor = null
,08-26 18:20:37.776  1015  1027 D WifiService: setWifiEnabled: false pid=6866, uid=10171
,08-26 18:20:37.776  1015  1027 D SettingsProvider: name = wifi_on
,08-26 18:20:37.776  1015  1044 I art     : Explicit concurrent mark sweep GC freed 22609(1319KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.459ms total 165.312ms
08-26 18:20:37.776  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 18:20:37.776  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.776  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.776  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.776  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.786  4126  4126 D BluetoothA2dp: Proxy object connected
,08-26 18:20:37.786  4126  4126 D A2dpProfile: Bluetooth service connected
,08-26 18:20:37.786  7630  7645 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.786  7630  7645 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:37.786  4126  4136 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.786  4126  4136 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:37.786  4126  4136 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 18:20:37.786  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:37.786  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 18:20:37.786  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.786  7630  7630 I BluetoothPbapService: Handler(): got msg=1
08-26 18:20:37.786  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.786  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.786  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.786  1015  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 18:20:37.786  1015  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 18:20:37.786  1015  1027 D SecContentProvider2: mCursor = null
,08-26 18:20:37.786  1015  1512 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 18:20:37.796  1015  1027 D WifiService: setWifiEnabled: true pid=6866, uid=10171
08-26 18:20:37.796  1015  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-26 18:20:37.796  1015  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-26 18:20:37.796  1015  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6866, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-26 18:20:37.796  1015  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-26 18:20:37.796  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 18:20:37.796  1015  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 18:20:37.796  1015  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 18:20:37.796  1015  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 18:20:37.796  1015  1027 D SettingsProvider: name = wifi_on
,08-26 18:20:37.796  1443  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 18:20:37.796  4126  4126 D BluetoothInputDevice: Proxy object connected
08-26 18:20:37.796  4126  4126 D HidProfile: Bluetooth service connected
,08-26 18:20:37.796  7630  7701 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 18:20:37.796  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:37.796  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:37.796  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.796  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.796  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.796  1015  1126 E WifiHW  : ##################### set firmware type 0 #####################
08-26 18:20:37.796  1443  1458 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 18:20:37.796  1015  1044 D BluetoothPan: Binding service...
,08-26 18:20:37.796  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 18:20:37.796  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.806  7630  7644 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 18:20:37.806  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 18:20:37.806  6866  7078 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.806  6866  7078 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.806  1178  1203 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.806  1178  1203 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 18:20:37.806  7630  7701 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 18:20:37.806  7630  7701 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:37.806  1443  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:37.806  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:37.806  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:37.806  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.806  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:37.806  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.816  1443  1470 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 18:20:37.816  1443  7600 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.816  1443  7600 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.816  4126  4140 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 18:20:37.816  4126  4140 D Bluetoothsap: Binding service...
,08-26 18:20:37.816  7630  7701 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-26 18:20:37.816  7630  7701 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:37.816  7630  7701 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:37.816  7630  7701 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@31ce4322
08-26 18:20:37.816  7630  7701 D BluetoothSocket: channel: 19
08-26 18:20:37.816  7630  7701 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 18:20:37.816  4126  4140 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-26 18:20:37.816  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 18:20:37.816  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.816  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.816  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.816  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.816  4126  4126 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 18:20:37.816  4126  4126 D SapProfile: Bluetooth service connected
08-26 18:20:37.816  4126  4126 D Bluetoothsap: getConnectedDevices()
08-26 18:20:37.816  4126  4140 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 18:20:37.816  4126  7699 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 18:20:37.816  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 18:20:37.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.826  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.826  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.826  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.826  4126  4126 D BluetoothPbap: Proxy object connected
08-26 18:20:37.826  4126  4126 D PbapServerProfile: Bluetooth service connected
,08-26 18:20:37.826  1469  1864 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:37.826  1015  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 18:20:37.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:37.826  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.826  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.826  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.826  1469  1864 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:37.826  1015  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 18:20:37.826  1015  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-26 18:20:37.826  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 18:20:37.826  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.826  1015  1015 D BluetoothA2dp: Proxy object connected
,08-26 18:20:37.836  1443  1458 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:37.836  1015  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 18:20:37.836  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:37.836  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.836  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.836  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.836  1443  1458 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:37.836  4126  4140 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 18:20:37.836  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 18:20:37.836  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.836  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.836  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.836  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.846  7541  7549 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.846  4126  4126 D BluetoothMap: Proxy object connected
08-26 18:20:37.846  4126  4126 D MapProfile: Bluetooth service connected
08-26 18:20:37.846  4126  4126 D BluetoothMap: getConnectedDevices()
,08-26 18:20:37.846  7541  7549 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.846  1015  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 18:20:37.846  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:37.846  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 18:20:37.846  1015  1044 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 18:20:37.846  4126  7699 D BluetoothPan: Binding service...
,08-26 18:20:37.846  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 18:20:37.846  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.846  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.846  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.846  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 18:20:37.846  1972  1981 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.846  1972  1981 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.846  4126  4126 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 18:20:37.846  4126  4126 D PanProfile: Bluetooth service connected
08-26 18:20:37.846  1456  1478 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.846  1456  1478 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.846  4126  4140 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 18:20:37.856  1015  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 18:20:37.856  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 18:20:37.856  1015  1044 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.856  1015  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.856  1015  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-26 18:20:37.856  4126  4140 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 18:20:37.856  1469  1481 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.856  1469  1481 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.856  1015  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 18:20:37.856  1015  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 18:20:37.856  1015  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 18:20:37.856  1015  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
08-26 18:20:37.856  4126  4126 D HeadsetProfile: Bluetooth service connected
08-26 18:20:37.856  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:37.856  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-26 18:20:37.856  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-26 18:20:37.866  1178  1178 D BluetoothTile:  onBluetoothStateChange:
08-26 18:20:37.866  1443  1443 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@1ca5d79, true
08-26 18:20:37.866  1443  1443 D BluetoothHeadset: registerMessageListener
08-26 18:20:37.866  1178  1178 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 18:20:37.866  1178  1178 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:37.866  1178  1178 D BluetoothTile:  getBluetoothState : 12
08-26 18:20:37.876  1879  1879 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 18:20:37.876  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
08-26 18:20:37.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:37.876  1015  1495 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 18:20:37.876  7630  7700 D HeadsetService: registerMessageListener
08-26 18:20:37.876  1015  1495 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 18:20:37.876  7630  7700 D HeadsetService: registerMessageListener
08-26 18:20:37.876  4126  4126 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-26 18:20:37.876  1015  1495 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.876  1015  1495 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:37.876  1015  1495 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 18:20:37.876  7630  7661 D HeadsetStateMachine: Disconnected process message: 70
08-26 18:20:37.876  7630  7661 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1b9321b3
08-26 18:20:37.876  1443  1443 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 18:20:37.876  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 18:20:37.886  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
08-26 18:20:37.886  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 18:20:37.886  1015  1496 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-26 18:20:37.886  4126  4126 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 18:20:37.886  4126  4126 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 18:20:37.886  4126  4126 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 18:20:37.886  4126  4126 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-26 18:20:37.886  1178  1743 D BluetoothTile:  handleUpdatestate:false name:null
08-26 18:20:37.886  1178  1178 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 18:20:37.886  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 18:20:37.886  1443  1443 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 18:20:37.886  1443  1443 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 18:20:37.886  7630  7705 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-26 18:20:37.896  7630  7661 D HeadsetStateMachine: Disconnected process message: 9
08-26 18:20:37.896  7630  7661 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
08-26 18:20:37.896  4126  4126 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 18:20:37.896  1015  1494 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 18:20:37.896  1015  1494 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-26 18:20:37.906   283   283 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 18:20:37.906   283   283 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 18:20:37.906   283   283 V voice   : voice_set_parameters: exit with code(-2)
08-26 18:20:37.906   283   283 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 18:20:37.906   283   283 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 18:20:37.906   283   283 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 18:20:37.906   283   283 V audio_hw_primary: adev_set_parameters: exit
08-26 18:20:37.906  1015  1494 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.906  1015  1494 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.906  1015  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-26 18:20:37.906  7630  7661 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 18:20:37.916  4126  4126 D DockEventReceiver: finishStartingService: stopping service
,08-26 18:20:37.916  4126  4126 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 18:20:37.916  7630  7705 D BluetoothSocket: bindListen(): myUserId = 0
08-26 18:20:37.916  7630  7705 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:37.916  1178  1178 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 18:20:37.916  1178  1178 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
08-26 18:20:37.916  7630  7705 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-26 18:20:37.916  7630  7705 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:37.916  7630  7705 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:37.916  7630  7705 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@155c1370
,08-26 18:20:37.916  7630  7705 D BluetoothSocket: channel: 5
,08-26 18:20:37.926  7630  7630 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
08-26 18:20:37.926  7630  7630 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 18:20:37.926  1015  1512 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 18:20:37.926  1015  1512 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.936  1015  1512 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.936  1015  1512 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:37.936  1015  1512 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 18:20:37.956  1972  1972 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 18:20:37.956  1015  1533 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 18:20:37.956  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:37.956  1015  1494 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-26 18:20:37.956  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:37.956  1015  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:37.956  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:37.966  1972  7714 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 18:20:37.966  1015  1496 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:37.966  1972  1972 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 18:20:37.976  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.976  1015  1496 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:37.976  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:37.976  7630  7715 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 18:20:37.976  7630  7715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 18:20:37.986  7630  7715 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-26 18:20:37.986  7630  7715 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 18:20:37.986  7630  7715 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 18:20:37.986  7630  7715 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3c6f69c
08-26 18:20:37.986  7630  7715 D BluetoothSocket: channel: 12
08-26 18:20:37.986  7630  7715 I BtOppRfcommListener: Accept thread started.
,08-26 18:20:37.986  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 18:20:37.986  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:37.986  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:37.986  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 18:20:37.996  1972  7714 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 18:20:38.066  1015  2072 V SAMP_SPCM_test: CSC File load.. 
,08-26 18:20:38.076  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-26 18:20:38.076  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
,08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
,08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-26 18:20:38.086  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 18:20:38.126  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 18:20:38.136  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown ,tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 18:20:38.146  1015  2072 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-26 18:20:38.146  1015  2072 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-26 18:20:38.146  1015  2072 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:38.146  1015  2072 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:38.146  1015  2072 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:38.146  1015  2072 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:38.156  1015  1042 D Tethering: interfaceAdded wlan0
,08-26 18:20:38.156  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 18:20:38.156  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:38.156  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:38.156  1015  1129 E Tethering: No numeric data
08-26 18:20:38.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:38.166  1015  1042 D Tethering: interfaceAdded p2p0
,08-26 18:20:38.166  1015  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 18:20:38.166  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.166  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.166  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:38.166  7723  7723 E Zygote  : MountEmulatedStorage()
08-26 18:20:38.166  7723  7723 I libpersona: KNOX_SDCARD checking this for 1000
08-26 18:20:38.166  7723  7723 E Zygote  : v2
08-26 18:20:38.166  7723  7723 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:38.166   277  1014 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-26 18:20:38.176   277  1014 D SoftapController: Softap fwReload - Ok
08-26 18:20:38.176  7723  7723 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:38.176   277  1014 D CommandListener: Setting iface cfg,
08-26 18:20:38.176   277  1014 D CommandListener: Trying to bring down wlan0
08-26 18:20:38.176  7723  7723 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:38.176  7723  7723 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:38.176   277  1014 D CommandListener: Clearing all IP addresses on wlan0
,08-26 18:20:38.176  1015  2072 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7723 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 18:20:38.186  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 18:20:38.186  1015  1129 D Tethering: clearTetheredNotification()
08-26 18:20:38.186  1015  1129 D Tethering: InitialState.processMessage what=4
,08-26 18:20:38.186  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:38.186  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:38.186  1015  1126 E WifiHW  : supplicant_name : p2p_supplicant
08-26 18:20:38.186  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:38.186  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:38.186  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 18:20:38.186  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:38.186  1015  1123 V NetworkStats: performPollLocked() took 5ms
08-26 18:20:38.186  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:38.196  1015  1129 E Tethering: No numeric data,
08-26 18:20:38.196  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:38.196  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 18:20:38.196  1015  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 18:20:38.196  1015  1129 D Tethering: clearTetheredNotification(),
,08-26 18:20:38.196  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:38.196  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:38.196  1178  1178 D HotspotTile: updateTetherState():false, false
08-26 18:20:38.196  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:38.196  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 18:20:38.196  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:38.206  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:38.206  1015  1123 V NetworkStats: performPollLocked() took 6ms
,08-26 18:20:38.206  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:38.206  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:38.216  7723  7723 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:38.216  7723  7723 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:38.236  7723  7723 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
,08-26 18:20:38.236  7730  7730 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-26 18:20:38.236  7730  7730 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 18:20:38.236  7730  7730 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 18:20:38.246  7730  7730 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-26 18:20:38.246   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7730
08-26 18:20:38.246   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-26 18:20:38.246  7730  7730 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 18:20:38.246  7730  7730 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:38.246  7730  7730 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-26 18:20:38.246  7730  7730 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 18:20:38.246   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7730
08-26 18:20:38.246   402   402 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 18:20:38.286  1015  2072 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 18:20:38.286  1015  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 18:20:38.286  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:38.286  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 18:20:38.286  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.286  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.286  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.286  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:38.296  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:38.296  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 18:20:38.296  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 18:20:38.296  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:38.296  1178  1178 D HotspotTile: onReceive : 2, 0
,08-26 18:20:38.296  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:38.296  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:38.296  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:38.306  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:38.306  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:38.306  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:38.306  1611  1611 I Hs20UtilService: Starting #19
08-26 18:20:38.306  1611  1637 I Hs20UtilService: Message received 5011
08-26 18:20:38.306  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:38.316  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 18:20:38.316  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:38.316  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
08-26 18:20:38.316  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 18:20:38.406   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-26 18:20:38.416  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 18:20:38.456  7730  7730 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 18:20:38.456  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 18:20:38.466  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,08-26 18:20:38.466   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7730
08-26 18:20:38.476   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 18:20:38.476  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 18:20:38.476  7730  7730 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:38.476  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:38.476  7730  7730 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 18:20:38.476  7730  7730 E wpa_supplicant: SIM READ ERROR
08-26 18:20:38.476  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:38.476  7730  7730 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 18:20:38.476  7730  7730 E wpa_supplicant: SIM READ ERROR
08-26 18:20:38.476  7730  7730 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:38.476  7730  7730 I wpa_supplicant: wpa_default_ap_write_once,
08-26 18:20:38.476  7730  7730 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 18:20:38.476  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:38.476  7730  7730 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-26 18:20:38.476  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:38.476  7730  7730 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 18:20:38.476  7730  7730 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 18:20:38.476  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:38.476  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:38.476  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:38.516   288   288 E SMD     : DCD OFF,
,08-26 18:20:38.626  7730  7730 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 18:20:38.756  7730  7730 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 18:20:38.756  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 18:20:38.766  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 18:20:38.766   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7730
08-26 18:20:38.766   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-26 18:20:38.776  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 18:20:38.776  7730  7730 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:38.776  7730  7730 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 18:20:38.776  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 18:20:38.786  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 18:20:38.786   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7730
08-26 18:20:38.786   402   402 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 18:20:38.786  7730  7730 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
,08-26 18:20:38.786  7730  7730 I wpa_supplicant: ssSupport state is = 1
08-26 18:20:38.786  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 18:20:38.796  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.786  7730  7730 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:38.786  7730  7730 E wpa_supplicant: SIM READ ERROR
08-26 18:20:38.786  7730  7730 I wpa_supplicant: wpa_default_ap_write_once
08-26 18:20:38.786  7730  7730 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-26 18:20:38.786  7730  7730 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 18:20:38.796  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.796  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
08-26 18:20:38.796  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.796  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:38.796  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:38.806  1015  3374 D SSRM:n  : SIOP:: AP = 350
,08-26 18:20:38.836  7730  7730 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 18:20:38.836  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 18:20:38.896  7730  7730 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 18:20:38.896  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 18:20:38.896  7730  7730 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 18:20:38.896  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 18:20:38.906  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 18:20:38.906  7730  7730 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 18:20:38.906  7730  7730 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-26 18:20:38.906  7730  7730 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 18:20:38.906  7730  7730 E wpa_supplicant: SIM READ ERROR
08-26 18:20:38.906  7730  7730 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 18:20:38.926  7730  7730 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 18:20:38.936  7730  7730 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-26 18:20:38.936  1015  1126 D WifiConfigStore: Loading config and enabling all networks 
08-26 18:20:38.936  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:38.936  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:38.936  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.936  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.936  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:38.936  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:38.936  1178  1178 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:38.936  1178  1178 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 18:20:38.946  1178  1743 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 18:20:38.946  4126  4126 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 18:20:38.946  1178  1178 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 18:20:38.946  1178  1178 D HotspotTile: onReceive : 3, 0
,08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:38.946  6866  6866 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:38.956  6866  6866 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:38.956  1015  1126 E WifiConfigStore: Not a HS20
,08-26 18:20:38.956  1015  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 18:20:38.956  1015  1535 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:38.956  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 18:20:38.956  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:38.956  1015  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:38.956  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:38.956  1015  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 18:20:38.956  1015  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 18:20:38.956  7730  7730 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 18:20:38.956  7730  7730 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 18:20:38.966  7730  7730 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 18:20:38.966  1611  1611 I Hs20UtilService: Starting #20
08-26 18:20:38.966  7730  7730 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 18:20:38.966  7730  7730 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 18:20:38.966  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 18:20:38.966  7730  7730 I wpa_supplicant: First Scan Start
08-26 18:20:38.966  1611  1637 I Hs20UtilService: Message received 5011
,08-26 18:20:38.966  7730  7730 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 18:20:38.966  1015  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-26 18:20:38.966  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 18:20:38.966  6704  6704 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 18:20:38.966  6704  6704 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 18:20:38.966  1015  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 18:20:38.966  1015  1126 I WifiNative-HAL: startHal
08-26 18:20:38.966  1015  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9ee0f88c
08-26 18:20:38.966  1015  1126 I WifiNative-HAL: Could not start hal
08-26 18:20:38.966  7126  7126 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 18:20:38.966  6704  6704 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 18:20:38.966  1015  1126 E WifiNative-wlan0: do suspend true
,08-26 18:20:38.966  1015  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 18:20:38.976   277  1014 D CommandListener: Setting iface cfg,
,08-26 18:20:38.976   277  1014 D CommandListener: Trying to bring up p2p0
08-26 18:20:38.976  1015  1125 D WifiP2pService: P2pEnablingState
08-26 18:20:38.976  1015  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 18:20:38.976  1015  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 18:20:38.976  1015  1125 D WifiP2pService: P2p socket connection successful
,08-26 18:20:38.976  1015  1125 D WifiP2pService: P2pEnabledState
,08-26 18:20:38.976  1015  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 18:20:38.976  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-26 18:20:38.976  1015  1149 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:38.976  1015  1149 I WifiNative-HAL: startHal
08-26 18:20:38.976  1015  1149 E wifi    : getStaticLongField sWifiHalHandle 0x993ab9bc
08-26 18:20:38.976  1015  1149 I WifiNative-HAL: Could not start hal
08-26 18:20:38.976  1015  1149 E WifiScanningService: could not start HAL
,08-26 18:20:38.976  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-26 18:20:38.976  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 18:20:38.976  1015  1126 E WifiNative-wlan0: invaild command id : 215
,08-26 18:20:38.976  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-26 18:20:38.986  1015  1150 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:38.986  1015  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 18:20:38.986  1015  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-26 18:20:38.986  1015  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 18:20:38.986  1015  1126 E WifiNative-wlan0: invaild command id : 215
08-26 18:20:38.986  1015  1128 E ConnectivityService: updateNetworkInfo(),
,08-26 18:20:38.986  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 18:20:38.986  1015  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-26 18:20:38.986  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
08-26 18:20:38.986  1015  1045 D WifiDisplayController: disconnect
08-26 18:20:38.986  1015  1045 D WifiDisplayController: updateConnection
08-26 18:20:38.986  1015  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 18:20:38.986  1015  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 18:20:38.986  7730  7730 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 18:20:38.996  7730  7730 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 18:20:38.996  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 18:20:38.996  1015  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 18:20:38.996  1015  1045 D WifiDisplayAdapter: onP2pDisconnected
08-26 18:20:38.996  1015  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 18:20:38.996  1015  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 18:20:38.996  1015  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-26 18:20:38.996  7730  7730 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-26 18:20:38.996  1015  1126 E WifiStateMachine: Failed to set frequency band 0
,08-26 18:20:38.996  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:38.996  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:38.996  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-26 18:20:39.006  1178  1178 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 18:20:39.006  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 18:20:39.006  1015  1496 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 18:20:39.006  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 18:20:39.006  1178  1178 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 18:20:39.006  1015  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-26 18:20:39.006  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:39.006  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:39.006  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:39.006  1015  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  secondary type: null
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  wps: 0
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  grpcapab: 0
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  devcapab: 0
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  status: 3
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  wfdInfo: null
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  groupownerAddress: null
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  GOdeviceName: null
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  interfaceAddress: 
08-26 18:20:39.006  1015  1045 D WifiDisplayController:  SConnectInfo : null
08-26 18:20:39.006  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:39.006  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:39.006  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:39.006  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:39.006  7096  7096 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 18:20:39.006  7096  7096 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 18:20:39.016  7111  7111 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 18:20:39.026  1015  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 18:20:39.026  1015  1125 D WifiP2pService: InactiveState
,08-26 18:20:39.026  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-26 18:20:39.026  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 18:20:39.026  7730  7730 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 18:20:39.026  1015  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-26 18:20:39.026  1015  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 18:20:39.146  1015  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 18:20:39.146  1015  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 18:20:39.146  1015  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-26 18:20:39.156   326   326 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:39.816  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:39.816  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:39.826  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 18:20:39.826  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 18:20:39.826  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@156a16f8 Bundle[{}]
,08-26 18:20:39.826  6866  6920 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 18:20:39.826  6866  6920 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 18:20:39.836  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 18:20:39.836  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 18:20:39.836  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 18:20:39.836  6866  6920 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 18:20:39.846  6866  6920 I System.out: Running OutgoingSocketThread
,08-26 18:20:39.846  6866  7747 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1375)
,08-26 18:20:39.846  6866  7747 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45005
,08-26 18:20:39.846  6866  7747 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 18:20:40.156   326   326 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 18:20:40.206  7730  7730 I wpa_supplicant: nl80211: Received scan results (25 BSSes),
08-26 18:20:40.206  7730  7730 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 18:20:40.206  7730  7730 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-26 18:20:40.206  7730  7730 I wpa_supplicant: Trying to associate with  'G700',
,08-26 18:20:40.206  7730  7730 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
08-26 18:20:40.206  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030,
08-26 18:20:40.206  1015  7744 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-26 18:20:40.236  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 18:20:40.236  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:40.316  7730  7730 E wpa_supplicant: Cmd 35605 not handled
,08-26 18:20:40.326  7730  7730 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 18:20:40.326  7730  7730 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-26 18:20:40.326  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:40.326  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:40.326  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
08-26 18:20:40.326  7730  7730 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-26 18:20:40.326  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 18:20:40.326  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:40.326  1015  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-26 18:20:40.326  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030,
08-26 18:20:40.326  7730  7730 I wpa_supplicant: Associated with F4.99.3E
08-26 18:20:40.326  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 18:20:40.326  7730  7730 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-26 18:20:40.326  7730  7730 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-26 18:20:40.326  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 18:20:40.326  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:40.326  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 18:20:40.326  1015  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-26 18:20:40.326  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 18:20:40.326  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-26 18:20:40.336  1015  1129 E Tethering: No numeric data
,08-26 18:20:40.336  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:40.336  1015  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 18:20:40.336  1178  1178 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 18:20:40.336  1015  1129 D Tethering: clearTetheredNotification()
08-26 18:20:40.336  1178  1178 D HotspotTile: updateTetherState():false, false,
,08-26 18:20:40.336  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:40.346  1015  1123 V NetworkStats: performPollLocked() took 9ms
08-26 18:20:40.336  7730  7730 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 18:20:40.336  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:40.336  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:40.336  7730  7730 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-26 18:20:40.336  7730  7730 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-26 18:20:40.336  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:40.346  7730  7730 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 18:20:40.346  7730  7730 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-26 18:20:40.346  7730  7730 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 18:20:40.346  1015  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 18:20:40.346  7730  7730 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 18:20:40.346  7730  7730 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-26 18:20:40.346  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:40.346  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:40.346  1015  1126 D SecContentProvider2: mCursor = null
08-26 18:20:40.346  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:40.346  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:40.346  1015  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 18:20:40.346  1015  1042 D Tethering: interfaceStatusChanged wlan0, true
,08-26 18:20:40.356  1015  1126 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 18:20:40.356  1015  1126 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 18:20:40.366  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:40.366  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:40.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:40.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:40.366  1015  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-26 18:20:40.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:40.366  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:40.366  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:40.366  1015  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 18:20:40.366  1015  1128 E ConnectivityService: updateNetworkInfo()
,08-26 18:20:40.376  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:40.376  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 18:20:40.376  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:40.376  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:40.376  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,08-26 18:20:40.376  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:40.386  1611  1611 I Hs20UtilService: Starting #21
,08-26 18:20:40.386  1611  1637 I Hs20UtilService: Message received 5007
,08-26 18:20:40.386  1015  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 18:20:40.386  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 18:20:40.396  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 18:20:40.396   277  1014 D CommandListener: Setting iface cfg
08-26 18:20:40.396  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 18:20:40.396  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:40.396  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 18:20:40.396  4126  4126 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 18:20:40.396  4126  4215 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 18:20:40.406  1015  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-26 18:20:40.406  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:40.406  1015  1126 D SecContentProvider2: mCursor = null
08-26 18:20:40.406  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:40.406  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:40.416  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:40.416  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 18:20:40.416  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:40.426  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:40.426  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:40.426  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:40.426  1015  1126 E WifiNative-wlan0: do suspend false
,08-26 18:20:40.436  1015  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 18:20:40.436  1015  1126 D SecContentProvider2: mCursor = null
,08-26 18:20:40.436  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 18:20:40.436  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 18:20:40.646  7750  7750 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 18:20:40.656  7750  7750 I dhcpcd  : version 5.5.6 starting
,08-26 18:20:40.656  7750  7750 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 18:20:40.706  7750  7750 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 18:20:40.706  7750  7750 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 18:20:40.706  7750  7750 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-26 18:20:40.706  7750  7750 I dhcpcd  : bssid match
08-26 18:20:40.706  7750  7750 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-26 18:20:40.836  7750  7750 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-26 18:20:40.846  6866  6920 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1376),
08-26 18:20:40.846  6866  6920 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1376)
,08-26 18:20:40.846  6866  6920 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1381)
,08-26 18:20:40.846  6866  6920 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 18:20:40.846  6866  6920 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1382)
08-26 18:20:40.846  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 18:20:40.846  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3349b722 added. We now have 2 listener(s)
,08-26 18:20:40.856  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 18:20:40.856  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 18:20:40.856  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:40.856  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:40.856  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127b85b3 added. We now have 9 listener(s)
08-26 18:20:40.856  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:40.856  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:40.866  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:40.866  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:40.876  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:40.876  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38399ae9 added. We now have 3 listener(s)
,08-26 18:20:40.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:40.876  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36f0236e added. We now have 10 listener(s)
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:40.876  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:40.876  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:40.876  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 18:20:40.876  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3349b722 removed from the list
,08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127b85b3 removed from the list
,08-26 18:20:40.876  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:40.876  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:40.876  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127b85b3 not in the list
08-26 18:20:40.876  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36f0236e removed from the list
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:40.876  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:40.876  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 18:20:40.876  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:40.876  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38399ae9 removed from the list
,08-26 18:20:40.886  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:40.886  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@241eca0f added. We now have 2 listener(s)
,08-26 18:20:40.886  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 18:20:40.886  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:40.886  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:40.886  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 18:20:40.886  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1946ca9c added. We now have 9 listener(s)
08-26 18:20:40.886  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:40.886  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:40.896  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:40.896  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:40.906  7750  7750 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-26 18:20:40.906  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:40.906  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:40.906  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:40.906  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367f087a added. We now have 3 listener(s)
,08-26 18:20:40.906  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:40.906  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:40.906  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:40.906  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:40.916  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:40.916  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3107f82b added. We now have 10 listener(s)
08-26 18:20:40.916  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:40.916  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:40.916  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:40.916  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:40.916  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:40.916  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:40.916  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:40.916  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 18:20:40.936  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-26 18:20:40.936  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:40.946  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
08-26 18:20:40.946  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 18:20:40.946  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-26 18:20:40.956  7630  7645 D BtGatt.GattService: registerClient() - UUID=f8e6c7dc-0572-4a00-9503-f88926263486,
,08-26 18:20:40.996  7630  7656 D BtGatt.GattService: onClientRegistered() - UUID=f8e6c7dc-0572-4a00-9503-f88926263486, clientIf=6
08-26 18:20:40.996  6866  7078 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 18:20:40.996  7630  7638 D BtGatt.GattService: start scan with filters
,08-26 18:20:41.006  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 18:20:41.006  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
,08-26 18:20:41.006  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: handling starting scan
,08-26 18:20:41.006  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 18:20:41.006  7630  7660 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f702bc8
,08-26 18:20:41.006  7630  7656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
,08-26 18:20:41.006  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: allow scan with filters
,08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-26 18:20:41.006  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 18:20:41.006  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 18:20:41.006  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 18:20:41.006  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
,08-26 18:20:41.006  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: Starting BLE batch scan
08-26 18:20:41.006  7630  7660 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 18:20:41.016  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:41.016  7630  7656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-26 18:20:41.016  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,08-26 18:20:41.016  6866  6920 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 18:20:41.016  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:41.016  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 18:20:41.016  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.016  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 18:20:41.016  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-26 18:20:41.016  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:41.016  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:41.016  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:41.016  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:41.016  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:41.026  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-26 18:20:41.026  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.026  7630  7700 D BtGatt.GattService: stopScan() - queue size =1
08-26 18:20:41.026  7630  7645 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:41.026  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:41.026  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:41.026  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:41.026  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:41.036  7630  7660 D BtGatt.ScanManager: filter size is 1
08-26 18:20:41.036  7630  7660 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 18:20:41.036  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 18:20:41.036  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 18:20:41.036  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:41.036  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-26 18:20:41.036  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.036  7630  7660 D BtGatt.ScanManager: stopping BLe Batch
,08-26 18:20:41.046  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 18:20:41.046  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.046  7630  7660 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 18:20:41.046  7630  7656 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 18:20:41.046  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.046  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-26 18:20:41.046  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:41.046  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.046  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:41.046  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.046  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@241eca0f removed from the list
08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.046  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1946ca9c removed from the list
08-26 18:20:41.046  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:41.046  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.046  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.046  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.046  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.046  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1946ca9c not in the list
08-26 18:20:41.046  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.046  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
08-26 18:20:41.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3107f82b removed from the list
08-26 18:20:41.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.056  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:41.056  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:41.056  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@367f087a removed from the list
08-26 18:20:41.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:41.056  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170bec07 added. We now have 2 listener(s)
,08-26 18:20:41.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 18:20:41.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:41.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:41.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.066  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@667d134 added. We now have 9 listener(s)
08-26 18:20:41.066  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:41.066  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:41.076  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:41.086  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:41.086  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 18:20:41.086  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:41.086  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:41.086  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33322cd2 added. We now have 3 listener(s)
08-26 18:20:41.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:41.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:41.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:41.086  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:41.086  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.086  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127141a3 added. We now have 10 listener(s)
08-26 18:20:41.086  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:41.086  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:41.086  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:41.086  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:41.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:41.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:41.086  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 18:20:41.086  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 18:20:41.086  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 18:20:41.106  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 18:20:41.106  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 18:20:41.106  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 18:20:41.106  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 18:20:41.106  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 18:20:41.116  7630  7645 D BtGatt.GattService: registerClient() - UUID=5cbe3c1e-5eb4-4088-bfcc-8b9ea05fc36e
,08-26 18:20:41.156  7630  7656 D BtGatt.GattService: onClientRegistered() - UUID=5cbe3c1e-5eb4-4088-bfcc-8b9ea05fc36e, clientIf=6
,08-26 18:20:41.156  6866  6877 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 18:20:41.156  7630  7704 D BtGatt.GattService: start scan with filters
,08-26 18:20:41.156  7630  7660 D BtGatt.ScanManager: handling starting scan
,08-26 18:20:41.166  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-26 18:20:41.166  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 18:20:41.166  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:41.166  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 18:20:41.166  7630  7656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 18:20:41.166  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.166  7630  7660 D BtGatt.ScanManager: allow scan with filters
08-26 18:20:41.166  7630  7660 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 18:20:41.166  7630  7660 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 18:20:41.166  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 18:20:41.166  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.166  7630  7660 D BtGatt.ScanManager: Starting BLE batch scan
08-26 18:20:41.166  7630  7660 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 18:20:41.166  7630  7656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 18:20:41.166  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.176  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 18:20:41.176  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.176  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:41.176  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:41.176  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 18:20:41.186  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:41.186  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 18:20:41.186  6866  6920 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 18:20:41.186  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:41.186  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:41.186  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 18:20:41.186  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 18:20:41.186  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.186  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 18:20:41.186  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 18:20:41.186  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170bec07 removed from the list
,08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.196  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@667d134 removed from the list
,08-26 18:20:41.196  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:41.196  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
,08-26 18:20:41.196  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-26 18:20:41.196  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-26 18:20:41.196  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:41.196  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.196  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@667d134 not in the list
,08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:41.196  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:41.196  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:41.196  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:41.206  7630  7638 D BtGatt.GattService: stopScan() - queue size =1
,08-26 18:20:41.206  7630  7645 D BtGatt.GattService: unregisterClient() - clientIf=6,
,08-26 18:20:41.206  7630  7660 D BtGatt.ScanManager: filter size is 1
,08-26 18:20:41.206  7630  7660 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 18:20:41.206  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16,
08-26 18:20:41.206  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.206  7630  7660 D BtGatt.ScanManager: stopping BLe Batch
,08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:41.206  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:41.206  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 18:20:41.206  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 18:20:41.206  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:41.206  7630  7660 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:41.206  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:41.206  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.216  7630  7656 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-26 18:20:41.216  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 18:20:41.216  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@127141a3 removed from the list
08-26 18:20:41.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.216  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:41.216  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.216  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.216  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33322cd2 removed from the list
08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134c54ff added. We now have 2 listener(s)
,08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.216  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a012cc added. We now have 9 listener(s)
,08-26 18:20:41.216  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:41.226  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:41.226  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 18:20:41.226  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 18:20:41.226  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 18:20:41.236  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 18:20:41.236  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:41.236  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:41.236  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 18:20:41.236  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aea842a added. We now have 3 listener(s)
,08-26 18:20:41.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-26 18:20:41.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 18:20:41.236  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 18:20:41.236  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.236  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9b421b added. We now have 10 listener(s)
,08-26 18:20:41.246  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:41.246  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:41.246  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 18:20:41.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 18:20:41.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 18:20:41.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 18:20:41.246  1015  1126 E WifiNative-wlan0: do suspend true
,08-26 18:20:41.246  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 18:20:41.246  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
08-26 18:20:41.256  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 18:20:41.256  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 18:20:41.256  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 18:20:41.256  6866  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 18:20:41.256  7630  7704 D BtGatt.GattService: registerClient() - UUID=ed0a22db-6c3e-47b9-9998-61acd6b004b0
,08-26 18:20:41.266  1015  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-26 18:20:41.276  1015  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 18:20:41.276  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:41.276  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-26 18:20:41.276  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.276  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-26 18:20:41.276  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.276  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.276  1015  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 18:20:41.276  1015  1126 E WifiStateMachine: VerifyingLinkState enter
08-26 18:20:41.276  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:41.286  1015  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 18:20:41.286  1015  1128 D ConnectivityService: Adding iface wlan0 to network 504,
,08-26 18:20:41.286  1015  1143 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-26 18:20:41.286  1015  1143 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 18:20:41.286  1015  1143 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 18:20:41.296  1015  1143 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 18:20:41.296  1015  1143 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 18:20:41.296  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 18:20:41.296  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:41.296  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.296  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.296  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.296  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.296  7630  7656 D BtGatt.GattService: onClientRegistered() - UUID=ed0a22db-6c3e-47b9-9998-61acd6b004b0, clientIf=6
,08-26 18:20:41.296  6866  6875 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 18:20:41.306  7630  7700 D BtGatt.GattService: start scan with filters
,08-26 18:20:41.306  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 18:20:41.306  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 18:20:41.306  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 18:20:41.306  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 18:20:41.306  7630  7660 D BtGatt.ScanManager: handling starting scan
08-26 18:20:41.316  1015  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 18:20:41.316  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 18:20:41.316  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 18:20:41.316  1015  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:41.316  1015  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 18:20:41.316  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 18:20:41.316  1015  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:41.316  1015  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 18:20:41.316  1015  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:41.316  1611  1611 I Hs20UtilService: Starting #22
,08-26 18:20:41.316  1015  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-26 18:20:41.326  7630  7656 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 18:20:41.326  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.326  7630  7660 D BtGatt.ScanManager: allow scan with filters
08-26 18:20:41.326  7630  7660 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 18:20:41.326  1015  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-26 18:20:41.326  7630  7660 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 18:20:41.326  1611  1637 I Hs20UtilService: Message received 5007
08-26 18:20:41.326  1015  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-26 18:20:41.326  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 18:20:41.326  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 18:20:41.326  1015  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 18:20:41.326  1015  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-26 18:20:41.326  1015  1128 D ConnectivityService: LTETest block dns file not exists
,08-26 18:20:41.326  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 18:20:41.326  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 18:20:41.326  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.326  7630  7660 D BtGatt.ScanManager: Starting BLE batch scan
08-26 18:20:41.326  7630  7660 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 18:20:41.326  4126  4126 I NearbySettings: MountReceiver.onReceive - Keep current state,
08-26 18:20:41.336  1178  1178 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:41.336  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 18:20:41.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.336  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.336  1015  1128 V NetworkStats: updateIfacesLocked()
08-26 18:20:41.336  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.336  1015  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:41.336  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:41.336  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:41.346  7630  7656 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 18:20:41.346  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.346  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 18:20:41.346  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 18:20:41.346  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-26 18:20:41.346  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 18:20:41.346  1015  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 18:20:41.356  1015  1128 V NetworkStats: performPollLocked() took 12ms
08-26 18:20:41.356  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:41.356  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 18:20:41.356  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 18:20:41.356  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:41.356  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 18:20:41.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.356  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.366  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 18:20:41.366  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:41.366  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.366  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.366  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@134c54ff removed from the list
08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.366  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a012cc removed from the list
08-26 18:20:41.366  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:41.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 18:20:41.366  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 18:20:41.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 18:20:41.366  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 18:20:41.366  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:41.366  1015  1128 E ConnectivityService: updateNetworkInfo()
08-26 18:20:41.366  1015  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 18:20:41.366  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.366  1015  1128 V NetworkStats: updateIfacesLocked()
08-26 18:20:41.366  1015  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-26 18:20:41.366  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.366  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:41.366  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 18:20:41.366  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:41.366  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.366  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.366  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.376  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@35a012cc not in the list
08-26 18:20:41.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 18:20:41.376  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 18:20:41.376  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 18:20:41.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 18:20:41.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 18:20:41.376  1015  1128 V NetworkStats: performPollLocked() took 4ms
,08-26 18:20:41.376  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.376  7630  7638 D BtGatt.GattService: stopScan() - queue size =1
,08-26 18:20:41.376  7630  7660 D BtGatt.ScanManager: filter size is 1
08-26 18:20:41.376  7630  7660 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 18:20:41.376  7630  7656 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 18:20:41.376  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.376  7630  7660 D BtGatt.ScanManager: stopping BLe Batch
08-26 18:20:41.376  1015  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
,08-26 18:20:41.376  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 18:20:41.376  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 18:20:41.376  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 18:20:41.376  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 18:20:41.376  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 18:20:41.376  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.376  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:41.376  7630  7645 D BtGatt.GattService: unregisterClient() - clientIf=6
08-26 18:20:41.376  7630  7656 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 18:20:41.376  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.376  1015  7748 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:41.376  7630  7660 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 18:20:41.376  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 18:20:41.376  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 18:20:41.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 18:20:41.376  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 18:20:41.376  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 18:20:41.386  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:41.386  1015  1128 D ConnectivityService:    accepting network in place of null
08-26 18:20:41.386  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 18:20:41.386  6866  6920 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 18:20:41.386  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 18:20:41.386   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-26 18:20:41.386   277  1010 D Netd    : getNetworkForDns: using netid 504 for uid 1000
08-26 18:20:41.386  1015  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 18:20:41.386  1015  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 18:20:41.386  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:41.386  1015  1319 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:41.386  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 18:20:41.386  1015  1319 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 18:20:41.386  1469  1469 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 18:20:41.386  1015  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-26 18:20:41.386  1015  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 18:20:41.386  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-26 18:20:41.386  1015  1319 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:41.386  1015  1319 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:41.386  1015  1319 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:41.386  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 18:20:41.386  1015  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-26 18:20:41.386  1015  1129 D Tethering: MasterInitialState.processMessage what=3
08-26 18:20:41.386  1015  1123 V NetworkStats: updateIfacesLocked()
08-26 18:20:41.386  1611  1611 I Hs20UtilService: Starting #23
08-26 18:20:41.386  1015  1123 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:41.386  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 18:20:41.386  1015  7748 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 18:20:41.386  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.386  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:41.386  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:41.396  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-26 18:20:41.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.396  1015  1128 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-26 18:20:41.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.396  1015  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-26 18:20:41.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.396  1015  1128 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-26 18:20:41.396  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c9b421b removed from the list
08-26 18:20:41.396  1015  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-26 18:20:41.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.396  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.396  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:41.396  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.396  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1aea842a removed from the list
08-26 18:20:41.396  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:41.396  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1921e4f7 added. We now have 2 listener(s)
08-26 18:20:41.396  1178  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:41.396  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:41.396  6866  6866 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 18:20:41.396  6866  6866 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 18:20:41.396  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:41.396  1611  1637 I Hs20UtilService: Message received 5007
08-26 18:20:41.396  1015  1123 V NetworkStats: performPollLocked() took 8ms
08-26 18:20:41.396  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.396  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.396  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.396  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.396  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.396  1015  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 18:20:41.396  7630  7656 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 18:20:41.396  7630  7656 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 18:20:41.396  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 18:20:41.396  4126  4126 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 18:20:41.406  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-26 18:20:41.406  1178  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 18:20:41.406  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.406  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 18:20:41.406  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 18:20:41.406  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
08-26 18:20:41.406  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-26 18:20:41.406  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 18:20:41.406  4126  4126 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-26 18:20:41.406  4126  4126 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 18:20:41.406  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:41.406  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:41.406  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:41.406  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.406  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@153bef64 added. We now have 9 listener(s)
08-26 18:20:41.406  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 18:20:41.406  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:41.406  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.406  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: EthernetConnected: false
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: updateDataNetType()
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 18:20:41.416  1178  1178 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 18:20:41.416  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 18:20:41.416  6866  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 18:20:41.416  1178  1178 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 18:20:41.416  1178  1178 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 18:20:41.416  6866  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 18:20:41.416  6866  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 18:20:41.416  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 18:20:41.416  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cbb6e82 added. We now have 3 listener(s)
,08-26 18:20:41.426  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:41.426  6866  6866 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 18:20:41.426  1015  1134 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 18:20:41.426  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 18:20:41.426  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:41.426  1015  1134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:41.426  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 18:20:41.426  1611  1611 I Hs20UtilService: Starting #24
08-26 18:20:41.426  1611  1637 I Hs20UtilService: Message received 5007
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 18:20:41.426  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 18:20:41.426  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1205d993 added. We now have 10 listener(s)
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 18:20:41.426  6866  6920 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 18:20:41.426  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 18:20:41.426  6866  6920 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.426  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.426  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1921e4f7 removed from the list
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.426  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@153bef64 removed from the list
08-26 18:20:41.426  6866  6920 D io.jxcore.node.ConnectivityMonitor: stop
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.426  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.426  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.426  6866  6920 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@153bef64 not in the list
08-26 18:20:41.426  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.426  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 18:20:41.436  4126  4126 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 18:20:41.436  4126  4126 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 18:20:41.436  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 18:20:41.436  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 18:20:41.436  6866  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 18:20:41.436  6866  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1205d993 removed from the list
08-26 18:20:41.436  6866  6920 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 18:20:41.436  6866  6920 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 18:20:41.436  6866  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 18:20:41.436  6866  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 18:20:41.436  6866  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1cbb6e82 removed from the list
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-26 18:20:41.436  6866  6920 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 18:20:41.446  1015  1494 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 18:20:41.446  1015  3406 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-26 18:20:41.446  1015  3406 D SecContentProvider2: mCursor = null,
08-26 18:20:41.446  1015  1533 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 18:20:41.446  1015  1533 D SecContentProvider2: mCursor = null
08-26 18:20:41.446  6866  7787 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1389, name: My test thread name)
08-26 18:20:41.446  6866  7787 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1389, thread name: My test thread name)
08-26 18:20:41.446  6866  7787 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1389, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 18:20:41.446  1015  1512 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 18:20:41.446  1015  1512 D SecContentProvider2: mCursor = null
08-26 18:20:41.446  6866  7788 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1391, name: My test thread name)
08-26 18:20:41.446  6866  7788 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1391, thread name: My test thread name)
08-26 18:20:41.446  6866  7788 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1391, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 18:20:41.446  1015  4357 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 18:20:41.446  1015  4357 D SecContentProvider2: mCursor = null
,08-26 18:20:41.446  6866  6920 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 18:20:41.446  6866  6920 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 18:20:41.446  6866  6920 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 18:20:41.446  6866  6920 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 18:20:41.446  6866  6920 D com.test.thalitest.ThaliTestRunner: Total duration: 23421 ms
08-26 18:20:41.446  6866  6920 I jxcore-log: *Native tests were executed*
08-26 18:20:41.446  6866  6920 I jxcore-log: 
,08-26 18:20:41.446  6866  6920 I jxcore-log: Total number of executed tests:  80
08-26 18:20:41.446  6866  6920 I jxcore-log: 
08-26 18:20:41.446  6866  6920 I jxcore-log: Number of passed tests:  80
08-26 18:20:41.446  6866  6920 I jxcore-log: 
08-26 18:20:41.446  6866  6920 I jxcore-log: Number of failed tests:  0
08-26 18:20:41.446  6866  6920 I jxcore-log: 
08-26 18:20:41.446  6866  6920 I jxcore-log: Number of ignored tests:  0
08-26 18:20:41.446  6866  6920 I jxcore-log: 
,08-26 18:20:41.456  6866  6920 I jxcore-log: Total duration:  23421
08-26 18:20:41.456  6866  6920 I jxcore-log: 
08-26 18:20:41.456  6866  6920 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-26 18:20:41.456  6866  6920 I jxcore-log: 
08-26 18:20:41.456  1015  1535 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-26 18:20:41.456  1015  1535 D SecContentProvider2: mCursor = null
,08-26 18:20:41.456  1015  1496 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-26 18:20:41.456  1015  1496 D SecContentProvider2: mCursor = null
08-26 18:20:41.456  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.456  6866  6920 I jxcore-log: 
08-26 18:20:41.456  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.456  6866  6920 I jxcore-log: 
08-26 18:20:41.456  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.456  6866  6920 I jxcore-log: 
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
,08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
,08-26 18:20:41.466  6866  6866 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
08-26 18:20:41.466  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.466  6866  6920 I jxcore-log: 
08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"},
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.476  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.476  6866  6920 I jxcore-log: 
,08-26 18:20:41.486  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.486  6866  6920 I jxcore-log: 
08-26 18:20:41.486  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-26 18:20:41.486  6866  6920 I jxcore-log: 
08-26 18:20:41.486  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.486  6866  6920 I jxcore-log: 
08-26 18:20:41.486  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 18:20:41.486  6866  6920 I jxcore-log: 
08-26 18:20:41.486   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
08-26 18:20:41.486  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 18:20:41.486  6866  6920 I jxcore-log: 
,08-26 18:20:41.496  1015  3406 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
,08-26 18:20:41.496  1178  1178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 18:20:41.516   288   288 E SMD     : DCD OFF,
,08-26 18:20:41.536  6866  6866 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 18:20:41.546  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 18:20:41.546  6866  6920 I jxcore-log: 
,08-26 18:20:41.696  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 18:20:41.696  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-26 18:20:41.696  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-26 18:20:41.696  1015  1027 D BatteryService: stay LED for fully charged
08-26 18:20:41.696  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 18:20:41.696  1015  1015 I MotionRecognitionService: Plugged
,08-26 18:20:41.696  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 18:20:41.706  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
08-26 18:20:41.706  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 18:20:41.706  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 18:20:41.706  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-26 18:20:41.706  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-26 18:20:41.706  1178  1178 D SViewCoverView: level :100 plugged : 2
,08-26 18:20:41.716  6866  6866 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 18:20:41.716  7630  7630 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 18:20:41.716  7630  7661 D HeadsetStateMachine: Disconnected process message: 10
,08-26 18:20:41.716  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 18:20:41.716  6866  6920 I jxcore-log: 
08-26 18:20:41.716  7790  7790 D AndroidRuntime: 
08-26 18:20:41.716  7790  7790 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 18:20:41.716  7790  7790 D AndroidRuntime: CheckJNI is OFF
,08-26 18:20:41.716  7790  7790 D AndroidRuntime: readGMSProperty: start
08-26 18:20:41.716  7790  7790 D AndroidRuntime: readGMSProperty: already setted!!
08-26 18:20:41.716  7790  7790 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 18:20:41.716  7790  7790 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 18:20:41.716  7790  7790 D AndroidRuntime: readGMSProperty: end
08-26 18:20:41.716  7790  7790 D AndroidRuntime: addProductProperty: start
,08-26 18:20:41.726  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:41.726  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:41.726  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-26 18:20:41.846  7790  7790 E AffinityControl: AffinityControl: registerfunction enter,
,08-26 18:20:41.876  7790  7790 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 18:20:41.886  1015  4357 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 18:20:41.886  1015  4357 D PackageManager: START PACKAGE DELETE: observer{859785262}
08-26 18:20:41.886  1015  4357 D PackageManager: pkg{<packageName>}
08-26 18:20:41.886  1015  4357 D PackageManager: user{0}
08-26 18:20:41.886  1015  4357 D PackageManager: caller{2000}
08-26 18:20:41.886  1015  4357 D PackageManager: flags{2}
08-26 18:20:41.886  1015  4357 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
08-26 18:20:41.886  1015  4357 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true,
08-26 18:20:41.886  1015  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
08-26 18:20:41.886  1015  4357 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 18:20:41.886  1015  4357 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-26 18:20:41.896  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-26 18:20:41.896  1015  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 18:20:41.896  1015  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-26 18:20:41.896  6866  6866 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
,08-26 18:20:41.896  6866  6920 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 18:20:41.896  6866  6920 I jxcore-log: 
,08-26 18:20:41.896  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-26 18:20:41.896  1015  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 18:20:41.906  1015  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-26 18:20:42.006  1015  1054 W PackageSettings: Skipping PackageSetting{2f93f1fb com.example.hello/10168} due to missing metadata
,08-26 18:20:42.036  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 18:20:42.036  6866  6866 D AndroidRuntime: Shutting down VM,
,08-26 18:20:42.036  6866  6866 E AndroidRuntime: FATAL EXCEPTION: main
08-26 18:20:42.036  6866  6866 E AndroidRuntime: Process: com.test.thalitest, PID: 6866
,08-26 18:20:42.036  6866  6866 E AndroidRuntime: java.lang.RuntimeException: Error receiving broadcast Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } in io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@80a5835
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:943)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: ,	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: Caused by: java.lang.SecurityException: ConnectivityService: Neither user 10171 nor current process has android.permission.ACCESS_NETWORK_STATE.
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1540)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.os.Parcel.readException(Parcel.java:1493)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.net.IConnectivityManager$Stub$Proxy.getActiveNetworkInfo(IConnectivityManager.java:1297)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.net.ConnectivityManager.getActiveNetworkInfo(ConnectivityManager.java:748)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor.updateConnectivityInfo(ConnectivityMonitor.java:152)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver.onReceive(ConnectivityMonitor.java:225)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:933)
08-26 18:20:42.036  6866  6866 E AndroidRuntime: 	... 8 more
08-26 18:20:42.036  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.036  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.036  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.036  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.056  7800  7800 E Zygote  : MountEmulatedStorage()
08-26 18:20:42.056  7800  7800 E Zygote  : v2
08-26 18:20:42.056  7800  7800 I libpersona: KNOX_SDCARD checking this for 1000
08-26 18:20:42.056  7800  7800 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:42.056  1015  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:42.056  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:42.056  1015  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 18:20:42.056  1015  1128 V NetworkStats: updateIfacesLocked()
08-26 18:20:42.056  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:42.056  1015  1128 V NetworkStats: performPollLocked(flags=0x1)
08-26 18:20:42.056  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:42.056  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:42.056  1015  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 18:20:42.056  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 18:20:42.066  1015  1128 V NetworkStats: performPollLocked() took 5ms
08-26 18:20:42.066  1015  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:42.066  1015  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7800 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-26 18:20:42.106  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-26 18:20:42.106  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.106  7800  7800 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.106  1015  1040 I ActivityManager: Killing 6866:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-26 18:20:42.106  1015  1040 I ActivityManager:   Force finishing activity ActivityRecord{275361b u0 com.test.thalitest/.MainActivity t2},
08-26 18:20:42.116  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 18:20:42.116  1015  1028 D SecContentProvider2: mCursor = null
,08-26 18:20:42.116  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 18:20:42.116  1015  1496 W ActivityManager: Can't find mystery application for Crash from pid=6866 uid=10171: android.os.BinderProxy@1b83efcf
,08-26 18:20:42.116  1015  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
08-26 18:20:42.116  1015  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-26 18:20:42.116  1178  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 18:20:42.116  1178  1730 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 18:20:42.116  1015  1054 I ActivityManager:   Force finishing activity ActivityRecord{275361b u0 com.test.thalitest/.MainActivity t2 f}
08-26 18:20:42.116  1015  1054 W ActivityManager: Duplicate finish request for ActivityRecord{275361b u0 com.test.thalitest/.MainActivity t2 f}
08-26 18:20:42.116  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 18:20:42.126  4869  6929 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 18:20:42.136  1015  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 18:20:42.146  1015  1040 D InputDispatcher: Focus left window: 6866
,08-26 18:20:42.146   258  2006 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
08-26 18:20:42.146   258   453 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 18:20:42.166  1015  1040 D InputDispatcher: Focused application released
,08-26 18:20:42.166  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 18:20:42.166  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 18:20:42.176  1015  1040 D FocusedStackFrame: Set to : 0
,08-26 18:20:42.176  1015  1040 W ActivityManager: mDVFSHelper.acquire()
,08-26 18:20:42.176  2682  2682 I art     : Explicit concurrent mark sweep GC freed 21141(1184KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 857us total 48.480ms
,08-26 18:20:42.196  1015  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-26 18:20:42.196  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:42.196  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:42.206  4869  4869 I art     : Explicit concurrent mark sweep GC freed 23792(1415KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.269ms total 80.892ms
,08-26 18:20:42.206  1497  1497 D Launcher: onRestart, Launcher: 667179910
,08-26 18:20:42.216  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 18:20:42.226  1879  1879 E SamsungIME: mOCRHelper is null
,08-26 18:20:42.236  1497  1497 D Launcher: onStart, Launcher: 667179910
,08-26 18:20:42.236  1497  1497 D Launcher.HomeView: onStart
,08-26 18:20:42.246  1497  1497 D Launcher: onResume, Launcher: 667179910
,08-26 18:20:42.246  1015  1496 D SettingsProvider: name = kids_home_mode
08-26 18:20:42.246  1015  1496 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 18:20:42.246  1015  1496 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 18:20:42.246  1015  1496 D SettingsProvider: selectionArgs: false
08-26 18:20:42.246  1015  1496 D SettingsProvider: selectionArgs: 10006
08-26 18:20:42.246  1015  1496 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 18:20:42.246  1015  1496 D SettingsProvider: ret = -1
,08-26 18:20:42.246  1497  1497 D Launcher.HomeView: onResume
,08-26 18:20:42.246  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-26 18:20:42.256  1456  1456 D RegisteredServicesCache: empty dynamic service
,08-26 18:20:42.256  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 18:20:42.286  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-26 18:20:42.286  1497  1497 D MenuAppsGridFragment: onResume
,08-26 18:20:42.286  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 18:20:42.286  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 18:20:42.286  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-26 18:20:42.286  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-26 18:20:42.286  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 18:20:42.296  1015  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-26 18:20:42.296  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 18:20:42.296  1015  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-26 18:20:42.296  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 18:20:42.296  1015  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 18:20:42.296  7800  7800 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 18:20:42.296  7800  7800 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 18:20:42.296  7800  7800 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-26 18:20:42.296  1015  1123 V NetworkStats: performPollLocked() took 7ms
08-26 18:20:42.296  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:42.306  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-26 18:20:42.316  7800  7800 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 18:20:42.316  7800  7800 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-26 18:20:42.316  7800  7800 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 18:20:42.316  7800  7800 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:42.316  1015  1533 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-26 18:20:42.316  1015  1533 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 18:20:42.316  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:42.316  1015  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 18:20:42.326  1015  1533 I ActivityManager: Killing 7196:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-26 18:20:42.326  1015  4518 D ActivityManager: handle home activity for 0
08-26 18:20:42.326  1015  4518 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-26 18:20:42.326  1015  4518 D KnoxTimeoutHandler: post home show event for user 0
08-26 18:20:42.336  1015  4518 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 18:20:42.336  1015  4518 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 18:20:42.336  1015  4518 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 18:20:42.336  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
08-26 18:20:42.336  1497  1497 D Launcher.HomeView: onPause
,08-26 18:20:42.336  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-26 18:20:42.336  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 18:20:42.346  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
08-26 18:20:42.346  1777  1777 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:42.346  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.346  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.346  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.346  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.356  7818  7818 E Zygote  : MountEmulatedStorage()
,08-26 18:20:42.356  7818  7818 E Zygote  : v2
08-26 18:20:42.356  7818  7818 I libpersona: KNOX_SDCARD checking this for 10121
08-26 18:20:42.356  7818  7818 I libpersona: KNOX_SDCARD not a persona,
,08-26 18:20:42.366  1015  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7818 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
,08-26 18:20:42.366  7818  7818 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:42.366  7818  7818 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:42.366  1015  1496 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-26 18:20:42.366  1015  1496 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-26 18:20:42.366  1015  1496 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:42.366  1015  1496 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:42.366  1015  1496 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder,
,08-26 18:20:42.376  7818  7818 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:42.376  2468  3277 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
08-26 18:20:42.376  1015  1134 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-26 18:20:42.376  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.376  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.376  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.376  1015  1134 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.386  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 18:20:42.386  1015  1028 D SecContentProvider2: mCursor = null
,08-26 18:20:42.396  1015  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 18:20:42.396  7826  7826 E Zygote  : MountEmulatedStorage(),
08-26 18:20:42.396  7826  7826 E Zygote  : v2
08-26 18:20:42.396  7826  7826 I libpersona: KNOX_SDCARD checking this for 10031,
08-26 18:20:42.396  7826  7826 I libpersona: KNOX_SDCARD not a persona,
08-26 18:20:42.396  1015  1134 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7826 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-26 18:20:42.396  7826  7826 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-26 18:20:42.406  7826  7826 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-26 18:20:42.406  1777  1777 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-26 18:20:42.416  1777  1777 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1,
08-26 18:20:42.416  1777  1777 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-26 18:20:42.416  7826  7826 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 18:20:42.416  1015  1494 D PersonaManager: isKioskContainerExistOnDevice
,08-26 18:20:42.416  1777  1777 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:42.436  7818  7818 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.436  7818  7818 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.436   258   258 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-26 18:20:42.446  7826  7826 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.446  7826  7826 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.456  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 18:20:42.456  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 18:20:42.456  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
,08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 18:20:42.466  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 18:20:42.466  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-26 18:20:42.466  1015  1495 D InputDispatcher: Focus entered window: 1497
,08-26 18:20:42.476  1456  1456 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 18:20:42.476  1497  1497 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 18:20:42.476  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 18:20:42.476  1777  1777 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 18:20:42.476  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 18:20:42.476  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 18:20:42.486  1777  1777 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 18:20:42.486  1015  3374 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 18:20:42.486  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 18:20:42.486  7818  7818 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:42.486  7818  7818 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 18:20:42.486  7818  7818 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 18:20:42.486  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-26 18:20:42.486  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-26 18:20:42.486  1015  1054 I art     : Explicit concurrent mark sweep GC freed 86606(5MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 24MB/37MB, paused 7.828ms total 233.114ms
,08-26 18:20:42.496  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{349c1d7d token=android.os.BinderProxy@f6c9220 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-26 18:20:42.496  1497  1497 D Launcher.HomeView: onStop
,08-26 18:20:42.496  1456  1456 D PersonaManager: isKioskContainerExistOnDevice
,08-26 18:20:42.496  1015  1160 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-26 18:20:42.516  1015  1054 D PackageManager: delete codoeFile: 
,08-26 18:20:42.516  1015  3406 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 18:20:42.516  1015  7849 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 18:20:42.516  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0,
08-26 18:20:42.516  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-26 18:20:42.516  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-26 18:20:42.516  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-26 18:20:42.526  1015  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-26 18:20:42.526  1015  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-26 18:20:42.526  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 18:20:42.526  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 18:20:42.526  1015  1535 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-26 18:20:42.526  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
08-26 18:20:42.526  1015  1039 W TextServicesManagerService: no available spell checker services found
,08-26 18:20:42.526  1015  1054 D PackageManager: result of delete: 1{859785262}
,08-26 18:20:42.526  1015  3406 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6866 uid 10171
,08-26 18:20:42.536  7818  7818 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:42.546  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.546  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.556  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:42.556  1015  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:42.556  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-26 18:20:42.556  7790  7790 D AndroidRuntime: Shutting down VM,
,08-26 18:20:42.566  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-26 18:20:42.566  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast,
08-26 18:20:42.566  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.566  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.566  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.566  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.576  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.576  1879  1879 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-26 18:20:42.576  7854  7854 E Zygote  : MountEmulatedStorage()
08-26 18:20:42.576  7854  7854 E Zygote  : v2
08-26 18:20:42.576  7854  7854 I libpersona: KNOX_SDCARD checking this for 10001
08-26 18:20:42.576  7854  7854 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:42.576  7854  7854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:42.586  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7854 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:42.586  7854  7854 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:42.586  7854  7854 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:42.586  1178  1178 I StatusBar: Icon Only
08-26 18:20:42.586  1178  1178 D PanelView: There is/are notification(s) 
,08-26 18:20:42.596  7818  7818 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 18:20:42.596  1015  1134 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-26 18:20:42.596  1015  1134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-26 18:20:42.606  1015  1134 W ActivityManager: userId = 0, bbcId = -10000
08-26 18:20:42.606  1015  1134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 18:20:42.606  1015  1134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 18:20:42.616  1015  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 18:20:42.616  1015  1054 D PackageManager: userId{-1}
08-26 18:20:42.616  1015  1054 D PackageManager: andCode{true}
,08-26 18:20:42.626  1015  1045 W ActivityManager: mDVFSHelper.release()
08-26 18:20:42.626  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2055fea8 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147311
,08-26 18:20:42.626  1015  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 18:20:42.626  7854  7854 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.626  7854  7854 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.626  7818  7818 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 18:20:42.636  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.636  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.636  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.636  1015  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.636  7126  7870 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 18:20:42.646  7126  7870 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 18:20:42.646  7126  7870 I System.out: (HTTPLog)-Static: isShipBuild true
08-26 18:20:42.646  7126  7870 I System.out: (HTTPLog)-Thread-1300-134895669: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 18:20:42.646  7126  7870 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 18:20:42.646   277  1010 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,08-26 18:20:42.646   277  1010 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-26 18:20:42.646  7874  7874 E Zygote  : MountEmulatedStorage()
,08-26 18:20:42.646  7874  7874 E Zygote  : v2
,08-26 18:20:42.646  7874  7874 I libpersona: KNOX_SDCARD checking this for 10003
08-26 18:20:42.646  7874  7874 I libpersona: KNOX_SDCARD not a persona
,08-26 18:20:42.646  1015  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7874 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 18:20:42.646  7874  7874 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-26 18:20:42.656  7874  7874 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-26 18:20:42.656  7874  7874 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 18:20:42.676  1972  2152 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 18:20:42.676  1015  1028 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:42.676  1015  1134 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 18:20:42.676  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 18:20:42.686  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.696  7874  7874 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.696  7874  7874 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.696  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.706  7126  7870 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 18:20:42.706  7339  7339 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-26 18:20:42.736  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.736  7243  7243 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-26 18:20:42.746  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 18:20:42.746  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 18:20:42.746  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 18:20:42.746  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.746  2799  7892 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-26 18:20:42.746  2799  7892 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
08-26 18:20:42.746  7281  7281 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-26 18:20:42.746  7281  7281 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-26 18:20:42.746  7281  7281 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-26 18:20:42.746  2799  7892 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 18:20:42.756  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.756  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.766  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-26 18:20:42.766  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-26 18:20:42.766  7126  7870 I Babel   : connection state changed from DISCONNECTED to CONNECTED,
08-26 18:20:42.766  7281  7281 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 18:20:42.766  7281  7281 I SA      : [OR] == isSIMCardReady false ==
,08-26 18:20:42.766  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.766  7790  7790 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 18:20:42.766  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 18:20:42.776  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 18:20:42.776  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 18:20:42.776  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 18:20:42.776  7281  7281 I SA      : [SCU] == networkStateCheck == true
,08-26 18:20:42.776  7281  7281 I SA      : [DM] getCountryCodeFromCSC : PL
08-26 18:20:42.776  7281  7281 I SA      : isChinaCountryCode : false
08-26 18:20:42.776  7281  7281 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-26 18:20:42.776  7281  7281 I SA      : [OR] == networkStateCheck true ==
08-26 18:20:42.776  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 18:20:42.776  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 18:20:42.776  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 18:20:42.776  1015  1216 I ActivityManager: Killing 7260:com.sec.android.diagmonagent/1000 (adj 15): empty #21
,08-26 18:20:42.786  1015  1216 I ActivityManager: Killing 7303:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-26 18:20:42.796  2799  7892 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-26 18:20:42.796  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
08-26 18:20:42.796  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-26 18:20:42.796  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts,
08-26 18:20:42.796  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-26 18:20:42.806  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts,
08-26 18:20:42.806  2799  7892 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-26 18:20:42.806  2799  7892 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-26 18:20:42.806  7281  7281 I SA      : [OR] GetMyCountryZoneTask
,08-26 18:20:42.806  7281  7281 I SA      : [OR] onReceive END
,08-26 18:20:42.816  1015  1216 I ActivityManager: Killing 7323:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-26 18:20:42.816  1225  1225 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 18:20:42.816  1015  3406 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-26 18:20:42.816  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-26 18:20:42.816  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:42.816  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:42.816  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-26 18:20:42.826  7281  7896 I SA      : [SRS] prepareGetMyCountryZone
,08-26 18:20:42.826  2799  7892 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-26 18:20:42.836  1015  4518 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-26 18:20:42.836  1015  4518 D SecContentProvider2: mCursor = null
,08-26 18:20:42.846  2799  7892 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-26 18:20:42.846  1015  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-26 18:20:42.846  1015  1040 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.fotaclient/com.sec.android.fotaclient.FotaRegisterReceiver}
08-26 18:20:42.846  1015  1040 W BroadcastQueue: android.os.TransactionTooLargeException
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:195)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 18:20:42.846  1015  1040 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-26 18:20:42.846  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 18:20:42.846  7281  7896 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 18:20:42.846  7281  7896 I SA      : [SSP] query invoked
,08-26 18:20:42.846  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.846  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.846  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 18:20:42.846  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 18:20:42.856  1015  1039 W libprocessgroup: failed to open /acct/uid_10008/pid_7323/cgroup.procs: No such file or directory
,08-26 18:20:42.856  7281  7896 I SA      : [TPMU] GetMccFromDB : null
,08-26 18:20:42.866  7900  7900 E Zygote  : MountEmulatedStorage(),
08-26 18:20:42.866  7900  7900 E Zygote  : v2
08-26 18:20:42.866  7900  7900 I libpersona: KNOX_SDCARD checking this for 10008,
08-26 18:20:42.866  7900  7900 I libpersona: KNOX_SDCARD not a persona
08-26 18:20:42.866  7900  7900 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-26 18:20:42.866  1015  1040 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7900 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 18:20:42.866  7900  7900 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-26 18:20:42.866  7281  7896 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-26 18:20:42.876  7900  7900 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-26 18:20:42.876  7281  7896 I SA      : [LBE] isSupportCheckDomainRegion : false
08-26 18:20:42.876  7281  7896 I SA      : [TPM] isNoProxy(default) : true
,08-26 18:20:42.886  7281  7896 E File    : fail readDirectory() errno=2
,08-26 18:20:42.896  7900  7900 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 18:20:42.896  7900  7900 D ActivityThread: Added TimaKeyStore provider
,08-26 18:20:42.976  7900  7900 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-26 18:20:42.986  7900  7900 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-26 18:20:42.986  7900  7900 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-26 18:20:43.006  7900  7900 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-26 18:20:43.006  1497  1497 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f6c9220 time:147695
,08-26 18:20:43.006  1015  1494 I ActivityManager: Killing 6943:com.google.android.gms.unstable/u0a11 (adj 15): empty #21
,08-26 18:20:43.016  2920  2920 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 18:20:43 GMT+02:00 2016
,08-26 18:20:43.016  1015  3406 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-26 18:20:43.016  1015  3406 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 18:20:43.016  1015  3406 W ActivityManager: userId = 0, bbcId = -10000
,08-26 18:20:43.016  1015  3406 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 18:20:43.016  1015  3406 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 18:20:43.016  1015  1494 I ActivityManager: Killing 4282:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-26 18:20:43.026  2920  2920 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-26 18:20:43.026  2920  2920 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-26 18:20:43.026  2920  2920 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 18:20:43.036  2920  2920 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 18:20:43.036  2920  7916 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 18:20:43.036  2920  7916 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-26 18:20:43.046  2920  7916 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-26 18:20:43.046  2920  7916 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-26 18:20:43.056  2920  7916 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-26 18:20:43.056  2920  7916 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,08-26 18:20:43.056  2920  7916 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:43.056  2920  7916 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:171)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.uploadRequestLog(NetworkChangeOperations.java:81)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.NetworkChangeOperations.doNetworkJob(NetworkChangeOperations.java:57)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.StateImplV2.networkChangeListener(StateImplV2.java:240)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:222)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
08-26 18:20:43.056  2920  7916 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 18:20:43.056  2920  7916 W SQLiteOpenHelper: Opened klms.db in read-only mode
,08-26 18:20:43.066  2920  7916 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 

```
