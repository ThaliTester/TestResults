#### Test 84265062e3ffea4_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
09-07 12:04:57.911  1020  1424 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 12:04:57.911  1020  1424 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 12:04:57.911  1020  1424 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 12:04:57.911  1020  1424 D BatteryService: stay LED for fully charged
09-07 12:04:57.911  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-07 12:04:57.921  1020  1020 I MotionRecognitionService: Plugged
09-07 12:04:57.921  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
09-07 12:04:57.921  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
--------- beginning of main
09-07 12:04:57.921  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-07 12:04:57.921  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
09-07 12:04:57.921  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
09-07 12:04:57.931  3170  3170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-07 12:04:57.931  3170  3274 D HeadsetStateMachine: Disconnected process message: 10
09-07 12:04:57.951  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 12:04:57.951  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 12:04:57.951  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 12:04:57.951  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 12:04:57.951  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 12:04:58.481  6742  6742 D AndroidRuntime: 
09-07 12:04:58.481  6742  6742 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 12:04:58.481  6742  6742 D AndroidRuntime: CheckJNI is OFF
09-07 12:04:58.481  6742  6742 D AndroidRuntime: readGMSProperty: start
09-07 12:04:58.481  6742  6742 D AndroidRuntime: readGMSProperty: already setted!!
09-07 12:04:58.481  6742  6742 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 12:04:58.481  6742  6742 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 12:04:58.481  6742  6742 D AndroidRuntime: readGMSProperty: end
09-07 12:04:58.481  6742  6742 D AndroidRuntime: addProductProperty: start
09-07 12:04:58.631   289   289 E SMD     : DCD OFF
09-07 12:04:58.641  6742  6742 E AffinityControl: AffinityControl: registerfunction enter
09-07 12:04:58.661  6742  6742 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 12:04:58.681  1020  1477 E PersonaManagerService: inState():  stateMachine is null !!
09-07 12:04:58.681  1020  1477 I PersonaManagerService: PersonaId don't exist
09-07 12:04:58.681  1020  1477 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-07 12:04:58.681  1020  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 12:04:58.711  1020  1477 W ActivityManager: mDVFSHelper.acquire()
09-07 12:04:58.711   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-07 12:04:58.721   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-07 12:04:58.721  1020  1477 D FocusedStackFrame: Set to : 0
09-07 12:04:58.731  1020  1050 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 12:04:58.731  1020  1050 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-07 12:04:58.741  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:04:58.741  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:04:58.741  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:04:58.741  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:04:58.751  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 12:04:58.751  1020  1050 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-07 12:04:58.751   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-07 12:04:58.751  6753  6753 E Zygote  : MountEmulatedStorage()
09-07 12:04:58.751  6753  6753 I libpersona: KNOX_SDCARD checking this for 10171
09-07 12:04:58.751  6753  6753 E Zygote  : v2
09-07 12:04:58.751  6753  6753 I libpersona: KNOX_SDCARD not a persona
09-07 12:04:58.761  6753  6753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:04:58.761  1020  1477 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6753 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 12:04:58.761  1020  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-07 12:04:58.761  1020  1477 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 12:04:58.761  1020  1477 D InputDispatcher: Focused application set to: xxxx
09-07 12:04:58.761  1020  1477 D InputDispatcher: Focus left window: 1483
09-07 12:04:58.761  6742  6742 D AndroidRuntime: Shutting down VM
09-07 12:04:58.761  6753  6753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:04:58.761  6753  6753 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-07 12:04:58.781  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 12:04:58.781  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 12:04:58.781  6753  6753 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:04:58.781  6753  6753 D ActivityThread: Added TimaKeyStore provider
09-07 12:04:58.791  1020  1033 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-07 12:04:58.791  1020  1020 V ActivityManager: Display changed displayId=0
09-07 12:04:58.801  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 12:04:58.811  1020  1033 D PersonaManager: isKioskContainerExistOnDevice
09-07 12:04:58.821  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-07 12:04:58.841   259   449 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
09-07 12:04:58.841   259   452 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
09-07 12:04:58.851  1483  1483 D Launcher: onTrimMemory. Level: 20
09-07 12:04:58.851  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{cfaba2b token=android.os.BinderProxy@189e8f77 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-07 12:04:58.941  6753  6753 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
09-07 12:04:58.971  6742  6742 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-07 12:04:59.001  6753  6753 I cr.library_loader: Time to load native libraries: 8 ms (timestamps 7237-7245)
,09-07 12:04:59.001  6753  6753 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 12:04:59.021  6753  6753 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3de6dce3}
,09-07 12:04:59.021  6753  6753 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 12:04:59.021  6753  6753 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-07 12:04:59.061  6753  6753 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-07 12:04:59.061  6753  6753 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-07 12:04:59.071  6753  6753 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-07 12:04:59.111  6753  6753 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-07 12:04:59.111  6753  6753 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 12:04:59.111  6753  6753 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 12:04:59.111  6753  6753 I Adreno-EGL: Local Branch: 
09-07 12:04:59.111  6753  6753 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 12:04:59.111  6753  6753 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 12:04:59.111  6753  6753 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 12:04:59.171  6753  6753 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 12:04:59.181  6753  6753 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-07 12:04:59.181  6753  6753 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-07 12:04:59.191  6753  6753 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-07 12:04:59.191  6753  6753 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,09-07 12:04:59.311  6753  6753 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 12:04:59.321  1020  1045 W ActivityManager: Activity pause timeout for ActivityRecord{bda7fca u0 com.test.thalitest/.MainActivity t2}
,09-07 12:04:59.321  6753  6753 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-07 12:04:59.331  6753  6753 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-07 12:04:59.331  6753  6753 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-07 12:04:59.341  6753  6753 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-07 12:04:59.341  6753  6753 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 12:04:59.341  6753  6753 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 12:04:59.381  6753  6791 D OpenGLRenderer: Render dirty regions requested: true
,09-07 12:04:59.381  1020  1477 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-07 12:04:59.381  1020  1477 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 12:04:59.381  1020  1477 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 12:04:59.381  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 12:04:59.381  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 12:04:59.391  6753  6780 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-07 12:04:59.391  6753  6753 V ActivityThread: updateVisibility : ActivityRecord{108c88c3 token=android.os.BinderProxy@3f638fd4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-07 12:04:59.401  6753  6753 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-07 12:04:59.401  6753  6753 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-07 12:04:59.411   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-07 12:04:59.431  1020  1481 D InputDispatcher: Focus entered window: 6753
,09-07 12:04:59.431  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 12:04:59.431  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 12:04:59.441  6753  6753 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-07 12:04:59.441  6753  6791 I OpenGLRenderer: Initialized EGL, version 1.4
,09-07 12:04:59.441  6753  6791 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-07 12:04:59.441  6753  6791 D OpenGLRenderer: Enabling debug mode 0
,09-07 12:04:59.461  1020  1368 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 12:04:59.461  1020  6797 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 12:04:59.471  1175  1175 I StatusBar: Icon Only
,09-07 12:04:59.471  1175  1175 D PanelView: There is/are notification(s) 
,09-07 12:04:59.481  1020  1050 I ActivityManager: Displayed Component not be shown by security: +666ms (total +748ms),
09-07 12:04:59.481  1020  1050 W ActivityManager: mDVFSHelper.release()
09-07 12:04:59.481  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{bda7fca u0 com.test.thalitest/.MainActivity t2} time:107726
,09-07 12:04:59.491  6753  6753 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-07 12:04:59.491  6753  6753 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f638fd4 time:107730
,09-07 12:04:59.491   259  1490 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
09-07 12:04:59.491   259   449 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,09-07 12:04:59.501  1973  1973 I SamsungIME: getCurrentCandidateView
,09-07 12:04:59.611  1973  1973 D SamsungIME: Dismiss ExpandCandiate
,09-07 12:04:59.681  6753  6753 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6753
,09-07 12:04:59.771  1973  1973 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 12:04:59.811  1973  1973 I SamsungIME: getDebugLevel  : 0x4f4c
,09-07 12:04:59.821  1973  1973 I SamsungIME: KeybaordView init() : load resources
,09-07 12:04:59.851  1973  1973 I SamsungIME: getCurrentKeyboard
,09-07 12:04:59.851  1973  1973 I SamsungIME: getTextKeyboard
,09-07 12:04:59.871  1973  1973 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-07 12:04:59.881  6753  6753 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 12:04:59.901  1020  1309 E Watchdog: !@Sync 3
,09-07 12:04:59.961  6753  6799 D jxcore_app_log: JniHelper::setJavaVM(0xb81cc2b0), pthread_self() = -1200249424
,09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 12:04:59.971  6753  6799 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@189b41b1 added. We now have 1 listener(s)
,09-07 12:04:59.971  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-07 12:04:59.981  6753  6799 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 12:04:59.981  6753  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:04:59.981  6753  6799 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-07 12:04:59.981  6753  6799 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24749604 added. We now have 1 listener(s)
09-07 12:04:59.981  6753  6799 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:04:59.991  1020  1099 V AlarmManager: waitForAlarm result :8
,09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-07 12:04:59.991  6753  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:00.001  6753  6799 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-07 12:05:00.001  6753  6799 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:00.001  6753  6799 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:00.001  6753  6799 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 12:05:00.001  6753  6799 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:00.011  6753  6799 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-07 12:05:00.011  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:00.011  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:00.031  6753  6753 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 12:05:00.531  1020  1480 I art     : Explicit concurrent mark sweep GC freed 26656(1594KB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 2.451ms total 140.953ms
,09-07 12:05:00.591  6753  6806 W jxcore-log: Initializing JXcore engine
09-07 12:05:00.591  6753  6806 W jxcore-log: JXcore engine is ready
,09-07 12:05:00.631   315   315 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6,
09-07 12:05:00.631   315   315 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-07 12:05:00.661  1988  1988 E audit   : type=1400 msg=audit(1473242700.661:205): avc:  denied  { ioctl } for  pid=6806 comm="Thread-1250" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3093 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
09-07 12:05:00.661  1988  1988 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:00.661  1988  1988 E audit   : type=1300 msg=audit(1473242700.661:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e2fb8f8 items=0 ppid=304 ppcomm=main pid=6806 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1250" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-07 12:05:00.661  1988  1988 E audit   : type=1320 msg=audit(1473242700.661:205): 
,09-07 12:05:00.671  6753  6806 W jxcore-log: Starting JXcore engine
,09-07 12:05:00.781  6753  6806 W jxcore-log: Platform android
09-07 12:05:00.781  6753  6806 W jxcore-log: 
09-07 12:05:00.781  6753  6806 W jxcore-log: Process ARCH arm
09-07 12:05:00.781  6753  6806 W jxcore-log: 
,09-07 12:05:00.981  6753  6806 I jxcore-log: JXcore Cordova bridge is ready!
09-07 12:05:00.981  6753  6806 I jxcore-log: 
,09-07 12:05:00.981  6753  6806 W jxcore-log: JXcore engine is started
,09-07 12:05:00.991  6753  6799 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-07 12:05:00.991  6753  6753 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 12:05:01.631   289   289 E SMD     : DCD OFF,
,09-07 12:05:04.631   289   289 E SMD     : DCD OFF,
,09-07 12:05:04.651  1020  1052 I PowerManagerService: [PWL] Off : 50s ago
,09-07 12:05:04.951  1020  3356 D SSRM:n  : SIOP:: AP = 320
,09-07 12:05:05.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:06.331  5607  5607 D FactoryTest: Not factory mode
,09-07 12:05:06.331  5607  5607 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-07 12:05:06.341  5607  5607 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,09-07 12:05:06.341  5607  5607 D MTPRx   : still no open session command from host, so toast
,09-07 12:05:06.341  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-07 12:05:06.341  5607  5607 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-07 12:05:06.341  5607  5607 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114586
,09-07 12:05:06.341  1020  1500 E PersonaManagerService: inState():  stateMachine is null !!
,09-07 12:05:06.341  1020  1500 I PersonaManagerService: PersonaId don't exist
09-07 12:05:06.341  1020  1500 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-07 12:05:06.351  1020  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 12:05:06.351  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:06.351  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:06.351  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-07 12:05:06.361  1020  1500 W ActivityManager: mDVFSHelper.acquire()
,09-07 12:05:06.381  1020  1500 D PersonaManager: isKioskContainerExistOnDevice,
,09-07 12:05:06.381  1020  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-07 12:05:06.381  1020  1500 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 12:05:06.381  1020  1500 D InputDispatcher: Focused application set to: xxxx
09-07 12:05:06.381  1020  1500 D InputDispatcher: Focus left window: 6753
,09-07 12:05:06.381  5607  5607 E MTPRx   : started activity for popup
,09-07 12:05:06.391  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 12:05:06.391  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 12:05:06.411  5607  5607 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 12:05:06.431  5607  5607 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-07 12:05:06.441  1020  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-07 12:05:06.441  1020  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 12:05:06.441  1020  1480 D InputDispatcher: Focused application set to: xxxx
,09-07 12:05:06.441  1020  1480 D InputDispatcher: Focus entered window: 6753
,09-07 12:05:06.441  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-07 12:05:06.451  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 12:05:06.451  1020  1499 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-07 12:05:06.451  1020  1499 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@255ed485 attribute=null, token = android.os.BinderProxy@3cd5bc15
,09-07 12:05:06.491  5607  5607 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-07 12:05:06.501  5607  5607 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-07 12:05:06.501  5607  5607 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-07 12:05:06.521  6753  6753 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 12:05:06.521  6753  6753 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-07 12:05:06.521  6753  6753 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 12:05:06.521  6753  6753 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-07 12:05:06.531  1020  1033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-07 12:05:06.531  1020  1033 D KnoxTimeoutHandler: postActiveUserChange for user 0
,09-07 12:05:06.531  1020  1033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 12:05:06.531  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-07 12:05:06.531  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
,09-07 12:05:06.541  6753  6753 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 12:05:06.541  6753  6753 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-07 12:05:06.551  6753  6753 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@24d64810 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7c08ad1, 16908290=android.view.AbsSavedState$1@7c08ad1}, android:focusedViewId=100}]}]
,09-07 12:05:06.551  6753  6753 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
,09-07 12:05:06.551  6753  6753 V ActivityThread: updateVisibility : ActivityRecord{108c88c3 token=android.os.BinderProxy@3f638fd4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-07 12:05:06.551  6753  6753 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-07 12:05:06.551  6753  6753 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,09-07 12:05:06.551  6753  6753 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3f638fd4 time:114794
,09-07 12:05:06.551  1020  1588 D PersonaManager: isKioskContainerExistOnDevice
,09-07 12:05:06.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:07.631   289   289 E SMD     : DCD OFF
09-07 12:05:07.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:07.961  1020  1432 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 12:05:07.961  1020  1432 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 12:05:07.961  1020  1432 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 12:05:07.961  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 12:05:07.961  1020  1432 D BatteryService: stay LED for fully charged
,09-07 12:05:07.971  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 12:05:07.971  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 12:05:07.971  1020  1020 I MotionRecognitionService: Plugged
,09-07 12:05:07.971  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 12:05:07.971  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 12:05:07.971  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 12:05:07.981  3170  3170 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 12:05:07.981  3170  3274 D HeadsetStateMachine: Disconnected process message: 10
,09-07 12:05:08.001  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:08.001  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:08.001  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 12:05:08.001  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-07 12:05:08.001  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 12:05:08.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:08.781  1020  1060 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,09-07 12:05:09.361  1020  1045 W ActivityManager: mDVFSHelper.release()
,09-07 12:05:09.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:10.631   289   289 E SMD     : DCD OFF
,09-07 12:05:10.631   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-07 12:05:11.761  1020  1099 V AlarmManager: waitForAlarm result :4,
,09-07 12:05:11.761  1020  1099 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-07 12:05:11.781  1020  1020 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-07 12:05:11.781  1020  1020 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-07 12:05:11.781  1020  1020 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-07 12:05:11.781  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-07 12:05:11.781  1175  1175 D KeyguardUpdateMonitor: handleTimeUpdate
,09-07 12:05:11.791  1989  1989 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos,
,09-07 12:05:11.791  1175  1175 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-07 12:05:11.801  1175  1175 D SecKeyguardClockView: HomeTimezone(): 1
,09-07 12:05:11.811  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 12:05:11.811  1175  1175 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,09-07 12:05:11.811  1175  1175 I KeyguardEffectViewController: *** don't update sliding image ***
,09-07 12:05:11.851  1020  1500 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:11.851  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-07 12:05:11.851  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:11.851  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:11.851  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:11.861  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 12:05:11.861  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 12:05:11.861  1175  1175 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 12:05:11.881  1175  1175 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,09-07 12:05:11.891  1175  1175 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-07 12:05:11.921  4739  4739 D ConnectivityManager: CallingUid : 10011, CallingPid : 4739
,09-07 12:05:11.921  1020  1368 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 12:05:11.921  1020  1133 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
09-07 12:05:11.921  1020  1133 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
09-07 12:05:11.921  1020  1133 D ConnectivityService: apparently satisfied.  currentScore=60
,09-07 12:05:11.921  4739  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-07 12:05:11.971  4739  6816 W DriveInitializer: Background init thread started
,09-07 12:05:12.001   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-07 12:05:12.001   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:12.011  4739  6816 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-07 12:05:12.061  1020  1368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:12.061  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.HeartbeatAlarm$ConnectionInfoPersistService; callingUser = 0; userId(target) = 0
,09-07 12:05:12.061  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:12.061  1020  1368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:12.061  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:12.091  4739  6816 W DriveInitializer: Background init thread ended
,09-07 12:05:12.101  1020  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:12.101  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-07 12:05:12.101  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:12.101  1020  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:12.101  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:12.121  1020  1368 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-07 12:05:12.121  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-07 12:05:12.141  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 12:05:12.171  1020  1045 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:12.171  1020  1045 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:12.171  1020  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:12.241  1989  1998 I art     : Explicit concurrent mark sweep GC freed 63449(3MB) AllocSpace objects, 14(224KB) LOS objects, 39% free, 10MB/17MB, paused 1.191ms total 79.196ms,
,09-07 12:05:13.341  1020  3369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-07 12:05:13.571  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-07 12:05:13.571  6753  6806 I jxcore-log: 
,09-07 12:05:13.571  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 12:05:13.571  6753  6806 I jxcore-log: 
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:13.581  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:13.581  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:13.581  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 12:05:13.581  6753  6806 I jxcore-log: 
09-07 12:05:13.581  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 12:05:13.581  6753  6806 I jxcore-log: 
,09-07 12:05:13.631   289   289 E SMD     : DCD OFF,
,09-07 12:05:14.231  6753  6806 D executeNativeTests: Running unit tests,
,09-07 12:05:14.331  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:14.331  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 added. We now have 2 listener(s)
,09-07 12:05:14.331  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 12:05:14.331  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:14.331  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:14.331  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:14.331  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 added. We now have 2 listener(s)
09-07 12:05:14.331  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:14.331  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:14.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.341  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:14.341  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.341  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:14.351  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-07 12:05:14.351  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:14.351  6753  6806 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-07 12:05:14.351  6753  6806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:14.351  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:14.351  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.351  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.351  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 removed from the list
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.351  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 removed from the list
09-07 12:05:14.351  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.351  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.351  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-07 12:05:14.361  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.361  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.361  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410],
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:05:14.361  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.361  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:14.361  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.361  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.361  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.361  6753  6806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:05:14.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.371  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:14.371  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.371  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:05:14.371  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:14.371  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:14.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:14.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:14.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:14.381  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 12:05:14.381  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-07 12:05:14.381  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.381  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 12:05:14.391  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:05:14.391  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-07 12:05:14.391  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-07 12:05:14.391  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 12:05:14.391  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 12:05:14.391  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 12:05:14.411  3170  3269 D BtGatt.GattService: registerClient() - UUID=ddf54b45-d48f-485d-b77f-155939d36032
,09-07 12:05:14.451  3170  3266 D BtGatt.GattService: onClientRegistered() - UUID=ddf54b45-d48f-485d-b77f-155939d36032, clientIf=6
,09-07 12:05:14.461  6753  6761 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 12:05:14.461  3170  3179 D BtGatt.GattService: start scan with filters
,09-07 12:05:14.461  3170  3272 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:14.461  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 12:05:14.461  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 12:05:14.461  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 12:05:14.461  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:14.471  3170  3272 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:14.471  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:14.471  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:14.481  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-07 12:05:14.481  3170  3266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 12:05:14.481  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.481  3170  3272 D BtGatt.ScanManager: allow scan with filters
,09-07 12:05:14.481  3170  3272 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 12:05:14.481  3170  3272 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-07 12:05:14.481  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:14.481  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 12:05:14.481  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.481  3170  3272 D BtGatt.ScanManager: Starting BLE batch scan
09-07 12:05:14.481  3170  3272 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:14.481  6753  6806 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 12:05:14.491  3170  3266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-07 12:05:14.491  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.491  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:14.491  6753  6806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 12:05:14.491  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.491  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 12:05:14.491  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:14.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:14.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:14.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 12:05:14.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:14.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 12:05:14.491  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:14.491  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:05:14.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 12:05:14.501  3170  3186 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:14.501  3170  3269 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:14.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 12:05:14.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:14.501  3170  3272 D BtGatt.ScanManager: filter size is 1
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:05:14.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:05:14.501  3170  3272 D BtGatt.ScanManager: delete FilterIndex - 3
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:14.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.501  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.501  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:14.501  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.501  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.501  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.511  6753  6806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:05:14.511  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:14.511  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:14.511  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:14.511  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 12:05:14.511  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.511  3170  3272 D BtGatt.ScanManager: stopping BLe Batch
,09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.521  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:14.521  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.521  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:14.521  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 12:05:14.521  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.521  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 12:05:14.521  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-07 12:05:14.521  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:14.521  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:14.521  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:05:14.521  3170  3272 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 12:05:14.521  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.531  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 12:05:14.531  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.531  3170  3266 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 12:05:14.531  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 12:05:14.541  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:05:14.541  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 12:05:14.541  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 12:05:14.541  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 12:05:14.541  3170  3186 D BtGatt.GattService: registerClient() - UUID=23682609-d106-4024-ad88-f5a7922c139e
,09-07 12:05:14.591  3170  3266 D BtGatt.GattService: onClientRegistered() - UUID=23682609-d106-4024-ad88-f5a7922c139e, clientIf=6
,09-07 12:05:14.591  6753  6761 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
09-07 12:05:14.591  3170  3269 D BtGatt.GattService: start scan with filters
,09-07 12:05:14.591  3170  3272 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:14.591  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
,09-07 12:05:14.591  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 12:05:14.591  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 12:05:14.591  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:14.591  3170  3266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 12:05:14.591  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.591  3170  3272 D BtGatt.ScanManager: allow scan with filters
,09-07 12:05:14.591  3170  3272 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 12:05:14.591  3170  3272 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-07 12:05:14.601  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:14.601  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 12:05:14.601  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:14.601  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 12:05:14.601  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.601  3170  3272 D BtGatt.ScanManager: Starting BLE batch scan
09-07 12:05:14.601  3170  3272 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:14.601  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:14.611  3170  3266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 12:05:14.611  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.611  6753  6806 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 12:05:14.621  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:14.621  6753  6806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 12:05:14.621  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:14.621  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.621  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:14.621  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 12:05:14.621  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.621  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:14.621  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-07 12:05:14.621  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:14.621  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:14.621  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 12:05:14.631  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:05:14.631  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 12:05:14.631  3170  3179 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:14.631  3170  3272 D BtGatt.ScanManager: filter size is 1
,09-07 12:05:14.631  3170  3272 D BtGatt.ScanManager: delete FilterIndex - 4
,09-07 12:05:14.631  3170  3186 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 12:05:14.631  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-07 12:05:14.631  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:14.631  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:14.631  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-07 12:05:14.631  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:14.641  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 12:05:14.641  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.641  3170  3272 D BtGatt.ScanManager: stopping BLe Batch
,09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false,
,09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:05:14.641  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:14.641  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 12:05:14.641  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.641  3170  3272 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 12:05:14.641  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.641  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:14.641  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.641  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.641  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.641  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.641  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.641  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.641  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:14.651  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:14.651  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
,09-07 12:05:14.651  3170  3266 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
09-07 12:05:14.651  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.651  6753  6806 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 12:05:14.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.651  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:14.661  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.661  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:14.661  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.661  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.661  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:14.661  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:14.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 12:05:14.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:14.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:14.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 12:05:14.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 12:05:14.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:05:14.681  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 12:05:14.681  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 12:05:14.681  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 12:05:14.681  3170  3179 D BtGatt.GattService: registerClient() - UUID=5460ab4f-0caa-4821-8309-d3f218be244b
,09-07 12:05:14.721  3170  3266 D BtGatt.GattService: onClientRegistered() - UUID=5460ab4f-0caa-4821-8309-d3f218be244b, clientIf=6
,09-07 12:05:14.721  6753  6762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 12:05:14.721  3170  3186 D BtGatt.GattService: start scan with filters
,09-07 12:05:14.731  3170  3272 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:14.731  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 12:05:14.731  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 12:05:14.731  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-07 12:05:14.731  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:14.731  3170  3266 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 12:05:14.731  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.731  3170  3272 D BtGatt.ScanManager: allow scan with filters
09-07 12:05:14.731  3170  3272 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 12:05:14.731  3170  3272 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-07 12:05:14.741  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-07 12:05:14.741  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 12:05:14.741  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 12:05:14.741  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:14.741  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 12:05:14.741  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.741  3170  3272 D BtGatt.ScanManager: Starting BLE batch scan
09-07 12:05:14.741  3170  3272 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:14.741  6753  6806 I io.jxcore.node.ConnectionHelper: start: OK
09-07 12:05:14.741  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.741  6753  6806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 12:05:14.741  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.741  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-07 12:05:14.741  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.741  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:14.741  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:14.741  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:14.741  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-07 12:05:14.741  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:14.741  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:05:14.741  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-07 12:05:14.751  3170  3266 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 12:05:14.751  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.751  3170  3269 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:14.751  3170  3179 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 12:05:14.751  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:14.751  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:14.751  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:05:14.751  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:14.751  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:14.751  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 12:05:14.751  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:14.751  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:05:14.761  3170  3272 D BtGatt.ScanManager: filter size is 1
,09-07 12:05:14.761  3170  3272 D BtGatt.ScanManager: delete FilterIndex - 5
09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:14.761  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:14.761  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.761  6753  6806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-07 12:05:14.761  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.761  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.761  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:14.761  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.761  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.761  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.761  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.761  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:14.761  3170  3266 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 12:05:14.761  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.761  3170  3272 D BtGatt.ScanManager: stopping BLe Batch
09-07 12:05:14.761  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.761  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.761  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.761  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
,09-07 12:05:14.761  6753  6806 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-07 12:05:14.771  3170  3266 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 12:05:14.771  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.771  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.771  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.771  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.771  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.771  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.771  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.771  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.771  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.771  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.771  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.771  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.771  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:14.771  3170  3272 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 12:05:14.771  3170  3266 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 12:05:14.771  3170  3266 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.771  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.771  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:05:14.771  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.771  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.771  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.771  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.771  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.771  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.771  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.771  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.771  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.771  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.781  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.781  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.781  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.781  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.781  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.781  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.781  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.781  6753  6806 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 12:05:14.781  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.781  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.781  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.781  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.781  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.781  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.781  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.781  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.781  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.781  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.781  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.781  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.781  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.781  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.791  6753  6806 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 12:05:14.791  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.791  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.791  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:05:14.791  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:14.791  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 12:05:14.791  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 12:05:14.791  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.791  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.791  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.791  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.791  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.791  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.791  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:14.791  6753  6806 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 12:05:14.791  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:14.791  6753  6806 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 12:05:14.791  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-07 12:05:14.801  6753  6806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:14.801  6753  6806 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:14.801  6753  6806 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 12:05:14.801  6753  6806 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.801  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.801  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 12:05:14.801  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.801  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.801  6753  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1314)
09-07 12:05:14.801  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.801  6753  6806 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 12:05:14.801  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.801  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.801  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.801  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.801  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.801  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.801  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.801  6753  6831 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1314
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.,internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 12:05:14.811  6753  6806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:14.811  6753  6806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 12:05:14.811  6753  6806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:14.811  6753  6806 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6830 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.811  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.811  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.811  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.811  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.811  6753  6830 D BluetoothSocket: connect(): myUserId = 0
09-07 12:05:14.811  6753  6830 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.811  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.811  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:14.821  3170  3186 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-07 12:05:14.821  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:14.821  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.821  6753  6753 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-07 12:05:14.821  6753  6753 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-07 12:05:14.821  6753  6832 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-07 12:05:14.821  6753  6832 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-07 12:05:14.821  6753  6830 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:14.821  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.821  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.821  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.821  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:14.821  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.821  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.821  6753  6753 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-07 12:05:14.821  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.821  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.821  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.821  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.821  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.821  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.821  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.821  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.821  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.821  6753  6806 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-07 12:05:14.821  6753  6806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 12:05:14.821  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 12:05:14.831  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 12:05:14.831  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.831  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.831  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.831  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.831  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:14.831  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13441be6 not in the list
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.831  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:14.831  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:14.831  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:14.831  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e642527 not in the list
09-07 12:05:14.841  6753  6806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:14.841  6753  6806 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 12:05:14.841  6753  6806 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-07 12:05:14.841  6753  6806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:05:14.841  6753  6806 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-07 12:05:14.841  6753  6806 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-07 12:05:14.841  6753  6806 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-07 12:05:14.841  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:14.841  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@397c5b1 added. We now have 2 listener(s)
09-07 12:05:14.841  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:14.841  6753  6806 D BluetoothAdapter: enable()
09-07 12:05:14.841  6753  6806 D BluetoothAdapter: enable(): BT is already enabled..!
09-07 12:05:14.851  1020  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 12:05:14.851  1020  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:14.851  1020  1480 D SecContentProvider2: mCursor = null
09-07 12:05:14.851  1020  1480 D WifiService: setWifiEnabled: true pid=6753, uid=10171
09-07 12:05:14.861  1020  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:14.861  1020  1480 W WifiService: Failed getting userId using ActivityManagerNative
09-07 12:05:14.861  1020  1480 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:14.861  1020  1480 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 12:05:14.861  1020  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 12:05:14.861  1020  1480 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 12:05:14.861  1020  1480 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 12:05:14.861  1020  1480 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 12:05:14.861  1020  1480 D SettingsProvider: name = wifi_on
09-07 12:05:14.861  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:14.861  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1dc14a96 added. We now have 3 listener(s)
09-07 12:05:14.861  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:14.871  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:14.871  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@160aa617 added. We now have 4 listener(s)
09-07 12:05:14.871  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:14.871  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:14.871  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2dedea04 added. We now have 5 listener(s)
09-07 12:05:14.871  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:14.871  1020  1424 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 12:05:14.881  1020  1424 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:14.881  1020  1424 D SecContentProvider2: mCursor = null
09-07 12:05:14.881  1020  1424 D WifiService: setWifiEnabled: false pid=6753, uid=10171
09-07 12:05:14.881  1020  1424 D SettingsProvider: name = wifi_on
,09-07 12:05:14.881  1020  1131 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-07 12:05:14.881  1361  1361 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 12:05:14.881  1361  1361 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-07 12:05:14.881  1361  1361 I wpa_supplicant: P2P: Current p2p state = IDLE
,09-07 12:05:14.891  1361  1361 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
09-07 12:05:14.891  6753  6806 D BluetoothAdapter: disable()
,09-07 12:05:14.891  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:14.901  1020  1033 D SettingsProvider: name = bluetooth_on,
,09-07 12:05:14.901  3170  3262 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
09-07 12:05:14.901  3170  3262 D BluetoothAdapterProperties: Setting state to 13
09-07 12:05:14.901  3170  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 12:05:14.901  3170  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-07 12:05:14.901  3170  3262 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 12:05:14.911  1020  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-07 12:05:14.911  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:14.911  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-07 12:05:14.911  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:14.911  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 12:05:14.911  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:14.911  3170  3170 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 12:05:14.911  1020  1131 E WifiNative-wlan0: do suspend true
09-07 12:05:14.911  3170  3262 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:14.911  3170  3262 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-07 12:05:14.911  3170  3262 D BluetoothAdapterService: terminating service from this receiver
09-07 12:05:14.911  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28c1065d, channel: 19, state: LISTENING
09-07 12:05:14.911  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28c1065d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16c4377a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@330e3bd2mSocket: android.net.LocalSocket@29b5a4a3 impl:android.net.LocalSocketImpl@1392f3a0 fd:FileDescriptor[76]
09-07 12:05:14.911  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29b5a4a3 impl:android.net.LocalSocketImpl@1392f3a0 fd:FileDescriptor[76]
09-07 12:05:14.911  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:14.911  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:14.911  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:14.911  3170  3262 D BluetoothAdapterProperties: onBluetoothDisable()
09-07 12:05:14.911  3170  3262 D BluetoothAdapterProperties: mDiscovering is false
,09-07 12:05:14.911  1020  1482 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled,
09-07 12:05:14.911  3170  3262 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-07 12:05:14.911  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:14.921  1367  1367 D BluetoothPbap: Proxy object disconnected
09-07 12:05:14.921  1367  1367 D PbapServerProfile: Bluetooth service disconnected
,09-07 12:05:14.921  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:14.921  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
09-07 12:05:14.921  3170  3266 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 12:05:14.921  3170  3266 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:14.931  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 12:05:14.931  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:14.931  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 12:05:14.931  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
09-07 12:05:14.931  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:14.931  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-07 12:05:14.941  1973  1973 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:14.941  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 12:05:14.941  1020  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:14.941  1020  1033 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 12:05:14.941  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.941  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 12:05:14.941  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:14.941  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.941  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:14.941  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.941  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 12:05:14.941  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:14.951  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.951  3170  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 12:05:14.951  3170  3262 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 12:05:14.951  3170  3262 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-07 12:05:14.951  3170  3262 E bt-btif : cmd socket is not created
09-07 12:05:14.951  6753  6830 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@27bf7a22, channel: -1, state: INIT
09-07 12:05:14.951  3170  3285 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-07 12:05:14.951  3170  3285 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-07 12:05:14.951  6753  6830 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@27bf7a22, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1c098cb3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e61a270mSocket: android.net.LocalSocket@1b079e9 impl:android.net.LocalSocketImpl@307f166e fd:FileDescriptor[106]
09-07 12:05:14.951  6753  6830 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1b079e9 impl:android.net.LocalSocketImpl@307f166e fd:FileDescriptor[106]
,09-07 12:05:14.951  3170  5180 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-07 12:05:14.951  6753  6830 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1314)
09-07 12:05:14.951  3170  3262 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-07 12:05:14.951  1020  1588 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:14.951  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:14.951  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:14.951  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:14.951  3170  3285 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 12:05:14.961  1020  1588 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:14.961  1020  1588 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:14.961  1020  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:14.961  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 12:05:14.961  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:14.961  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2cf0431e, channel: 5, state: LISTENING
09-07 12:05:14.961  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2cf0431e, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@19f887a5, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1df3e7ffmSocket: android.net.LocalSocket@3fc3a9cc impl:android.net.LocalSocketImpl@23d3a415 fd:FileDescriptor[74]
09-07 12:05:14.961  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fc3a9cc impl:android.net.LocalSocketImpl@23d3a415 fd:FileDescriptor[74]
09-07 12:05:14.961  3170  3170 I BtOppRfcommListener: stopping Accept Thread
09-07 12:05:14.961  3170  3170 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3a59732a, channel: 12, state: LISTENING
09-07 12:05:14.961  3170  3170 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3a59732a, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ab8834, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@15a9051bmSocket: android.net.LocalSocket@66796b8 impl:android.net.LocalSocketImpl@14576c91 fd:FileDescriptor[80]
09-07 12:05:14.961  3170  3170 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@66796b8 impl:android.net.LocalSocketImpl@14576c91 fd:FileDescriptor[80]
,09-07 12:05:14.961  3170  5180 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-07 12:05:14.961  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:14.961  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 12:05:14.971  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:14.971  1020  1500 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 12:05:14.971  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 12:05:14.971  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:14.971  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:14.971  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:14.971  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 12:05:14.971  3170  3170 V BluetoothOppManager: cleanUp...
,09-07 12:05:14.971  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.981  1367  1367 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:14.981  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:14.981  1020  3356 D SSRM:n  : SIOP:: AP = 330
,09-07 12:05:14.981  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:14.981  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:14.981  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 12:05:14.991  1020  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 12:05:14.991  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:14.991  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:14.991  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:14.991  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:15.001  6838  6838 E Zygote  : MountEmulatedStorage(),
,09-07 12:05:15.001  6838  6838 I libpersona: KNOX_SDCARD checking this for 10055
09-07 12:05:15.001  6838  6838 E Zygote  : v2
09-07 12:05:15.001  6838  6838 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:15.001  1020  1477 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6838 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-07 12:05:15.011  6838  6838 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 12:05:15.011  6838  6838 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:15.011  6838  6838 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:15.041  6838  6838 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:15.041  6838  6838 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:15.061  1361  1361 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,09-07 12:05:15.061  1020  1130 D WifiP2pService: InactiveState{ what=147461 }
,09-07 12:05:15.071  1020  1130 D WifiP2pService: P2pEnabledState{ what=147461 }
09-07 12:05:15.071  1020  1130 D WifiP2pService: DefaultState{ what=147461 }
,09-07 12:05:15.071  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-07 12:05:15.071  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 12:05:15.071   279   995 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:05:15.081  1989  3026 V NativeCrypto: Read error: ssl=0xb86c35c0: I/O error during system call, Connection timed out,
09-07 12:05:15.081  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 12:05:15.081  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 12:05:15.081  6838  6838 D UserAnalysis.PlaceProvider: PlaceProvider onCreate(),
09-07 12:05:15.081  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.081  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-07 12:05:15.081  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:15.081  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-07 12:05:15.081  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.081  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-07 12:05:15.081  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:15.091  1020  1130 D WifiP2pService: InactiveState{ what=131204 }
09-07 12:05:15.081  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:15.091  1020  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
09-07 12:05:15.091  1989  3026 V NativeCrypto: SSL shutdown failed: ssl=0xb86c35c0: I/O error during system call, Broken pipe
09-07 12:05:15.091  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-07 12:05:15.091  1989  3026 E GCM     : Wifi connection closed with errorCode 20
09-07 12:05:15.091  1020  1499 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
09-07 12:05:15.091  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 12:05:15.101  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 12:05:15.101  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:15.101  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:15.101  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.101  1020  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:15.101  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.101  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.101  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.101  1020  1020 D RttService: SCAN_AVAILABLE : 1
,09-07 12:05:15.101  1020  1153 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:05:15.101  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:05:15.101  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
,09-07 12:05:15.111  1020  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:05:15.111  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:15.111  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 12:05:15.111  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 12:05:15.111  1020  1130 D WifiP2pService: P2pDisablingState
,09-07 12:05:15.111  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 12:05:15.111  6838  6838 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-07 12:05:15.111  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 12:05:15.111  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:15.111  1020  1050 D WifiDisplayController: disconnect
09-07 12:05:15.111  1020  1050 D WifiDisplayController: updateConnection
09-07 12:05:15.111  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:15.111  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 12:05:15.121  6838  6838 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-07 12:05:15.121  6838  6838 D UserAnalysis: Create SecureDbHelper
09-07 12:05:15.121  1020  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 12:05:15.121  1020  1130 D WifiP2pService: p2p socket connection lost
09-07 12:05:15.121  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-22ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:15.121  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-22ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:15.121  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-07 12:05:15.121  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:15.121  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-07 12:05:15.121  1020  1768 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 12:05:15.121  1020  1768 I qtaguid : Tagging socket 351 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1020, getuid(): 1000
09-07 12:05:15.121  1020  1130 D WifiP2pService: P2pDisabledState
09-07 12:05:15.121  1020  1131 E WifiNative-wlan0: do suspend true
09-07 12:05:15.121  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 12:05:15.121  6838  6838 D IntelligenceServiceApplication: onCreate()
09-07 12:05:15.121  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
09-07 12:05:15.121  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:15.121  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 12:05:15.131  1020  1768 I qtaguid : Untagging socket 351
09-07 12:05:15.131  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-07 12:05:15.131  1020  1768 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 12:05:15.131  1020  1432 I ActivityManager: Killing 6431:com.google.android.gms:car/u0a11 (adj 15): empty #21
,09-07 12:05:15.141  6838  6838 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-07 12:05:15.141  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 12:05:15.141  6838  6838 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-07 12:05:15.141  1020  1432 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
09-07 12:05:15.141  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.141  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.141  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.141  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:15.151  6838  6838 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
09-07 12:05:15.151  1020  1480 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:15.151  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:15.151  3170  3285 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-07 12:05:15.151  3170  3285 W bt-btif : ag scb idx 1 not allocated
09-07 12:05:15.151  3170  3285 W bt-btif : ag scb idx 2 not allocated
09-07 12:05:15.151  3170  3285 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 12:05:15.151  3170  3318 I bt_userial_mct: exiting userial_read_thread
09-07 12:05:15.151  3170  3318 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 12:05:15.151  3170  3266 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 12:05:15.151  3170  3287 I bt_vendor: hw_epilog_process
09-07 12:05:15.151  3170  3266 D bt_userial_mct: userial_close
09-07 12:05:15.151  3170  3266 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-07 12:05:15.161  6861  6861 E Zygote  : MountEmulatedStorage()
09-07 12:05:15.161  6861  6861 E Zygote  : v2
09-07 12:05:15.161  6861  6861 I libpersona: KNOX_SDCARD checking this for 10105,
09-07 12:05:15.161  6861  6861 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:15.161  6861  6861 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:15.161  1020  1432 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6861 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-07 12:05:15.161  6861  6861 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:15.171  6861  6861 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 12:05:15.181  1020  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:15.181  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.181  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.181  1020  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.181  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:15.191  6861  6861 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:15.201  6861  6861 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:15.241  1020  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:15.241  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.241  1020  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.241  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:15.241  1020  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-07 12:05:15.241  1020  1130 D WifiP2pService: DefaultState{ what=143375 }
,09-07 12:05:15.251  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:15.251  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:15.251  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.251  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.251  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 12:05:15.251  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:15.271   279   995 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:05:15.271   279   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 12:05:15.271   279   990 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-07 12:05:15.271  1020  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-07 12:05:15.281  1020  1133 V NetworkStats: updateIfacesLocked()
09-07 12:05:15.281  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.281  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
,09-07 12:05:15.281  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:15.281  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:15.281  1361  1361 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 12:05:15.281  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 12:05:15.281  1020  1133 V NetworkStats: performPollLocked() took 7ms
09-07 12:05:15.281  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.291  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-07 12:05:15.291  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:15.291  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:15.291  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:15.291  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:15.291  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.291  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:15.301  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:15.301  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-07 12:05:15.301  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:15.301  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:15.301  1175  1175 D HotspotTile: onReceive : 0, 0
,09-07 12:05:15.301  1020  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-07 12:05:15.301  1175  1632 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-07 12:05:15.301  1020  1768 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:05:15.301  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.301  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:15.301  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.311  4739  6815 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-07 12:05:15.311  1020  1133 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-07 12:05:15.311  1020  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-07 12:05:15.311  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 12:05:15.311  1020  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-07 12:05:15.311  1020  1133 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-07 12:05:15.311  1020  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-07 12:05:15.311  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-07 12:05:15.311  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:15.311  1449  1449 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 12:05:15.311  1449  1449 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:15.311  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:15.311  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:15.311  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:15.321  1020  1128 V NetworkStats: updateIfacesLocked()
,09-07 12:05:15.321  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-07 12:05:15.321  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.321  1020  1020 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,09-07 12:05:15.321  1020  1134 D Tethering: MasterInitialState.processMessage what=3
09-07 12:05:15.321  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:15.321  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:15.321  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:15.321  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: updateDataNetType(),
,09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-07 12:05:15.331  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:05:15.331  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-07 12:05:15.331  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:15.331  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:15.331  6753  6753 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-07 12:05:15.331  1020  1133 D ConnectivityService: nai.networkMonitor.doQuit()
,09-07 12:05:15.331  1020  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-07 12:05:15.331  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:15.331  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:15.331  1020  1049 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-07 12:05:15.331  1020  1128 V NetworkStats: performPollLocked() took 14ms
09-07 12:05:15.331  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:15.331  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.331  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.331  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.341  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.341  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.341  1020  1129 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-07 12:05:15.341  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.341  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.341  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.361   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 12:05:15.361   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:15.361  6861  6884 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 12:05:15.371   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 12:05:15.371   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:15.371  6861  6884 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 12:05:15.381  1361  1361 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 12:05:15.381  3170  3266 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 12:05:15.381  3170  3266 I bt_vendor: bluetooth satus is on
09-07 12:05:15.381  3170  3266 I bt_vendor: bt-vendor : resetting BT status
09-07 12:05:15.381  3170  3266 I bt_vendor: Starting hciattach daemon
09-07 12:05:15.381  3170  3266 I bt_vendor: try to set false
,09-07 12:05:15.381  3170  3266 I bt_vendor: Starting hciattach daemon
09-07 12:05:15.381  3170  3266 I bt_vendor: try to set false
,09-07 12:05:15.381  3170  3266 I bt_vendor: cleanup
09-07 12:05:15.381  3170  3285 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-07 12:05:15.381  3170  3266 I GKI_LINUX: GKI_exit_task 0 done
09-07 12:05:15.381  3170  3266 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-07 12:05:15.391  3170  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-07 12:05:15.391  3170  3262 D BtConfig.SecureMode: isSecureModeOn:false
09-07 12:05:15.391  3170  3262 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-07 12:05:15.391  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-07 12:05:15.391  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 12:05:15.391  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-07 12:05:15.391  1020  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.391  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.391  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.391  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.391  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.391  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 12:05:15.391  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:15.391  3170  3170 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-07 12:05:15.401  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-07 12:05:15.401  3170  3170 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:05:15.401  3170  3170 D BtGatt.GattService: stop()
09-07 12:05:15.401  3170  3170 D BtGatt.AdvertiseManager: advertise clients cleared
,09-07 12:05:15.401  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:15.401  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.401  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.401  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.401  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.401  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 12:05:15.401  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 12:05:15.411  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 12:05:15.411  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.411  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.411  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:15.411  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.411  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.411  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.411  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-07 12:05:15.411  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 12:05:15.411  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 12:05:15.421  3170  3170 D HeadsetService: Received stop request...Stopping profile...
09-07 12:05:15.421  1020  1368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:15.421  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.421  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.421  1020  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.421  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.421  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-07 12:05:15.421  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 12:05:15.421  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.421  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 12:05:15.421  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-07 12:05:15.431  1361  1361 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-07 12:05:15.431  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:15.431  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:15.431  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
09-07 12:05:15.431  1367  1367 D HeadsetProfile: Bluetooth service disconnected
,09-07 12:05:15.431  1020  1424 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.431  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.431  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.431  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.431  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.441  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-07 12:05:15.441  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 12:05:15.441  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 12:05:15.451  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.451  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.451  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.451  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:15.451  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.451  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.451  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.451  3170  3262 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.451  1020  1432 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.451  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-07 12:05:15.451  1020  1432 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.451  1020  1432 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.451  1020  1432 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:15.451  1361  1361 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-07 12:05:15.461  1361  1361 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 12:05:15.461  1361  1361 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-07 12:05:15.461  1361  1361 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 12:05:15.461  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.461  1361  1361 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 12:05:15.461  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 12:05:15.461  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.461  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-07 12:05:15.461  1020  1134 D Tethering: InitialState.processMessage what=4
09-07 12:05:15.461  1020  1033 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:15.461  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.461  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:15.461  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.461  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.461  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.461  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.461  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:15.461  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:15.461  1020  1134 E Tethering: No numeric data
09-07 12:05:15.461  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-07 12:05:15.461  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 12:05:15.461  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:15.461  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.461  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:15.461  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.471  3170  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 12:05:15.471  3170  3262 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 12:05:15.471  3170  3262 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 12:05:15.471  3170  3262 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 12:05:15.471  3170  3262 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 12:05:15.471  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:05:15.471  1020  1134 D Tethering: clearTetheredNotification()
,09-07 12:05:15.471  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-07 12:05:15.471  3170  3170 D A2dpService: Received stop request...Stopping profile...
,09-07 12:05:15.471  3170  3279 D A2dpStateMachine: Exit Disconnected: -1
,09-07 12:05:15.471  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.471  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:15.471  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.471  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:15.471  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 12:05:15.471  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 12:05:15.471  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:15.481  1020  1128 V NetworkStats: performPollLocked() took 5ms
09-07 12:05:15.481  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:15.481  1020  1020 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:15.481  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 12:05:15.481  3170  3170 D HidService: Received stop request...Stopping profile...
,09-07 12:05:15.481  3170  3170 D HidService: Stopping Bluetooth HidService
09-07 12:05:15.481  3170  3170 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:05:15.481  3170  3170 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 12:05:15.481  3170  3170 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:05:15.481  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:15.481  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.481  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:15.481  1367  1367 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:15.481  1367  1367 D A2dpProfile: Bluetooth service disconnected
,09-07 12:05:15.481  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-07 12:05:15.481  1367  1367 D HidProfile: Bluetooth service disconnected
,09-07 12:05:15.481  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-07 12:05:15.481  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:15.481  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 12:05:15.481  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.491  3170  3170 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-07 12:05:15.491  3170  3170 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-07 12:05:15.491  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.491  3170  3170 D HealthService: Received stop request...Stopping profile...
,09-07 12:05:15.491  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.491  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.491  3170  3170 D PanService: Received stop request...Stopping profile...
,09-07 12:05:15.491  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.491  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.501  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 12:05:15.501  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.501  3170  3170 D BluetoothMapService: Received stop request...Stopping profile...
,09-07 12:05:15.501  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:15.501  1367  1367 D PanProfile: Bluetooth service disconnected
,09-07 12:05:15.501  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.501  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.501  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.501  1367  1367 D BluetoothMap: Proxy object disconnected
09-07 12:05:15.501  1367  1367 D MapProfile: Bluetooth service disconnected
09-07 12:05:15.501  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.501  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.501  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.501  3170  3170 D SapService: Received stop request...Stopping profile...
09-07 12:05:15.501  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 12:05:15.501  3170  3170 D SapService: Stopping Bluetooth SapService
09-07 12:05:15.501  3170  3170 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:15.511  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 12:05:15.511  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:15.511  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-07 12:05:15.511  3170  3170 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:15.511  3170  3170 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 12:05:15.511  3170  3280 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,09-07 12:05:15.511  3170  3170 I GKI_LINUX: GKI_exit_task 2 done
09-07 12:05:15.511  3170  3170 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-07 12:05:15.511  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 12:05:15.511  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.511  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:15.511  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 12:05:15.511  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.511  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.511  3170  3170 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:05:15.511  3170  3170 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-07 12:05:15.511  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true,
09-07 12:05:15.511  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.511  3170  3170 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:15.511  3170  3170 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:05:15.511  3170  3170 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 12:05:15.511  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.511  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-07 12:05:15.511   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb76057c8
,09-07 12:05:15.511   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-07 12:05:15.511   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
09-07 12:05:15.511   274   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1218423496)
,09-07 12:05:15.521  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.521  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.521  1367  1367 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-07 12:05:15.521  1367  1367 D SapProfile: Bluetooth service disconnected
,09-07 12:05:15.521  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-07 12:05:15.521  3170  3170 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 12:05:15.521  3170  3170 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 12:05:15.521  3170  3170 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-07 12:05:15.521  3170  3170 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 12:05:15.521  3170  3170 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 12:05:15.521  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.521  3170  3262 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-07 12:05:15.521  3170  3262 D BluetoothAdapterProperties: Setting state to 10
,09-07 12:05:15.521  3170  3262 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 12:05:15.521  3170  3262 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 12:05:15.521  3170  3262 D BluetoothAdapterService: updateAdapterState state is 10
,09-07 12:05:15.531  3170  3262 D BluetoothAdapterService: Autoconnection is available 
,09-07 12:05:15.531  3170  3262 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 12:05:15.531  3170  3262 I BluetoothAdapterState: Entering OffState
,09-07 12:05:15.531  3170  3269 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:15.531  3170  3269 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.531  3170  3179 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 12:05:15.531  1425  1453 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:15.531  1425  1453 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.531  1989  2000 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:15.531  1989  2000 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.541  1367  1378 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:15.541  1367  1378 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.541  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
09-07 12:05:15.541  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.541  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.541  1449  1947 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:15.541  1449  1947 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.541  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.541  1367  1378 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 12:05:15.551  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.551  1367  1384 D Bluetoothsap: onBluetoothStateChange: up=false
09-07 12:05:15.551  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.551  1367  1384 D Bluetoothsap: Unbinding service...
,09-07 12:05:15.551  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.551  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.561  1367  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 12:05:15.561  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-07 12:05:15.561  1175  2147 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:15.561  1175  2147 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:15.561  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:15.561  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:15.561  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.561  1367  1378 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 12:05:15.561  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3,
09-07 12:05:15.561  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.571  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.571  1449  1449 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-07 12:05:15.571  1438  1696 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:15.571  1438  1696 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:15.571  1367  1384 D BluetoothPbap: onBluetoothStateChange: up=false
09-07 12:05:15.571  1449  1449 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-07 12:05:15.571  6753  6762 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:15.571  6753  6762 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:15.571  6753  6762 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 12:05:15.571  6753  6762 D BluetoothLeAdvertiser: Exit stop advertising
09-07 12:05:15.571  6753  6762 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false,
09-07 12:05:15.571  6753  6762 D BluetoothLeScanner: Exiting stopAllScan
,09-07 12:05:15.571  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-07 12:05:15.571  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 12:05:15.581  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-07 12:05:15.581   274   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-07 12:05:15.581  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
09-07 12:05:15.581   274   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-07 12:05:15.581  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
09-07 12:05:15.581   274   348 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1218423496) wakelock released: 1, error no: 0
09-07 12:05:15.581   274   348 I rmt_storage: 
09-07 12:05:15.581   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb76057c8
,09-07 12:05:15.591  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:15.591  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 12:05:15.591  1175  1668 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:15.591  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:15.591  1175  1175 D BluetoothTile:  getBluetoothState : 10
09-07 12:05:15.591  1175  1668 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:15.591  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:15.591  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:15.591  1973  1973 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:15.591  1020  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:15.591  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:15.591  1020  1081 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 12:05:15.591  1989  2168 D BluetoothAdapter: 298732497: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:15.591  1989  2168 D BluetoothAdapter: 298732497: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:15.591  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 12:05:15.591  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-07 12:05:15.601  1020  1482 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:15.601  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.601  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:15.601  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.601  1020  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.601  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:15.601  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:15.601  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:15.601  3170  3266 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 12:05:15.601  3170  3170 I GKI_LINUX: GKI_exit_task 1 done
09-07 12:05:15.601  3170  3170 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-07 12:05:15.601  3170  3170 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 12:05:15.611  3170  3170 I art     : System.exit called, status: 0
,09-07 12:05:15.611  3170  3170 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 12:05:15.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:15.651  1361  1361 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 12:05:15.671  1020  1588 I ActivityManager: Process com.android.bluetooth (pid 3170)(adj 0) has died(31,733)
,09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=329 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=327 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.app,s.gmm.map.m.q.a(PG:8690)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=326 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at ,android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=325 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=323 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=292 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=291 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.691  6861  6861 D StrictMode: StrictMode policy violation; ~duration=291 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:15.691  6861  6861 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:15.701  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-07 12:05:15.711  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-07 12:05:15.711  1020  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:15.711  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 12:05:15.711  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.711  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:15.711  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:15.721  1361  1361 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
09-07 12:05:15.721  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.721  1602  1602 I Hs20UtilService: Starting #8
09-07 12:05:15.721  1602  1636 I Hs20UtilService: Message received 5007
09-07 12:05:15.721  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:15.721  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:15.721  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 12:05:15.721  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 12:05:15.731  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 12:05:15.731  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 12:05:15.731  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:15.731  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 12:05:15.731  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 12:05:15.741  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 12:05:15.741  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 12:05:15.741  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 12:05:15.751  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 12:05:15.751  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:15.751  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 12:05:15.751  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 12:05:15.751  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-07 12:05:15.751  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.751  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.751  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.751  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.761  6861  6902 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-07 12:05:15.761  6919  6919 E Zygote  : MountEmulatedStorage()
09-07 12:05:15.761  6919  6919 E Zygote  : v2
09-07 12:05:15.771  6919  6919 I libpersona: KNOX_SDCARD checking this for 10064
09-07 12:05:15.771  6919  6919 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:15.771  1020  1481 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6919 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:15.771  6919  6919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:15.771  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:15.771  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.771  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.771  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:15.771  6919  6919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:15.771  6919  6919 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:15.771  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-07 12:05:15.791  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:15.801  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.801  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.801  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 12:05:15.801  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:15.801  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.801  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 12:05:15.801  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:15.801  6919  6919 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:15.801  6919  6919 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:15.821  1020  1133 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:15.821  1020  1020 I ApplicationPolicy: updateDataUsageMap
,09-07 12:05:15.821  1020  1044 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:15.821  6919  6919 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 12:05:15.831  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:15.831  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-07 12:05:15.831  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-07 12:05:15.831  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:15.841  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:15.841  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:15.841  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.841  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.841  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:15.841  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:15.841  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:15.841  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-07 12:05:15.841  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:15.841  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:15.841  6919  6919 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:15.841  1175  1175 D HotspotTile: onReceive : 1, 0
09-07 12:05:15.841  1989  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:15.851  6919  6919 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 12:05:15.851  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:15.851  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:15.851  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:15.861  1989  1989 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=0117399b-bf88-4c24-b8ee-aacfeb2b972f
,09-07 12:05:15.881  6919  6919 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 12:05:15.881  1020  1481 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-07 12:05:15.891  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.891  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.891  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:15.891  1020  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:15.901  6937  6937 E Zygote  : MountEmulatedStorage(),
09-07 12:05:15.901  6937  6937 I libpersona: KNOX_SDCARD checking this for 10065
09-07 12:05:15.901  6937  6937 E Zygote  : v2
09-07 12:05:15.901  6937  6937 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:15.901  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:15.901  1020  1481 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6937 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:15.901  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:15.901  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:15.901  1020  1081 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-07 12:05:15.901  1020  1081 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-07 12:05:15.911  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:15.911  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.911  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:15.911  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 12:05:15.911  1989  1989 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 12:05:15.931  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:15.931  6937  6937 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:15.941  1020  1477 I ActivityManager: Killing 5929:com.android.defcontainer/u0a3 (adj 15): empty #21
,09-07 12:05:15.951  1020  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:15.951  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.951  1020  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.951  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:15.971  6937  6937 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:15.991  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:15.991  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:15.991  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-07 12:05:15.991  1020  1081 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-07 12:05:15.991  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.001  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.001  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.001  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.011  6953  6953 E Zygote  : MountEmulatedStorage()
09-07 12:05:16.011  1020  1081 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6953 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-07 12:05:16.011  1020  1081 I ActivityManager: Killing 6469:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,09-07 12:05:16.011  6953  6953 E Zygote  : v2
09-07 12:05:16.011  6953  6953 I libpersona: KNOX_SDCARD checking this for 10102
09-07 12:05:16.011  6953  6953 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:16.011  6953  6953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 12:05:16.021  6953  6953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:16.021  6953  6953 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 12:05:16.041  6953  6953 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:16.041  6953  6953 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:16.061  6953  6953 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 12:05:16.081  1989  2157 W GCoreFlp: No location to return for getLastLocation()
,09-07 12:05:16.131  4256  4268 I art     : Explicit concurrent mark sweep GC freed 1403(48KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 655us total 20.780ms
,09-07 12:05:16.141  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:16.141  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.141  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.151  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.151  1020  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:16.151  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.151  1020  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.151  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.151  1989  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 12:05:16.151  1020  1499 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:16.161  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.161  1020  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.161  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.161  4739  6875 D UdcContextInitService: registered all accounts: true
,09-07 12:05:16.171  1989  2177 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-07 12:05:16.231  1989  2177 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-07 12:05:16.281  1989  2177 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,09-07 12:05:16.281  6953  6975 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
09-07 12:05:16.281  6953  6975 I Babel_SMS: MmsConfig.loadMmsSettings
09-07 12:05:16.281  6953  6975 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
09-07 12:05:16.281  6953  6975 I Babel_SMS: MmsConfig.loadFromDatabase
,09-07 12:05:16.291  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-07 12:05:16.291  1020  1047 D Tethering: interfaceRemoved wlan0
09-07 12:05:16.291  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 12:05:16.311  6953  6975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-07 12:05:16.311  6953  6975 I Babel_SMS: MmsConfig.loadFromResources
,09-07 12:05:16.311  6953  6975 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,09-07 12:05:16.321  6953  6975 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,09-07 12:05:16.331  1020  1482 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-07 12:05:16.331  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-07 12:05:16.331  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.331  1020  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.331  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 12:05:16.351  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:16.361  6953  6953 I Babel_Crash: startup - clean
,09-07 12:05:16.391  1020  1482 I ActivityManager: Killing 6494:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,09-07 12:05:16.391  1020  1432 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:16.391  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:16.391  1020  1432 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.391  1020  1432 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.391  1020  1432 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:16.401  1602  1602 I Hs20UtilService: Starting #9
,09-07 12:05:16.401  1602  1636 I Hs20UtilService: Message received 5007
,09-07 12:05:16.401  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 12:05:16.401  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 12:05:16.401  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:16.401  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:16.401  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:16.401  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 12:05:16.401  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:16.411  1020  1424 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:16.411  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 12:05:16.411  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:05:16.411  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.411  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.411  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:16.411  1602  1602 I Hs20UtilService: Starting #10
09-07 12:05:16.411  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:16.411  6953  6953 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 12:05:16.411  6953  6953 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 12:05:16.421  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 12:05:16.421  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:16.421  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 12:05:16.421  6953  6953 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-07 12:05:16.421  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-07 12:05:16.421  6953  6953 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-07 12:05:16.421  6953  6953 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-07 12:05:16.431  6953  6953 W AudioCapabilities: Unsupported mime audio/x-ima
,09-07 12:05:16.431  6953  6953 W AudioCapabilities: Unsupported mime audio/qcelp
,09-07 12:05:16.431  6953  6953 W AudioCapabilities: Unsupported mime audio/evrc
,09-07 12:05:16.431  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.431  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.431  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.441  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.441  1020  1047 D Tethering: interfaceRemoved p2p0
09-07 12:05:16.441  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 12:05:16.441  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.441  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.441  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.441  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.451  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.451  6953  6953 W VideoCapabilities: Unsupported mime video/wvc1
09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.451  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 12:05:16.451  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.451  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.451  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.461  6953  6953 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-07 12:05:16.461  6953  6953 W VideoCapabilities: Unsupported mime video/wvc1
,09-07 12:05:16.461  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-07 12:05:16.461  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.461  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.461  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-07 12:05:16.461  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-07 12:05:16.461  6953  6953 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-07 12:05:16.471  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
09-07 12:05:16.471  6953  6953 W VideoCapabilities: Unsupported mime video/mp43
,09-07 12:05:16.471  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.471  6953  6953 W VideoCapabilities: Unsupported mime video/sorenson
09-07 12:05:16.471  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.471  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.471  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.481  6953  6953 W VideoCapabilities: Unsupported mime video/mp4v-esdp
09-07 12:05:16.481  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.481  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.481  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.481  1020  1020 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.481  1020  1020 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.481  1020  1020 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-07 12:05:16.491  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:16.491  1020  1482 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-07 12:05:16.491  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 12:05:16.491  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.491  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:16.491  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 12:05:16.501  6953  6953 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-07 12:05:16.501  1367  1367 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:16.501  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:16.511  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:16.511  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 12:05:16.511  1020  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-07 12:05:16.511  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.511  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.511  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.511  1020  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.521  6979  6979 E Zygote  : MountEmulatedStorage()
09-07 12:05:16.521  6979  6979 E Zygote  : v2
09-07 12:05:16.521  6979  6979 I libpersona: KNOX_SDCARD checking this for 1002
09-07 12:05:16.521  6979  6979 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:16.531  6979  6979 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:16.531  1020  1477 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6979 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-07 12:05:16.531  6979  6979 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:16.531  6979  6979 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:16.541  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:05:16.541  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:05:16.541  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:05:16.551  6953  6953 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-07 12:05:16.551  6979  6979 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:16.551  6979  6979 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:16.551  1020  1481 I ActivityManager: Killing 6518:com.samsung.android.sm/1000 (adj 15): empty #21
,09-07 12:05:16.561  6953  6953 I vclib   : onServiceConnected
,09-07 12:05:16.571  6979  6979 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 12:05:16.571  6979  6979 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 12:05:16.591  6979  6979 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-07 12:05:16.621  6979  6979 D BtSettings.ProfileConfig: Adding GattService
,09-07 12:05:16.621  6979  6979 D BtSettings.ProfileConfig: Adding HeadsetService
09-07 12:05:16.621  6979  6979 D BtSettings.ProfileConfig: Adding A2dpService
,09-07 12:05:16.621  6979  6979 D BtSettings.ProfileConfig: Adding HidService
09-07 12:05:16.621  6979  6979 D BtSettings.ProfileConfig: Adding HealthService
09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding PanService
,09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding SapService
09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding SapClientService
09-07 12:05:16.631  6979  6979 D BtSettings.ProfileConfig: Adding HidDevService
,09-07 12:05:16.631  6979  6979 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 12:05:16.631  1020  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 12:05:16.631  1020  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.631  1020  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.631  1020  1032 D SettingsProvider: selectionArgs: false
09-07 12:05:16.631  1020  1032 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.631  1020  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.631  1020  1032 D SettingsProvider: ret = -1
,09-07 12:05:16.631  1020  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:16.631  1020  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.631  1020  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.631  1020  1480 D SettingsProvider: selectionArgs: false
,09-07 12:05:16.631  1020  1480 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.631  1020  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:16.631  1020  1480 D SettingsProvider: ret = -1
,09-07 12:05:16.631   289   289 E SMD     : DCD OFF
,09-07 12:05:16.631  1020  1432 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-07 12:05:16.631  1020  1432 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.631  1020  1432 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.631   315   315 I ServiceManager: Waiting for service AtCmdFwd...
09-07 12:05:16.631  1020  1432 D SettingsProvider: selectionArgs: false
09-07 12:05:16.631  1020  1432 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.631  1020  1432 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.631  1020  1432 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1033 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-07 12:05:16.641  1020  1033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1033 D SettingsProvider: selectionArgs: false
,09-07 12:05:16.641  1020  1033 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:16.641  1020  1033 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1081 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-07 12:05:16.641  1020  1081 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1081 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1081 D SettingsProvider: selectionArgs: false
09-07 12:05:16.641  1020  1081 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1081 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1081 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1424 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-07 12:05:16.641  1020  1424 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1424 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1424 D SettingsProvider: selectionArgs: false
09-07 12:05:16.641  1020  1424 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1424 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1424 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-07 12:05:16.641  1020  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1499 D SettingsProvider: selectionArgs: false
,09-07 12:05:16.641  1020  1499 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1499 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1588 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-07 12:05:16.641  1020  1588 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1588 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1588 D SettingsProvider: selectionArgs: false
09-07 12:05:16.641  1020  1588 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1588 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1588 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:16.641  1020  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:16.641  1020  1500 D SettingsProvider: selectionArgs: false
09-07 12:05:16.641  1020  1500 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1500 D SettingsProvider: ret = -1,
09-07 12:05:16.641  1020  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:16.641  1020  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:16.641  1020  1477 D SettingsProvider: selectionArgs: false
09-07 12:05:16.641  1020  1477 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1477 D SettingsProvider: ret = -1
,09-07 12:05:16.641  1020  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-07 12:05:16.641  1020  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:16.641  1020  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.641  1020  1481 D SettingsProvider: selectionArgs: false
,09-07 12:05:16.641  1020  1481 D SettingsProvider: selectionArgs: 1002
09-07 12:05:16.641  1020  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.641  1020  1481 D SettingsProvider: ret = -1
09-07 12:05:16.651  1020  1368 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 12:05:16.651  1020  1368 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-07 12:05:16.651  1020  1368 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:16.651  1020  1368 D SettingsProvider: selectionArgs: false
09-07 12:05:16.651  1020  1368 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:16.651  1020  1368 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:16.651  1020  1368 D SettingsProvider: ret = -1
,09-07 12:05:16.651  1020  1032 I ActivityManager: Killing 6568:com.osp.app.signin/u0a36 (adj 15): empty #21
,09-07 12:05:16.661  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:16.661  1020  1499 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:16.661  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 12:05:16.661  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.661  1020  1499 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.661  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.671  1989  6996 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 12:05:16.671  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:16.831  1020  1477 I art     : Explicit concurrent mark sweep GC freed 56177(3MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 24MB/36MB, paused 2.531ms total 156.603ms
,09-07 12:05:16.831  1020  1432 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-07 12:05:16.831  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.831  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.831  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.831  1020  1432 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.841  6997  6997 E Zygote  : MountEmulatedStorage()
09-07 12:05:16.841  6997  6997 E Zygote  : v2
09-07 12:05:16.841  6997  6997 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:16.841  6997  6997 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:16.841  6997  6997 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:16.851  1020  1432 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6997 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 12:05:16.851  1020  1424 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 12:05:16.851  6997  6997 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:16.851  6997  6997 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:16.851  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:16.851  1020  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.851  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.861  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:16.861  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:16.861  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:16.861  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:16.871  1989  6996 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-07 12:05:16.881  6997  6997 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:16.881  6997  6997 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:16.901  6997  6997 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-07 12:05:16.911  6997  6997 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-07 12:05:16.911  6997  6997 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-07 12:05:16.921  6997  6997 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-07 12:05:16.921  6997  6997 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-07 12:05:16.921  6997  6997 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-07 12:05:16.921  6997  6997 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:16.931  1020  1368 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,09-07 12:05:16.931  6997  7012 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-07 12:05:16.931  1020  1368 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-07 12:05:16.941  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-07 12:05:16.941  1780  1780 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 12:05:16.941  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.941  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.941  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.941  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.951  7014  7014 E Zygote  : MountEmulatedStorage(),
09-07 12:05:16.951  7014  7014 I libpersona: KNOX_SDCARD checking this for 10121
09-07 12:05:16.951  7014  7014 E Zygote  : v2
09-07 12:05:16.951  7014  7014 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:16.951  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:16.951  1020  1045 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7014 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 12:05:16.961  1020  1368 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-07 12:05:16.961  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 12:05:16.961  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.961  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.961  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:16.961  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 12:05:16.961  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 12:05:16.981  7023  7023 E Zygote  : MountEmulatedStorage(),
09-07 12:05:16.981  7023  7023 E Zygote  : v2
09-07 12:05:16.981  7023  7023 I libpersona: KNOX_SDCARD checking this for 10031
09-07 12:05:16.981  7023  7023 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:16.981  7023  7023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-07 12:05:16.981  1020  1368 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7023 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,09-07 12:05:16.981  7023  7023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:16.981  7023  7023 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:16.991  2611  2619 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
09-07 12:05:16.991  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-07 12:05:16.991  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:16.991  7014  7014 D ActivityThread: Added TimaKeyStore provider,
09-07 12:05:16.991  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.991  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.991  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:16.991  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.001  7023  7023 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:17.001   304   304 I art     : Explicit concurrent mark sweep GC freed 8694(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 26.694ms
,09-07 12:05:17.001  7023  7023 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.021   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.277ms,
,09-07 12:05:17.041   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 677us total 17.614ms,
,09-07 12:05:17.051  7044  7044 E Zygote  : MountEmulatedStorage(),
09-07 12:05:17.051  7044  7044 E Zygote  : v2
09-07 12:05:17.051  7044  7044 I libpersona: KNOX_SDCARD checking this for 10001,
09-07 12:05:17.051  7044  7044 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:17.051  7044  7044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:17.061  1020  1020 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7044 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-07 12:05:17.061  7044  7044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:17.061  7044  7044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.071  1780  1780 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,09-07 12:05:17.071  1780  1780 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,09-07 12:05:17.071  1780  1780 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
09-07 12:05:17.071  1780  1780 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-07 12:05:17.081  1780  1780 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-07 12:05:17.081  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:05:17.081  7014  7014 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-07 12:05:17.081  7014  7014 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 12:05:17.081  1780  1780 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,09-07 12:05:17.091  1020  1081 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-07 12:05:17.091  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.091  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.091  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.091  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.101  7044  7044 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:17.101  7044  7044 D ActivityThread: Added TimaKeyStore provider
09-07 12:05:17.101  7014  7014 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:17.111  7059  7059 E Zygote  : MountEmulatedStorage()
,09-07 12:05:17.111  7059  7059 E Zygote  : v2
09-07 12:05:17.111  7059  7059 I libpersona: KNOX_SDCARD checking this for 10077
09-07 12:05:17.111  7059  7059 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:17.111  1020  1081 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7059 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 12:05:17.111  7059  7059 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:17.111  7014  7014 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-07 12:05:17.121  7059  7059 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:17.121  7059  7059 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.121  7014  7014 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-07 12:05:17.121  1020  1368 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
09-07 12:05:17.121  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.121  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.121  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.121  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.121  7023  7023 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-07 12:05:17.131  7069  7069 E Zygote  : MountEmulatedStorage()
09-07 12:05:17.131  7069  7069 E Zygote  : v2
09-07 12:05:17.131  7069  7069 I libpersona: KNOX_SDCARD checking this for 10141
09-07 12:05:17.131  7069  7069 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:17.131  7069  7069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 12:05:17.141  1020  1368 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7069 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
09-07 12:05:17.141  7069  7069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:17.141  1020  1368 I ActivityManager: Killing 6584:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,09-07 12:05:17.141  7069  7069 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.151  1020  1368 I ActivityManager: Killing 6600:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,09-07 12:05:17.161  7059  7059 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:17.161  7059  7059 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.161  1020  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-07 12:05:17.161  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.161  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.161  7069  7069 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:17.161  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.161  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.171  7069  7069 D ActivityThread: Added TimaKeyStore provider
09-07 12:05:17.171  2763  7087 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-07 12:05:17.171  2763  7087 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-07 12:05:17.171  2763  7087 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
09-07 12:05:17.171  2763  7087 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
09-07 12:05:17.171  2763  7087 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-07 12:05:17.181  7090  7090 E Zygote  : MountEmulatedStorage()
,09-07 12:05:17.181  7090  7090 E Zygote  : v2
09-07 12:05:17.181  7090  7090 I libpersona: KNOX_SDCARD checking this for 10032
,09-07 12:05:17.181  7090  7090 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:17.181  7090  7090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:17.181  1020  1480 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7090 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 12:05:17.191  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 12:05:17.191  7090  7090 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:17.191  7090  7090 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.211  7069  7069 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-07 12:05:17.211  7069  7069 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:05:17.211  7069  7069 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 12:05:17.211  7069  7069 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-07 12:05:17.231  7090  7090 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:17.231  7090  7090 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.241  1020  1424 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-07 12:05:17.241  1020  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.241  1020  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.241  1020  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.241  1020  1424 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.261  7107  7107 E Zygote  : MountEmulatedStorage()
09-07 12:05:17.261  7107  7107 E Zygote  : v2
09-07 12:05:17.261  7107  7107 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:17.261  7107  7107 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:17.261  7107  7107 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:17.261  1020  1424 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7107 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 12:05:17.261  1020  1424 I ActivityManager: Killing 6619:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-07 12:05:17.261  7107  7107 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:17.261  7107  7107 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.281  1020  1481 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.291  7107  7107 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:17.291  7107  7107 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.311  1020  1500 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.321  7090  7123 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-07 12:05:17.321  7090  7123 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-07 12:05:17.331  7090  7090 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-07 12:05:17.331  1020  1480 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,09-07 12:05:17.331  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.331  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.331  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.331  1020  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.341  7090  7123 D SPPClientService: PushLog.txt file is not deleted.
09-07 12:05:17.341  7090  7123 D SPPClientService: PushLog.txt file is not deleted.
09-07 12:05:17.341  7090  7123 D SPPClientService: ============PushLog. stop!
,09-07 12:05:17.351  1020  1480 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7127 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:17.351  7127  7127 E Zygote  : MountEmulatedStorage()
09-07 12:05:17.351  7127  7127 E Zygote  : v2
09-07 12:05:17.351  7127  7127 I libpersona: KNOX_SDCARD checking this for 10036
09-07 12:05:17.351  7127  7127 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:17.351  7127  7127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:17.351  1020  1480 I ActivityManager: Killing 6550:com.android.providers.calendar/u0a37 (adj 15): empty #21
,09-07 12:05:17.351  1020  1424 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-07 12:05:17.351  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.351  1020  1424 W ActivityManager: userId = 0, bbcId = -10000,
09-07 12:05:17.351  1020  1424 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-07 12:05:17.351  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-07 12:05:17.361  7127  7127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:17.361  7127  7127 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.371  7107  7107 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-07 12:05:17.381  7127  7127 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:17.381  7127  7127 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.391  1020  1432 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.411  1020  1480 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.421  7127  7127 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@2b8a6b6b
,09-07 12:05:17.421  7090  7135 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-07 12:05:17.431  7127  7127 I SA      : [SSP] onCreated
,09-07 12:05:17.451  7127  7127 I SA      : [TPM] There is no property file,
,09-07 12:05:17.451  7127  7127 I SA      : [SCU] isHaveSA() - false
,09-07 12:05:17.451  7127  7127 I SA      : [TPM] getModelProperty : null
,09-07 12:05:17.451  7127  7127 I SA      : [TPM] getCSCProperty : null
,09-07 12:05:17.461  7127  7127 I SA      : [DM] FLOATING AMOLED FEATURE: true
,09-07 12:05:17.461  7127  7127 I SA      : [DM] PRODUCT AMOLED FEATURE: false
09-07 12:05:17.461  7127  7127 I SA      : [DM] TFT FEATURE: false
,09-07 12:05:17.461  7127  7127 I SA      : [DM] init START
,09-07 12:05:17.471  7127  7127 I SA      : [DM] This device is not a Vodafone
,09-07 12:05:17.471  7127  7127 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,09-07 12:05:17.471  7127  7127 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,09-07 12:05:17.471  7127  7127 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,09-07 12:05:17.481  7127  7127 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-07 12:05:17.481  7127  7127 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-07 12:05:17.481  7127  7127 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-07 12:05:17.481  7127  7127 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-07 12:05:17.481  7127  7127 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-07 12:05:17.481  7127  7127 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
09-07 12:05:17.491  7127  7127 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-07 12:05:17.501  7127  7127 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-07 12:05:17.501  7127  7127 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
09-07 12:05:17.501  7127  7127 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,09-07 12:05:17.501  7127  7127 I SA      : [SCU] isHaveSA() - false
09-07 12:05:17.501  7127  7127 I SA      : support phone number id : false
09-07 12:05:17.501  7127  7127 I SA      : [DM] Supports Ref Jpn : true
,09-07 12:05:17.501  7127  7127 I SA      : [DM] init END
09-07 12:05:17.501  7127  7127 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,09-07 12:05:17.501  7127  7127 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-07 12:05:17.501  7127  7127 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-07 12:05:17.511  1020  1032 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.511  6699  6707 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-07 12:05:17.521  1020  1477 D RCPManagerService: exchangeData() failure , invalid userId
,09-07 12:05:17.521  7127  7127 I SA      : [SLFUCHKMGR] constructor called
,09-07 12:05:17.531  1483  1483 D Launcher.Model: reloadBadges entered.
09-07 12:05:17.531  6699  6707 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-07 12:05:17.531  6699  6707 D BadgeProvider: sendNotify, [notify] : null
09-07 12:05:17.531  6699  6707 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-07 12:05:17.531  6699  6707 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-07 12:05:17.531  6699  6707 D BadgeProvider: update, [UpdateCount] : 1
,09-07 12:05:17.541  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-07 12:05:17.541  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.541  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:17.541  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:17.541  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 12:05:17.541  1020  1032 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-07 12:05:17.551  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.551  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.551  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.551  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.561  7127  7127 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-07 12:05:17.561  7127  7127 I SA      : [OR] == isSIMCardReady false ==
,09-07 12:05:17.561  7157  7157 E Zygote  : MountEmulatedStorage()
09-07 12:05:17.561  7157  7157 E Zygote  : v2
09-07 12:05:17.561  7157  7157 I libpersona: KNOX_SDCARD checking this for 10110
09-07 12:05:17.561  7157  7157 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:17.561  7157  7157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:17.561  7157  7157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 12:05:17.561  7157  7157 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.571  1020  1477 D RCPManagerService: exchangeData() failure , invalid userId,
09-07 12:05:17.571  1020  1032 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7157 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:17.571  1020  1500 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
09-07 12:05:17.571  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.571  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:17.571  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:17.571  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-07 12:05:17.571  7107  7107 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-07 12:05:17.571  7127  7127 I SA      : [SCU] == networkStateCheck == false
09-07 12:05:17.571  7127  7127 I SA      : [OR] onReceive END
,09-07 12:05:17.571  6953  7156 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-07 12:05:17.581  1239  1239 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:17.581  7107  7107 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-07 12:05:17.591  7107  7107 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-07 12:05:17.591  7107  7107 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-07 12:05:17.591  7107  7107 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-07 12:05:17.591  7107  7107 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-07 12:05:17.591  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-07 12:05:17.601  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.601  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.601  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.601  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.601  1020  1481 D RCPManagerService: exchangeData() failure , invalid userId,
09-07 12:05:17.611  7157  7157 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:17.611  7157  7157 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.611  7172  7172 E Zygote  : MountEmulatedStorage(),
09-07 12:05:17.611  7172  7172 I libpersona: KNOX_SDCARD checking this for 10008
09-07 12:05:17.611  7172  7172 E Zygote  : v2
09-07 12:05:17.611  7172  7172 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:17.611  1020  1033 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7172 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:17.621  1020  1033 I ActivityManager: Killing 6640:com.android.mms/u0a41 (adj 15): empty #21
09-07 12:05:17.621  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:17.621  1020  1432 I ActivityManager: Killing 6656:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,09-07 12:05:17.621  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:17.621  1020  1033 I ActivityManager: Killing 6673:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-07 12:05:17.631  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
09-07 12:05:17.631  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
09-07 12:05:17.631  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.631  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.631  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:17.631  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:17.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:17.651  7187  7187 E Zygote  : MountEmulatedStorage()
09-07 12:05:17.651  7187  7187 E Zygote  : v2
,09-07 12:05:17.651  7187  7187 I libpersona: KNOX_SDCARD checking this for 10009
09-07 12:05:17.651  7187  7187 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:17.651  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:17.651  7187  7187 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 12:05:17.651  7172  7172 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.651  1020  1033 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7187 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,09-07 12:05:17.651  1020  1033 I ActivityManager: Killing 6714:com.wsomacp/u0a23 (adj 15): empty #21
09-07 12:05:17.651  7187  7187 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:17.661  7187  7187 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-07 12:05:17.671  7187  7187 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:17.671  7187  7187 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:17.701  1020  1368 D CountryDetector: No listener is left
,09-07 12:05:17.741  1020  1424 I ActivityManager: Killing 6479:com.android.calendar/u0a131 (adj 15): empty #21
,09-07 12:05:17.751  2882  2882 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 12:05:17 GMT+02:00 2016
,09-07 12:05:17.751  1020  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-07 12:05:17.751  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.751  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:17.751  1020  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:17.751  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 12:05:17.751  2882  2882 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 12:05:17.761  1020  1500 I ActivityManager: Killing 5771:com.android.vending/u0a26 (adj 15): empty #21
,09-07 12:05:17.761  2882  2882 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-07 12:05:17.761  2882  2882 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 12:05:17.761  1020  1477 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:17.761  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.761  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:17.761  1020  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:17.771  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:17.771  2882  2882 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-07 12:05:17.771  2882  7203 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-07 12:05:17.771  2882  7203 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-07 12:05:17.781  4739  7205 I iu.SyncManager: SYNC; picasa accounts
,09-07 12:05:17.781  2882  7203 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-07 12:05:17.781  2882  7203 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,09-07 12:05:17.781  2882  2882 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-07 12:05:17.801  4739  4739 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,09-07 12:05:17.811  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.811  1020  1499 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-07 12:05:17.811  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.821  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-07 12:05:17.841  1020  1033 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 12:05:17.941  1020  1477 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 12:05:17.941  1020  1477 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:17.941  1020  1477 D SecContentProvider2: mCursor = null
,09-07 12:05:17.941  1020  1477 D WifiService: setWifiEnabled: true pid=6753, uid=10171
,09-07 12:05:17.941  1020  1477 W ActivityManager: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-07 12:05:17.941  1020  1477 W WifiService: Failed getting userId using ActivityManagerNative
09-07 12:05:17.941  1020  1477 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:17.941  1020  1477 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 12:05:17.941  1020  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 12:05:17.941  1020  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 12:05:17.941  1020  1477 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 12:05:17.941  1020  1477 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 12:05:17.951  1020  1477 D SettingsProvider: name = wifi_on
,09-07 12:05:17.951   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 12:05:17.951   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:17.951  7157  7209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 12:05:17.951   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 12:05:17.951   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:17.951  7157  7209 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 12:05:17.961   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-07 12:05:17.961   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:17.961  7157  7210 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-07 12:05:17.971   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-07 12:05:17.971   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:17.971  7157  7210 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-07 12:05:17.981  1020  1131 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 12:05:17.981  7157  7157 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-07 12:05:17.981  7157  7157 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-07 12:05:17.981  7157  7157 I GAv4    :   adb logcat -s GAv4
,09-07 12:05:18.021  1020  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 12:05:18.021  1020  1500 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 12:05:18.021  1020  1500 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-07 12:05:18.021  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 12:05:18.031  1020  1500 D BatteryService: stay LED for fully charged
,09-07 12:05:18.031  1020  1020 I MotionRecognitionService: Plugged
,09-07 12:05:18.031  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 12:05:18.041  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 12:05:18.041  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 12:05:18.041  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-07 12:05:18.041  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 12:05:18.061  7157  7157 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:05:18.061  1020  1081 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 12:05:18.071  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:18.071  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:18.071  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
09-07 12:05:18.071  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
09-07 12:05:18.071  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 12:05:18.071  7157  7157 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:05:18.081  7157  7215 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-07 12:05:18.291  1989  2177 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,09-07 12:05:18.291  1989  2177 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,09-07 12:05:18.321  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:18.321  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:18.321  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:18.321  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-07 12:05:18.351  7157  7157 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-07 12:05:18.371  7157  7157 I cr.library_loader: Time to load native libraries: 4 ms (timestamps 6614-6618)
,09-07 12:05:18.371  7157  7157 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-07 12:05:18.381  1020  1047 D Tethering: interfaceAdded wlan0
,09-07 12:05:18.391  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 12:05:18.391  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:18.391  1020  1134 E Tethering: No numeric data,
,09-07 12:05:18.391  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 12:05:18.391  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:18.391  1020  1134 D Tethering: clearTetheredNotification()
09-07 12:05:18.391  1020  1134 D Tethering: InitialState.processMessage what=4
,09-07 12:05:18.401  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.401  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-07 12:05:18.401  1020  1134 E Tethering: No numeric data
,09-07 12:05:18.401  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:18.401  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:18.401  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:18.401  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 12:05:18.401  1020  1047 D Tethering: interfaceAdded p2p0
,09-07 12:05:18.401  7157  7157 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {330e3bd2}
,09-07 12:05:18.401  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:05:18.401  1020  1128 V NetworkStats: performPollLocked() took 7ms
09-07 12:05:18.401  1020  1134 D Tethering: clearTetheredNotification()
09-07 12:05:18.401  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:18.401  7157  7157 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-07 12:05:18.401  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:18.401  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-07 12:05:18.401  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 12:05:18.401  7157  7157 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 12:05:18.401  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.401  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:18.401  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
09-07 12:05:18.411   279   995 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-07 12:05:18.411   279   995 D SoftapController: Softap fwReload - Ok
09-07 12:05:18.411  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.411  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:18.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:18.411  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated,
09-07 12:05:18.411  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:18.411  1020  1128 V NetworkStats: performPollLocked() took 3ms
09-07 12:05:18.411   279   995 D CommandListener: Setting iface cfg
09-07 12:05:18.411   279   995 D CommandListener: Trying to bring down wlan0
09-07 12:05:18.411   279   995 D CommandListener: Clearing all IP addresses on wlan0
,09-07 12:05:18.411  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:18.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:18.411  1020  1131 E WifiHW  : supplicant_name : p2p_supplicant
,09-07 12:05:18.431  7157  7157 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,09-07 12:05:18.431  7157  7157 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-07 12:05:18.441  7157  7157 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-07 12:05:18.451  7157  7157 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
09-07 12:05:18.451  7157  7157 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-07 12:05:18.451  7157  7157 I Adreno-EGL: Build Date: 04/06/15 Mon
09-07 12:05:18.451  7157  7157 I Adreno-EGL: Local Branch: 
09-07 12:05:18.451  7157  7157 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-07 12:05:18.451  7157  7157 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-07 12:05:18.451  7157  7157 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-07 12:05:18.481  7239  7239 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-07 12:05:18.481  7239  7239 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 12:05:18.481  7239  7239 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 12:05:18.511  7239  7239 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-07 12:05:18.511   367   367 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7239
09-07 12:05:18.511   367   367 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,09-07 12:05:18.511  7239  7239 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 12:05:18.511  7239  7239 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:18.511  7239  7239 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 12:05:18.511  7239  7239 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 12:05:18.511   367   367 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7239
09-07 12:05:18.511   367   367 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,09-07 12:05:18.511  1020  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 12:05:18.521  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:18.521  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:18.521  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:18.521  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:18.521  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:18.521  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:18.521  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:18.521  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-07 12:05:18.521  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:18.521  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:18.521  1175  1175 D HotspotTile: onReceive : 2, 0
,09-07 12:05:18.521  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:18.521  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.531  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:18.531  7157  7157 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-07 12:05:18.541  7157  7252 W cr.media: Requires BLUETOOTH permission
,09-07 12:05:18.551  7157  7157 I NSApplication: Starting up...
,09-07 12:05:18.551  1020  1482 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 12:05:18.561  1020  1500 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-07 12:05:18.561  1020  1368 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-07 12:05:18.561  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:18.561  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:18.561  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:18.561  1020  1368 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:18.581  7257  7257 E Zygote  : MountEmulatedStorage(),
09-07 12:05:18.581  7257  7257 E Zygote  : v2
09-07 12:05:18.581  7257  7257 I libpersona: KNOX_SDCARD checking this for 10117
09-07 12:05:18.581  7257  7257 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:18.581  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:18.581  1020  1368 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7257 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-07 12:05:18.581  1020  1368 I ActivityManager: Killing 6919:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,09-07 12:05:18.581  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:18.591  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 12:05:18.601  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:18.601  7257  7257 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:18.621  7257  7257 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-07 12:05:18.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:18.701   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,09-07 12:05:18.711  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed,
,09-07 12:05:18.751  7239  7239 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 12:05:18.751  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 12:05:18.761  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 12:05:18.761   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7239,
09-07 12:05:18.761   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
09-07 12:05:18.771  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 12:05:18.771  7239  7239 I wpa_supplicant: ssSupport state is = 1,
09-07 12:05:18.771  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-07 12:05:18.771  7239  7239 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:18.771  7239  7239 E wpa_supplicant: SIM READ ERROR
09-07 12:05:18.771  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:18.771  7239  7239 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-07 12:05:18.771  7239  7239 E wpa_supplicant: SIM READ ERROR
09-07 12:05:18.771  7239  7239 I wpa_supplicant: Blacklist: Clear (all) 
09-07 12:05:18.771  7239  7239 I wpa_supplicant: wpa_default_ap_write_once
09-07 12:05:18.771  7239  7239 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-07 12:05:18.771  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:18.771  7239  7239 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 12:05:18.771  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:18.771  7239  7239 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:18.771  7239  7239 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 12:05:18.781  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:18.781  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:18.781  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 12:05:18.821  7239  7239 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-07 12:05:18.981  1020  1499 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-07 12:05:18.981  1020  1499 I ActivityManager: Killing 6937:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,09-07 12:05:18.991  1020  1424 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:18.991  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:18.991  1020  1424 W ActivityManager: userId = 0, bbcId = -10000,
09-07 12:05:18.991  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:18.991  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:18.991  1602  1602 I Hs20UtilService: Starting #11
09-07 12:05:18.991  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:19.001  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 12:05:19.001  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:19.001  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 12:05:19.001  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:19.011  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:19.011  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:19.011  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:19.011  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:19.011  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:19.021  1602  1602 I Hs20UtilService: Starting #12
,09-07 12:05:19.021  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:19.021  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 12:05:19.021  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:19.021  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
09-07 12:05:19.021  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:19.041  7239  7239 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-07 12:05:19.051  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 12:05:19.061  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 12:05:19.061   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7239
09-07 12:05:19.061   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 12:05:19.061  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 12:05:19.061  7239  7239 I wpa_supplicant: ssSupport state is = 1
,09-07 12:05:19.061  7239  7239 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-07 12:05:19.061  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,09-07 12:05:19.071  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
09-07 12:05:19.071   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7239,
,09-07 12:05:19.071   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-07 12:05:19.071  7239  7239 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
09-07 12:05:19.071  7239  7239 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:19.071  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-07 12:05:19.071  7239  7239 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:19.071  7239  7239 E wpa_supplicant: SIM READ ERROR
09-07 12:05:19.071  7239  7239 I wpa_supplicant: wpa_default_ap_write_once
,09-07 12:05:19.071  7239  7239 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 12:05:19.071  7239  7239 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-07 12:05:19.081  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
,09-07 12:05:19.081  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-07 12:05:19.081  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
09-07 12:05:19.081  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:19.081  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:19.081  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-07 12:05:19.141  7239  7239 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-07 12:05:19.141  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 12:05:19.221  7239  7239 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-07 12:05:19.221  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 12:05:19.221  7239  7239 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 12:05:19.231  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
09-07 12:05:19.231  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-07 12:05:19.231  7239  7239 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-07 12:05:19.231  7239  7239 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:19.231  7239  7239 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:19.231  7239  7239 E wpa_supplicant: SIM READ ERROR
09-07 12:05:19.231  7239  7239 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 12:05:19.261  7239  7239 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 12:05:19.271  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 12:05:19.271  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:19.271  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:19.271  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 12:05:19.271  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:19.271  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:19.271  7239  7239 I wpa_supplicant: Skip scan - bUseNetwork false,
09-07 12:05:19.281  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:19.281  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-07 12:05:19.281  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:19.281  1020  1131 D WifiConfigStore: Loading config and enabling all networks 
09-07 12:05:19.281  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 12:05:19.281  1175  1175 D HotspotTile: onReceive : 3, 0
,09-07 12:05:19.281  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:19.291  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:19.291  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:19.291  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:19.291  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:19.291  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:19.291  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:19.291  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:19.291  1020  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:19.291  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:19.291  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:19.291  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:19.291  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:19.291  1602  1602 I Hs20UtilService: Starting #13
,09-07 12:05:19.301  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:19.301  1020  1131 E WifiConfigStore: Not a HS20
09-07 12:05:19.301  1020  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 12:05:19.301  1020  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 12:05:19.301  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 12:05:19.301  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:19.301  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 12:05:19.301  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:19.301  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-07 12:05:19.301  7239  7239 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 12:05:19.301  7239  7239 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-07 12:05:19.301  7239  7239 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 12:05:19.301  7239  7239 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 12:05:19.301  7239  7239 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
,09-07 12:05:19.301  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-07 12:05:19.301  7239  7239 I wpa_supplicant: First Scan Start
09-07 12:05:19.301  7239  7239 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 12:05:19.321  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:05:19.321  1020  1131 D WifiNative-wlan0: Setting external_sim to 1
,09-07 12:05:19.321  1020  1131 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:05:19.321  1020  1131 I WifiNative-HAL: startHal
09-07 12:05:19.321  1020  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9d44e88c
09-07 12:05:19.321  1020  1131 I WifiNative-HAL: Could not start hal
,09-07 12:05:19.321  1020  1131 E WifiNative-wlan0: do suspend true
,09-07 12:05:19.321  1020  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 12:05:19.321  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-07 12:05:19.321  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
,09-07 12:05:19.321   279   995 D CommandListener: Setting iface cfg
09-07 12:05:19.321   279   995 D CommandListener: Trying to bring up p2p0
09-07 12:05:19.321  1020  1152 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:19.321  1020  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-07 12:05:19.321  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 12:05:19.321  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 12:05:19.321  1020  1131 E WifiNative-wlan0: invaild command id : 215
,09-07 12:05:19.331  1020  1152 I WifiNative-HAL: startHal
09-07 12:05:19.331  1020  1130 D WifiP2pService: P2pEnablingState
,09-07 12:05:19.331  1020  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 12:05:19.331  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 12:05:19.331  1020  1130 D WifiP2pService: P2p socket connection successful
09-07 12:05:19.331  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 12:05:19.331  1020  1130 D WifiP2pService: P2pEnabledState
09-07 12:05:19.331  1020  1131 E WifiNative-wlan0: invaild command id : 215
09-07 12:05:19.331  1020  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e9069bc
09-07 12:05:19.331  1020  1152 I WifiNative-HAL: Could not start hal
09-07 12:05:19.331  1020  1152 E WifiScanningService: could not start HAL
09-07 12:05:19.331  1020  1020 D RttService: SCAN_AVAILABLE : 3
09-07 12:05:19.331  1020  1153 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:05:19.331  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 12:05:19.331  1020  1133 E ConnectivityService: updateNetworkInfo(),
09-07 12:05:19.331  7239  7239 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 12:05:19.331  7239  7239 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
09-07 12:05:19.331  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 12:05:19.331  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 12:05:19.331  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:19.331  7239  7239 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 12:05:19.331  1020  1050 D WifiDisplayController: disconnect
09-07 12:05:19.331  1020  1131 E WifiStateMachine: Failed to set frequency band 0
09-07 12:05:19.331  1020  1050 D WifiDisplayController: updateConnection
,09-07 12:05:19.331  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:19.331  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:19.331  1020  1131 D SecContentProvider2: mCursor = null
09-07 12:05:19.331  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 12:05:19.341  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress,
09-07 12:05:19.341  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:05:19.341  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
09-07 12:05:19.341  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:19.341  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 12:05:19.341  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,09-07 12:05:19.341  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:19.341  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:19.341  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 12:05:19.341  1020  1432 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 12:05:19.341  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 12:05:19.341  1020  1130 D WifiP2pService: DeviceAddress: 0a:76:28
09-07 12:05:19.341  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  secondary type: null
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  wps: 0
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  grpcapab: 0
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  devcapab: 0
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  status: 3
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  wfdInfo: null
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  groupownerAddress: null
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  GOdeviceName: null
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  interfaceAddress: 
09-07 12:05:19.341  1020  1050 D WifiDisplayController:  SConnectInfo : null
,09-07 12:05:19.341  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-07 12:05:19.341  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 12:05:19.351  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:19.351  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:19.351  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:19.351  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 12:05:19.351  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 12:05:19.351  1020  1588 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-07 12:05:19.351  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:19.351  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:19.351  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:19.351  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:19.361  7287  7287 E Zygote  : MountEmulatedStorage(),
09-07 12:05:19.361  7287  7287 E Zygote  : v2
,09-07 12:05:19.361  7287  7287 I libpersona: KNOX_SDCARD checking this for 10064
,09-07 12:05:19.361  7287  7287 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:19.371  7287  7287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:19.371  1020  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 12:05:19.371  1020  1588 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7287 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-07 12:05:19.371  7287  7287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:19.371  1020  1130 D WifiP2pService: InactiveState
09-07 12:05:19.371  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
09-07 12:05:19.371  7287  7287 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 12:05:19.371  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
09-07 12:05:19.371  7239  7239 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 12:05:19.371  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
09-07 12:05:19.371  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 12:05:19.391  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:19.391  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:19.391  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-07 12:05:19.391   304   304 I art     : Explicit concurrent mark sweep GC freed 8695(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 697us total 20.295ms
,09-07 12:05:19.401  7287  7287 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:19.401  7287  7287 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:19.411   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 572us total 16.443ms
,09-07 12:05:19.421  7287  7287 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-07 12:05:19.421   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 17.021ms
,09-07 12:05:19.431  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:19.431  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 12:05:19.451  7287  7287 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 12:05:19.451  1020  1033 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-07 12:05:19.461  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:19.461  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:19.461  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:19.461  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:19.471  7302  7302 E Zygote  : MountEmulatedStorage()
09-07 12:05:19.471  7302  7302 I libpersona: KNOX_SDCARD checking this for 10065
09-07 12:05:19.471  7302  7302 E Zygote  : v2
09-07 12:05:19.471  7302  7302 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:19.471  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:19.471  1020  1033 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7302 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:19.471  1020  1033 I ActivityManager: Killing 6838:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-07 12:05:19.471  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:19.471  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:19.481  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:19.491  7302  7302 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:19.511  7302  7302 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:19.521  1020  1368 I ActivityManager: Killing 6979:com.android.bluetooth/1002 (adj 15): empty #21
,09-07 12:05:19.631   289   289 E SMD     : DCD OFF,
,09-07 12:05:19.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:20.421  7239  7239 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
,09-07 12:05:20.421  7239  7239 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
09-07 12:05:20.421  7239  7239 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-07 12:05:20.431  1020  7283 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-07 12:05:20.431  7239  7239 I wpa_supplicant: Trying to associate with  'G700'
09-07 12:05:20.431  7239  7239 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 12:05:20.431  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-07 12:05:20.441  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:20.441  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:20.651   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,09-07 12:05:20.651  7239  7239 E wpa_supplicant: Cmd 35605 not handled
,09-07 12:05:20.651  7239  7239 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 12:05:20.651  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 12:05:20.651  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:20.651  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 12:05:20.651  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:20.651  7239  7239 I wpa_supplicant: Associated with F4.99.3E
09-07 12:05:20.651  7239  7239 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-07 12:05:20.651  7239  7239 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 12:05:20.651  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-07 12:05:20.651  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:20.651  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:20.651  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 12:05:20.651  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:20.651  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
09-07 12:05:20.651  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 12:05:20.651  1020  1134 E Tethering: No numeric data
,09-07 12:05:20.661  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-07 12:05:20.661  1020  1134 D Tethering: clearTetheredNotification()
09-07 12:05:20.661  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:20.661  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:20.661  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:20.661  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:20.661  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:20.661  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 12:05:20.661  1020  1131 D SecContentProvider2: mCursor = null
09-07 12:05:20.661  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:20.661  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 12:05:20.661  1020  1128 V NetworkStats: performPollLocked() took 6ms
,09-07 12:05:20.671  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:20.671  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:20.671  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:20.671  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:20.691  7239  7239 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 12:05:20.691  7239  7239 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-07 12:05:20.691  7239  7239 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 12:05:20.691  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-07 12:05:20.691  7239  7239 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:05:20.691  7239  7239 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 12:05:20.691  7239  7239 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 12:05:20.691  7239  7239 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 12:05:20.691  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-07 12:05:20.701  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,09-07 12:05:20.701  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,09-07 12:05:20.701  1020  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 12:05:20.701  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 12:05:20.701  1020  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-07 12:05:20.711  1020  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-07 12:05:20.711  1020  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-07 12:05:20.711  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:20.711  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-07 12:05:20.711  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:20.711  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:20.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:20.721  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:20.721  1020  1424 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:20.721  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:20.721  1020  1424 W ActivityManager: userId = 0, bbcId = -10000,
09-07 12:05:20.721  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:20.721  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:20.721  1602  1602 I Hs20UtilService: Starting #14
,09-07 12:05:20.721  1602  1636 I Hs20UtilService: Message received 5007
,09-07 12:05:20.731  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-07 12:05:20.731  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 12:05:20.731  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 12:05:20.741  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 12:05:20.741   279   995 D CommandListener: Setting iface cfg
,09-07 12:05:20.741  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 12:05:20.741  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:20.741  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 12:05:20.741  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:20.751  1020  1131 E WifiStateMachine: Start Dhcp Watchdog 2
,09-07 12:05:20.751  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 12:05:20.751  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:20.761  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 12:05:20.761  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:20.761  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.761  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.761  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:20.761  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:20.761  1020  1131 E WifiNative-wlan0: do suspend false
,09-07 12:05:20.771  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-07 12:05:20.771  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 12:05:20.771  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-07 12:05:20.771  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:20.981  1020  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-07 12:05:20.991  1020  1480 D WifiService: setWifiEnabled: false pid=6753, uid=10171
09-07 12:05:20.981  1020  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:20.981  1020  1480 D SecContentProvider2: mCursor = null
09-07 12:05:20.991  1020  1480 D SettingsProvider: name = wifi_on
,09-07 12:05:20.991  7320  7320 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
09-07 12:05:20.991  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-07 12:05:21.001  7320  7320 I dhcpcd  : version 5.5.6 starting
,09-07 12:05:21.001  7320  7320 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-07 12:05:21.021  1020  1131 E WifiNative-wlan0: do suspend true
,09-07 12:05:21.041  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
09-07 12:05:21.041  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 },
09-07 12:05:21.041  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:21.041  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:21.041  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.041  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.041  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 12:05:21.041  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.051   279   995 D CommandListener: Clearing all IP addresses on wlan0
09-07 12:05:21.051  1020  1133 E ConnectivityService: updateNetworkInfo()
,09-07 12:05:21.051  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:05:21.051  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:21.051  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-07 12:05:21.051   279   995 E Netd    : no such netId 503
09-07 12:05:21.051  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 12:05:21.051  1020  1133 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
09-07 12:05:21.051  1020  1133 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-07 12:05:21.051  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:21.051  1020  1133 V NetworkStats: updateIfacesLocked()
09-07 12:05:21.051  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:21.061  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:21.061  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:21.061  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:21.061  1020  1133 V NetworkStats: performPollLocked() took 6ms
,09-07 12:05:21.061  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:21.061  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:21.061  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 12:05:21.061  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-07 12:05:21.071  1020  1130 D WifiP2pService: InactiveState{ what=131204 }
09-07 12:05:21.061  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.071  1020  1130 D WifiP2pService: P2pEnabledState{ what=131204 }
,09-07 12:05:21.061  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.071  1020  1133 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-07 12:05:21.071  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 1
09-07 12:05:21.071  1020  1133 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 12:05:21.071  1020  1152 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:21.071  1020  1020 D RttService: SCAN_AVAILABLE : 1
09-07 12:05:21.071  1020  1153 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:05:21.071  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:21.071  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:21.071  1020  1131 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-07 12:05:21.071  1020  7318 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:21.071  1020  7318 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-07 12:05:21.071  1020  1133 D ConnectivityService: nai.networkMonitor.doQuit()
09-07 12:05:21.071  1020  1133 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow(),
,09-07 12:05:21.071  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:21.071  1020  1081 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:21.071  1020  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:21.071  1020  1081 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 12:05:21.071  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:21.081  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-07 12:05:21.081  1602  1602 I Hs20UtilService: Starting #15
09-07 12:05:21.081  1020  1133 E ConnectivityService: updateNetworkInfo()
,09-07 12:05:21.081  7320  7320 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-07 12:05:21.081  7320  7320 E dhcpcd  : wlan0: sendmsg: Network is unreachable
09-07 12:05:21.081  7320  7320 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-07 12:05:21.081  1602  1636 I Hs20UtilService: Message received 5007
09-07 12:05:21.081  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 12:05:21.081  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 12:05:21.081  7320  7320 I dhcpcd  : bssid match
,09-07 12:05:21.081  7320  7320 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-07 12:05:21.091  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-07 12:05:21.091  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
09-07 12:05:21.091  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:21.091  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
09-07 12:05:21.091  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-07 12:05:21.091  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:21.091  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-07 12:05:21.091  1020  1130 D WifiP2pService: P2pDisablingState
,09-07 12:05:21.091  1020  1130 D WifiP2pService: P2pDisablingState{ what=147458 }
09-07 12:05:21.091  1020  1130 D WifiP2pService: p2p socket connection lost
09-07 12:05:21.091  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-07 12:05:21.091  1020  1130 D WifiP2pService: P2pDisabledState
09-07 12:05:21.091  1020  1131 E WifiNative-wlan0: do suspend true
09-07 12:05:21.091  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-07 12:05:21.091  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-07 12:05:21.091  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:21.091  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:21.091  1020  1050 D WifiDisplayController: disconnect
09-07 12:05:21.091  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 12:05:21.091  1020  1050 D WifiDisplayController: updateConnection
09-07 12:05:21.091  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:21.091  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 12:05:21.091  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:21.101  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-07 12:05:21.101  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
09-07 12:05:21.101  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:21.101  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 12:05:21.101  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 12:05:21.101  1020  1432 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 12:05:21.101  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 12:05:21.101  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 12:05:21.101  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 12:05:21.101  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:21.101  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:21.111  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:21.111  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 12:05:21.111  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:21.111  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:21.111  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-07 12:05:21.111  7287  7287 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 12:05:21.111  7302  7302 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:21.121  1020  1130 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-07 12:05:21.121   279   995 D CommandListener: Clearing all IP addresses on wlan0,
09-07 12:05:21.121  1020  1130 D WifiP2pService: DefaultState{ what=143375 }
,09-07 12:05:21.131  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:21.131  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:21.131  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.131  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.131  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.131  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.131  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-07 12:05:21.131  7239  7239 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-07 12:05:21.141  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:21.141  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:21.141  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.141  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.141  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.141  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.141  1020  1499 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:21.141  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 12:05:21.141  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:21.141  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:21.141  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:21.141  1602  1602 I Hs20UtilService: Starting #16
,09-07 12:05:21.141  1602  1636 I Hs20UtilService: Message received 5007
,09-07 12:05:21.151  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:21.151  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:21.151  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:21.151  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-07 12:05:21.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.151  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:21.151  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-07 12:05:21.151  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:21.161  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:21.161  1175  1175 D HotspotTile: onReceive : 0, 0
,09-07 12:05:21.161  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:21.161  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:21.161  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:21.161  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:21.161  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:21.161  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:21.161  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:21.161  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:21.171  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-07 12:05:21.171  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 12:05:21.171  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:21.171  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:21.171  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:21.171  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 12:05:21.171  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:21.181  1020  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:21.181  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:21.181  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:21.181  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:21.181  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:21.181  1602  1602 I Hs20UtilService: Starting #17
,09-07 12:05:21.181  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 12:05:21.181  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:21.181  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
09-07 12:05:21.181  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:21.191  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:21.251  7320  7320 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-07 12:05:21.261  7239  7239 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 12:05:21.281  7320  7320 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,09-07 12:05:21.361  7239  7239 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
,09-07 12:05:21.361  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 12:05:21.361  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-07 12:05:21.361  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-07 12:05:21.381  7239  7239 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
,09-07 12:05:21.391  7239  7239 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-07 12:05:21.391  7239  7239 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,09-07 12:05:21.391  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.391  7239  7239 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-07 12:05:21.391  7239  7239 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-07 12:05:21.391  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.391  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:21.391  1020  1134 D Tethering: InitialState.processMessage what=4
09-07 12:05:21.391  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.391  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:21.391  1020  1134 E Tethering: No numeric data
,09-07 12:05:21.391  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-07 12:05:21.391  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.391  1020  1134 D Tethering: clearTetheredNotification()
,09-07 12:05:21.401  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:21.401  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:21.401  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.401  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:21.401  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:21.401  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.401  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:21.401  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-07 12:05:21.401  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 12:05:21.401  1020  1128 V NetworkStats: performPollLocked() took 7ms
,09-07 12:05:21.401  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:21.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:21.411  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:21.641  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false,
09-07 12:05:21.641  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.641  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:21.671  7239  7239 I wpa_supplicant: Blacklist: Clear (all) ,
,09-07 12:05:21.711  7239  7239 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,09-07 12:05:21.721  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:21.721  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:21.721  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,09-07 12:05:21.821  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-07 12:05:21.821  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-07 12:05:21.821  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:21.821  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:21.821  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:21.821  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.821  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.821  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:21.821  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:21.821  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:21.821  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-07 12:05:21.831  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:21.831  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:21.831  1989  2168 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 12:05:21.831  1175  1175 D HotspotTile: onReceive : 1, 0
,09-07 12:05:21.831  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:21.841  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:21.841  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:21.841  1020  1588 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:21.841  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:21.841  1020  1588 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:21.841  1020  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:21.841  1020  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:21.851  1602  1602 I Hs20UtilService: Starting #18
,09-07 12:05:21.851  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:21.851  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-07 12:05:21.851  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-07 12:05:21.851  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
,09-07 12:05:21.851  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:21.881  1020  1477 I ActivityManager: Killing 6861:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,09-07 12:05:22.401   279   988 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-07 12:05:22.411  1020  1047 D Tethering: interfaceRemoved wlan0
,09-07 12:05:22.411  1020  1047 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-07 12:05:22.591  1020  1047 D Tethering: interfaceRemoved p2p0
,09-07 12:05:22.591  1020  1047 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-07 12:05:22.641   289   289 E SMD     : DCD OFF
,09-07 12:05:23.331  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-07 12:05:24.001  6753  6806 D BluetoothAdapter: enable()
,09-07 12:05:24.001  1020  1477 W ActivityManager: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,09-07 12:05:24.001  1020  1477 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
09-07 12:05:24.001  1020  1477 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:24.001  1020  1477 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 12:05:24.001  1020  1477 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
,09-07 12:05:24.001  1020  1477 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 12:05:24.001  1020  1477 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 12:05:24.001  1020  1477 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
09-07 12:05:24.001  1020  1477 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 12:05:24.001  1020  1477 D SettingsProvider: name = bluetooth_on
09-07 12:05:24.001  1020  1477 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:24.011  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-07 12:05:24.011  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:24.011  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-07 12:05:24.011  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-07 12:05:24.021  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-07 12:05:24.021  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:24.021  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:24.021  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-07 12:05:24.041  7352  7352 E Zygote  : MountEmulatedStorage()
09-07 12:05:24.041  7352  7352 E Zygote  : v2
09-07 12:05:24.041  7352  7352 I libpersona: KNOX_SDCARD checking this for 1002
09-07 12:05:24.041  7352  7352 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:24.041  1020  1049 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7352 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-07 12:05:24.041  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:24.041  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-07 12:05:24.051  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 12:05:24.071  7352  7352 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:24.071  7352  7352 D ActivityThread: Added TimaKeyStore provider,
,09-07 12:05:24.091  7352  7352 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 12:05:24.091  7352  7352 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 12:05:24.121  7352  7352 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding GattService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding HeadsetService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding A2dpService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding HidService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding HealthService
09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding PanService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding SapService
09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding SapClientService
,09-07 12:05:24.161  7352  7352 D BtSettings.ProfileConfig: Adding HidDevService
09-07 12:05:24.161  7352  7352 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 12:05:24.161  1020  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 12:05:24.161  1020  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.161  1020  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.161  1020  1480 D SettingsProvider: selectionArgs: false
09-07 12:05:24.161  1020  1480 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:24.161  1020  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.161  1020  1480 D SettingsProvider: ret = -1
,09-07 12:05:24.161  1020  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-07 12:05:24.161  1020  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.161  1020  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1499 D SettingsProvider: selectionArgs: false
,09-07 12:05:24.171  1020  1499 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1499 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-07 12:05:24.171  1020  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1500 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1500 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1500 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1482 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-07 12:05:24.171  1020  1482 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1482 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1482 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1482 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1482 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1482 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1033 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-07 12:05:24.171  1020  1033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1033 D SettingsProvider: selectionArgs: false
,09-07 12:05:24.171  1020  1033 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1033 D SettingsProvider: ret = -1
09-07 12:05:24.171  1020  1588 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,09-07 12:05:24.171  1020  1588 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1588 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1588 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1588 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:24.171  1020  1588 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1588 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1081 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-07 12:05:24.171  1020  1081 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1081 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1081 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1081 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1081 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1081 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1368 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-07 12:05:24.171  1020  1368 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1368 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1368 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1368 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:24.171  1020  1368 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1368 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:24.171  1020  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1481 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1481 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1481 D SettingsProvider: ret = -1
09-07 12:05:24.171  1020  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:24.171  1020  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.171  1020  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.171  1020  1477 D SettingsProvider: selectionArgs: false
09-07 12:05:24.171  1020  1477 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.171  1020  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.171  1020  1477 D SettingsProvider: ret = -1
,09-07 12:05:24.171  1020  1424 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.181  1020  1424 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 12:05:24.181  1020  1424 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.181  1020  1424 D SettingsProvider: selectionArgs: false
09-07 12:05:24.181  1020  1424 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.181  1020  1424 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:24.181  1020  1424 D SettingsProvider: ret = -1
,09-07 12:05:24.181  1020  1432 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 12:05:24.181  1020  1432 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.181  1020  1432 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.181  1020  1432 D SettingsProvider: selectionArgs: false
09-07 12:05:24.181  1020  1432 D SettingsProvider: selectionArgs: 1002
09-07 12:05:24.181  1020  1432 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.181  1020  1432 D SettingsProvider: ret = -1
,09-07 12:05:24.201  7352  7352 D BluetoothAdapterState: make
,09-07 12:05:24.201  7352  7352 I bluedroid: init
,09-07 12:05:24.201  7352  7367 I BluetoothAdapterState: Entering OffState
,09-07 12:05:24.211  7352  7352 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-07 12:05:24.211  7352  7352 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 12:05:24.211  7352  7352 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-07 12:05:24.211  7352  7352 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 12:05:24.211  7352  7352 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-07 12:05:24.211  7352  7352 I bluedroid: get_profile_interface socket
09-07 12:05:24.211  7352  7352 I bluedroid: get_profile_interface map_client
,09-07 12:05:24.211  7352  7370 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-07 12:05:24.211  7352  7352 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-07 12:05:24.221  7352  7370 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 12:05:24.221  7352  7370 E BluetoothServiceJni: populateRssiValuesNative
,09-07 12:05:24.221  7352  7370 I bluedroid: getModelRssiValues
09-07 12:05:24.221  7352  7370 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 12:05:24.221  7352  7370 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 12:05:24.221  7352  7370 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 12:05:24.221  1020  1020 D SettingsProvider: name = bluetooth_name
,09-07 12:05:24.221  7352  7352 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:24.221  1020  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 12:05:24.221  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.231  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.231  1020  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.231  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.231  7352  7361 I bluedroid: config_hci_snoop_log
,09-07 12:05:24.231  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,09-07 12:05:24.231  1020  1049 D BluetoothManagerService: Ble is always on enable gatt
,09-07 12:05:24.231  1020  1049 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-07 12:05:24.231  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 12:05:24.231  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 12:05:24.241  7352  7352 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-07 12:05:24.241  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:24.241  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:24.251  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 12:05:24.251  7352  7367 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-07 12:05:24.251  7352  7367 D BluetoothAdapterProperties: Setting state to 11
,09-07 12:05:24.251  7352  7367 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 12:05:24.251  7352  7367 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 12:05:24.251  7352  7367 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 12:05:24.251  7352  7367 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:24.251  7352  7367 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-07 12:05:24.251  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 12:05:24.261  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:24.261  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,09-07 12:05:24.261  7352  7367 D BluetoothSecureManager: getInstant: null
09-07 12:05:24.261  7352  7367 D BluetoothSecureManager: calling getMethod for getService
,09-07 12:05:24.261  7352  7367 D BluetoothSecureManager: calling getService
,09-07 12:05:24.261  7352  7367 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1f41055b
,09-07 12:05:24.261  1020  1033 D BluetoothSecureManagerService: isSecureModeEnabled
09-07 12:05:24.261  1020  1033 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-07 12:05:24.261  7352  7367 D BtConfig.SecureMode: isSecureModeOn:false
09-07 12:05:24.261  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 12:05:24.271  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:24.271  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-07 12:05:24.271  1175  1175 D BluetoothTile:  getBluetoothState : 11
,09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-07 12:05:24.271  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
09-07 12:05:24.271  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:24.271  1973  1973 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.271  1020  1477 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 12:05:24.271  7352  7367 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.271  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 12:05:24.281  7352  7367 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
09-07 12:05:24.281  1020  1499 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 12:05:24.281  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:24.281  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 12:05:24.281  1020  1500 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:24.281  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.281  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:24.291  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.291  1020  1500 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:24.291  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:24.291  7352  7367 D BluetoothBondStateMachine: make
,09-07 12:05:24.291  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:24.291  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:24.291  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:24.291  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 12:05:24.301  1020  1588 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-07 12:05:24.301  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-07 12:05:24.301  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-07 12:05:24.301  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-07 12:05:24.301  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:24.301  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:24.301  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:24.301  1020  1588 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:24.301  7352  7373 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 12:05:24.311  7374  7374 E Zygote  : MountEmulatedStorage(),
09-07 12:05:24.311  7374  7374 I libpersona: KNOX_SDCARD checking this for 10055
09-07 12:05:24.311  7374  7374 E Zygote  : v2
09-07 12:05:24.311  7374  7374 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:24.311  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:24.311  1020  1588 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7374 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-07 12:05:24.311  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:24.321  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 12:05:24.321  1020  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.321  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.321  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.321  1020  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.321  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.321  7352  7352 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:24.321  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 12:05:24.321  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-07 12:05:24.321  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:24.321  1020  1432 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.321  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.321  1020  1432 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:24.321  1020  1432 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.321  1020  1432 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.321  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 12:05:24.321  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 12:05:24.321  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.321  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-07 12:05:24.321  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 12:05:24.321  7352  7352 D BtGatt.GattService: Received start request. Starting profile...
09-07 12:05:24.321  7352  7352 D BtGatt.GattService: start()
09-07 12:05:24.321  7352  7352 D BtGatt.GattService: start()
09-07 12:05:24.321  7352  7352 I bluedroid: get_profile_interface gatt
09-07 12:05:24.321  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:24.321  7352  7352 D BtGatt.AdvertiseManager: advertise manager created
,09-07 12:05:24.331  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:24.331  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.331  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.331  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-07 12:05:24.331  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:24.331  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 12:05:24.331  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.331  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.331  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.331  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.331  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.331  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 12:05:24.331  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 12:05:24.331  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-07 12:05:24.331  1020  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.331  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.331  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:24.331  1020  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.331  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.341  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-07 12:05:24.341  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 12:05:24.341  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 12:05:24.341  1020  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.341  1020  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.341  7352  7352 D BtGatt.GattService: mStartError = false
09-07 12:05:24.341  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:24.341  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.341  1020  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.341  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.341  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 12:05:24.341  7352  7352 D HeadsetService: Received start request. Starting profile...
09-07 12:05:24.341  7352  7352 D HeadsetService: start()
09-07 12:05:24.341  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:24.341  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:24.341  1020  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.341  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.351  7352  7352 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:05:24.351  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:24.351  1020  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.351  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:24.351  7352  7352 D HeadsetStateMachine: make
,09-07 12:05:24.351  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 12:05:24.351  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 12:05:24.351  7352  7367 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 12:05:24.351  7352  7352 E HeadsetStateMachine: # of Max HF connection is 2
09-07 12:05:24.351  1020  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:24.351  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:24.351  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 12:05:24.351  7374  7374 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:24.351  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.351  1020  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.351  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 12:05:24.361  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:24.361  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.361  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
09-07 12:05:24.361  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 12:05:24.361  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 12:05:24.361  7352  7367 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 12:05:24.361  1020  1432 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-07 12:05:24.361  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
09-07 12:05:24.361  1020  1432 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.361  1020  1432 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:24.361  1020  1432 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 12:05:24.371  1020  1482 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-07 12:05:24.371  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 12:05:24.371  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:24.371  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:24.371  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-07 12:05:24.371  7352  7352 I bluedroid: get_profile_interface handsfree
,09-07 12:05:24.391  7352  7352 I DualScoManager: Instantiating Dual Sco Manager
09-07 12:05:24.391  7352  7352 I DualScoManager: Set HeadsetServiceHelper
09-07 12:05:24.391  7374  7374 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-07 12:05:24.391  7352  7352 D BluetoothAtMessage: createCMTIContentObservers
,09-07 12:05:24.391  1020  1499 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-07 12:05:24.391  1020  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:24.391  1020  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:24.391  1020  1499 D SettingsProvider: selectionArgs: false
09-07 12:05:24.391  1020  1499 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:24.391  1020  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:24.391  1020  1499 D SettingsProvider: ret = -1
,09-07 12:05:24.391  7352  7393 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 12:05:24.401  7352  7352 D HeadsetService: mStartError = false
09-07 12:05:24.401  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.401  7352  7352 D A2dpService: Received start request. Starting profile...
,09-07 12:05:24.401  7352  7352 D A2dpService: start()
,09-07 12:05:24.401  7352  7393 D HeadsetStateMachine: Clear mHeadsetBrsf
09-07 12:05:24.401  7352  7393 D HeadsetStateMachine: map size, before remove : 0
,09-07 12:05:24.401  7352  7393 D HeadsetStateMachine: map size, after remove: 0
,09-07 12:05:24.401  7352  7352 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-07 12:05:24.401  7352  7352 I bluedroid: get_profile_interface avrcp
,09-07 12:05:24.411  7352  7352 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 12:05:24.411  7352  7352 D Avrcp   : Initialize Media Controller
,09-07 12:05:24.411  7352  7352 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,09-07 12:05:24.411  7352  7352 E Avrcp   : getActiveSessions
09-07 12:05:24.411  7352  7352 D Avrcp   : pick active media Controller
09-07 12:05:24.411  7352  7352 D Avrcp   : Get the active Media Controller 
,09-07 12:05:24.421  7374  7374 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-07 12:05:24.421  7374  7374 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-07 12:05:24.421  7374  7374 D UserAnalysis: Create SecureDbHelper
,09-07 12:05:24.431  7352  7352 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 12:05:24.431  7352  7395 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 12:05:24.431  7352  7352 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:05:24.431  7352  7352 D A2dpStateMachine: make
,09-07 12:05:24.431  7374  7374 D IntelligenceServiceApplication: onCreate()
09-07 12:05:24.431  7352  7352 I bluedroid: get_profile_interface a2dp
09-07 12:05:24.431  7352  7397 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-07 12:05:24.431  7352  7352 E bt-btif : warning : media task started media_task_refcnt 1 
,09-07 12:05:24.441  1020  1424 I ActivityManager: Killing 6997:com.sec.pcw.device/1000 (adj 15): empty #21
09-07 12:05:24.441  7352  7352 D A2dpService: mStartError = false
09-07 12:05:24.441  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.441  7352  7396 D A2dpStateMachine: Enter Disconnected: -2
,09-07 12:05:24.441  7352  7352 I BluetoothHidServiceJni: classInitNative: succeeds
,09-07 12:05:24.441  7352  7352 D HidService: Received start request. Starting profile...
09-07 12:05:24.441  7352  7352 D HidService: start()
09-07 12:05:24.441  7352  7352 I bluedroid: get_profile_interface hidhost
09-07 12:05:24.441  7352  7352 D HidService: setHidService(): set to: null
09-07 12:05:24.441  7352  7352 D HidService: mStartError = false
09-07 12:05:24.441  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.441  7352  7352 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 12:05:24.451  7352  7352 D HealthService: Received start request. Starting profile...
09-07 12:05:24.451  7374  7374 D IntelligenceServiceApplication: no applications having user consent for prediction
09-07 12:05:24.451  7352  7352 D HealthService: start()
,09-07 12:05:24.451  7352  7352 I bluedroid: get_profile_interface health
09-07 12:05:24.451  7352  7352 D HealthService: mStartError = false
09-07 12:05:24.451  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.451  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-07 12:05:24.451  7352  7352 I BluetoothPanServiceJni: classInitNative(L105): succeeds
09-07 12:05:24.451  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-07 12:05:24.451  7352  7395 D BluetoothMediaBrowser: no now playing list
,09-07 12:05:24.451  7374  7374 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
09-07 12:05:24.451  7352  7395 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-07 12:05:24.451  7352  7352 D PanService: Received start request. Starting profile...
09-07 12:05:24.451  7352  7352 D PanService: start()
09-07 12:05:24.451  7352  7352 D BluetoothPanServiceJni: initializeNative(L110): pan
09-07 12:05:24.451  7352  7352 I bluedroid: get_profile_interface pan
,09-07 12:05:24.451  7352  7352 D PanService: mStartError = false
09-07 12:05:24.451  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.461  7352  7352 D BluetoothMapService: Received start request. Starting profile...
09-07 12:05:24.461  7352  7352 D BluetoothMapService: start()
,09-07 12:05:24.461  7352  7352 D BluetoothMapService: mStartError = false
09-07 12:05:24.461  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.461  7352  7352 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-07 12:05:24.461  7352  7352 D SapService: Received start request. Starting profile...
09-07 12:05:24.461  7352  7352 D SapService: start()
09-07 12:05:24.461  7352  7352 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 12:05:24.461  7352  7352 I bluedroid: get_profile_interface sap
09-07 12:05:24.461  7352  7352 D SapService: mStartError = false
09-07 12:05:24.461  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:24.461  7352  7352 D HeadsetStateMachine: Try to query the phonestate on bind
09-07 12:05:24.461  7374  7374 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-07 12:05:24.461  1425  1463 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 12:05:24.471  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0,
09-07 12:05:24.471  7352  7352 D HeadsetStateMachine: Proxy object connected
09-07 12:05:24.471  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 12:05:24.471  7352  7352 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-07 12:05:24.471  1425  1463 I Telecom : BluetoothPhoneService: Result of Message : true
09-07 12:05:24.471  7352  7352 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 12:05:24.471  7352  7352 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-07 12:05:24.471  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 12:05:24.471  7352  7352 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
09-07 12:05:24.471  7352  7352 D BluetoothA2dp: Proxy object connected
,09-07 12:05:24.471  7352  7352 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-07 12:05:24.471  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 12:05:24.471  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-07 12:05:24.471  7352  7393 D HeadsetStateMachine: Disconnected process message: 11
09-07 12:05:24.471  7352  7393 D HeadsetStateMachine: Disconnected process message: 18
09-07 12:05:24.471  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 12:05:24.471  7352  7393 D HeadsetStateMachine: Disconnected process message: 10
09-07 12:05:24.471  7352  7393 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-07 12:05:24.471  7352  7393 D HeadsetStateMachine: Disconnected process message: 11
,09-07 12:05:24.471  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 12:05:24.471  1020  1482 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-07 12:05:24.481  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:24.481  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:24.481  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:24.481  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:24.491  7402  7402 E Zygote  : MountEmulatedStorage(),
09-07 12:05:24.491  7402  7402 E Zygote  : v2
09-07 12:05:24.491  7402  7402 I libpersona: KNOX_SDCARD checking this for 10105
09-07 12:05:24.491  7402  7402 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:24.491  7402  7402 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-07 12:05:24.491  7402  7402 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-07 12:05:24.491  1020  1482 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7402 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-07 12:05:24.491  7402  7402 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-07 12:05:24.521  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
09-07 12:05:24.521  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 12:05:24.521  7352  7367 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-07 12:05:24.521  7352  7367 I bluedroid: enable
,09-07 12:05:24.521  7352  7367 I bt_hci_bdroid: init
,09-07 12:05:24.521  7352  7413 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-07 12:05:24.521  7402  7402 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:24.531  7402  7402 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:24.531  7352  7367 I bt_vendor: bt-vendor : init
09-07 12:05:24.531  7352  7367 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 12:05:24.531  7352  7367 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 12:05:24.531  7352  7367 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-07 12:05:24.531  7352  7367 D bt_userial_mct: userial_init
,09-07 12:05:24.531  7352  7367 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-07 12:05:24.531  7352  7367 I bt_vendor: Starting hciattach daemon
09-07 12:05:24.531  7352  7367 I bt_vendor: try to set false
,09-07 12:05:24.531  7352  7367 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-07 12:05:24.531  7352  7367 I bt_vendor: Starting hciattach daemon
09-07 12:05:24.531  7352  7367 I bt_vendor: try to set true
,09-07 12:05:24.551  7421  7421 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-07 12:05:24.601  7427  7427 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-07 12:05:24.611  7428  7428 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 12:05:24.631  7432  7432 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 12:05:24.631  7433  7433 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,09-07 12:05:24.641  7434  7434 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-07 12:05:24.651  7435  7435 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,09-07 12:05:24.671   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 12:05:24.671   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:24.671  7402  7438 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 12:05:24.681   258   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
09-07 12:05:24.681   258   522 W Vold    : Returning OperationFailed - no handler for errno 0
,09-07 12:05:24.681  7402  7438 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
,09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: ,	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
,09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=151 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	,at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:24.841  1020  1424 I ActivityManager: Killing 7014:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=149 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.k.a(PG:2107)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07, 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.k.d(PG:1187)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.k.c(PG:18147)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.k.d(PG:583)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.v.a(PG:1161)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.y.a(PG:2188)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.e.b(PG:170)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.q.e.b(PG:15188)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102),
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.exists(File.java:363)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:24.841  7402  7402 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.io.File.lastModified(File.java:571)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.a,ccess$1600(ActivityThread.java:181)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-07 12:05:24.841  7402  7402 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-07 12:05:24.851  7450  7450 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
09-07 12:05:24.851  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-07 12:05:24.861  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-07 12:05:24.861  7451  7451 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,09-07 12:05:24.891  7352  7367 I bt_vendor: bluetooth satus is on
,09-07 12:05:24.891  7352  7417 D bt_userial_mct: userial_open(port:0)
09-07 12:05:24.891  7352  7417 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-07 12:05:24.891  7352  7417 I bt_vendor: Done intiailizing UART
,09-07 12:05:24.891  7352  7417 I bt_vendor: Done intiailizing UART
09-07 12:05:24.891  7352  7417 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-07 12:05:24.891  7352  7417 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-07 12:05:24.901  7352  7453 D bt_userial_mct: Entering userial_read_thread()
,09-07 12:05:24.901  7402  7443 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-07 12:05:24.901  7352  7413 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 12:05:24.901  7352  7413 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:05:24.901  7352  7413 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 12:05:24.901  7352  7413 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_A2D
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_GAP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_SAP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_SMP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_BTIF
09-07 12:05:24.911  7352  7413 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-07 12:05:24.991  7352  7413 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-07 12:05:25.001  7352  7413 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa4158ed1 
,09-07 12:05:25.001  7352  7413 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa4158ed1 
,09-07 12:05:25.011  7352  7370 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-07 12:05:25.011  7352  7370 E bt-btif : Calling BTA_HhEnable
,09-07 12:05:25.011  7352  7370 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 12:05:25.021  7352  7370 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 12:05:25.021  7352  7370 E BluetoothServiceJni: populateRssiValuesNative
09-07 12:05:25.021  7352  7370 I bluedroid: getModelRssiValues
09-07 12:05:25.021  7352  7370 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 12:05:25.021  7352  7370 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
09-07 12:05:25.021  1020  3356 D SSRM:n  : SIOP:: AP = 330
,09-07 12:05:25.061  1020  1499 I art     : Explicit concurrent mark sweep GC freed 68510(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.502ms total 149.169ms
,09-07 12:05:25.071  1020  1482 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:25.071  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.071  1020  1482 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:25.071  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-07 12:05:25.071  7352  7370 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 12:05:25.071  1020  1020 D SettingsProvider: name = bluetooth_name
,09-07 12:05:25.071  7352  7370 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 12:05:25.071  7352  7370 D BluetoothAdapterProperties: Scan Mode:20
09-07 12:05:25.071  7352  7370 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:25.071  7352  7370 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-07 12:05:25.071  7352  7370 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-07 12:05:25.071  7352  7370 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-07 12:05:25.071  7352  7370 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 12:05:25.071  7352  7370 E bt-btif : btif_sock_init: !vhci_init
09-07 12:05:25.071  7352  7370 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-07 12:05:25.071  7352  7370 D IOP_DB_BT: db_open: db_open : handle 3027828752l, read 13894 bytes onto local cache
09-07 12:05:25.071  7352  7370 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
09-07 12:05:25.071  7352  7370 D IOP_DB_BT: db_query: result 1
09-07 12:05:25.071  7352  7370 I         : iop_db_open: iop_db_open status 0
09-07 12:05:25.071  7352  7370 D bte_conf: Device ID record 1 : primary
09-07 12:05:25.071  7352  7370 D bte_conf:   vendorId            = 0075
09-07 12:05:25.071  7352  7370 D bte_conf:   vendorIdSource      = 0001
09-07 12:05:25.071  7352  7370 D bte_conf:   product             = 0100
09-07 12:05:25.071  7352  7370 D bte_conf:   version             = 0200
09-07 12:05:25.071  7352  7370 D bte_conf:   clientExecutableURL = 
09-07 12:05:25.071  7352  7370 D bte_conf:   serviceDescription  = 
09-07 12:05:25.071  7352  7370 D bte_conf:   documentationURL    = 
09-07 12:05:25.071  7352  7370 D bte_conf: bte_load_did_conf no section named DID2.
09-07 12:05:25.071  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:25.071  7352  7370 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-07 12:05:25.081  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:25.081  7352  7367 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
09-07 12:05:25.081  7352  7453 E bt_mct  : hci lib postload completed
09-07 12:05:25.081  7352  7367 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:05:25.081  7352  7367 D BluetoothAdapterProperties: State =  11
09-07 12:05:25.081  1020  1032 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-07 12:05:25.081  7352  7367 D BluetoothAdapterProperties: Setting state to 12
09-07 12:05:25.081  7352  7367 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 12:05:25.081  7352  7370 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 12:05:25.081  7352  7370 D BluetoothAdapterProperties: Scan Mode:21
09-07 12:05:25.081  7352  7370 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:25.091  1020  1499 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-07 12:05:25.091  1020  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:25.091  1020  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:25.091  1020  1499 D SettingsProvider: selectionArgs: false
09-07 12:05:25.091  1020  1499 D SettingsProvider: selectionArgs: 1002
09-07 12:05:25.091  1020  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:25.091  1020  1499 D SettingsProvider: ret = -1
,09-07 12:05:25.091  7352  7367 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 12:05:25.091  7352  7367 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 12:05:25.091  1020  1368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:25.091  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:25.091  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:25.101  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.101  1020  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.101  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.111  7352  7367 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:25.111  7352  7367 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 12:05:25.111  7352  7367 D BluetoothAdapterService: starting service from this receiver
,09-07 12:05:25.111  1020  1424 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:25.111  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.111  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.111  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.111  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:25.111  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:25.111  1425  1453 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 12:05:25.111  1425  1453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.111  7352  7367 I BluetoothAdapterState: Entering On State from state = 11
,09-07 12:05:25.121  1989  1998 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.121  1989  1998 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.121  1367  1384 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 12:05:25.121  1367  1384 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:25.121  7352  7352 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:25.121  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:25.121  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:25.121  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 12:05:25.121  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 12:05:25.121  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.121  1020  1020 D BluetoothA2dp: Proxy object connected
,09-07 12:05:25.121  1367  1378 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:25.121  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:25.121  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.121  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:25.121  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.121  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.121  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.121  1367  1378 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:25.131  1449  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 12:05:25.131  1449  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.131  7352  7352 I BluetoothPbapService: Handler(): got msg=1
,09-07 12:05:25.131  1020  1368 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,09-07 12:05:25.131  7352  7459 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.131  7352  7459 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.131  1425  3275 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:25.131  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 12:05:25.131  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.131  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.131  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.131  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.141  1425  3275 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:25.141  1367  1384 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 12:05:25.141  1367  1367 D HeadsetProfile: Bluetooth service connected
09-07 12:05:25.141  7352  7460 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 12:05:25.141  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-07 12:05:25.141  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.141  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.141  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.141  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.141  1367  1378 D Bluetoothsap: onBluetoothStateChange: up=true
09-07 12:05:25.141  1367  1378 D Bluetoothsap: Binding service...
,09-07 12:05:25.141  7352  7460 D BluetoothSocket: bindListen(): myUserId = 0
09-07 12:05:25.141  7352  7460 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:25.141  1367  1367 D BluetoothMap: Proxy object connected
09-07 12:05:25.141  1367  1367 D MapProfile: Bluetooth service connected
09-07 12:05:25.141  1367  1367 D BluetoothMap: getConnectedDevices()
,09-07 12:05:25.151  7352  7460 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-07 12:05:25.151  7352  7460 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:25.151  7352  7460 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 12:05:25.151  7352  7460 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c46a19c
,09-07 12:05:25.151  7352  7460 D BluetoothSocket: channel: 19
09-07 12:05:25.151  7352  7460 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 12:05:25.151  1367  1378 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 12:05:25.151  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-07 12:05:25.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.151  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.151  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.151  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.151  1367  1378 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 12:05:25.151  1425  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0,
,09-07 12:05:25.151  1367  1367 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 12:05:25.151  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:25.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.151  1367  1367 D SapProfile: Bluetooth service connected
09-07 12:05:25.151  1367  1367 D Bluetoothsap: getConnectedDevices()
09-07 12:05:25.151  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.151  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.161  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.161  1425  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:25.161  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-07 12:05:25.161  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:25.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.161  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
09-07 12:05:25.161  1367  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 12:05:25.161  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-07 12:05:25.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.161  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.161  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.161  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.161  1367  1384 D BluetoothPan: Binding service...
,09-07 12:05:25.171  1367  1367 D BluetoothInputDevice: Proxy object connected
,09-07 12:05:25.171  1367  1367 D HidProfile: Bluetooth service connected
09-07 12:05:25.171  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 12:05:25.171  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.171  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.171  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.171  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.171  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
09-07 12:05:25.171  1367  1367 D PanProfile: Bluetooth service connected
,09-07 12:05:25.171  1175  1960 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.171  1175  1960 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.171  7402  7410 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.171  7402  7410 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.171  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.171  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:25.171  1367  6906 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:25.171  1367  6906 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:25.171  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-07 12:05:25.181  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.181  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.181  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.181  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.181  1367  1367 D BluetoothA2dp: Proxy object connected
,09-07 12:05:25.181  1438  1448 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.181  1438  1448 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:25.181  1367  1367 D A2dpProfile: Bluetooth service connected
,09-07 12:05:25.181  7352  7459 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:05:25.181  1367  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 12:05:25.181  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-07 12:05:25.181  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.181  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.181  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.181  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.181  1449  1947 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:25.181  1367  1367 D BluetoothPbap: Proxy object connected
09-07 12:05:25.181  1367  1367 D PbapServerProfile: Bluetooth service connected
,09-07 12:05:25.181  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 12:05:25.181  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.191  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.191  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.191  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.191  1449  1947 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:25.191  6753  6761 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:25.191  6753  6761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:25.191  1020  1049 D BluetoothPan: Binding service...
,09-07 12:05:25.191  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-07 12:05:25.191  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.191  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 12:05:25.191  1425  6888 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:25.191  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 12:05:25.191  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:25.191  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.191  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.191  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.201  1425  6888 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:25.201  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 12:05:25.201  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 12:05:25.201  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:25.201  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
09-07 12:05:25.201  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 12:05:25.211  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3def0c58, true
09-07 12:05:25.211  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 12:05:25.221  1425  1425 D BluetoothHeadset: registerMessageListener
,09-07 12:05:25.221  1973  1973 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:25.221  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 12:05:25.221  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:25.221  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-07 12:05:25.221  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:25.221  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:25.221  1020  1481 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
09-07 12:05:25.221  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.221  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-07 12:05:25.231  7352  7459 D HeadsetService: registerMessageListener
09-07 12:05:25.231  7352  7459 D HeadsetService: registerMessageListener
,09-07 12:05:25.231  7352  7393 D HeadsetStateMachine: Disconnected process message: 70
09-07 12:05:25.231  7352  7393 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@19f887a5
09-07 12:05:25.231  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-07 12:05:25.231  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.231  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 12:05:25.231  1020  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:25.231  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:25.231  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:25.231  1020  1481 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:25.231  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:25.231  1020  1480 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 12:05:25.231  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 12:05:25.231  7352  7462 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-07 12:05:25.231  1367  1367 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-07 12:05:25.231  1367  1367 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 12:05:25.231  1367  1367 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 12:05:25.231  1367  1367 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 12:05:25.241  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:25.241  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-07 12:05:25.241  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-07 12:05:25.241  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 12:05:25.241  7352  7462 D BluetoothSocket: bindListen(): myUserId = 0
09-07 12:05:25.241  7352  7462 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:25.241  7352  7462 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
09-07 12:05:25.241  7352  7462 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:25.241  7352  7462 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 12:05:25.241  7352  7462 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16c4377a
,09-07 12:05:25.241  7352  7462 D BluetoothSocket: channel: 5
,09-07 12:05:25.241  7352  7393 D HeadsetStateMachine: Disconnected process message: 9
,09-07 12:05:25.241  7352  7393 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 12:05:25.251   284  1018 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-07 12:05:25.251   284  1018 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 12:05:25.251   284  1018 V voice   : voice_set_parameters: exit with code(-2)
09-07 12:05:25.251   284  1018 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-07 12:05:25.251   284  1018 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 12:05:25.251  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-07 12:05:25.251   284  1018 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 12:05:25.251   284  1018 V audio_hw_primary: adev_set_parameters: exit
09-07 12:05:25.251  7352  7393 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 12:05:25.261  1020  1588 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 12:05:25.261  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.261  1020  1588 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.261  1020  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.261  1020  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 12:05:25.271  1367  1367 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:25.271  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:25.271  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:25.271  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 12:05:25.281  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:25.281  7352  7352 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 12:05:25.281  1020  1368 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:25.281  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 12:05:25.281  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.281  1020  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:25.281  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:25.301  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:25.301  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.301  1020  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:25.301  1020  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:25.301  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
09-07 12:05:25.301  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:25.311  1989  7468 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 12:05:25.311  1020  1081 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-07 12:05:25.311  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:25.311  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:25.311  1020  1081 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:25.311  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:25.311  1020  1477 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 12:05:25.331  1020  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:25.331  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:25.331  1020  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:25.331  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:25.341  7352  7472 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 12:05:25.341  7352  7472 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:25.341  7352  7472 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-07 12:05:25.341  7352  7472 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:25.341  7352  7472 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 12:05:25.341  7352  7472 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ab8834
09-07 12:05:25.341  7352  7472 D BluetoothSocket: channel: 12
09-07 12:05:25.341  7352  7472 I BtOppRfcommListener: Accept thread started.
,09-07 12:05:25.341  1989  7468 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-07 12:05:25.641   289   289 E SMD     : DCD OFF,
,09-07 12:05:27.011  6753  6806 D BluetoothAdapter: disable()
,09-07 12:05:27.011  1020  1368 D SettingsProvider: name = bluetooth_on
,09-07 12:05:27.021  7352  7367 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-07 12:05:27.021  7352  7367 D BluetoothAdapterProperties: Setting state to 13
09-07 12:05:27.021  7352  7367 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-07 12:05:27.021  7352  7367 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 12:05:27.021  7352  7367 D BluetoothAdapterService: updateAdapterState state is 13
,09-07 12:05:27.021  1020  1477 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.021  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.021  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.031  1020  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.031  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.031  7352  7352 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-07 12:05:27.031  7352  7367 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:27.031  7352  7367 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-07 12:05:27.031  7352  7367 D BluetoothAdapterService: terminating service from this receiver
,09-07 12:05:27.031  7352  7352 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@28c1065d, channel: 19, state: LISTENING
09-07 12:05:27.031  7352  7352 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@28c1065d, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c46a19c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@330e3bd2mSocket: android.net.LocalSocket@29b5a4a3 impl:android.net.LocalSocketImpl@1392f3a0 fd:FileDescriptor[74]
09-07 12:05:27.031  7352  7352 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@29b5a4a3 impl:android.net.LocalSocketImpl@1392f3a0 fd:FileDescriptor[74]
,09-07 12:05:27.031  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.031  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:27.031  1020  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:27.031  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.041  7352  7367 D BluetoothAdapterProperties: onBluetoothDisable()
,09-07 12:05:27.041  7352  7367 D BluetoothAdapterProperties: mDiscovering is false
,09-07 12:05:27.041  1020  1480 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 12:05:27.041  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:27.041  7352  7367 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-07 12:05:27.041  1020  1020 I InputMethodManagerService: [BT Setting State] State =13
,09-07 12:05:27.051  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 12:05:27.051  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:27.051  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 12:05:27.051  1175  1175 D BluetoothTile:  getBluetoothState : 13
,09-07 12:05:27.051  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:27.051  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null,
09-07 12:05:27.051  1973  1973 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0,
09-07 12:05:27.051  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-07 12:05:27.051  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:27.061  1020  1432 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:27.061  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:27.061  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:27.061  1020  1081 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 12:05:27.061  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:27.061  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:27.061  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 12:05:27.061  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:27.071  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.071  7352  7370 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 12:05:27.071  7352  7370 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:27.071  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:27.071  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:27.071  1367  1367 D BluetoothPbap: Proxy object disconnected
,09-07 12:05:27.071  1367  1367 D PbapServerProfile: Bluetooth service disconnected
09-07 12:05:27.071  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:27.071  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:27.071  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:27.071  6753  6753 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-07 12:05:27.071  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:27.071  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:27.071  7352  7367 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-07 12:05:27.071  7352  7367 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-07 12:05:27.081  1020  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 12:05:27.081  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.081  7352  7367 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-07 12:05:27.081  7352  7367 E bt-btif : cmd socket is not created
09-07 12:05:27.081  7352  7472 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-07 12:05:27.081  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:27.081  7352  7367 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-07 12:05:27.081  7352  7413 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-07 12:05:27.081  7352  7413 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-07 12:05:27.081  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:27.081  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:27.081  7352  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:27.081  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.081  1020  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.081  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 12:05:27.091  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:27.101  7352  7352 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@298cab59, channel: 5, state: LISTENING
,09-07 12:05:27.101  7352  7352 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@298cab59, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16c4377a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2cf0431emSocket: android.net.LocalSocket@1df3e7ff impl:android.net.LocalSocketImpl@3fc3a9cc fd:FileDescriptor[76]
,09-07 12:05:27.101  7352  7352 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1df3e7ff impl:android.net.LocalSocketImpl@3fc3a9cc fd:FileDescriptor[76]
,09-07 12:05:27.101  7352  7352 I BtOppRfcommListener: stopping Accept Thread
,09-07 12:05:27.101  7352  7352 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@23d3a415, channel: 12, state: LISTENING
,09-07 12:05:27.101  7352  7352 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@23d3a415, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ab8834, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a59732amSocket: android.net.LocalSocket@15a9051b impl:android.net.LocalSocketImpl@66796b8 fd:FileDescriptor[79]
,09-07 12:05:27.111  7352  7352 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@15a9051b impl:android.net.LocalSocketImpl@66796b8 fd:FileDescriptor[79]
,09-07 12:05:27.111  7352  7472 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-07 12:05:27.111  1367  1367 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:27.111  7352  7352 V BluetoothOppManager: cleanUp...
,09-07 12:05:27.121  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:27.121  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:27.121  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-07 12:05:27.141  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:27.141  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-07 12:05:27.291  7352  7413 W bt-btif : ag scb idx 1 not allocated
09-07 12:05:27.291  7352  7413 W bt-btif : ag scb idx 2 not allocated
09-07 12:05:27.291  7352  7413 E bt-btif : BTA AG is already disabled, ignoring ...
09-07 12:05:27.291  7352  7453 I bt_userial_mct: exiting userial_read_thread
09-07 12:05:27.291  7352  7453 D bt_userial_mct: Leaving userial_evt_read_thread()
09-07 12:05:27.291  7352  7370 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-07 12:05:27.291  7352  7417 I bt_vendor: hw_epilog_process
09-07 12:05:27.291  7352  7370 D bt_userial_mct: userial_close
09-07 12:05:27.291  7352  7370 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-07 12:05:27.711  7352  7370 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-07 12:05:27.711  7352  7370 I bt_vendor: bluetooth satus is on
09-07 12:05:27.711  7352  7370 I bt_vendor: bt-vendor : resetting BT status
09-07 12:05:27.711  7352  7370 I bt_vendor: Starting hciattach daemon
09-07 12:05:27.711  7352  7370 I bt_vendor: try to set false
,09-07 12:05:27.711  7352  7370 I bt_vendor: Starting hciattach daemon
09-07 12:05:27.711  7352  7370 I bt_vendor: try to set false
,09-07 12:05:27.711  7352  7370 I bt_vendor: cleanup
,09-07 12:05:27.711  7352  7413 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-07 12:05:27.711  7352  7370 I GKI_LINUX: GKI_exit_task 0 done
09-07 12:05:27.711  7352  7370 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-07 12:05:27.711  7352  7367 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-07 12:05:27.711  7352  7367 D BtConfig.SecureMode: isSecureModeOn:false
09-07 12:05:27.711  7352  7367 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12,
09-07 12:05:27.711  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-07 12:05:27.711  1020  1032 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:27.711  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 12:05:27.711  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
09-07 12:05:27.711  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService,
09-07 12:05:27.711  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.711  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:27.711  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
09-07 12:05:27.721  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 12:05:27.721  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
09-07 12:05:27.721  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.721  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:27.721  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-07 12:05:27.721  7352  7352 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:27.721  1020  1482 W ActivityManager: userId = 0, bbcId = -10000,
09-07 12:05:27.721  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:27.721  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.721  7352  7352 D BtGatt.GattService: Received stop request...Stopping profile...
09-07 12:05:27.721  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 12:05:27.721  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 12:05:27.721  7352  7352 D BtGatt.GattService: stop()
09-07 12:05:27.721  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-07 12:05:27.721  7352  7352 D BtGatt.AdvertiseManager: advertise clients cleared
09-07 12:05:27.721  1020  1432 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.721  1020  1432 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.721  1020  1432 W ActivityManager: userId = 0, bbcId = -10000,
09-07 12:05:27.721  1020  1432 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.721  1020  1432 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.721  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:27.731  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService,
09-07 12:05:27.731  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:27.731  1020  1499 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:27.731  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-07 12:05:27.731  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-07 12:05:27.731  7352  7352 D HeadsetService: Received stop request...Stopping profile...
09-07 12:05:27.731  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.731  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.731  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:27.731  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 12:05:27.731  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.731  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 12:05:27.731  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 12:05:27.731  1020  1588 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.731  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.731  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-07 12:05:27.731  1367  1367 D HeadsetProfile: Bluetooth service disconnected
09-07 12:05:27.731  1020  1588 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.731  1020  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.731  1020  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-07 12:05:27.741  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-07 12:05:27.741  1020  1081 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.741  1020  1081 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.741  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.741  1020  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:27.741  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.741  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.741  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:27.741  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.741  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.741  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.741  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-07 12:05:27.741  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 12:05:27.741  7352  7367 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 12:05:27.751  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:27.751  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.751  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:27.751  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.751  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:27.751  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:27.751  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 12:05:27.751  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 12:05:27.751  7352  7367 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 12:05:27.751  7352  7367 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 12:05:27.751  7352  7367 D BluetoothAdapterState: Stopping profile services that were post enabled
09-07 12:05:27.751  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-07 12:05:27.751  7352  7352 D A2dpService: Received stop request...Stopping profile...
09-07 12:05:27.751  7352  7396 D A2dpStateMachine: Exit Disconnected: -1
,09-07 12:05:27.751  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.761  1367  1367 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:27.761  1367  1367 D A2dpProfile: Bluetooth service disconnected
,09-07 12:05:27.761  1020  1020 D BluetoothA2dp: Proxy object disconnected
,09-07 12:05:27.761  1020  1020 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-07 12:05:27.761  7352  7352 D HidService: Received stop request...Stopping profile...
09-07 12:05:27.761  7352  7352 D HidService: Stopping Bluetooth HidService
09-07 12:05:27.761  7352  7352 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-07 12:05:27.761  7352  7352 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-07 12:05:27.761  7352  7352 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-07 12:05:27.761  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.761  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-07 12:05:27.761  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:27.761  7352  7352 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 12:05:27.761  1367  1367 D BluetoothInputDevice: Proxy object disconnected
09-07 12:05:27.761  7352  7352 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...,
09-07 12:05:27.761  7352  7352 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-07 12:05:27.761  7352  7352 D HealthService: Received stop request...Stopping profile...
,09-07 12:05:27.761  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:27.761  1367  1367 D HidProfile: Bluetooth service disconnected
,09-07 12:05:27.771  7352  7352 D PanService: Received stop request...Stopping profile...
,09-07 12:05:27.771  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.771  7352  7352 D BluetoothMapService: Received stop request...Stopping profile...
09-07 12:05:27.771  1020  1020 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-07 12:05:27.771  1367  1367 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-07 12:05:27.771  1367  1367 D PanProfile: Bluetooth service disconnected
,09-07 12:05:27.771  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.781  7352  7352 D SapService: Received stop request...Stopping profile...
09-07 12:05:27.781  7352  7352 D SapService: Stopping Bluetooth SapService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:27.781  1367  1367 D BluetoothMap: Proxy object disconnected
09-07 12:05:27.781  1367  1367 D MapProfile: Bluetooth service disconnected
,09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,09-07 12:05:27.781  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-07 12:05:27.781  7352  7352 D BluetoothA2dp: Proxy object disconnected
09-07 12:05:27.781  1367  1367 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-07 12:05:27.781  1367  1367 D SapProfile: Bluetooth service disconnected
09-07 12:05:27.781  7352  7397 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-07 12:05:27.781  7352  7352 I GKI_LINUX: GKI_exit_task 2 done
09-07 12:05:27.781  7352  7352 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-07 12:05:27.781  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-07 12:05:27.781  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.781  7352  7352 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-07 12:05:27.781  7352  7352 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-07 12:05:27.781  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService,
09-07 12:05:27.781  7352  7352 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-07 12:05:27.781  7352  7352 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-07 12:05:27.781  7352  7352 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 12:05:27.781  7352  7352 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-07 12:05:27.781  7352  7352 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-07 12:05:27.791  7352  7352 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-07 12:05:27.791  7352  7352 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-07 12:05:27.791  7352  7367 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true,
09-07 12:05:27.791  7352  7367 D BluetoothAdapterProperties: Setting state to 10
09-07 12:05:27.791  7352  7367 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-07 12:05:27.791  7352  7367 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 12:05:27.791  7352  7367 D BluetoothAdapterService: updateAdapterState state is 10
09-07 12:05:27.791  7352  7367 D BluetoothAdapterService: Autoconnection is available ,
09-07 12:05:27.791  7352  7367 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-07 12:05:27.791  7352  7367 I BluetoothAdapterState: Entering OffState
,09-07 12:05:27.791  1425  3275 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:27.791  1425  3275 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:27.791  1989  2165 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.791  1989  2165 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.791  1367  1384 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:27.791  1367  1384 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.791  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 12:05:27.791  1449  1947 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.791  1449  1947 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.801  7352  7371 D BluetoothAdapter: onBluetoothStateChange: up=false
09-07 12:05:27.801  7352  7371 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.801  1367  6906 D BluetoothMap: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1367  1384 D Bluetoothsap: onBluetoothStateChange: up=false
09-07 12:05:27.801  1367  1384 D Bluetoothsap: Unbinding service...
,09-07 12:05:27.801  1367  1378 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1175  2147 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1175  2147 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.801  7402  7411 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.801  7402  7411 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.801  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1020  1049 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:27.801  1367  1384 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1438  1448 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-07 12:05:27.801  1438  1448 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-07 12:05:27.811  7352  7362 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-07 12:05:27.811  1367  1378 D BluetoothPbap: onBluetoothStateChange: up=false
,09-07 12:05:27.811  6753  6761 D BluetoothAdapter: onBluetoothStateChange: up=false,
09-07 12:05:27.811  6753  6761 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-07 12:05:27.811  6753  6761 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-07 12:05:27.811  6753  6761 D BluetoothLeAdvertiser: Exit stop advertising
09-07 12:05:27.811  6753  6761 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-07 12:05:27.811  6753  6761 D BluetoothLeScanner: Exiting stopAllScan
,09-07 12:05:27.811  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-07 12:05:27.811  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 12:05:27.821  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:27.821  1020  1020 I InputMethodManagerService: [BT Setting State] State =10
,09-07 12:05:27.821  1020  1020 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 12:05:27.831  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:27.831  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 12:05:27.831  1175  1668 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:27.831  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:27.831  1175  1175 D BluetoothTile:  getBluetoothState : 10
,09-07 12:05:27.831  1175  1668 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:27.831  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
09-07 12:05:27.831  1175  1175 D BluetoothAdapter: 753623485: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:27.831  1020  1081 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:27.831  1020  1588 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-07 12:05:27.831  1973  1973 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:27.831  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:27.831  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-07 12:05:27.841  1989  2168 D BluetoothAdapter: 298732497: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:27.841  1989  2168 D BluetoothAdapter: 298732497: getState() :  mService = null. Returning STATE_OFF
,09-07 12:05:27.841  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:27.841  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:27.841  1020  1424 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:27.841  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.841  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:27.841  1020  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 12:05:27.841  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:27.851  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:27.851  7352  7370 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-07 12:05:27.851  7352  7352 I GKI_LINUX: GKI_exit_task 1 done
09-07 12:05:27.851  7352  7352 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-07 12:05:27.851  7352  7352 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-07 12:05:27.851  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:27.851  7352  7352 I art     : System.exit called, status: 0
,09-07 12:05:27.851  7352  7352 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-07 12:05:27.851  1020  1033 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 12:05:27.851  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.851  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:27.851  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:27.851  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-07 12:05:27.861  1367  1367 D DockEventReceiver: finishStartingService: stopping service
,09-07 12:05:27.861  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:27.871  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:27.871  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-07 12:05:27.951  1020  1482 I ActivityManager: Process com.android.bluetooth (pid 7352)(adj 0) has died(42,723)
,09-07 12:05:27.961  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:27.961  1020  1368 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:27.961  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 12:05:27.971  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:27.971  1020  1368 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 12:05:27.971  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:27.981  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:27.981  1989  7487 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 12:05:28.071  1989  2156 I art     : Explicit concurrent mark sweep GC freed 37759(2MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 11MB/18MB, paused 1.359ms total 88.468ms
,09-07 12:05:28.071  1020  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:28.081  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:28.081  1020  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:28.081  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:28.091  1020  1033 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-07 12:05:28.091  1020  1033 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,09-07 12:05:28.091  1020  1033 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,09-07 12:05:28.091  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-07 12:05:28.091  1020  1033 D BatteryService: stay LED for fully charged
,09-07 12:05:28.091  1989  7487 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-07 12:05:28.091  1020  1020 I MotionRecognitionService: Plugged
,09-07 12:05:28.091  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 12:05:28.091  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 12:05:28.091  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 12:05:28.101  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 12:05:28.101  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 12:05:28.121  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:28.121  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:28.121  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:28.121  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,09-07 12:05:28.121  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 12:05:28.641   289   289 E SMD     : DCD OFF
,09-07 12:05:29.661  1020  1052 I PowerManagerService: [PWL] Off : 75s ago
,09-07 12:05:29.661  1020  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-07 12:05:29.661  1020  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-07 12:05:29.661  1020  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1020, ws=null) (elapsedTime=14320)
,09-07 12:05:29.911  1020  1309 E Watchdog: !@Sync 4
,09-07 12:05:30.031  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:30.031  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:30.651   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:31.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:31.641   289   289 E SMD     : DCD OFF
,09-07 12:05:32.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:33.031  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:33.031  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2606410f added. We now have 6 listener(s)
09-07 12:05:33.031  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:33.031  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:33.031  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3916759c added. We now have 7 listener(s)
09-07 12:05:33.031  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:33.031  6753  6806 I System.out: IsBluetoothEnabled
09-07 12:05:33.031  6753  6806 D BluetoothAdapter: disable()
,09-07 12:05:33.031  1020  1033 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-07 12:05:33.041  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:33.041  6753  6806 D BluetoothAdapter: enable()
,09-07 12:05:33.041  1020  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,09-07 12:05:33.041  1020  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
09-07 12:05:33.041  1020  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 12:05:33.041  1020  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-07 12:05:33.041  1020  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:33.051  1020  1480 D SettingsProvider: name = bluetooth_on
,09-07 12:05:33.061  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:33.061  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:33.071  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
09-07 12:05:33.071  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
09-07 12:05:33.071  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:33.071  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:33.071  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:33.071  1020  1049 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:33.091  7495  7495 E Zygote  : MountEmulatedStorage(),
,09-07 12:05:33.091  7495  7495 E Zygote  : v2,
09-07 12:05:33.091  7495  7495 I libpersona: KNOX_SDCARD checking this for 1002
09-07 12:05:33.091  7495  7495 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:33.091  1020  1049 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7495 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-07 12:05:33.091  7495  7495 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:33.101  7495  7495 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:33.101  7495  7495 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:33.131  7495  7495 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:33.131  7495  7495 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:33.151  7495  7495 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-07 12:05:33.151  7495  7495 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-07 12:05:33.171  7495  7495 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding GattService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding HeadsetService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding A2dpService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding HidService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding HealthService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding PanService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding SapService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding HeadsetClientService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding SapClientService
,09-07 12:05:33.211  7495  7495 D BtSettings.ProfileConfig: Adding HidDevService
,09-07 12:05:33.221  7495  7495 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-07 12:05:33.221  1020  1081 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-07 12:05:33.221  1020  1081 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.221  1020  1081 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:33.221  1020  1081 D SettingsProvider: selectionArgs: false
09-07 12:05:33.221  1020  1081 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:33.221  1020  1081 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.221  1020  1081 D SettingsProvider: ret = -1
,09-07 12:05:33.221  1020  1032 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-07 12:05:33.221  1020  1032 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.221  1020  1032 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.221  1020  1032 D SettingsProvider: selectionArgs: false
09-07 12:05:33.221  1020  1032 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.221  1020  1032 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.221  1020  1032 D SettingsProvider: ret = -1
,09-07 12:05:33.221  1020  1033 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-07 12:05:33.221  1020  1033 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.221  1020  1033 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.221  1020  1033 D SettingsProvider: selectionArgs: false
09-07 12:05:33.221  1020  1033 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.221  1020  1033 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.221  1020  1033 D SettingsProvider: ret = -1
,09-07 12:05:33.221  1020  1499 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-07 12:05:33.221  1020  1499 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 12:05:33.221  1020  1499 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.221  1020  1499 D SettingsProvider: selectionArgs: false
09-07 12:05:33.221  1020  1499 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.221  1020  1499 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.221  1020  1499 D SettingsProvider: ret = -1
,09-07 12:05:33.221  1020  1500 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-07 12:05:33.221  1020  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.221  1020  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:33.221  1020  1500 D SettingsProvider: selectionArgs: false
09-07 12:05:33.221  1020  1500 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.221  1020  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.221  1020  1500 D SettingsProvider: ret = -1
,09-07 12:05:33.221  1020  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
09-07 12:05:33.221  1020  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1477 D SettingsProvider: selectionArgs: false
09-07 12:05:33.231  1020  1477 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:33.231  1020  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1477 D SettingsProvider: ret = -1
,09-07 12:05:33.231  1020  1480 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:33.231  1020  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1480 D SettingsProvider: selectionArgs: false
09-07 12:05:33.231  1020  1480 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:33.231  1020  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1480 D SettingsProvider: ret = -1
,09-07 12:05:33.231  1020  1588 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-07 12:05:33.231  1020  1588 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1588 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.231  1020  1588 D SettingsProvider: selectionArgs: false
09-07 12:05:33.231  1020  1588 D SettingsProvider: selectionArgs: 1002,
,09-07 12:05:33.231  1020  1588 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.231  1020  1588 D SettingsProvider: ret = -1,
09-07 12:05:33.231  1020  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService,
09-07 12:05:33.231  1020  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1481 D SettingsProvider: selectionArgs: false
09-07 12:05:33.231  1020  1481 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.231  1020  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.231  1020  1481 D SettingsProvider: ret = -1
,09-07 12:05:33.231  1020  1368 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:33.231  1020  1368 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1368 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.231  1020  1368 D SettingsProvider: selectionArgs: false
,09-07 12:05:33.231  1020  1368 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.231  1020  1368 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.231  1020  1368 D SettingsProvider: ret = -1
09-07 12:05:33.231  1020  1424 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,09-07 12:05:33.231  1020  1424 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1424 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.231  1020  1424 D SettingsProvider: selectionArgs: false
09-07 12:05:33.231  1020  1424 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.231  1020  1424 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:33.231  1020  1424 D SettingsProvider: ret = -1
09-07 12:05:33.231  1020  1432 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-07 12:05:33.231  1020  1432 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.231  1020  1432 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.231  1020  1432 D SettingsProvider: selectionArgs: false,
09-07 12:05:33.231  1020  1432 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.231  1020  1432 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:33.231  1020  1432 D SettingsProvider: ret = -1
,09-07 12:05:33.251  7495  7495 D BluetoothAdapterState: make
,09-07 12:05:33.251  7495  7495 I bluedroid: init,
,09-07 12:05:33.251  7495  7510 I BluetoothAdapterState: Entering OffState
,09-07 12:05:33.261  7495  7495 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
09-07 12:05:33.261  7495  7495 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-07 12:05:33.261  7495  7495 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-07 12:05:33.261  7495  7495 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-07 12:05:33.261  7495  7495 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-07 12:05:33.261  7495  7495 I bluedroid: get_profile_interface socket,
09-07 12:05:33.261  7495  7495 I bluedroid: get_profile_interface map_client
09-07 12:05:33.261  7495  7513 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-07 12:05:33.261  7495  7513 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
09-07 12:05:33.261  7495  7513 E BluetoothServiceJni: populateRssiValuesNative
09-07 12:05:33.261  7495  7513 I bluedroid: getModelRssiValues
09-07 12:05:33.261  7495  7513 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-07 12:05:33.261  7495  7513 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 12:05:33.261  7495  7495 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-07 12:05:33.261  1020  1020 D SettingsProvider: name = bluetooth_name
,09-07 12:05:33.261  7495  7513 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 12:05:33.271  7495  7495 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:33.271  1020  1368 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 12:05:33.271  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.271  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.271  1020  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.271  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.271  7495  7506 I bluedroid: config_hci_snoop_log
,09-07 12:05:33.271  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-07 12:05:33.281  1020  1049 D BluetoothManagerService: Ble is always on enable gatt
,09-07 12:05:33.281  1020  1049 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-07 12:05:33.281  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-07 12:05:33.281  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 12:05:33.281  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:33.281  7495  7495 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
09-07 12:05:33.281  1020  1049 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-07 12:05:33.291  1020  1049 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-07 12:05:33.291  1020  1049 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-07 12:05:33.291  7495  7510 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-07 12:05:33.291  7495  7510 D BluetoothAdapterProperties: Setting state to 11
09-07 12:05:33.291  7495  7510 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-07 12:05:33.291  7495  7510 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-07 12:05:33.291  7495  7510 D BluetoothAdapterService: updateAdapterState state is 11
,09-07 12:05:33.291  7495  7510 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:33.291  7495  7510 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-07 12:05:33.291  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:33.291  1020  1020 I InputMethodManagerService: [BT Setting State] State =11
,09-07 12:05:33.301  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
09-07 12:05:33.301  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-07 12:05:33.301  7495  7510 D BluetoothSecureManager: getInstant: null
09-07 12:05:33.301  1175  1175 D BluetoothTile:  getBluetoothState : 11
09-07 12:05:33.301  7495  7510 D BluetoothSecureManager: calling getMethod for getService
09-07 12:05:33.301  7495  7510 D BluetoothSecureManager: calling getService
,09-07 12:05:33.301  7495  7510 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1db331f8
09-07 12:05:33.301  1020  1481 D BluetoothSecureManagerService: isSecureModeEnabled
09-07 12:05:33.301  1020  1481 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-07 12:05:33.301  7495  7510 D BtConfig.SecureMode: isSecureModeOn:false
,09-07 12:05:33.301  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 12:05:33.301  1973  1973 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:33.301  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
,09-07 12:05:33.301  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-07 12:05:33.301  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-07 12:05:33.311  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:33.311  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.311  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-07 12:05:33.311  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:33.311  1020  1081 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:33.311  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:33.311  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 12:05:33.311  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-07 12:05:33.311  1020  1499 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:33.311  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 12:05:33.311  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-07 12:05:33.311  7495  7510 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-07 12:05:33.311  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-07 12:05:33.321  7495  7510 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:33.321  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:33.321  7495  7510 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:33.321  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-07 12:05:33.321  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-07 12:05:33.321  7495  7510 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:33.321  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-07 12:05:33.321  7495  7510 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-07 12:05:33.321  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:33.331  7495  7510 D BluetoothBondStateMachine: make
,09-07 12:05:33.331  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:33.331  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-07 12:05:33.331  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-07 12:05:33.331  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
09-07 12:05:33.331  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-07 12:05:33.331  7495  7517 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-07 12:05:33.341  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.341  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.341  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.341  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.341  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.341  1020  3369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 12:05:33.341  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-07 12:05:33.341  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-07 12:05:33.341  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-07 12:05:33.341  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.341  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.341  7495  7495 D BtGatt.DebugUtils: handleDebugAction() action=null
09-07 12:05:33.341  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.341  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.341  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.341  7495  7495 D BtGatt.GattService: Received start request. Starting profile...
,09-07 12:05:33.341  7495  7495 D BtGatt.GattService: start()
09-07 12:05:33.341  7495  7495 D BtGatt.GattService: start()
09-07 12:05:33.341  7495  7495 I bluedroid: get_profile_interface gatt
,09-07 12:05:33.341  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-07 12:05:33.341  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-07 12:05:33.341  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-07 12:05:33.341  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:33.341  7495  7495 D BtGatt.AdvertiseManager: advertise manager created
,09-07 12:05:33.351  1020  1424 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-07 12:05:33.351  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.351  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:33.351  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.351  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.351  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-07 12:05:33.351  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-07 12:05:33.351  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-07 12:05:33.351  1020  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.351  1020  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.361  1020  1481 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.361  1020  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.361  1020  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.361  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-07 12:05:33.361  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-07 12:05:33.361  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-07 12:05:33.361  7495  7495 D BtGatt.GattService: mStartError = false
09-07 12:05:33.361  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.361  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.361  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-07 12:05:33.361  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.361  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-07 12:05:33.361  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.361  7495  7495 D HeadsetService: Received start request. Starting profile...
09-07 12:05:33.361  7495  7495 D HeadsetService: start()
09-07 12:05:33.361  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-07 12:05:33.361  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-07 12:05:33.361  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-07 12:05:33.361  7495  7495 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-07 12:05:33.361  7495  7495 D HeadsetStateMachine: make
09-07 12:05:33.361  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.361  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.361  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:33.361  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.361  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.371  7495  7495 E HeadsetStateMachine: # of Max HF connection is 2
,09-07 12:05:33.371  1020  1032 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-07 12:05:33.371  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.371  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-07 12:05:33.371  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-07 12:05:33.371  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.371  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.371  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-07 12:05:33.371  7495  7510 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-07 12:05:33.381  1020  1588 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.381  1020  1588 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.381  1020  1588 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.381  1020  1588 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.381  1020  1588 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:33.381  1020  1477 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-07 12:05:33.381  1020  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.381  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-07 12:05:33.381  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-07 12:05:33.381  7495  7510 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-07 12:05:33.381  1020  1477 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.381  1020  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.381  1020  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-07 12:05:33.381  1020  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:33.381  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-07 12:05:33.381  7495  7495 I bluedroid: get_profile_interface handsfree
09-07 12:05:33.381  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:33.381  1020  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:33.381  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:33.381  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:33.381  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:33.381  7495  7510 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-07 12:05:33.381  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-07 12:05:33.391  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-07 12:05:33.391  7495  7510 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,09-07 12:05:33.391  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-07 12:05:33.391  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-07 12:05:33.391  7495  7510 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-07 12:05:33.391  7495  7510 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-07 12:05:33.391  7495  7510 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-07 12:05:33.391  7495  7510 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-07 12:05:33.391  7495  7510 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-07 12:05:33.401  7495  7495 I DualScoManager: Instantiating Dual Sco Manager
09-07 12:05:33.401  7495  7495 I DualScoManager: Set HeadsetServiceHelper
09-07 12:05:33.401  7495  7495 D BluetoothAtMessage: createCMTIContentObservers
,09-07 12:05:33.401  1020  1368 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-07 12:05:33.401  1020  1368 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:33.401  1020  1368 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:33.401  1020  1368 D SettingsProvider: selectionArgs: false
09-07 12:05:33.401  1020  1368 D SettingsProvider: selectionArgs: 1002
09-07 12:05:33.401  1020  1368 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:33.401  1020  1368 D SettingsProvider: ret = -1
,09-07 12:05:33.401  7495  7523 D HeadsetStateMachine: Enter Disconnected: -2
,09-07 12:05:33.401  7495  7495 D HeadsetService: mStartError = false
09-07 12:05:33.401  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.411  7495  7523 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-07 12:05:33.411  7495  7523 D HeadsetStateMachine: map size, before remove : 0
09-07 12:05:33.411  7495  7523 D HeadsetStateMachine: map size, after remove: 0
,09-07 12:05:33.411  7495  7495 D A2dpService: Received start request. Starting profile...
,09-07 12:05:33.411  7495  7495 D A2dpService: start()
,09-07 12:05:33.411  7495  7495 I BluetoothAvrcpServiceJni: classInitNative: succeeds,
,09-07 12:05:33.411  7495  7495 I bluedroid: get_profile_interface avrcp
,09-07 12:05:33.421  7495  7495 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-07 12:05:33.421  7495  7495 D Avrcp   : Initialize Media Controller
09-07 12:05:33.421  7495  7495 D Avrcp   : Get the Context Package Name: com.android.bluetooth
09-07 12:05:33.421  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:33.421  7495  7495 E Avrcp   : getActiveSessions
09-07 12:05:33.421  7495  7495 D Avrcp   : pick active media Controller
09-07 12:05:33.421  7495  7495 D Avrcp   : Get the active Media Controller 
,09-07 12:05:33.431  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:33.441  7495  7495 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-07 12:05:33.441  7495  7524 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-07 12:05:33.441  7495  7495 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-07 12:05:33.441  7495  7495 D A2dpStateMachine: make
,09-07 12:05:33.441  7495  7495 I bluedroid: get_profile_interface a2dp
,09-07 12:05:33.441  7495  7526 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-07 12:05:33.441  7495  7495 E bt-btif : warning : media task started media_task_refcnt 1 
,09-07 12:05:33.441  7495  7495 D A2dpService: mStartError = false
09-07 12:05:33.441  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.441  7495  7525 D A2dpStateMachine: Enter Disconnected: -2
,09-07 12:05:33.451  7495  7495 I BluetoothHidServiceJni: classInitNative: succeeds,
,09-07 12:05:33.451  7495  7495 D HidService: Received start request. Starting profile...
09-07 12:05:33.451  7495  7495 D HidService: start()
09-07 12:05:33.451  7495  7495 I bluedroid: get_profile_interface hidhost
09-07 12:05:33.451  7495  7495 D HidService: setHidService(): set to: null
09-07 12:05:33.451  7495  7495 D HidService: mStartError = false
09-07 12:05:33.451  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.451  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-07 12:05:33.451  7495  7495 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-07 12:05:33.451  7495  7495 D HealthService: Received start request. Starting profile...
09-07 12:05:33.451  7495  7495 D HealthService: start()
,09-07 12:05:33.461  7495  7524 D BluetoothMediaBrowser: no now playing list
,09-07 12:05:33.461  7495  7524 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-07 12:05:33.461  7495  7495 I bluedroid: get_profile_interface health
09-07 12:05:33.461  7495  7495 D HealthService: mStartError = false
09-07 12:05:33.461  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.461  7495  7495 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-07 12:05:33.461  7495  7495 D PanService: Received start request. Starting profile...
,09-07 12:05:33.461  7495  7495 D PanService: start()
09-07 12:05:33.461  7495  7495 D BluetoothPanServiceJni: initializeNative(L110): pan
,09-07 12:05:33.461  7495  7495 I bluedroid: get_profile_interface pan
,09-07 12:05:33.461  7495  7495 D PanService: mStartError = false
,09-07 12:05:33.461  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:33.471  7495  7495 D HeadsetStateMachine: Try to query the phonestate on bind
,09-07 12:05:33.471  1425  3275 I Telecom : BluetoothPhoneService: queryPhoneState
,09-07 12:05:33.471  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-07 12:05:33.471  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-07 12:05:33.471  1425  3275 I Telecom : BluetoothPhoneService: Result of Message : true
,09-07 12:05:33.471  7495  7495 D BluetoothMapService: Received start request. Starting profile...
,09-07 12:05:33.471  7495  7495 D BluetoothMapService: start()
,09-07 12:05:33.471  7495  7495 D BluetoothMapService: mStartError = false
,09-07 12:05:33.471  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:33.471  7495  7495 D HeadsetStateMachine: Proxy object connected
,09-07 12:05:33.471  7495  7495 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-07 12:05:33.481  7495  7495 D SapService: Received start request. Starting profile...
,09-07 12:05:33.481  7495  7495 D SapService: start()
09-07 12:05:33.481  7495  7495 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-07 12:05:33.481  7495  7495 I bluedroid: get_profile_interface sap
09-07 12:05:33.481  7495  7495 D SapService: mStartError = false
09-07 12:05:33.481  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:33.481  7495  7495 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-07 12:05:33.481  7495  7495 D HeadsetPhoneState: sendDeviceDataStateChanged
09-07 12:05:33.481  7495  7495 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-07 12:05:33.481  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-07 12:05:33.481  7495  7495 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 12:05:33.481  7495  7495 D BluetoothA2dp: Proxy object connected
09-07 12:05:33.481  7495  7495 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-07 12:05:33.481  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-07 12:05:33.481  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-07 12:05:33.481  7495  7523 D HeadsetStateMachine: Disconnected process message: 11
09-07 12:05:33.481  7495  7523 D HeadsetStateMachine: Disconnected process message: 18
09-07 12:05:33.481  7495  7523 D HeadsetStateMachine: Disconnected process message: 10
09-07 12:05:33.481  7495  7523 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-07 12:05:33.481  7495  7523 D HeadsetStateMachine: Disconnected process message: 11
,09-07 12:05:33.481  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-07 12:05:33.481  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-07 12:05:33.511  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-07 12:05:33.511  7495  7495 E BluetoothAdapterService(1063005458): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-07 12:05:33.511  7495  7510 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-07 12:05:33.511  7495  7510 I bluedroid: enable
,09-07 12:05:33.511  7495  7510 I bt_hci_bdroid: init
,09-07 12:05:33.511  7495  7510 I bt_vendor: bt-vendor : init
,09-07 12:05:33.511  7495  7510 I bt_vendor: bt-vendor : get_bt_soc_type
09-07 12:05:33.511  7495  7510 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-07 12:05:33.511  7495  7510 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
09-07 12:05:33.511  7495  7510 D bt_userial_mct: userial_init
,09-07 12:05:33.511  7495  7530 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
09-07 12:05:33.511  7495  7510 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-07 12:05:33.511  7495  7510 I bt_vendor: Starting hciattach daemon
09-07 12:05:33.511  7495  7510 I bt_vendor: try to set false
,09-07 12:05:33.521  7495  7510 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-07 12:05:33.521  7495  7510 I bt_vendor: Starting hciattach daemon
09-07 12:05:33.521  7495  7510 I bt_vendor: try to set true
,09-07 12:05:33.541  7534  7534 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-07 12:05:33.581  7540  7540 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-07 12:05:33.591  7541  7541 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 12:05:33.601  7543  7543 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 12:05:33.611  7544  7544 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-07 12:05:33.621  7545  7545 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-07 12:05:33.631  7546  7546 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-07 12:05:33.641   315   315 I ServiceManager: Waiting for service AtCmdFwd...,
,09-07 12:05:33.821  7549  7549 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,09-07 12:05:33.831  7550  7550 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-07 12:05:33.881  7495  7510 I bt_vendor: bluetooth satus is on,
09-07 12:05:33.881  7495  7532 D bt_userial_mct: userial_open(port:0)
09-07 12:05:33.881  7495  7532 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
09-07 12:05:33.881  7495  7532 I bt_vendor: Done intiailizing UART
,09-07 12:05:33.881  7495  7532 I bt_vendor: Done intiailizing UART
09-07 12:05:33.881  7495  7532 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
09-07 12:05:33.881  7495  7532 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-07 12:05:33.891  7495  7552 D bt_userial_mct: Entering userial_read_thread()
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_HCI
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_AVDT
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_AVRC
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_A2D
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_BNEP
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_BTM
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_GAP
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_PAN
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_SAP
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_SDP
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_GATT
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_SMP
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-07 12:05:33.891  7495  7530 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-07 12:05:33.991  7495  7530 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-07 12:05:33.991  7495  7530 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa425ced1 
,09-07 12:05:33.991  7495  7530 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa425ced1 
,09-07 12:05:34.011  7495  7513 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-07 12:05:34.011  7495  7513 E bt-btif : Calling BTA_HhEnable
,09-07 12:05:34.011  7495  7513 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-07 12:05:34.011  7495  7513 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,09-07 12:05:34.011  7495  7513 E BluetoothServiceJni: populateRssiValuesNative
09-07 12:05:34.011  7495  7513 I bluedroid: getModelRssiValues
,09-07 12:05:34.011  7495  7513 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-07 12:05:34.011  7495  7513 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-07 12:05:34.021  7495  7513 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,09-07 12:05:34.021  1020  1020 D SettingsProvider: name = bluetooth_name
,09-07 12:05:34.021  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:34.021  7495  7513 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-07 12:05:34.021  7495  7513 D BluetoothAdapterProperties: Scan Mode:20
,09-07 12:05:34.021  7495  7513 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:34.031  7495  7513 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
09-07 12:05:34.031  7495  7513 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-07 12:05:34.031  7495  7513 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-07 12:05:34.031  7495  7513 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-07 12:05:34.031  7495  7513 E bt-btif : btif_sock_init: !vhci_init
,09-07 12:05:34.031  7495  7513 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-07 12:05:34.031  7495  7513 D IOP_DB_BT: db_open: db_open : handle 2963312656l, read 13894 bytes onto local cache
09-07 12:05:34.031  7495  7513 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-07 12:05:34.031  7495  7513 D IOP_DB_BT: db_query: result 1
09-07 12:05:34.031  7495  7513 I         : iop_db_open: iop_db_open status 0
09-07 12:05:34.031  7495  7513 D bte_conf: Device ID record 1 : primary
,09-07 12:05:34.031  7495  7513 D bte_conf:   vendorId            = 0075
09-07 12:05:34.031  7495  7513 D bte_conf:   vendorIdSource      = 0001
09-07 12:05:34.031  7495  7513 D bte_conf:   product             = 0100
09-07 12:05:34.031  7495  7513 D bte_conf:   version             = 0200
09-07 12:05:34.031  7495  7513 D bte_conf:   clientExecutableURL = 
09-07 12:05:34.031  7495  7513 D bte_conf:   serviceDescription  = 
09-07 12:05:34.031  7495  7513 D bte_conf:   documentationURL    = 
09-07 12:05:34.031  7495  7513 D bte_conf: bte_load_did_conf no section named DID2.
09-07 12:05:34.031  7495  7513 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-07 12:05:34.031  7495  7510 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-07 12:05:34.031  7495  7510 D BluetoothAdapterProperties: ScanMode =  20
09-07 12:05:34.031  7495  7510 D BluetoothAdapterProperties: State =  11
,09-07 12:05:34.031  1020  1482 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-07 12:05:34.031  7495  7552 E bt_mct  : hci lib postload completed
,09-07 12:05:34.031  7495  7510 D BluetoothAdapterProperties: Setting state to 12
,09-07 12:05:34.041  7495  7510 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-07 12:05:34.041  7495  7513 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-07 12:05:34.041  7495  7513 D BluetoothAdapterProperties: Scan Mode:21
09-07 12:05:34.041  7495  7513 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-07 12:05:34.041  1020  1500 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-07 12:05:34.041  1020  1500 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-07 12:05:34.041  1020  1500 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:34.041  1020  1500 D SettingsProvider: selectionArgs: false
09-07 12:05:34.041  1020  1500 D SettingsProvider: selectionArgs: 1002
,09-07 12:05:34.041  1020  1500 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-07 12:05:34.051  1020  1500 D SettingsProvider: ret = -1
,09-07 12:05:34.051  7495  7510 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-07 12:05:34.051  7495  7510 D BluetoothAdapterService: updateAdapterState state is 12
,09-07 12:05:34.051  1020  1500 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:34.051  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.051  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.051  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.051  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:34.051  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:34.061  7495  7510 D BluetoothAdapterService: Autoconnection is available 
09-07 12:05:34.061  1020  1424 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:34.061  7495  7510 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-07 12:05:34.061  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-07 12:05:34.061  7495  7510 D BluetoothAdapterService: starting service from this receiver
09-07 12:05:34.061  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 12:05:34.061  1425  6888 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.061  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 12:05:34.061  1425  6888 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.061  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.061  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.061  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-07 12:05:34.061  7495  7510 I BluetoothAdapterState: Entering On State from state = 11
09-07 12:05:34.061  1989  2164 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.061  1989  2164 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.061  1367  1384 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.061  1367  1384 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.061  1020  1049 D BluetoothA2dp: onBluetoothStateChange: up=true
09-07 12:05:34.061  1020  1049 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-07 12:05:34.071  1020  1020 D BluetoothA2dp: Proxy object connected
,09-07 12:05:34.071  1367  6906 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.071  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:34.071  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:34.071  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:34.071  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.071  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.071  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.071  1367  6906 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.071  1449  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.071  1449  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:34.081  1425  1453 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.081  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 12:05:34.081  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:34.081  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.081  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.081  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.081  1425  1453 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.091  7495  7506 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:34.091  7495  7515 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.091  7495  7515 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:34.091  1367  1378 D BluetoothMap: onBluetoothStateChange: up=true
,09-07 12:05:34.091  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-07 12:05:34.091  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.091  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.091  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.091  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.091  1367  1384 D Bluetoothsap: onBluetoothStateChange: up=true
09-07 12:05:34.091  1367  1384 D Bluetoothsap: Binding service...
,09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:34.091  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:34.091  1367  1384 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-07 12:05:34.091  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-07 12:05:34.091  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-07 12:05:34.101  7495  7495 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-07 12:05:34.101  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.101  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.101  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.101  1367  1384 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-07 12:05:34.101  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:34.101  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:34.101  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@390dcba5 added. We now have 8 listener(s)
09-07 12:05:34.101  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:34.101  1425  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.111  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:34.111  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:34.111  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.111  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.111  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.111  1425  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.111  1020  1049 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.111  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:34.111  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-07 12:05:34.111  1020  1049 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.111  1367  6906 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-07 12:05:34.111  7495  7495 I BluetoothPbapService: Handler(): got msg=1
09-07 12:05:34.111  1020  1033 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 12:05:34.111  1020  1033 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:34.111  1020  1033 D SecContentProvider2: mCursor = null
,09-07 12:05:34.111  1020  1500 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-07 12:05:34.111  1020  1033 D WifiService: setWifiEnabled: false pid=6753, uid=10171
,09-07 12:05:34.111  1020  1033 D SettingsProvider: name = wifi_on
,09-07 12:05:34.111  1367  1367 D HeadsetProfile: Bluetooth service connected
,09-07 12:05:34.111  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-07 12:05:34.111  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.121  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.121  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.121  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.121  1367  1378 D BluetoothPan: Binding service...
,09-07 12:05:34.121  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 12:05:34.121  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.121  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.121  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.121  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.131  7495  7558 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-07 12:05:34.131  1175  1195 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 12:05:34.131  1175  1195 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.131  7402  7411 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-07 12:05:34.131  7402  7411 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.131  1367  1367 D BluetoothMap: Proxy object connected
09-07 12:05:34.131  1367  1367 D MapProfile: Bluetooth service connected
09-07 12:05:34.131  1367  1367 D BluetoothMap: getConnectedDevices()
09-07 12:05:34.131  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:34.131  1020  1049 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.131  1020  1049 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-07 12:05:34.131  1367  6906 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-07 12:05:34.131  7495  7558 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 12:05:34.131  1020  1477 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-07 12:05:34.131  7495  7558 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-07 12:05:34.131  1020  1477 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-07 12:05:34.131  1020  1477 D SecContentProvider2: mCursor = null
,09-07 12:05:34.131  1367  6906 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.131  7495  7558 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
09-07 12:05:34.131  7495  7558 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:34.131  7495  7558 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 12:05:34.131  7495  7558 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c46a19c
09-07 12:05:34.131  7495  7558 D BluetoothSocket: channel: 19
09-07 12:05:34.131  7495  7558 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-07 12:05:34.131  1367  1367 D Bluetoothsap: BluetoothSAP Proxy object connected
09-07 12:05:34.131  1367  1367 D SapProfile: Bluetooth service connected
09-07 12:05:34.131  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-07 12:05:34.131  1367  1367 D Bluetoothsap: getConnectedDevices()
09-07 12:05:34.131  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-07 12:05:34.131  1020  1477 D WifiService: setWifiEnabled: true pid=6753, uid=10171
,09-07 12:05:34.141  1020  1477 W WifiService: Failed getting userId using ActivityManagerNative
09-07 12:05:34.141  1020  1477 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:34.141  1020  1477 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
09-07 12:05:34.141  1020  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-07 12:05:34.141  1020  1477 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-07 12:05:34.141  1020  1477 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-07 12:05:34.141  1020  1477 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-07 12:05:34.141  1020  1477 W ActivityManager: Permission Denial: getCurrentUser() from pid=6753, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
09-07 12:05:34.141  1020  1477 D SettingsProvider: name = wifi_on
09-07 12:05:34.141  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.141  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.141  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.141  1438  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.141  1438  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.141  1367  1384 D BluetoothPbap: onBluetoothStateChange: up=true
,09-07 12:05:34.141  1020  1049 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-07 12:05:34.141  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.141  1367  1367 D BluetoothInputDevice: Proxy object connected
09-07 12:05:34.141  1367  1367 D HidProfile: Bluetooth service connected
09-07 12:05:34.141  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.141  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.141  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.141  1020  1131 E WifiHW  : ##################### set firmware type 0 #####################
,09-07 12:05:34.151  1367  1367 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 12:05:34.151  1367  1367 D PanProfile: Bluetooth service connected
09-07 12:05:34.151  1449  1478 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.151  1020  1049 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-07 12:05:34.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:34.151  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.151  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.151  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.151  1367  1367 D BluetoothA2dp: Proxy object connected
09-07 12:05:34.151  1449  1478 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.151  1367  1367 D A2dpProfile: Bluetooth service connected
09-07 12:05:34.151  6753  6762 D BluetoothAdapter: onBluetoothStateChange: up=true
09-07 12:05:34.151  6753  6762 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-07 12:05:34.151  1020  1049 D BluetoothPan: Binding service...
,09-07 12:05:34.151  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-07 12:05:34.151  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.151  1020  1020 D BluetoothPan: BluetoothPAN Proxy object connected
,09-07 12:05:34.161  1425  1463 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-07 12:05:34.161  1020  1049 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-07 12:05:34.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-07 12:05:34.161  1020  1049 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.161  1020  1049 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.161  1020  1049 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.161  1425  1463 E BluetoothHeadset: BluetoothHeadset service is binded
,09-07 12:05:34.161  1020  1049 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-07 12:05:34.161  1020  1049 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-07 12:05:34.161  1020  1020 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:34.161  1020  1020 I InputMethodManagerService: [BT Setting State] State =12
09-07 12:05:34.161  1020  1020 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-07 12:05:34.171  1425  1425 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@189b41b1, true
,09-07 12:05:34.171  1425  1425 D BluetoothHeadset: registerMessageListener
,09-07 12:05:34.171  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,09-07 12:05:34.171  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-07 12:05:34.181  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-07 12:05:34.181  1175  1175 D BluetoothTile:  getBluetoothState : 12
,09-07 12:05:34.181  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null,
,09-07 12:05:34.181  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:34.181  1973  1973 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-07 12:05:34.181  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
,09-07 12:05:34.181  1020  1499 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-07 12:05:34.191  1020  1368 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-07 12:05:34.191  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-07 12:05:34.191  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-07 12:05:34.191  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.191  7495  7506 D HeadsetService: registerMessageListener
,09-07 12:05:34.191  7495  7506 D HeadsetService: registerMessageListener
09-07 12:05:34.191  1367  1367 D BluetoothPbap: Proxy object connected
09-07 12:05:34.191  1367  1367 D PbapServerProfile: Bluetooth service connected
09-07 12:05:34.191  1367  1367 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:34.191  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.191  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:34.191  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:34.191  1425  1425 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-07 12:05:34.191  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-07 12:05:34.191  7495  7523 D HeadsetStateMachine: Disconnected process message: 70
,09-07 12:05:34.191  1175  1668 D BluetoothTile:  handleUpdatestate:false name:null
09-07 12:05:34.191  7495  7523 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@19f887a5
,09-07 12:05:34.191  1367  1367 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,09-07 12:05:34.191  7495  7561 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-07 12:05:34.191  1367  1367 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-07 12:05:34.191  1367  1367 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-07 12:05:34.191  1367  1367 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-07 12:05:34.201  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-07 12:05:34.201  1425  1425 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-07 12:05:34.201  1425  1425 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-07 12:05:34.201  7495  7561 D BluetoothSocket: bindListen(): myUserId = 0
09-07 12:05:34.201  7495  7561 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:34.201  7495  7523 D HeadsetStateMachine: Disconnected process message: 9
,09-07 12:05:34.201  7495  7523 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-07 12:05:34.201  7495  7561 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
,09-07 12:05:34.201  7495  7561 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:34.201  7495  7561 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-07 12:05:34.201  1020  2046 V SAMP_SPCM_test: CSC File load.. 
09-07 12:05:34.201  7495  7561 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16c4377a
,09-07 12:05:34.201  7495  7561 D BluetoothSocket: channel: 5
,09-07 12:05:34.211  1367  1367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-07 12:05:34.211   284   284 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-07 12:05:34.211   284   284 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-07 12:05:34.211   284   284 V voice   : voice_set_parameters: exit with code(-2)
,09-07 12:05:34.211   284   284 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-07 12:05:34.211   284   284 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-07 12:05:34.211   284   284 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-07 12:05:34.211   284   284 V audio_hw_primary: adev_set_parameters: exit
,09-07 12:05:34.221  7495  7523 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-07 12:05:34.221  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-07 12:05:34.251  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-07 12:05:34.261  1020  2046 ,W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
09-07 12:05:34.261  1020  2046 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
09-07 12:05:34.261  1020  1368 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-07 12:05:34.261  1020  1368 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
09-07 12:05:34.261  1020  1368 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.261  1020  1368 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.261  1020  1368 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-07 12:05:34.271  1020  2046 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
09-07 12:05:34.271  1020  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:34.271  1020  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:34.271  1020  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:34.271  1020  2046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:34.281  7564  7564 E Zygote  : MountEmulatedStorage()
09-07 12:05:34.281  7564  7564 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:34.281  7564  7564 E Zygote  : v2
09-07 12:05:34.281  7564  7564 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:34.281  7564  7564 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:34.281  1020  2046 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7564 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 12:05:34.281  7564  7564 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:34.291  7564  7564 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 12:05:34.291  1367  1367 D DockEventReceiver: finishStartingService: stopping service
09-07 12:05:34.291  1367  1367 D BluetoothNotiBroadcastReceiver: onReceive
,09-07 12:05:34.301  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-07 12:05:34.301  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-07 12:05:34.311  7495  7495 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
,09-07 12:05:34.311  7495  7495 D BtConfig.SecureMode: isSecureModeOn:false,
,09-07 12:05:34.311  7564  7564 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:34.311  1020  1482 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-07 12:05:34.311  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.321  7564  7564 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:34.321  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.321  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.321  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-07 12:05:34.341  1989  1989 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-07 12:05:34.341  1020  1424 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-07 12:05:34.341  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-07 12:05:34.341  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.341  1020  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:34.341  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:34.341  7564  7564 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-07 12:05:34.351  1020  1432 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-07 12:05:34.371  1989  7584 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-07 12:05:34.371  1989  1989 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-07 12:05:34.381  7495  7586 D BluetoothSocket: bindListen(): myUserId = 0
,09-07 12:05:34.381  7495  7586 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-07 12:05:34.391  7495  7586 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,09-07 12:05:34.391  7495  7586 D BluetoothSocket: bindListen(), new LocalSocket 
09-07 12:05:34.391  7495  7586 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,09-07 12:05:34.391  7495  7586 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ab8834
,09-07 12:05:34.391  7495  7586 D BluetoothSocket: channel: 12
09-07 12:05:34.391  7495  7586 I BtOppRfcommListener: Accept thread started.
,09-07 12:05:34.521  1020  1480 I art     : Explicit concurrent mark sweep GC freed 28542(1619KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.556ms total 144.840ms
09-07 12:05:34.521  1020  1480 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:34.521  1020  1047 D Tethering: interfaceAdded wlan0,
09-07 12:05:34.521  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:34.521  1020  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-07 12:05:34.521  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-07 12:05:34.521  1020  1134 E Tethering: No numeric data
09-07 12:05:34.531  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:34.531  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:34.531  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:34.531  1020  1047 D Tethering: interfaceAdded p2p0
,09-07 12:05:34.531   279   995 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,09-07 12:05:34.531  1020  1047 D Tethering: p2p0 is not a tetherable iface, ignoring
09-07 12:05:34.531   279   995 D SoftapController: Softap fwReload - Ok
,09-07 12:05:34.531  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:34.531  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-07 12:05:34.531  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 12:05:34.541  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 12:05:34.541  1020  1134 D Tethering: clearTetheredNotification()
09-07 12:05:34.541  1020  1134 D Tethering: InitialState.processMessage what=4
,09-07 12:05:34.541   279   995 D CommandListener: Setting iface cfg
09-07 12:05:34.541   279   995 D CommandListener: Trying to bring down wlan0
,09-07 12:05:34.541   279   995 D CommandListener: Clearing all IP addresses on wlan0,
09-07 12:05:34.541  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:34.541  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:34.541  1020  1134 E Tethering: No numeric data
09-07 12:05:34.541  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:34.541  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:34.551  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:34.551  1175  1175 D HotspotTile: updateTetherState():false, false
,09-07 12:05:34.551  1020  1128 V NetworkStats: performPollLocked() took 5ms
09-07 12:05:34.551  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.551  1020  1131 E WifiHW  : supplicant_name : p2p_supplicant
,09-07 12:05:34.551  1020  1131 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-07 12:05:34.551  1020  1131 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
09-07 12:05:34.561  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:34.561  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-07 12:05:34.561  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:34.561  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:34.561  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:34.561  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:34.561  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:34.561  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:34.561  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-07 12:05:34.561  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-07 12:05:34.561  1175  1175 D HotspotTile: onReceive : 2, 0
,09-07 12:05:34.571  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:34.571  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:34.571  1020  1134 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,09-07 12:05:34.571  1020  1424 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-07 12:05:34.571  1020  1134 D Tethering: clearTetheredNotification()
,09-07 12:05:34.571  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.571  1020  1424 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-07 12:05:34.571  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-07 12:05:34.581  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.581  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.581  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-07 12:05:34.581  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.581  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:34.591  1020  1500 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:34.591  1020  1500 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:34.591  1020  1500 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-07 12:05:34.591  1020  1500 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:34.591  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-07 12:05:34.591  1020  1500 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:34.591  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 12:05:34.591  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:34.591  1020  2046 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-07 12:05:34.591  1602  1602 I Hs20UtilService: Starting #19
,09-07 12:05:34.591  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:34.591  1989  7584 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
09-07 12:05:34.591  1020  1128 V NetworkStats: performPollLocked() took 10ms
09-07 12:05:34.591  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.601  7594  7594 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-07 12:05:34.601  7594  7594 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-07 12:05:34.601  7594  7594 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-07 12:05:34.601  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:34.601  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:34.601  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 12:05:34.601  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:34.601  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
09-07 12:05:34.601  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-07 12:05:34.611  7594  7594 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,09-07 12:05:34.611   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7594
09-07 12:05:34.611   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,09-07 12:05:34.611  7594  7594 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-07 12:05:34.611  7594  7594 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:34.611  7594  7594 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-07 12:05:34.611  7594  7594 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-07 12:05:34.611   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7594
09-07 12:05:34.611   367   367 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-07 12:05:34.641   289   289 E SMD     : DCD OFF
,09-07 12:05:34.651   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,09-07 12:05:34.751   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-07 12:05:34.751  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-07 12:05:34.801  7594  7594 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-07 12:05:34.801  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-07 12:05:34.811  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 12:05:34.811   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7594
09-07 12:05:34.811   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 12:05:34.811  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 12:05:34.811  7594  7594 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:34.811  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-07 12:05:34.811  7594  7594 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:34.811  7594  7594 E wpa_supplicant: SIM READ ERROR
09-07 12:05:34.811  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:34.811  7594  7594 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:34.811  7594  7594 E wpa_supplicant: SIM READ ERROR
09-07 12:05:34.811  7594  7594 I wpa_supplicant: Blacklist: Clear (all) 
09-07 12:05:34.811  7594  7594 I wpa_supplicant: wpa_default_ap_write_once
09-07 12:05:34.811  7594  7594 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-07 12:05:34.811  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-07 12:05:34.811  7594  7594 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-07 12:05:34.811  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:34.811  7594  7594 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-07 12:05:34.811  7594  7594 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
09-07 12:05:34.811  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
09-07 12:05:34.811  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:34.811  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 12:05:34.921  7594  7594 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-07 12:05:35.031  1020  3356 D SSRM:n  : SIOP:: AP = 310,
,09-07 12:05:35.081  7594  7594 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-07 12:05:35.081  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-07 12:05:35.091  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-07 12:05:35.091   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7594
,09-07 12:05:35.091   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-07 12:05:35.101  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 12:05:35.101  7594  7594 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:35.101  7594  7594 I wpa_supplicant: Ctrl_iface: loading cred from phone
,09-07 12:05:35.101  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-07 12:05:35.111  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-07 12:05:35.111   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7594
09-07 12:05:35.111   367   367 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-07 12:05:35.111  7594  7594 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-07 12:05:35.111  7594  7594 I wpa_supplicant: ssSupport state is = 1
09-07 12:05:35.111  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:35.111  7594  7594 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-07 12:05:35.111  7594  7594 E wpa_supplicant: SIM READ ERROR
09-07 12:05:35.111  7594  7594 I wpa_supplicant: wpa_default_ap_write_once
09-07 12:05:35.111  7594  7594 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
,09-07 12:05:35.111  7594  7594 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-07 12:05:35.111  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-07 12:05:35.111  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false,
09-07 12:05:35.111  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
09-07 12:05:35.121  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:35.121  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:35.121  1020  1047 D Tethering: interfaceStatusChanged p2p0, false
,09-07 12:05:35.231  7594  7594 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-07 12:05:35.231  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-07 12:05:35.311  7594  7594 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,09-07 12:05:35.311  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
09-07 12:05:35.311  7594  7594 I wpa_supplicant: Skip scan - bUseNetwork false
,09-07 12:05:35.521  1020  1047 D Tethering: interfaceLinkStateChanged p2p0, false
09-07 12:05:35.521  1020  1047 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-07 12:05:35.521  1020  1047 D Tethering: interfaceStatusChanged p2p0, false,
,09-07 12:05:35.561  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
09-07 12:05:35.561  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-07 12:05:35.561  7594  7594 I wpa_supplicant: HOTSPOT20_ENABLE called
,09-07 12:05:35.561  7594  7594 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-07 12:05:35.561  7594  7594 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-07 12:05:35.561  7594  7594 E wpa_supplicant: SIM READ ERROR,
09-07 12:05:35.561  7594  7594 I wpa_supplicant: Blacklist: Clear (all) 
,09-07 12:05:35.581  7594  7594 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-07 12:05:35.591  7594  7594 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-07 12:05:35.601  1020  1131 D WifiConfigStore: Loading config and enabling all networks 
,09-07 12:05:35.601  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-07 12:05:35.601  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:35.601  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:35.601  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:35.601  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:35.601  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:35.601  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-07 12:05:35.601  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-07 12:05:35.601  1175  1668 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-07 12:05:35.601  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:35.611  1175  1175 D HotspotTile: onReceive : 3, 0
,09-07 12:05:35.611  1367  1367 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-07 12:05:35.621  1020  1033 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:35.621  6753  6753 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:35.621  1020  1131 E WifiConfigStore: Not a HS20
,09-07 12:05:35.621  1020  1131 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-07 12:05:35.621  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:35.621  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:35.631  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:35.631  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-07 12:05:35.631  1020  1131 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-07 12:05:35.631  6753  6753 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:35.631  1602  1602 I Hs20UtilService: Starting #20
,09-07 12:05:35.631  1020  1131 D WifiNative-wlan0: callSECApiBoolean - ID [13]
,09-07 12:05:35.641  7594  7594 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-07 12:05:35.641  1602  1636 I Hs20UtilService: Message received 5011
,09-07 12:05:35.641  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-07 12:05:35.641  6536  6536 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-07 12:05:35.641  6536  6536 D SecurityLogAgent: StateMachine : Current State = 1
09-07 12:05:35.641  6536  6536 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-07 12:05:35.641  7594  7594 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 12:05:35.641  7594  7594 I wpa_supplicant: reset timer : RESET_TIMER 0
09-07 12:05:35.641  7594  7594 I wpa_supplicant: P2P: Current p2p state = IDLE
09-07 12:05:35.641  7594  7594 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-07 12:05:35.641  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
,09-07 12:05:35.641  7594  7594 I wpa_supplicant: First Scan Start
09-07 12:05:35.641  7594  7594 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-07 12:05:35.651   315   315 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-07 12:05:35.651  1020  1131 D WifiNative-wlan0: Setting external_sim to 1
09-07 12:05:35.651  1020  1131 D WifiStateMachine: Setting OUI to DA-A1-19
09-07 12:05:35.651  1020  1131 I WifiNative-HAL: startHal
09-07 12:05:35.651  1020  1131 E wifi    : getStaticLongField sWifiHalHandle 0x9d44e88c
09-07 12:05:35.651  1020  1131 I WifiNative-HAL: Could not start hal
,09-07 12:05:35.651  6953  6953 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 12:05:35.651  1020  1131 E WifiNative-wlan0: do suspend true
,09-07 12:05:35.651  1020  1131 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-07 12:05:35.651  1020  1130 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-07 12:05:35.651   279   995 D CommandListener: Setting iface cfg
09-07 12:05:35.651   279   995 D CommandListener: Trying to bring up p2p0
,09-07 12:05:35.651  1020  1020 D WifiScanningService: SCAN_AVAILABLE : 3
09-07 12:05:35.651  1020  1130 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-07 12:05:35.661  1020  1130 D WifiP2pService: P2pEnablingState
09-07 12:05:35.661  1020  1152 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:35.661  1020  1152 I WifiNative-HAL: startHal
,09-07 12:05:35.661  1020  1152 E wifi    : getStaticLongField sWifiHalHandle 0x9e9069bc
09-07 12:05:35.661  1020  1152 I WifiNative-HAL: Could not start hal
09-07 12:05:35.661  1020  1152 E WifiScanningService: could not start HAL
09-07 12:05:35.661  1020  1020 D RttService: SCAN_AVAILABLE : 3
09-07 12:05:35.661  1020  1153 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-07 12:05:35.661  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 12:05:35.661  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
,09-07 12:05:35.661  1020  1130 D WifiP2pService: P2pEnablingState{ what=147457 }
09-07 12:05:35.661  1020  1131 E WifiNative-wlan0: invaild command id : 215
09-07 12:05:35.661  1020  1130 D WifiP2pService: P2p socket connection successful
09-07 12:05:35.661  1020  1131 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-07 12:05:35.661  1020  1131 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-07 12:05:35.661  1020  1131 E WifiNative-wlan0: invaild command id : 215
09-07 12:05:35.661  1020  1130 D WifiP2pService: P2pEnabledState
,09-07 12:05:35.661  1020  1130 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-07 12:05:35.661  1020  1133 E ConnectivityService: updateNetworkInfo()
,09-07 12:05:35.661  1020  1020 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-07 12:05:35.661  7594  7594 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-07 12:05:35.661  1020  1050 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-07 12:05:35.661  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:35.661  1020  1050 D WifiDisplayController: disconnect
09-07 12:05:35.661  1020  1050 D WifiDisplayController: updateConnection
09-07 12:05:35.661  1020  1050 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-07 12:05:35.661  1020  1050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-07 12:05:35.661  7594  7594 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 12:05:35.671  1020  1050 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-07 12:05:35.671  1020  1050 D WifiDisplayAdapter: onP2pDisconnected
09-07 12:05:35.671  7594  7594 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
09-07 12:05:35.671  1020  1050 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-07 12:05:35.671  1020  1050 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-07 12:05:35.671  1020  1131 E WifiStateMachine: Failed to set frequency band 0
,09-07 12:05:35.671  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress
09-07 12:05:35.671  1020  1130 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
09-07 12:05:35.671  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:35.671  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:35.671  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-07 12:05:35.671  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-07 12:05:35.671  1020  1032 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-07 12:05:35.671  1020  1130 D WifiP2pService: DeviceAddress: 0a:76:28
,09-07 12:05:35.671  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-07 12:05:35.671  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-07 12:05:35.671  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:35.671  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:35.681  1020  1050 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  primary type: 10-0050F204-5
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  secondary type: null
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  wps: 0
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  grpcapab: 0
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  devcapab: 0
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  status: 3
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  wfdInfo: null
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  groupownerAddress: null
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  GOdeviceName: null
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  interfaceAddress: 
09-07 12:05:35.681  1020  1050 D WifiDisplayController:  SConnectInfo : null
,09-07 12:05:35.681  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:35.681  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:35.681  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-07 12:05:35.681  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-07 12:05:35.681  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-07 12:05:35.681  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:35.681  7287  7287 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-07 12:05:35.681  7287  7287 D FileShare-Client: Outbound.stopDelayTimer - 
,09-07 12:05:35.691  7302  7302 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-07 12:05:35.701  1020  1130 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-07 12:05:35.701  1020  1130 D WifiP2pService: InactiveState
,09-07 12:05:35.701  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
,09-07 12:05:35.701  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 12:05:35.701  7594  7594 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-07 12:05:35.701  1020  1130 D WifiP2pService: InactiveState{ what=143376 }
,09-07 12:05:35.701  1020  1130 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:36.151  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:36.151  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@24d64810 Bundle[{}]
,09-07 12:05:36.161  6753  6806 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 12:05:36.161  6753  6806 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
09-07 12:05:36.161  6753  6806 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-07 12:05:36.171  6753  6806 I System.out: Running OutgoingSocketThread
,09-07 12:05:36.171  6753  7602 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1344),
,09-07 12:05:36.181  6753  7602 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54209,
09-07 12:05:36.181  6753  7602 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-07 12:05:36.861  7594  7594 I wpa_supplicant: nl80211: Received scan results (24 BSSes),
09-07 12:05:36.861  7594  7594 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-07 12:05:36.861  7594  7594 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-07 12:05:36.861  7594  7594 I wpa_supplicant: Trying to associate with  'G700'
,09-07 12:05:36.861  7594  7594 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-07 12:05:36.861  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-07 12:05:36.871  1020  7600 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-07 12:05:36.881  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:36.881  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:37.171  6753  6806 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1345)
,09-07 12:05:37.171  6753  6806 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1345)
,09-07 12:05:37.171  6753  6806 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1350)
,09-07 12:05:37.181  6753  6806 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-07 12:05:37.181  6753  6806 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1351)
,09-07 12:05:37.181  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 12:05:37.181  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@258a2b7a added. We now have 2 listener(s)
,09-07 12:05:37.181  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-07 12:05:37.181  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:05:37.181  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.181  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.181  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6fdf2b added. We now have 9 listener(s)
,09-07 12:05:37.181  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.181  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:37.191  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:37.191  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:37.201  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:37.201  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:37.201  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24347d21 added. We now have 3 listener(s)
,09-07 12:05:37.201  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ff8546 added. We now have 10 listener(s)
09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.201  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:37.201  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:37.201  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:37.201  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.201  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:37.201  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@258a2b7a removed from the list
09-07 12:05:37.201  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.201  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6fdf2b removed from the list
09-07 12:05:37.201  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:37.201  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.201  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.211  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.211  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f6fdf2b not in the list
,09-07 12:05:37.211  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.211  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.211  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10ff8546 removed from the list
09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.211  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.211  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.211  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.211  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24347d21 removed from the list
09-07 12:05:37.211  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.211  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@318b4307 added. We now have 2 listener(s)
09-07 12:05:37.211  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 12:05:37.221  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.221  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.221  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.221  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2521dc34 added. We now have 9 listener(s)
09-07 12:05:37.221  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.221  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 12:05:37.221  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:37.231  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-07 12:05:37.231  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-07 12:05:37.231  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:05:37.231  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:37.231  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:37.241  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.241  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1eafd2 added. We now have 3 listener(s)
09-07 12:05:37.241  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 12:05:37.241  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.241  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.241  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.241  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f08a3 added. We now have 10 listener(s)
09-07 12:05:37.241  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.241  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:37.241  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:37.241  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:37.241  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:37.241  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 12:05:37.241  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 12:05:37.251  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-07 12:05:37.251  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 12:05:37.251  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 12:05:37.251  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 12:05:37.251  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-07 12:05:37.261  7495  7515 D BtGatt.GattService: registerClient() - UUID=ef5236f5-1419-4e0c-8f92-c8e27a13cd46
,09-07 12:05:37.301  7495  7513 D BtGatt.GattService: onClientRegistered() - UUID=ef5236f5-1419-4e0c-8f92-c8e27a13cd46, clientIf=6,
,09-07 12:05:37.301  6753  6761 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 12:05:37.301  7495  7506 D BtGatt.GattService: start scan with filters
,09-07 12:05:37.311  7495  7522 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:37.311  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 12:05:37.311  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 12:05:37.311  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 12:05:37.311  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:37.311  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:37.311  7495  7522 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f5c2d12
09-07 12:05:37.311  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 12:05:37.311  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:37.311  7495  7513 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 12:05:37.321  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.321  7495  7522 D BtGatt.ScanManager: allow scan with filters
09-07 12:05:37.321  7495  7522 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-07 12:05:37.321  7495  7522 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-07 12:05:37.321  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:37.321  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 12:05:37.321  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.321  7495  7522 D BtGatt.ScanManager: Starting BLE batch scan
09-07 12:05:37.321  7495  7522 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:37.321  7495  7513 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 12:05:37.331  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.331  6753  6806 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-07 12:05:37.331  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:37.331  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.341  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:37.341  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-07 12:05:37.341  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 12:05:37.341  7495  7514 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:37.341  7495  7557 D BtGatt.GattService: unregisterClient() - clientIf=6
09-07 12:05:37.341  7495  7522 D BtGatt.ScanManager: filter size is 1
09-07 12:05:37.341  7495  7522 D BtGatt.ScanManager: delete FilterIndex - 3
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 12:05:37.341  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:37.341  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:37.341  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-07 12:05:37.341  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.351  7495  7522 D BtGatt.ScanManager: stopping BLe Batch
09-07 12:05:37.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 12:05:37.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:05:37.351  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:05:37.351  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:37.351  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:37.351  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:37.351  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:37.351  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 12:05:37.351  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.351  7495  7522 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 12:05:37.351  7495  7513 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-07 12:05:37.351  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.361  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:37.361  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:37.361  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 12:05:37.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:37.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:37.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 12:05:37.361  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@318b4307 removed from the list
09-07 12:05:37.361  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 12:05:37.361  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2521dc34 removed from the list
,09-07 12:05:37.361  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 12:05:37.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.361  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-07 12:05:37.361  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.371  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2521dc34 not in the list
,09-07 12:05:37.371  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.371  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 12:05:37.371  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b0f08a3 removed from the list
09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:37.371  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.371  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.371  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.371  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e1eafd2 removed from the list
,09-07 12:05:37.371  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.371  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57f8bff added. We now have 2 listener(s),
,09-07 12:05:37.381  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 12:05:37.381  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.381  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:05:37.381  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.381  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a307dcc added. We now have 9 listener(s)
,09-07 12:05:37.381  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.381  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:37.381  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:37.391  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:37.391  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
09-07 12:05:37.391  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 12:05:37.391  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.391  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1084672a added. We now have 3 listener(s)
,09-07 12:05:37.391  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.401  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.401  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
09-07 12:05:37.401  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.401  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.401  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.401  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144ae91b added. We now have 10 listener(s)
09-07 12:05:37.401  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:37.401  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:37.401  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:37.401  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:37.401  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 12:05:37.401  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:37.401  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:37.401  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 12:05:37.411  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 12:05:37.411  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:05:37.411  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-07 12:05:37.411  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-07 12:05:37.411  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 12:05:37.421  7495  7515 D BtGatt.GattService: registerClient() - UUID=580a44e2-78de-4e8f-9a5c-4c908b7da8a0
,09-07 12:05:37.461  7495  7513 D BtGatt.GattService: onClientRegistered() - UUID=580a44e2-78de-4e8f-9a5c-4c908b7da8a0, clientIf=6
,09-07 12:05:37.461  6753  6762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 12:05:37.461  7495  7506 D BtGatt.GattService: start scan with filters
,09-07 12:05:37.461  7495  7522 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:37.461  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-07 12:05:37.461  7495  7513 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-07 12:05:37.461  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.461  7495  7522 D BtGatt.ScanManager: allow scan with filters
09-07 12:05:37.461  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-07 12:05:37.461  7495  7522 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 12:05:37.461  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 12:05:37.471  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:37.471  7495  7522 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-07 12:05:37.471  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-07 12:05:37.471  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.471  7495  7522 D BtGatt.ScanManager: Starting BLE batch scan
09-07 12:05:37.471  7495  7522 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:37.471  7495  7513 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 12:05:37.471  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.471  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:37.481  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:37.481  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.481  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:37.481  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-07 12:05:37.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:37.491  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 12:05:37.491  6753  6806 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-07 12:05:37.491  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:37.491  7594  7594 E wpa_supplicant: Cmd 35605 not handled
09-07 12:05:37.491  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:37.491  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:37.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.491  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:37.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.491  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@57f8bff removed from the list
09-07 12:05:37.491  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.491  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a307dcc removed from the list
09-07 12:05:37.491  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:37.491  7594  7594 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-07 12:05:37.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:37.491  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-07 12:05:37.491  7594  7594 I wpa_supplicant: Associated with F4.99.3E
09-07 12:05:37.491  7594  7594 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 12:05:37.491  7594  7594 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-07 12:05:37.491  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.491  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-07 12:05:37.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 12:05:37.491  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.491  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:37.501  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 12:05:37.501  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-07 12:05:37.501  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.501  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a307dcc not in the list
,09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-07 12:05:37.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:37.501  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-07 12:05:37.501  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 12:05:37.501  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, false
,09-07 12:05:37.501  1020  1047 D Tethering: interfaceStatusChanged wlan0, false
,09-07 12:05:37.501  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-07 12:05:37.501  7495  7509 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:37.511  7495  7522 D BtGatt.ScanManager: filter size is 1
09-07 12:05:37.511  7495  7522 D BtGatt.ScanManager: delete FilterIndex - 4
,09-07 12:05:37.511  7495  7515 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 12:05:37.511  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 12:05:37.511  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.511  7495  7522 D BtGatt.ScanManager: stopping BLe Batch
,09-07 12:05:37.511  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
,09-07 12:05:37.511  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:05:37.511  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:37.511  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:37.511  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 12:05:37.511  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:37.511  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,09-07 12:05:37.511  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-07 12:05:37.511  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-07 12:05:37.511  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.511  7495  7522 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-07 12:05:37.511  1020  1134 E Tethering: No numeric data
,09-07 12:05:37.521  1020  1134 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-07 12:05:37.521  7495  7513 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 12:05:37.521  1020  1134 D Tethering: clearTetheredNotification()
09-07 12:05:37.521  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.521  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:37.521  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:37.521  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:37.521  1020  1128 V NetworkStats: performPollLocked(flags=0x1)
,09-07 12:05:37.521  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:37.521  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-07 12:05:37.521  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
,09-07 12:05:37.521  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:37.521  1175  1175 D HotspotTile: updateTetherState():false, false
09-07 12:05:37.521  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-07 12:05:37.531  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 12:05:37.521  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:37.531  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:37.531  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.531  1020  1128 V NetworkStats: performPollLocked() took 8ms
09-07 12:05:37.531  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:37.531  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-07 12:05:37.531  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:37.531  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.531  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@144ae91b removed from the list
09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-07 12:05:37.531  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.531  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.531  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.531  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1084672a removed from the list
,09-07 12:05:37.531  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:37.531  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.531  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29a4fbf7 added. We now have 2 listener(s)
,09-07 12:05:37.541  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:37.541  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 12:05:37.541  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:05:37.541  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:05:37.541  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.541  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180eba64 added. We now have 9 listener(s)
,09-07 12:05:37.541  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:37.541  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:37.551  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:37.551  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:37.551  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:37.551  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:37.551  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.551  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.561  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.561  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94eb182 added. We now have 3 listener(s)
,09-07 12:05:37.561  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-07 12:05:37.561  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-07 12:05:37.561  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:05:37.561  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.561  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d236093 added. We now have 10 listener(s)
,09-07 12:05:37.561  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.561  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-07 12:05:37.561  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 12:05:37.561  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-07 12:05:37.561  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 12:05:37.561  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 12:05:37.571  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-07 12:05:37.571  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 12:05:37.571  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-07 12:05:37.581  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-07 12:05:37.581  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-07 12:05:37.581  6753  6806 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-07 12:05:37.581  7495  7506 D BtGatt.GattService: registerClient() - UUID=5e0539d7-418c-4929-90ac-8e30aa3f8285
,09-07 12:05:37.621  7495  7513 D BtGatt.GattService: onClientRegistered() - UUID=5e0539d7-418c-4929-90ac-8e30aa3f8285, clientIf=6
,09-07 12:05:37.621  6753  6762 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-07 12:05:37.621  7495  7514 D BtGatt.GattService: start scan with filters
,09-07 12:05:37.621  7495  7522 D BtGatt.ScanManager: handling starting scan
,09-07 12:05:37.621  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-07 12:05:37.621  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-07 12:05:37.621  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-07 12:05:37.621  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-07 12:05:37.631  7495  7513 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-07 12:05:37.631  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.631  7495  7522 D BtGatt.ScanManager: allow scan with filters
09-07 12:05:37.631  7495  7522 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-07 12:05:37.631  7495  7522 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-07 12:05:37.631  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-07 12:05:37.631  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.631  7495  7522 D BtGatt.ScanManager: Starting BLE batch scan
,09-07 12:05:37.631  7495  7522 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-07 12:05:37.631  7495  7513 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-07 12:05:37.631  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.631  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-07 12:05:37.631  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-07 12:05:37.641  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-07 12:05:37.641  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-07 12:05:37.641  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-07 12:05:37.651   289   289 E SMD     : DCD OFF
,09-07 12:05:37.651  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-07 12:05:37.651  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:37.651  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.651  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.651  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@29a4fbf7 removed from the list
09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.651  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180eba64 removed from the list
09-07 12:05:37.651  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:37.651  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-07 12:05:37.651  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-07 12:05:37.651  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@180eba64 not in the list
,09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-07 12:05:37.651  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-07 12:05:37.651  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-07 12:05:37.661  7495  7557 D BtGatt.GattService: stopScan() - queue size =1
,09-07 12:05:37.661  7495  7509 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-07 12:05:37.661  7495  7522 D BtGatt.ScanManager: filter size is 1
09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-07 12:05:37.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-07 12:05:37.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-07 12:05:37.661  7495  7522 D BtGatt.ScanManager: delete FilterIndex - 5
,09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-07 12:05:37.661  7495  7513 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-07 12:05:37.661  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.661  7495  7522 D BtGatt.ScanManager: stopping BLe Batch
,09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-07 12:05:37.661  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-07 12:05:37.661  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.661  7495  7513 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-07 12:05:37.661  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-07 12:05:37.661  7495  7522 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d236093 removed from the list
09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.671  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.671  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.671  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@94eb182 removed from the list
09-07 12:05:37.671  6753  6753 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-07 12:05:37.671  6753  6753 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-07 12:05:37.671  7495  7513 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-07 12:05:37.671  7495  7513 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201972ef added. We now have 2 listener(s)
,09-07 12:05:37.671  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 12:05:37.671  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.671  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-07 12:05:37.671  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb4f1fc added. We now have 9 listener(s)
09-07 12:05:37.671  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 12:05:37.671  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-07 12:05:37.681  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-07 12:05:37.681  6753  6806 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-07 12:05:37.681  6753  6806 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-07 12:05:37.681  6753  6806 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-07 12:05:37.681  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-07 12:05:37.681  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281ceeda added. We now have 3 listener(s)
,09-07 12:05:37.681  7594  7594 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-07 12:05:37.681  7594  7594 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-07 12:05:37.691  7594  7594 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-07 12:05:37.691  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 12:05:37.691  7594  7594 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-07 12:05:37.691  7594  7594 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 12:05:37.691  7594  7594 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb44f0b added. We now have 10 listener(s)
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 12:05:37.691  7594  7594 I wpa_supplicant: Blacklist: Clear (temp) 
09-07 12:05:37.691  7594  7594 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-07 12:05:37.691  6753  6806 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.691  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@201972ef removed from the list
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb4f1fc removed from the list
09-07 12:05:37.691  1020  1047 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-07 12:05:37.691  1020  1047 D Tethering: interfaceLinkStateChanged wlan0, true
09-07 12:05:37.691  1020  1047 D Tethering: interfaceStatusChanged wlan0, true
,09-07 12:05:37.691  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 12:05:37.691  6753  6806 D io.jxcore.node.ConnectivityMonitor: stop
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.691  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.691  6753  6806 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fb4f1fc not in the list
09-07 12:05:37.691  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bb44f0b removed from the list
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 12:05:37.691  6753  6806 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 12:05:37.691  6753  6806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 12:05:37.691  6753  6806 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-07 12:05:37.691  6753  6806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@281ceeda removed from the list
,09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 12:05:37.691  6753  6806 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-07 12:05:37.691  6753  6753 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 12:05:37.701  1020  1131 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-07 12:05:37.701  1020  1131 E WifiConfigStore: setLastSelectedConfiguration -1
,09-07 12:05:37.701  6753  7606 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1358, name: My test thread name)
09-07 12:05:37.701  6753  7606 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1358, thread name: My test thread name)
09-07 12:05:37.701  6753  7606 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1358, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 12:05:37.701  1020  1131 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-07 12:05:37.701  1020  1133 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-07 12:05:37.701  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:05:37.701  1020  1133 E ConnectivityService: updateNetworkInfo()
,09-07 12:05:37.701  6753  7608 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1360, name: My test thread name)
09-07 12:05:37.701  6753  7608 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1360, thread name: My test thread name)
09-07 12:05:37.701  6753  7608 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1360, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-07 12:05:37.711  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:37.711  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:37.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.711  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:37.711  6753  6806 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-07 12:05:37.711  6753  6806 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-07 12:05:37.711  6753  6806 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-07 12:05:37.711  6753  6806 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-07 12:05:37.711  6753  6806 D com.test.thalitest.ThaliTestRunner: Total duration: 23380 ms
09-07 12:05:37.711  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:05:37.711  1020  1482 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-07 12:05:37.711  1020  1482 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-07 12:05:37.711  1020  1482 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:37.711  1020  1482 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:37.711  1020  1482 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-07 12:05:37.711  6753  6806 I jxcore-log: *Native tests were executed*
09-07 12:05:37.711  6753  6806 I jxcore-log: 
09-07 12:05:37.711  6753  6806 I jxcore-log: Total number of executed tests:  80
09-07 12:05:37.711  6753  6806 I jxcore-log: 
,09-07 12:05:37.711  6753  6806 I jxcore-log: Number of passed tests:  80
09-07 12:05:37.711  6753  6806 I jxcore-log: 
09-07 12:05:37.711  6753  6806 I jxcore-log: Number of failed tests:  0
09-07 12:05:37.711  6753  6806 I jxcore-log: 
09-07 12:05:37.711  6753  6806 I jxcore-log: Number of ignored tests:  0
09-07 12:05:37.711  6753  6806 I jxcore-log: 
,09-07 12:05:37.711  6753  6806 I jxcore-log: Total duration:  23380
09-07 12:05:37.711  6753  6806 I jxcore-log: 
09-07 12:05:37.711  6753  6806 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-07 12:05:37.711  6753  6806 I jxcore-log: 
,09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.721  1020  1131 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.721  1602  1602 I Hs20UtilService: Starting #21
09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.721  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.721  6753  6806 I jxcore-log: 
09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  1367  1367 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731   279   995 D CommandListener: Setting iface cfg
09-07 12:05:37.731  1367  1367 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  1602  1636 I Hs20UtilService: Message received 5007
09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
,09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  1020  1131 E WifiStateMachine: Start Dhcp Watchdog 3
09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  6753  6753 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 12:05:37.731  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-07 12:05:37.731  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.731  6753  6806 I jxcore-log: 
09-07 12:05:37.731  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:37.731  1020  1131 D SecContentProvider2: mCursor = null
09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
09-07 12:05:37.741  1367  1367 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-07 12:05:37.741  1367  1367 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-07 12:05:37.741  1367  2236 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
09-07 12:05:37.741  6753  6806 I jxcore-log: 
09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
09-07 12:05:37.741  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-07 12:05:37.741  6753  6806 I jxcore-log: 
,09-07 12:05:37.751  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:37.751  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:37.751  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.751  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.751  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:37.751  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:37.751  1020  1131 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-07 12:05:37.751  1020  1131 D SecContentProvider2: mCursor = null
,09-07 12:05:37.751  1020  1131 E WifiNative-wlan0: do suspend false
,09-07 12:05:37.751  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-07 12:05:37.751  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 12:05:37.851  6753  6753 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 12:05:37.851  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:05:37.851  6753  6806 I jxcore-log: 
,09-07 12:05:37.981  7614  7614 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 12:05:37.981  7614  7614 I dhcpcd  : version 5.5.6 starting,
,09-07 12:05:37.981  7614  7614 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-07 12:05:38.011  7610  7610 D AndroidRuntime: ,
09-07 12:05:38.011  7610  7610 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-07 12:05:38.011  7610  7610 D AndroidRuntime: CheckJNI is OFF,
09-07 12:05:38.011  7610  7610 D AndroidRuntime: readGMSProperty: start
09-07 12:05:38.011  7610  7610 D AndroidRuntime: readGMSProperty: already setted!!,
09-07 12:05:38.011  7610  7610 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-07 12:05:38.011  7610  7610 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-07 12:05:38.011  7610  7610 D AndroidRuntime: readGMSProperty: end
09-07 12:05:38.011  7610  7610 D AndroidRuntime: addProductProperty: start
,09-07 12:05:38.031  7614  7614 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-07 12:05:38.031  7614  7614 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-07 12:05:38.031  7614  7614 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-07 12:05:38.031  7614  7614 I dhcpcd  : bssid match
09-07 12:05:38.031  7614  7614 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,09-07 12:05:38.031  6753  6753 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
09-07 12:05:38.031  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:05:38.031  6753  6806 I jxcore-log: 
,09-07 12:05:38.151  1020  1500 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-07 12:05:38.151  1020  1500 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
09-07 12:05:38.151  1020  1500 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
09-07 12:05:38.151  1020  1500 D BatteryService: stay LED for fully charged
09-07 12:05:38.151  1020  1020 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-07 12:05:38.151  1020  1020 I MotionRecognitionService: Plugged
09-07 12:05:38.151  1020  1020 I MotionRecognitionService: mGripSensorEnabled= false
,09-07 12:05:38.161  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-07 12:05:38.161  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-07 12:05:38.161  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-07 12:05:38.161  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-07 12:05:38.161  7610  7610 E AffinityControl: AffinityControl: registerfunction enter
,09-07 12:05:38.171  6753  6753 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-07 12:05:38.171  6753  6806 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-07 12:05:38.171  6753  6806 I jxcore-log: 
,09-07 12:05:38.181  7495  7495 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-07 12:05:38.181  7495  7523 D HeadsetStateMachine: Disconnected process message: 10
,09-07 12:05:38.181  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:38.191  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:38.191  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,09-07 12:05:38.191  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
09-07 12:05:38.191  1175  1175 D SViewCoverView: level :100 plugged : 2
,09-07 12:05:38.191  7610  7610 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,09-07 12:05:38.211  1020  1368 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-07 12:05:38.211  1020  1368 D PackageManager: START PACKAGE DELETE: observer{367978962}
09-07 12:05:38.211  1020  1368 D PackageManager: pkg{<packageName>}
09-07 12:05:38.211  1020  1368 D PackageManager: user{0}
09-07 12:05:38.211  1020  1368 D PackageManager: caller{2000}
09-07 12:05:38.211  1020  1368 D PackageManager: flags{2}
09-07 12:05:38.211  1020  1368 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-07 12:05:38.211  1020  1368 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-07 12:05:38.211  1020  1368 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-07 12:05:38.211  1020  1368 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-07 12:05:38.211  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,09-07 12:05:38.211  1020  1060 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-07 12:05:38.211  1020  1060 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-07 12:05:38.221  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled,
09-07 12:05:38.221  1020  1060 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-07 12:05:38.221  1020  1060 D PackageManager: !@killApplicatoin: 10171, uninstall pkg,
,09-07 12:05:38.231  1020  1045 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg,
09-07 12:05:38.231  1020  1045 I ActivityManager: Killing 6753:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-07 12:05:38.301  1020  1060 W PackageSettings: Skipping PackageSetting{2835ac73 com.example.hello/10168} due to missing metadata
,09-07 12:05:38.311   259  1775 I SurfaceFlinger: id=13 Removed NainActivit (6/8),
09-07 12:05:38.311  1020  1033 I WindowState: WIN DEATH: Window{138dab2a u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 12:05:38.311   259  1490 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-07 12:05:38.321  1020  1033 D InputDispatcher: Focus left window: 6753
,09-07 12:05:38.331  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-07 12:05:38.331  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-07 12:05:38.351  1020  1045 I ActivityManager:   Force finishing activity ActivityRecord{bda7fca u0 com.test.thalitest/.MainActivity t2}
,09-07 12:05:38.351  1020  1081 W ActivityManager: Spurious death for ProcessRecord{c63baa3 6753:com.test.thalitest/u0a171}, curProc for 6753: null
,09-07 12:05:38.361  1020  1060 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-07 12:05:38.361  1020  1060 I ActivityManager:   Force finishing activity ActivityRecord{bda7fca u0 com.test.thalitest/.MainActivity t2 f}
09-07 12:05:38.361  1020  1060 W ActivityManager: Duplicate finish request for ActivityRecord{bda7fca u0 com.test.thalitest/.MainActivity t2 f}
,09-07 12:05:38.381  1020  1060 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-07 12:05:38.381  7614  7614 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,09-07 12:05:38.431  2647  2647 I art     : Explicit concurrent mark sweep GC freed 19558(1116KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 797us total 30.875ms
09-07 12:05:38.431  7614  7614 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,09-07 12:05:38.441  4739  4739 I art     : Explicit concurrent mark sweep GC freed 22100(1344KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.292ms total 77.242ms
,09-07 12:05:38.451  1020  1045 D InputDispatcher: Focused application released,
09-07 12:05:38.451  1020  1045 D FocusedStackFrame: Set to : 0,
,09-07 12:05:38.461  1020  1045 W ActivityManager: mDVFSHelper.acquire()
,09-07 12:05:38.471  1020  1045 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false,
,09-07 12:05:38.501  1483  1483 D Launcher: onRestart, Launcher: 273418334
,09-07 12:05:38.521  1973  1973 E SamsungIME: mOCRHelper is null
,09-07 12:05:38.521  1989  2160 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-07 12:05:38.541  1449  1449 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-07 12:05:38.561  1020  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-07 12:05:38.561  1020  1128 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-07 12:05:38.561  1020  1128 V NetworkStats: performPollLocked(flags=0x3)
,09-07 12:05:38.571  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:38.571  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:38.571  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-07 12:05:38.581  1020  1020 D RCPManagerService: PackageReceiver onReceive(),
,09-07 12:05:38.591  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-07 12:05:38.591  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED,
09-07 12:05:38.591  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-07 12:05:38.591  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-07 12:05:38.601  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter,
,09-07 12:05:38.601  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty,
,09-07 12:05:38.621  1020  1128 V NetworkStats: performPollLocked() took 51ms
,09-07 12:05:38.631  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:38.631  1483  1483 D Launcher: onStart, Launcher: 273418334
09-07 12:05:38.631  1483  1483 D Launcher.HomeView: onStart
,09-07 12:05:38.631  1483  1483 D Launcher: onResume, Launcher: 273418334
,09-07 12:05:38.631  1020  1477 D SettingsProvider: name = kids_home_mode
09-07 12:05:38.631  1020  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-07 12:05:38.631  1020  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-07 12:05:38.631  1020  1477 D SettingsProvider: selectionArgs: false
09-07 12:05:38.631  1020  1477 D SettingsProvider: selectionArgs: 10006
09-07 12:05:38.631  1020  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-07 12:05:38.631  1020  1477 D SettingsProvider: ret = -1
,09-07 12:05:38.631  1483  1483 D Launcher.HomeView: onResume
,09-07 12:05:38.641  1438  1438 D PersonaManager: isKioskContainerExistOnDevice,
,09-07 12:05:38.661  2882  2882 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Sep 07 12:05:38 GMT+02:00 2016
09-07 12:05:38.661  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-07 12:05:38.661  1020  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-07 12:05:38.661  1020  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-07 12:05:38.661  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-07 12:05:38.661  1020  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-07 12:05:38.661  1020  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:38.661  1020  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-07 12:05:38.671  1483  1483 D MenuAppsGridFragment: onResume
,09-07 12:05:38.681  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-07 12:05:38.681  1483  1483 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-07 12:05:38.681  1020  1060 I art     : Explicit concurrent mark sweep GC freed 47040(2MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 25MB/37MB, paused 16.266ms total 298.656ms
,09-07 12:05:38.681  2882  2882 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-07 12:05:38.691  1020  1482 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,09-07 12:05:38.691  1020  1482 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-07 12:05:38.701  1020  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-07 12:05:38.701  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.701  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.701  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.701  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.701  2882  2882 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-07 12:05:38.711  2882  2882 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-07 12:05:38.711  2882  2882 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false,
,09-07 12:05:38.721  1020  1081 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-07 12:05:38.721  1020  1081 D SecContentProvider2: mCursor = null
,09-07 12:05:38.731  7653  7653 E Zygote  : MountEmulatedStorage()
09-07 12:05:38.731  7653  7653 E Zygote  : v2
09-07 12:05:38.731  7653  7653 I libpersona: KNOX_SDCARD checking this for 10090
09-07 12:05:38.731  7653  7653 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:38.731  7653  7653 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:38.731  1020  1482 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7653 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-07 12:05:38.731  7653  7653 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:38.741  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
09-07 12:05:38.741  7653  7653 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:38.741  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-07 12:05:38.751  1020  1033 D ActivityManager: handle home activity for 0
,09-07 12:05:38.751  1020  1033 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-07 12:05:38.751  1020  1033 D KnoxTimeoutHandler: post home show event for user 0
09-07 12:05:38.751  1020  1033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-07 12:05:38.751  1020  1033 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-07 12:05:38.751  1020  1033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-07 12:05:38.751  1483  1483 D Launcher.HomeView: onPause
,09-07 12:05:38.751  1483  1483 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-07 12:05:38.751  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
09-07 12:05:38.751  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,09-07 12:05:38.751  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:38.751  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-07 12:05:38.751  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:38.751  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-07 12:05:38.761  1020  1481 I TactileAssist: enable value -1
,09-07 12:05:38.761  1020  1481 I TactileAssist: internal enable value -1
09-07 12:05:38.761  1020  1481 I TactileAssist: intensity value -1
09-07 12:05:38.761  1020  1481 I TactileAssist: saveAppList value true
,09-07 12:05:38.761  1020  1481 I TactileAssist: List of disabled apps :
,09-07 12:05:38.761  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.761  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.761  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.761  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.781  7668  7668 E Zygote  : MountEmulatedStorage()
09-07 12:05:38.781  7668  7668 E Zygote  : v2
09-07 12:05:38.781  7668  7668 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:38.781  7668  7668 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:38.781  7668  7668 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:38.781  1020  1131 E WifiNative-wlan0: do suspend true
,09-07 12:05:38.781  7668  7668 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:38.781  7668  7668 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:38.781  1020  1045 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7668 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 12:05:38.791  7653  7653 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:38.791  1020  1045 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
09-07 12:05:38.791  7653  7653 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:38.791  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.791  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.791  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.791  1020  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.811  1020  1130 D WifiP2pService: InactiveState{ what=143375 }
,09-07 12:05:38.811  1020  1130 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-07 12:05:38.811  1020  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-07 12:05:38.811  1020  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
09-07 12:05:38.811  1020  1045 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7679 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 12:05:38.811  1020  1044 W TextServicesManagerService: no available spell checker services found
09-07 12:05:38.811  7679  7679 E Zygote  : MountEmulatedStorage()
09-07 12:05:38.811  7679  7679 E Zygote  : v2
09-07 12:05:38.811  7679  7679 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:38.811  7679  7679 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:38.811  7679  7679 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:38.821  7679  7679 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:38.821  7679  7679 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 12:05:38.821  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-07 12:05:38.831  1020  1060 D PackageManager: delete codoeFile: 
09-07 12:05:38.831  7668  7668 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:38.831  7668  7668 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:38.841  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-07 12:05:38.841  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-07 12:05:38.841   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-07 12:05:38.841  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-07 12:05:38.851  1020  1048 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicy: uID is 10171
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-07 12:05:38.851  1020  1131 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-07 12:05:38.851  1020  1131 E WifiStateMachine: VerifyingLinkState enter,
09-07 12:05:38.851  1020  1060 I AASA_removePackage: UID=10171 Target=com.test.thalitest
09-07 12:05:38.851  1020  1060 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-07 12:05:38.851  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-07 12:05:38.851  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 12:05:38.851  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:38.851  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:38.861  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.861  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.861  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.861  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:38.861  1020  1033 D InputDispatcher: Focus entered window: 1483
09-07 12:05:38.861  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:38.861  7679  7679 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:38.861  1020  1050 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-07 12:05:38.861  1020  1050 D PointerIcon: setMouseCustomIcon IconType is same.101
09-07 12:05:38.861  7679  7679 D ActivityThread: Added TimaKeyStore provider
09-07 12:05:38.861  1020  1133 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-07 12:05:38.861  1020  1060 D PackageManager: result of delete: 1{367978962}
09-07 12:05:38.861  1483  1483 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-07 12:05:38.861  1020  1133 D ConnectivityService: Adding iface wlan0 to network 504
,09-07 12:05:38.861  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:38.871  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:38.871  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:38.871  7610  7610 D AndroidRuntime: Shutting down VM
,09-07 12:05:38.871  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:38.881  2882  7652 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-07 12:05:38.881  1483  1483 V ActivityThread: updateVisibility : ActivityRecord{cfaba2b token=android.os.BinderProxy@189e8f77 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-07 12:05:38.881  1483  1483 D Launcher.HomeView: onStop
,09-07 12:05:38.881  1020  1133 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-07 12:05:38.881  1020  1133 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-07 12:05:38.891  1020  1133 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-07 12:05:38.891  1020  1133 E ConnectivityService: Unexpected mtu value: 0, wlan0,
,09-07 12:05:38.891  1020  1133 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-07 12:05:38.891  1020  1133 D ConnectivityService: LTETest block dns file not exists
,09-07 12:05:38.891  1020  1060 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-07 12:05:38.891  1020  1060 D PackageManager: userId{-1}
09-07 12:05:38.891  1020  1060 D PackageManager: andCode{true}
,09-07 12:05:38.891  1020  1480 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-07 12:05:38.891  2882  7652 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,09-07 12:05:38.901  1020  7701 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-07 12:05:38.901  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:38.901  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:38.901  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.901  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.901  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:38.901  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:38.911  1020  1480 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6753 uid 10171
,09-07 12:05:38.921  1973  1973 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-07 12:05:38.931  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicy: uID is 10171
09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-07 12:05:38.931  1020  3356 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-07 12:05:38.931  1020  1060 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-07 12:05:38.931  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-07 12:05:38.941  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-07 12:05:38.941  1020  1020 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-07 12:05:38.941  7653  7653 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-07 12:05:38.941  7653  7653 D elm:15121: ELMEngine.ELMEngine( context ).
,09-07 12:05:38.951  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.951  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.951  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.951  1020  1060 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.951  7679  7679 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-07 12:05:38.961  7653  7653 D elm:15121: MDMBridge.setEnterpriseBridge(),
,09-07 12:05:38.961  7703  7703 E Zygote  : MountEmulatedStorage()
09-07 12:05:38.971  7703  7703 E Zygote  : v2
09-07 12:05:38.971  7703  7703 I libpersona: KNOX_SDCARD checking this for 10003
09-07 12:05:38.971  7703  7703 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:38.971  7703  7703 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:38.971  7703  7703 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:38.971  7703  7703 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:38.971  1020  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7703 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,09-07 12:05:38.971  1020  1045 W ActivityManager: mDVFSHelper.release()
09-07 12:05:38.981  2882  2882 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
09-07 12:05:38.981  1020  1163 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,09-07 12:05:38.991  1020  1481 D SecContentProvider2: uri = -1 selection = getSealedState
09-07 12:05:38.991  1020  1481 D SecContentProvider2: mCursor = null
,09-07 12:05:38.991  1020  1081 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
09-07 12:05:38.991  1020  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-07 12:05:38.991  7679  7679 I PopupuiReceiver_KNOX: getSealedState : true
09-07 12:05:38.991  1020  1588 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-07 12:05:38.991  1020  1588 D SecContentProvider2: mCursor = null
09-07 12:05:38.991  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.991  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:38.991  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:38.991  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.991  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:38.991  7679  7679 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,09-07 12:05:38.991  1020  1500 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-07 12:05:38.991  1020  1500 D SecContentProvider2: mCursor = null
09-07 12:05:38.991  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:38.991  7679  7679 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
09-07 12:05:38.991  7679  7679 D PopupuiReceiver: Action package removed
09-07 12:05:39.001  7703  7703 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:39.001  7703  7703 D ActivityThread: Added TimaKeyStore provider
09-07 12:05:39.001  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-07 12:05:39.001  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-07 12:05:39.001  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
09-07 12:05:39.001  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-07 12:05:39.001  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-07 12:05:39.001  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:39.001  1020  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-07 12:05:39.001  1020  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 12:05:39.001  1020  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-07 12:05:39.001  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:39.011  7718  7718 E Zygote  : MountEmulatedStorage(),
09-07 12:05:39.011  7718  7718 E Zygote  : v2
09-07 12:05:39.011  7718  7718 I libpersona: KNOX_SDCARD checking this for 10048
09-07 12:05:39.011  7718  7718 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:39.011  7718  7718 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:39.011  7718  7718 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:39.011  1020  1081 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7718 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-07 12:05:39.011  7718  7718 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-07 12:05:39.011  1020  1146 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-07 12:05:39.021  1020  1146 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 12:05:39.021  1020  1146 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 12:05:39.021  1020  1146 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-07 12:05:39.021  1020  1146 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-07 12:05:39.031  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:39.031  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:39.031  1020  1081 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-07 12:05:39.031   304   304 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 23.837ms,
,09-07 12:05:39.041  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:39.041  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.041  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-07 12:05:39.041  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.041  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.041  1020  1081 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:39.041  1175  1175 I StatusBar: Icon Only
,09-07 12:05:39.041  1175  1175 D PanelView: There is/are notification(s) 
09-07 12:05:39.041  7718  7718 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-07 12:05:39.041  7718  7718 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:39.041  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:39.051  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:39.051  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 12:05:39.051   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 575us total 16.727ms
09-07 12:05:39.051  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-07 12:05:39.051  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-07 12:05:39.051  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-07 12:05:39.071   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 570us total 16.316ms
,09-07 12:05:39.081  7733  7733 E Zygote  : MountEmulatedStorage(),
,09-07 12:05:39.081  7610  7610 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-07 12:05:39.081  7733  7733 E Zygote  : v2
09-07 12:05:39.081  7733  7733 I libpersona: KNOX_SDCARD checking this for 10145
09-07 12:05:39.081  7733  7733 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:39.081  7733  7733 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:39.081  1020  1081 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7733 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-07 12:05:39.091  7733  7733 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-07 12:05:39.091  7733  7733 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-07 12:05:39.091  1020  1081 I ActivityManager: Killing 7023:com.sec.android.soagent/u0a31 (adj 15): empty #21
09-07 12:05:39.091  1020  1050 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36c38c97 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147334
09-07 12:05:39.091  1020  1131 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-07 12:05:39.101  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 12:05:39.101  1020  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-07 12:05:39.101  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:39.101  1020  1499 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-07 12:05:39.101  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:39.101  1020  1133 V NetworkStats: updateIfacesLocked()
09-07 12:05:39.101  1020  1499 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-07 12:05:39.101  1020  1499 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:39.101  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:39.101  1020  1499 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:39.101  1020  1499 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-07 12:05:39.111  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:39.111  1020  1133 V NetworkStats: performPollLocked() took 5ms
09-07 12:05:39.111  1020  1045 W ActivityManager: Failed to clear dns cache for: com.sec.android.soagent
,09-07 12:05:39.111  7653  7653 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-07 12:05:39.121  1020  1081 D PersonaManager: isKioskContainerExistOnDevice
,09-07 12:05:39.121  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:39.121  1020  1133 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-07 12:05:39.131  7668  7668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-07 12:05:39.131  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit,
09-07 12:05:39.131  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:39.131  1020  1133 E ConnectivityService: updateNetworkInfo()
09-07 12:05:39.131  1020  1133 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-07 12:05:39.131  7653  7653 D elm:15121: ElmAgentService : onCreate()
09-07 12:05:39.131  1020  1133 V NetworkStats: updateIfacesLocked()
09-07 12:05:39.131  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling,
09-07 12:05:39.131  1020  1133 V NetworkStats: performPollLocked(flags=0x1)
09-07 12:05:39.131  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:39.131  7653  7743 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-07 12:05:39.131  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox updated
09-07 12:05:39.131  1020  1133 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-07 12:05:39.131  7653  7743 D elm:15121: MainReceiver.listeningToPackageRemoved()
,09-07 12:05:39.131  7653  7743 D elm:15121: MDMBridge.getInstance()
09-07 12:05:39.131  7653  7743 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
09-07 12:05:39.141  1020  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-07 12:05:39.141  1020  1133 V NetworkStats: performPollLocked() took 7ms
09-07 12:05:39.141  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,09-07 12:05:39.141  7653  7743 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-07 12:05:39.151  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-07 12:05:39.151  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-07 12:05:39.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:39.151  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.151  7733  7733 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:39.151  7733  7733 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:39.161  7718  7718 D Compatibility: onReceive() it will make start service
09-07 12:05:39.161  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:39.161  1020  1133 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-07 12:05:39.161  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
09-07 12:05:39.161  1020  1133 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
09-07 12:05:39.161  1020  1081 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-07 12:05:39.161  1020  7607 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:39.161  1020  1081 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
09-07 12:05:39.161  1020  7607 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-07 12:05:39.161  1020  7607 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-07 12:05:39.161  1020  7607 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-07 12:05:39.161  1020  1081 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:39.161  1020  1081 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:39.161  1020  1081 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
09-07 12:05:39.161  1020  7607 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-07 12:05:39.161  1020  1133 D ConnectivityService:    accepting network in place of null
09-07 12:05:39.161  1449  1449 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-07 12:05:39.161  1449  1449 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-07 12:05:39.161  1020  1130 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-07 12:05:39.171   279   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-07 12:05:39.171   279   990 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-07 12:05:39.171  1020  1131 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,09-07 12:05:39.171  7668  7754 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,09-07 12:05:39.171  7668  7754 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:39.171  7668  7754 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:05:39.171  7668  7754 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-07 12:05:39.171  7668  7754 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,09-07 12:05:39.181  7668  7754 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-07 12:05:39.181  7668  7754 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.deleteAMData(DatabaseHandler.java:160)
09-07 12:05:39.181  7668  7754 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:112)
09-07 12:05:39.181  7668  7754 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-07 12:05:39.181  7668  7754 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-07 12:05:39.181  7668  7754 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-07 12:05:39.181  7668  7754 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-07 12:05:39.181  1020  1020 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-07 12:05:39.181  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-07 12:05:39.181  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-07 12:05:39.181  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-07 12:05:39.181  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.181  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.181  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-07 12:05:39.181  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.181  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.181  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.181  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:39.191  7755  7755 E Zygote  : MountEmulatedStorage()
09-07 12:05:39.191  7755  7755 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:39.191  7755  7755 E Zygote  : v2
09-07 12:05:39.191  7755  7755 I libpersona: KNOX_SDCARD not a persona
,09-07 12:05:39.201  1020  1020 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7755 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-07 12:05:39.201  7755  7755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:39.201  1020  1424 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-07 12:05:39.201  1020  1020 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-07 12:05:39.201  1020  1424 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-07 12:05:39.201  1020  1020 I WifiTrafficPoller: mBoosterFLAG : 0
09-07 12:05:39.201  1020  1020 I WifiTrafficPoller: current booster mode : FullMode
09-07 12:05:39.201  1020  1424 W ActivityManager: userId = 0, bbcId = -10000
09-07 12:05:39.201  1020  1424 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-07 12:05:39.201  1020  1424 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive,
09-07 12:05:39.201  7755  7755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:39.211  7755  7755 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-07 12:05:39.211  1020  1482 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
09-07 12:05:39.211  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.211  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.211  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.211  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-07 12:05:39.211  7653  7653 D elm:15121: ElmAgentService : onDestroy().
,09-07 12:05:39.211  7718  7762 D Compatibility: onHandleIntent()
,09-07 12:05:39.221  7718  7762 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-07 12:05:39.221  7718  7762 D Compatibility: found: 2
,09-07 12:05:39.231  7771  7771 E Zygote  : MountEmulatedStorage()
09-07 12:05:39.231  7771  7771 I libpersona: KNOX_SDCARD checking this for 1000
09-07 12:05:39.231  7771  7771 E Zygote  : v2
09-07 12:05:39.231  7771  7771 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:39.231  7771  7771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-07 12:05:39.231  1020  1482 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7771 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-07 12:05:39.231  7771  7771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:39.231  7771  7771 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-07 12:05:39.231  1020  1482 I ActivityManager: Killing 7044:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
09-07 12:05:39.241  7755  7755 D TimaKeyStoreProvider: TimaSignature is unavailable
09-07 12:05:39.241  1020  1482 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
09-07 12:05:39.241  7718  7762 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-07 12:05:39.241  7755  7755 D ActivityThread: Added TimaKeyStore provider
09-07 12:05:39.241  7718  7762 D Compatibility: skipping ResolveInfo{3f68361 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-07 12:05:39.241  7718  7762 D Compatibility: considering ResolveInfo{a03ae86 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-07 12:05:39.241  7718  7762 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
09-07 12:05:39.241  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.241  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.241  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.241  1020  1482 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-07 12:05:39.241  7718  7762 D Compatibility: enabling receiver ResolveInfo{24625347 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-07 12:05:39.251  7771  7771 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-07 12:05:39.251  7718  7762 D Compatibility: enabling receiver ResolveInfo{23274774 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-07 12:05:39.251  7771  7771 D ActivityThread: Added TimaKeyStore provider
,09-07 12:05:39.261  7718  7762 D Compatibility: enabling receiver ResolveInfo{2736f49d com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-07 12:05:39.261  7787  7787 E Zygote  : MountEmulatedStorage(),
09-07 12:05:39.261  7787  7787 I libpersona: KNOX_SDCARD checking this for 10052
09-07 12:05:39.261  7787  7787 E Zygote  : v2
09-07 12:05:39.261  7787  7787 I libpersona: KNOX_SDCARD not a persona
09-07 12:05:39.261  7787  7787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-07 12:05:39.261  1020  1482 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7787 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,09-07 12:05:39.271  7787  7787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-07 12:05:39.271  7787  7787 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL

```
