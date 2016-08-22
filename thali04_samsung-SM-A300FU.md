#### Test 822030602c9dbcd_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
08-22 18:30:22.461  1015  1216 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-22 18:30:22.461  1015  1216 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 266, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 18:30:22.461  1015  1216 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 18:30:22.461  1015  1216 D BatteryService: stay LED for fully charged
08-22 18:30:22.461  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-22 18:30:22.471  1015  1015 I MotionRecognitionService: Plugged
08-22 18:30:22.471  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
--------- beginning of main
08-22 18:30:22.471  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 18:30:22.471  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
08-22 18:30:22.471  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 18:30:22.471  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-22 18:30:22.491  3143  3143 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 18:30:22.491  3143  3253 D HeadsetStateMachine: Disconnected process message: 10
08-22 18:30:22.501  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-22 18:30:22.501  1170  1170 D SViewCoverView: level :100 plugged : 2
08-22 18:30:22.501  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 18:30:22.501  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 18:30:22.501  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:23.071  6683  6683 D AndroidRuntime: 
08-22 18:30:23.071  6683  6683 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 18:30:23.071  6683  6683 D AndroidRuntime: CheckJNI is OFF
08-22 18:30:23.071  6683  6683 D AndroidRuntime: readGMSProperty: start
08-22 18:30:23.071  6683  6683 D AndroidRuntime: readGMSProperty: already setted!!
08-22 18:30:23.071  6683  6683 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 18:30:23.071  6683  6683 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 18:30:23.071  6683  6683 D AndroidRuntime: readGMSProperty: end
08-22 18:30:23.071  6683  6683 D AndroidRuntime: addProductProperty: start
08-22 18:30:23.231  6683  6683 E AffinityControl: AffinityControl: registerfunction enter
08-22 18:30:23.261  6683  6683 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-22 18:30:23.281  1015  1478 E PersonaManagerService: inState():  stateMachine is null !!
08-22 18:30:23.281  1015  1478 I PersonaManagerService: PersonaId don't exist
08-22 18:30:23.281  1015  1478 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-22 18:30:23.291  1015  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 18:30:23.301  1015  1478 W ActivityManager: mDVFSHelper.acquire()
08-22 18:30:23.311   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-22 18:30:23.311   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-22 18:30:23.321  1015  1478 D FocusedStackFrame: Set to : 0
08-22 18:30:23.331  1015  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-22 18:30:23.331  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:23.331  1015  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-22 18:30:23.331  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:23.331  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:23.331  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:23.351  6695  6695 E Zygote  : MountEmulatedStorage()
08-22 18:30:23.351  6695  6695 E Zygote  : v2
08-22 18:30:23.351  6695  6695 I libpersona: KNOX_SDCARD checking this for 10171
08-22 18:30:23.351  6695  6695 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:23.351  6695  6695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:23.351  1015  1478 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6695 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 18:30:23.351  1015  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-22 18:30:23.351  1015  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 18:30:23.351  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 18:30:23.351  1015  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-22 18:30:23.351   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-22 18:30:23.351  6695  6695 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:23.361  6695  6695 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-22 18:30:23.361  1015  1478 D InputDispatcher: Focused application set to: xxxx
08-22 18:30:23.361  1015  1478 D InputDispatcher: Focus left window: 1479
08-22 18:30:23.361  6683  6683 D AndroidRuntime: Shutting down VM
08-22 18:30:23.361  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 18:30:23.361  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 18:30:23.381  6695  6695 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:23.381  6695  6695 D ActivityThread: Added TimaKeyStore provider
08-22 18:30:23.381  1015  1219 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-22 18:30:23.391  1015  1015 V ActivityManager: Display changed displayId=0
08-22 18:30:23.391  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 18:30:23.421  1015  1219 D PersonaManager: isKioskContainerExistOnDevice
08-22 18:30:23.421   287   287 E SMD     : DCD OFF
08-22 18:30:23.441  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-22 18:30:23.461   257  1037 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
08-22 18:30:23.461   257   443 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
08-22 18:30:23.461  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1f476995 token=android.os.BinderProxy@2912ae85 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-22 18:30:23.461  1479  1479 D Launcher: onTrimMemory. Level: 20
08-22 18:30:23.541  6695  6695 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-22 18:30:23.551  6695  6695 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 7214-7216)
08-22 18:30:23.551  6695  6695 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 18:30:23.571  6683  6683 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 18:30:23.581  6695  6695 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a2a8b42}
,08-22 18:30:23.591  6695  6695 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 18:30:23.611  6695  6695 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0,
,08-22 18:30:23.651  6695  6695 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-22 18:30:23.651  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:30:23.661  6695  6695 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 18:30:23.721  6695  6695 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 18:30:23.721  6695  6695 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 18:30:23.721  6695  6695 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 18:30:23.721  6695  6695 I Adreno-EGL: Local Branch: 
08-22 18:30:23.721  6695  6695 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 18:30:23.721  6695  6695 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 18:30:23.721  6695  6695 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 18:30:23.811  6695  6695 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 18:30:23.821  6695  6695 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 18:30:23.831  6695  6695 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-22 18:30:23.841  6695  6695 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 18:30:23.841  6695  6695 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-22 18:30:23.931  1015  1041 W ActivityManager: Activity pause timeout for ActivityRecord{1a232dc6 u0 com.test.thalitest/.MainActivity t2}
,08-22 18:30:23.941  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:30:23.951  6695  6695 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-22 18:30:23.961  6695  6695 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-22 18:30:23.961  6695  6695 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-22 18:30:23.971  6695  6695 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-22 18:30:23.981  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:30:23.981  6695  6695 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:30:24.111  6695  6736 D OpenGLRenderer: Render dirty regions requested: true
,08-22 18:30:24.111  1015  1532 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 18:30:24.111  1015  1532 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 18:30:24.111  1015  1532 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 18:30:24.121  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-22 18:30:24.121  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 18:30:24.121  6695  6723 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-22 18:30:24.131  6695  6695 V ActivityThread: updateVisibility : ActivityRecord{3258d2a2 token=android.os.BinderProxy@6166c97 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-22 18:30:24.131  6695  6695 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-22 18:30:24.131  6695  6695 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-22 18:30:24.141   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-22 18:30:24.151  1015  1509 D InputDispatcher: Focus entered window: 6695
,08-22 18:30:24.151  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 18:30:24.151  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 18:30:24.151  6695  6695 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-22 18:30:24.151  6695  6736 I OpenGLRenderer: Initialized EGL, version 1.4
,08-22 18:30:24.161  6695  6736 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-22 18:30:24.161  6695  6736 D OpenGLRenderer: Enabling debug mode 0
,08-22 18:30:24.181  1015  4218 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 18:30:24.191  1170  1170 I StatusBar: Icon Only
,08-22 18:30:24.191  1170  1170 D PanelView: There is/are notification(s) 
08-22 18:30:24.191  1015  6741 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 18:30:24.201  1015  1046 I ActivityManager: Displayed Component not be shown by security: +778ms (total +879ms)
,08-22 18:30:24.201  1015  1046 W ActivityManager: mDVFSHelper.release()
08-22 18:30:24.211  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a232dc6 u0 com.test.thalitest/.MainActivity t2} time:107870
,08-22 18:30:24.211  6695  6695 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-22 18:30:24.211   257   445 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-22 18:30:24.211   257  1037 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-22 18:30:24.211  1863  1863 I SamsungIME: getCurrentCandidateView
,08-22 18:30:24.211  6695  6695 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6166c97 time:107878
,08-22 18:30:24.261  6695  6695 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6695
,08-22 18:30:24.301  1863  1863 D SamsungIME: Dismiss ExpandCandiate
,08-22 18:30:24.441  6695  6695 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 18:30:24.461  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 18:30:24.481  1015  1320 E Watchdog: !@Sync 3
,08-22 18:30:24.501  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,08-22 18:30:24.511  1863  1863 I SamsungIME: KeybaordView init() : load resources
,08-22 18:30:24.531  6695  6740 D jxcore_app_log: JniHelper::setJavaVM(0xb7a3d2b0), pthread_self() = -1208176064
,08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 18:30:24.531  6695  6740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3772ac08 added. We now have 1 listener(s)
,08-22 18:30:24.531  1863  1863 I SamsungIME: getCurrentKeyboard
08-22 18:30:24.531  1863  1863 I SamsungIME: getTextKeyboard
,08-22 18:30:24.541  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-22 18:30:24.541  6695  6740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:30:24.541  6695  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:30:24.541  6695  6740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 18:30:24.551  6695  6740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1155a987 added. We now have 1 listener(s)
,08-22 18:30:24.551  6695  6740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:24.561  1863  1863 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619,
,08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-22 18:30:24.561  6695  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:24.571  6695  6740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-22 18:30:24.571  6695  6740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:24.571  6695  6740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:24.571  6695  6740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 18:30:24.571  6695  6740 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:30:24.571  6695  6740 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 18:30:24.571  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:24.581  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:24.611  6695  6695 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 18:30:25.151  6695  6749 W jxcore-log: Initializing JXcore engine
08-22 18:30:25.151  6695  6749 W jxcore-log: JXcore engine is ready
,08-22 18:30:25.201  2000  2000 E audit   : type=1400 msg=audit(1471883425.201:205): avc:  denied  { ioctl } for  pid=6749 comm="Thread-1225" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2071 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-22 18:30:25.201  2000  2000 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:25.201  2000  2000 E audit   : type=1300 msg=audit(1471883425.201:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e3ff8f8 items=0 ppid=305 ppcomm=main pid=6749 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1225" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-22 18:30:25.201  2000  2000 E audit   : type=1320 msg=audit(1471883425.201:205): 
,08-22 18:30:25.221  6695  6749 W jxcore-log: Starting JXcore engine
,08-22 18:30:25.321  6695  6749 W jxcore-log: Platform android
08-22 18:30:25.321  6695  6749 W jxcore-log: 
08-22 18:30:25.321  6695  6749 W jxcore-log: Process ARCH arm
08-22 18:30:25.321  6695  6749 W jxcore-log: 
,08-22 18:30:25.521  6695  6749 I jxcore-log: JXcore Cordova bridge is ready!
08-22 18:30:25.521  6695  6749 I jxcore-log: 
,08-22 18:30:25.521  6695  6749 W jxcore-log: JXcore engine is started
,08-22 18:30:25.531  6695  6740 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-22 18:30:25.531  6695  6695 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-22 18:30:26.001   316   316 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-22 18:30:26.001   316   316 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-22 18:30:26.431   287   287 E SMD     : DCD OFF,
,08-22 18:30:29.081  1015  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-22 18:30:29.231  1015  3347 D SSRM:n  : SIOP:: AP = 320,
,08-22 18:30:29.431   287   287 E SMD     : DCD OFF
,08-22 18:30:31.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:31.201  5601  5601 D FactoryTest: Not factory mode
,08-22 18:30:31.201  5601  5601 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-22 18:30:31.201  5601  5601 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-22 18:30:31.201  5601  5601 D MTPRx   : still no open session command from host, so toast
,08-22 18:30:31.201  5601  5601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-22 18:30:31.201  5601  5601 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-22 18:30:31.211  5601  5601 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114871
,08-22 18:30:31.211  1015  1027 E PersonaManagerService: inState():  stateMachine is null !!
,08-22 18:30:31.211  1015  1027 I PersonaManagerService: PersonaId don't exist
08-22 18:30:31.211  1015  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-22 18:30:31.211  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 18:30:31.211  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:31.211  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:31.211  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-22 18:30:31.221  1015  1027 W ActivityManager: mDVFSHelper.acquire()
,08-22 18:30:31.231  1015  1027 D PersonaManager: isKioskContainerExistOnDevice
,08-22 18:30:31.241  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-22 18:30:31.241  1015  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 18:30:31.241  1015  1027 D InputDispatcher: Focused application set to: xxxx
08-22 18:30:31.241  1015  1027 D InputDispatcher: Focus left window: 6695
08-22 18:30:31.241  5601  5601 E MTPRx   : started activity for popup
08-22 18:30:31.251  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 18:30:31.251  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 18:30:31.271  5601  5601 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:30:31.301  5601  5601 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-22 18:30:31.311  1015  1532 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-22 18:30:31.311  1015  1532 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 18:30:31.311  1015  1532 D InputDispatcher: Focused application set to: xxxx
,08-22 18:30:31.311  1015  1532 D InputDispatcher: Focus entered window: 6695
,08-22 18:30:31.321  1015  1478 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 18:30:31.321  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 18:30:31.321  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 18:30:31.321  1015  1478 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2b74e5f1 attribute=null, token = android.os.BinderProxy@ca15a81
,08-22 18:30:31.351  5601  5601 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-22 18:30:31.361  5601  5601 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-22 18:30:31.361  5601  5601 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-22 18:30:31.381  6695  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 18:30:31.381  6695  6695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED,
08-22 18:30:31.381  6695  6695 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 18:30:31.381  6695  6695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-22 18:30:31.381  1015  1028 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-22 18:30:31.381  1015  1028 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-22 18:30:31.391  1015  1028 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-22 18:30:31.391  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 18:30:31.391  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
,08-22 18:30:31.401  6695  6695 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 18:30:31.401  6695  6695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-22 18:30:31.411  6695  6695 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2604fb43 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@18d04da8, 16908290=android.view.AbsSavedState$1@18d04da8}, android:focusedViewId=100}]}]
,08-22 18:30:31.411  6695  6695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-22 18:30:31.411  6695  6695 V ActivityThread: updateVisibility : ActivityRecord{3258d2a2 token=android.os.BinderProxy@6166c97 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-22 18:30:31.411  6695  6695 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-22 18:30:31.411  6695  6695 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-22 18:30:31.411  6695  6695 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6166c97 time:115071
,08-22 18:30:31.411  1015  1219 D PersonaManager: isKioskContainerExistOnDevice
,08-22 18:30:32.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:32.431   287   287 E SMD     : DCD OFF,
,08-22 18:30:32.521  1015  1027 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 18:30:32.521  1015  1027 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 18:30:32.521  1015  1027 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-22 18:30:32.521  1015  1027 D BatteryService: stay LED for fully charged
,08-22 18:30:32.521  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 18:30:32.521  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 18:30:32.531  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
08-22 18:30:32.531  1015  1015 I MotionRecognitionService: Plugged
08-22 18:30:32.531  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 18:30:32.531  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 18:30:32.531  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 18:30:32.541  3143  3143 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 18:30:32.541  3143  3253 D HeadsetStateMachine: Disconnected process message: 10
,08-22 18:30:32.551  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-22 18:30:32.551  1170  1170 D SViewCoverView: level :100 plugged : 2
,08-22 18:30:32.551  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:32.551  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:32.551  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:33.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:33.371  1015  1055 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-22 18:30:34.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:34.221  1015  1041 W ActivityManager: mDVFSHelper.release(),
,08-22 18:30:35.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:35.431   287   287 E SMD     : DCD OFF
,08-22 18:30:36.011   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-22 18:30:36.341  1015  1094 V AlarmManager: waitForAlarm result :4
,08-22 18:30:36.341  1015  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.361  2029  2029 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-22 18:30:36.421  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:36.421  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.421  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.421  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.421  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.471  4801  4801 D ConnectivityManager: CallingUid : 10011, CallingPid : 4801
,08-22 18:30:36.471  1015  1509 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 18:30:36.471  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-22 18:30:36.481  1015  1127 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-22 18:30:36.481  1015  1127 D ConnectivityService: apparently satisfied.  currentScore=60
,08-22 18:30:36.481  4801  6757 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 18:30:36.531  4801  6758 W DriveInitializer: Background init thread started
,08-22 18:30:36.571   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-22 18:30:36.571   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:36.571  4801  6758 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-22 18:30:36.601  2029  2029 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-22 18:30:36.651  1015  1532 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:36.651  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.651  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.651  1015  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.651  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.671  4801  6758 W DriveInitializer: Background init thread ended
,08-22 18:30:36.671  1015  1475 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,08-22 18:30:36.671  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.691  1015  4218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:36.691  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.691  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.691  1015  4218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.691  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.721  4801  6766 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-22 18:30:36.721  4801  6766 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-22 18:30:36.751  2029  2029 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 18:30:36.781  1015  1041 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:36.781  1015  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.781  1015  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.881  1015  1446 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:36.881  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.881  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.881  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.881  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.911  1015  4193 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:36.911  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-22 18:30:36.911  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.911  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.911  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.971  1015  4194 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:36.981  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.981  1015  4194 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.981  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:36.981  1015  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:36.991  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:36.991  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:36.991  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.161  1015  1446 I art     : Explicit concurrent mark sweep GC freed 41292(2MB) AllocSpace objects, 17(272KB) LOS objects, 33% free, 24MB/36MB, paused 2.500ms total 154.864ms
,08-22 18:30:37.201  1015  4194 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.201  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:37.201  1015  4194 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.201  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.201  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:37.201  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:37.201  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:37.201  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:37.221  6771  6771 E Zygote  : MountEmulatedStorage()
08-22 18:30:37.221  6771  6771 E Zygote  : v2
08-22 18:30:37.221  6771  6771 I libpersona: KNOX_SDCARD checking this for 10011
08-22 18:30:37.221  6771  6771 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:37.221  1015  4194 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6771 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-22 18:30:37.221  6771  6771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:37.221  6771  6771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:37.231  6771  6771 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:30:37.251  6771  6771 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:37.251  6771  6771 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:37.271  6771  6771 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-22 18:30:37.271  6771  6771 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-22 18:30:37.311  6771  6771 I MultiDex: VM with version 2.1.0 has multidex support
08-22 18:30:37.311  6771  6771 I MultiDex: install
08-22 18:30:37.311  6771  6771 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-22 18:30:37.341  6771  6771 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-22 18:30:37.401  6771  6771 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-22 18:30:37.401  6771  6771 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3143779e: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-22 18:30:37.401  6771  6771 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-22 18:30:37.421  6771  6771 D ChimeraCfgMgr: Reading stored module config
,08-22 18:30:37.421  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-22 18:30:37.431  1015  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.441  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:37.441  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.441  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.451  1015  4193 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.451  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:37.451  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.451  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.501  2029  2029 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=b86e4000-8cdf-41fa-9061-da2932130ef6
,08-22 18:30:37.511  1015  1446 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 18:30:37.511  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-22 18:30:37.511  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:37.511  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.511  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.521  2029  2029 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 18:30:37.521  2029  2029 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-22 18:30:37.531  6771  6771 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-22 18:30:37.541  6771  6771 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-22 18:30:37.551  6771  6789 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-22 18:30:37.551  1015  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.561  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:37.561  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.561  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.611   282  1013 D WVCdm   : Instantiating CDM.
,08-22 18:30:37.611   282   685 I WVCdm   : CdmEngine::OpenSession
,08-22 18:30:37.611   282   685 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-22 18:30:37.651   282   685 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-22 18:30:37.661  4159  5150 I art     : Explicit concurrent mark sweep GC freed 1452(50KB) AllocSpace objects, 0(0B) LOS objects, 46% free, 4MB/8MB, paused 715us total 23.962ms
,08-22 18:30:37.681   282   685 W WVCdm   : Could not load liboemcrypto.so. Falling Back to L3.  dlopen failed: library "liboemcrypto.so" not found
,08-22 18:30:37.731   282   685 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-22 18:30:37.731   282   721 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-22 18:30:37.731   282   721 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-22 18:30:37.731   282   721 I WVCdm   : CdmEngine::GenerateKeyRequest
,08-22 18:30:37.741   282   721 D WVCdm   : PrepareKeyRequest: nonce=4270139829
,08-22 18:30:37.771  6771  6779 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-22 18:30:37.771  6771  6779 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:37.771  6771  6779 I System.out: (HTTPLog)-Static: isShipBuild true
08-22 18:30:37.771  6771  6779 I System.out: (HTTPLog)-Thread-1199-165564179: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-22 18:30:37.771  6771  6779 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:37.771   277   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 18:30:37.771   277   990 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-22 18:30:37.821  6771  6779 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 18:30:37.821  6771  6779 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6771, getuid(): 10011
,08-22 18:30:37.821  2029  2204 W GCoreFlp: No location to return for getLastLocation()
,08-22 18:30:37.851  1015  4193 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.851  1015  4193 W ActivityManager: userId = 0, bbcId = -10000,
08-22 18:30:37.851  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.851  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 18:30:37.861  1015  1486 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:37.871  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:37.871  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.871  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.871  1015  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-22 18:30:37.871  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:37.871  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:37.871  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:37.901  4801  6767 D UdcContextInitService: registered all accounts: true
,08-22 18:30:37.901  2029  2211 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 18:30:37.911  2029  2223 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-22 18:30:38.061  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-22 18:30:38.061  6695  6749 I jxcore-log: 
,08-22 18:30:38.071  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-22 18:30:38.071  6695  6749 I jxcore-log: 
,08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:38.071  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:38.071  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:38.071  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-22 18:30:38.071  6695  6749 I jxcore-log: 
,08-22 18:30:38.081  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-22 18:30:38.081  6695  6749 I jxcore-log: 
,08-22 18:30:38.121  6771  6779 I qtaguid : Untagging socket 30
,08-22 18:30:38.141  2029  2223 I art     : Explicit concurrent mark sweep GC freed 52557(2MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 11MB/18MB, paused 1.371ms total 75.738ms
,08-22 18:30:38.221  1015  1446 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-22 18:30:38.221  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-22 18:30:38.221  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:38.221  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 18:30:38.221  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:38.431   287   287 E SMD     : DCD OFF
,08-22 18:30:38.461  6800  6800 I dex2oat : ----------------------------------------------------
,08-22 18:30:38.461  6800  6800 I dex2oat : <SS>: S T A R T I N G . . .
08-22 18:30:38.461  6800  6800 I dex2oat : <SS>: Zip is absent. Canceled.
,08-22 18:30:38.461  6800  6800 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-22 18:30:38.501  6800  6800 I dex2oat : dex2oat took 47.230ms (threads: 4)
,08-22 18:30:38.521  6771  6779 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 18:30:38.521  6771  6779 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 18:30:38.521  6771  6779 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 18:30:38.521  6771  6779 I Adreno-EGL: Local Branch: 
08-22 18:30:38.521  6771  6779 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 18:30:38.521  6771  6779 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 18:30:38.521  6771  6779 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 18:30:38.571  1015  3367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 18:30:38.591  6771  6779 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 18:30:38.591  6771  6779 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 18:30:38.591  6771  6779 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 18:30:38.591  6771  6779 I Adreno-EGL: Local Branch: 
08-22 18:30:38.591  6771  6779 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 18:30:38.591  6771  6779 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 18:30:38.591  6771  6779 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 18:30:38.661  6771  6779 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-22 18:30:38.661  6771  6779 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 18:30:38.661  6771  6779 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 18:30:38.661  6771  6779 I Adreno-EGL: Local Branch: 
08-22 18:30:38.661  6771  6779 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 18:30:38.661  6771  6779 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 18:30:38.661  6771  6779 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 18:30:38.801  6695  6749 D ExecuteNativeTests: Running unit tests,
,08-22 18:30:38.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:30:38.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 added. We now have 2 listener(s)
,08-22 18:30:38.901  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 18:30:38.901  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:30:38.901  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:30:38.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:38.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 added. We now have 2 listener(s)
08-22 18:30:38.901  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:38.901  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 18:30:38.911  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:38.911  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:38.911  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:38.911  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:38.921  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:38.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:30:38.921  6695  6749 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-22 18:30:38.921  6695  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 18:30:38.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:38.921  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:38.921  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:38.921  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:38.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:38.921  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.921  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:38.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 removed from the list
08-22 18:30:38.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 removed from the list
08-22 18:30:38.921  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:38.921  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:38.921  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.931  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.931  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.931  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:38.931  6695  6749 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-22 18:30:38.931  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:38.931  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:38.931  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:38.931  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.931  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.931  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.931  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:38.931  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:38.931  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.931  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.931  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.931  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:38.931  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.931  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 18:30:38.951  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:38.951  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:38.951  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:38.951  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.951  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.951  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.951  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:38.951  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:38.951  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.951  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.951  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:38.951  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:38.951  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:38.951  6695  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-22 18:30:38.951  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:38.961  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:38.961  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:38.961  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:38.961  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:30:38.961  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:30:38.961  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:30:38.961  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:38.961  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-22 18:30:38.961  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:38.961  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-22 18:30:38.971  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:38.971  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:30:38.981  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-22 18:30:38.981  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-22 18:30:38.981  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-22 18:30:38.981  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:30:38.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:38.991  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-22 18:30:39.001  3143  3336 D BtGatt.GattService: registerClient() - UUID=0e84319a-cf35-41aa-9a2e-e80f1423b62f
,08-22 18:30:39.041  3143  3240 D BtGatt.GattService: onClientRegistered() - UUID=0e84319a-cf35-41aa-9a2e-e80f1423b62f, clientIf=6
,08-22 18:30:39.041  6695  6703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 18:30:39.051  3143  3335 D BtGatt.GattService: start scan with filters
,08-22 18:30:39.051  3143  3251 D BtGatt.ScanManager: handling starting scan
08-22 18:30:39.051  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 18:30:39.051  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:30:39.051  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:39.051  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:30:39.051  3143  3251 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:39.051  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:39.051  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 18:30:39.061  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:39.061  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 18:30:39.061  3143  3240 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 18:30:39.061  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.061  3143  3251 D BtGatt.ScanManager: allow scan with filters
,08-22 18:30:39.061  3143  3251 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 18:30:39.071  3143  3251 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-22 18:30:39.071  6695  6749 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 18:30:39.071  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 18:30:39.071  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.071  3143  3251 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:30:39.071  3143  3251 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 18:30:39.081  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.081  6695  6749 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:39.081  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.081  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:30:39.081  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:30:39.081  3143  3152 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:30:39.081  3143  3240 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 18:30:39.081  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.081  3143  3336 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:30:39.081  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:30:39.081  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:39.091  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-22 18:30:39.091  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.091  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:30:39.091  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:30:39.091  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:30:39.091  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:30:39.091  3143  3251 D BtGatt.ScanManager: filter size is 1
08-22 18:30:39.091  3143  3251 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 18:30:39.091  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.091  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.091  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.091  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:39.091  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.091  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:39.091  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.091  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.091  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.091  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.091  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.091  6695  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 18:30:39.101  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:39.101  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 18:30:39.101  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.101  3143  3251 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:30:39.101  1015  1219 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-22 18:30:39.101  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-22 18:30:39.101  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:39.101  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-22 18:30:39.101  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.101  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:39.101  3143  3251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 18:30:39.111  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 18:30:39.111  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:39.111  3143  3240 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 18:30:39.111  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.111  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.111  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:30:39.111  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:30:39.111  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:30:39.111  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:30:39.111  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:39.111  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:30:39.121  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.121  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:30:39.121  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:30:39.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:30:39.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:30:39.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:39.131  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:30:39.131  3143  3336 D BtGatt.GattService: registerClient() - UUID=38bd19a2-7351-4246-9821-e83d1635eb6e
,08-22 18:30:39.151  2029  6769 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-22 18:30:39.151  2029  6769 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:39.151  2029  6769 I System.out: (HTTPLog)-Static: isShipBuild true
08-22 18:30:39.151  2029  6769 I System.out: (HTTPLog)-Thread-277-452874294: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-22 18:30:39.151  2029  6769 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:39.151   277   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 18:30:39.151   277   990 D Netd    : getNetworkForDns: using netid 502 for uid 10011
,08-22 18:30:39.151  2029  6769 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 18:30:39.151  2029  6769 I qtaguid : Tagging socket 60 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2029, getuid(): 10011
,08-22 18:30:39.171  3143  3240 D BtGatt.GattService: onClientRegistered() - UUID=38bd19a2-7351-4246-9821-e83d1635eb6e, clientIf=6
,08-22 18:30:39.181  6695  6705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 18:30:39.181  3143  3335 D BtGatt.GattService: start scan with filters
,08-22 18:30:39.181  3143  3251 D BtGatt.ScanManager: handling starting scan
,08-22 18:30:39.181  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:30:39.181  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:30:39.181  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:39.181  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:30:39.181  3143  3240 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-22 18:30:39.181  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.181  3143  3251 D BtGatt.ScanManager: allow scan with filters
08-22 18:30:39.181  3143  3251 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 18:30:39.181  3143  3251 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-22 18:30:39.191  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 18:30:39.191  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.191  3143  3251 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:30:39.191  3143  3251 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 18:30:39.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:30:39.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:30:39.191  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:39.191  3143  3240 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 18:30:39.191  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-22 18:30:39.191  2029  6769 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10011, pid: 2029, getuid(): 10011
,08-22 18:30:39.191  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 18:30:39.191  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.201  6695  6749 I io.jxcore.node.ConnectionHelper: start: OK
,08-22 18:30:39.201  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:30:39.201  6695  6749 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:39.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.201  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-22 18:30:39.201  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.201  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:39.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:39.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-22 18:30:39.201  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:30:39.201  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 18:30:39.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:30:39.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:30:39.201  3143  3152 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:30:39.211  3143  3251 D BtGatt.ScanManager: filter size is 1
08-22 18:30:39.211  3143  3335 D BtGatt.GattService: unregisterClient() - clientIf=6
08-22 18:30:39.211  3143  3251 D BtGatt.ScanManager: delete FilterIndex - 4
,08-22 18:30:39.211  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 18:30:39.211  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.211  3143  3251 D BtGatt.ScanManager: stopping BLe Batch
08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:30:39.211  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:30:39.211  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:30:39.211  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:30:39.211  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 18:30:39.211  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.211  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.211  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:39.211  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.211  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.211  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.211  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.211  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.211  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.211  3143  3251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 18:30:39.221  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.221  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:39.221  3143  3240 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-22 18:30:39.221  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.231  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:30:39.231  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.231  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.231  6695  6749 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.231  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:39.231  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
08-22 18:30:39.231  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-22 18:30:39.231  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:30:39.231  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:39.231  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:30:39.241  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,08-22 18:30:39.241  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.241  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.241  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:30:39.251  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:30:39.251  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:30:39.251  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:30:39.251  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:30:39.251  1015  3347 D SSRM:n  : SIOP:: AP = 340
,08-22 18:30:39.251  3143  3155 D BtGatt.GattService: registerClient() - UUID=ced0ff25-7553-4c6a-ae42-5413dd2dbb0f
,08-22 18:30:39.301  3143  3240 D BtGatt.GattService: onClientRegistered() - UUID=ced0ff25-7553-4c6a-ae42-5413dd2dbb0f, clientIf=6
,08-22 18:30:39.301  6695  6705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 18:30:39.301  3143  3152 D BtGatt.GattService: start scan with filters
08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: handling starting scan
,08-22 18:30:39.301  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-22 18:30:39.301  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:30:39.301  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:30:39.301  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:30:39.301  3143  3240 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 18:30:39.301  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: allow scan with filters,
,08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-22 18:30:39.301  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:30:39.301  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:30:39.301  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:30:39.301   282  1013 I WVCdm   : CdmEngine::CloseSession
08-22 18:30:39.301  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 18:30:39.301  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:30:39.301  3143  3251 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-22 18:30:39.311   282  1013 I WVCdm   : L3 Terminate.
,08-22 18:30:39.311  3143  3240 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 18:30:39.311  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.311  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:30:39.311  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 18:30:39.311  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.321  6695  6749 I io.jxcore.node.ConnectionHelper: start: OK
08-22 18:30:39.321  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.321  6695  6749 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:39.321  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.321  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:30:39.321  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.321  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:30:39.321  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:39.321  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:39.321  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:30:39.321  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:30:39.321  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:30:39.321  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:30:39.321  3143  3155 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:30:39.321  3143  3251 D BtGatt.ScanManager: filter size is 1
,08-22 18:30:39.321  3143  3251 D BtGatt.ScanManager: delete FilterIndex - 5
,08-22 18:30:39.321  3143  3240 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 18:30:39.321  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:30:39.321  3143  3251 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:30:39.321  3143  3152 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 18:30:39.331  3143  3240 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 18:30:39.331  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.331  3143  3251 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 18:30:39.331  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:30:39.331  3143  3240 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 18:30:39.331  3143  3240 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:30:39.331  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:30:39.331  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:30:39.331  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:30:39.331  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:30:39.341  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.341  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.341  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:39.341  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.341  6695  6749 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-22 18:30:39.341  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.341  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.341  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:30:39.341  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.341  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.341  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.341  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.341  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.341  6695  6749 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-22 18:30:39.341  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.341  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.341  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.341  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.341  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.341  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.341  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.341  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.341  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.341  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.341  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:39.351  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.351  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:30:39.351  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.351  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.351  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.351  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.351  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.351  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.351  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.351  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.351  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.351  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.351  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.351  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.351  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.351  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.351  6695  6749 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-22 18:30:39.351  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.361  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.361  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.361  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.361  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.361  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.361  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.361  6695  6749 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-22 18:30:39.361  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.361  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.361  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.361  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.361  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.361  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list,
08-22 18:30:39.361  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.361  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.361  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.371  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-22 18:30:39.371  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:39.371  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-22 18:30:39.371  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.371  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.371  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.371  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.371  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.371  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.371  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.371  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.371  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.371  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.371  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.371  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:39.371  6695  6749 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:39.371  6695  6749 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-22 18:30:39.371  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-22 18:30:39.371  6695  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:30:39.371  6695  6749 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:39.371  6695  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:30:39.371  6695  6749 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-22 18:30:39.371  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:39.371  6695  6749 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-22 18:30:39.371  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-22 18:30:39.381  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-22 18:30:39.381  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-22 18:30:39.381  6695  6749 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-22 18:30:39.381  6695  6749 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-22 18:30:39.381  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.381  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.381  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.381  2029  2223 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.381  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.381  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.381  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-22 18:30:39.381  6695  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1289)
08-22 18:30:39.381  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.381  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.381  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.381  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.381  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.381  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.381  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.381  6695  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1289
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.381  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.381  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.391  6695  6749 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.391  2029  2223 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-22 18:30:39.391  6695  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:39.391  6695  6749 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-22 18:30:39.391  6695  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-22 18:30:39.391  6695  6749 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-22 18:30:39.391  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.391  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.391  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.391  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.391  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.391  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.391  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release:, 1 listener(s) left
,08-22 18:30:39.401  2029  2223 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-22 18:30:38.002+0200, stopTime=2016-08-22 18:30:39.409+0200, duration=1407ms
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.401  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.401  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.401  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.401  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.401  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:3,9.401  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.401  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.401  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:30:39.401   277   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 18:30:39.401   277   990 D Netd    : getNetworkForDns: using netid 502 for uid 10011
08-22 18:30:39.401  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-22 18:30:39.401  6695  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-22 18:30:39.411  6695  6695 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.411  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.411  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.411  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.411  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6813 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
,08-22 18:30:39.411  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:39.411  2029  6816 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
,08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.411  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.411  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:30:39.411  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:30:39.411  6695  6749 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,08-22 18:30:39.411  6695  6821 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-22 18:30:39.411  6695  6813 D BluetoothSocket: connect(): myUserId = 0
08-22 18:30:39.411  6695  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-22 18:30:39.411  6695  6821 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-22 18:30:39.411  6695  6813 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:39.411  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-22 18:30:39.411  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.411  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.411  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
,08-22 18:30:39.411  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.411  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.411  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.411  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.411  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-22 18:30:39.411  6695  6695 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-22 18:30:39.421  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.421  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.421  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.421  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.421  3143  3155 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:30:39.421  6695  6813 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[106]}
,08-22 18:30:39.421  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.421  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.421  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.421  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.421  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.421  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.421  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.421  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.421  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.421  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.421  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.421  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.421  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.421  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.431  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
,08-22 18:30:39.431  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:30:39.431  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:30:39.431  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:30:39.431  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.431  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.431  6695  6749 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bb00c31 not in the list
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:30:39.431  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:30:39.431  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.431  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.431  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:30:39.431  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:30:39.431  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:30:39.431  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c924f16 not in the list
08-22 18:30:39.431  6695  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:39.431  6695  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-22 18:30:39.431  6695  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-22 18:30:39.431  6695  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 18:30:39.431  6695  6749 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-22 18:30:39.431  6695  6749 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-22 18:30:39.431  6695  6749 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-22 18:30:39.431  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:39.431  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1763c008 added. We now have 2 listener(s)
08-22 18:30:39.431  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:30:39.441  6695  6749 D BluetoothAdapter: enable()
,08-22 18:30:39.441  6695  6749 D BluetoothAdapter: enable(): BT is already enabled..!
,08-22 18:30:39.441  1015  4193 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 18:30:39.441  1015  4193 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 18:30:39.441  1015  4193 D SecContentProvider2: mCursor = null
,08-22 18:30:39.441  1015  4193 D WifiService: setWifiEnabled: true pid=6695, uid=10171
,08-22 18:30:39.451  1015  4193 W ActivityManager: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 18:30:39.451  1015  4193 W WifiService: Failed getting userId using ActivityManagerNative
08-22 18:30:39.451  1015  4193 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 18:30:39.451  1015  4193 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 18:30:39.451  1015  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 18:30:39.451  1015  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 18:30:39.451  1015  4193 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 18:30:39.451  1015  4193 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 18:30:39.451  1015  4193 D SettingsProvider: name = wifi_on
,08-22 18:30:39.451  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:39.451  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@282b63a1 added. We now have 3 listener(s)
08-22 18:30:39.451  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:39.461  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:39.461  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25aa9c6 added. We now have 4 listener(s)
08-22 18:30:39.461  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:39.461  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:30:39.461  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3578cd87 added. We now have 5 listener(s)
08-22 18:30:39.461  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:39.471  1015  1478 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 18:30:39.471  1015  1478 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 18:30:39.471  1015  1478 D SecContentProvider2: mCursor = null
,08-22 18:30:39.471  1015  1478 D WifiService: setWifiEnabled: false pid=6695, uid=10171
,08-22 18:30:39.471  1015  1478 D SettingsProvider: name = wifi_on
,08-22 18:30:39.471  6695  6749 D BluetoothAdapter: disable()
,08-22 18:30:39.471  1015  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-22 18:30:39.481  1350  1350 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 18:30:39.481  1350  1350 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 18:30:39.481  1350  1350 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-22 18:30:39.481  1350  1350 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 18:30:39.481  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:39.491  1015  1027 D SettingsProvider: name = bluetooth_on
,08-22 18:30:39.501  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-22 18:30:39.511  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 18:30:39.521  3143  3234 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-22 18:30:39.521  3143  3234 D BluetoothAdapterProperties: Setting state to 13
08-22 18:30:39.521  3143  3234 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 18:30:39.521  3143  3234 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:39.521  3143  3234 D BluetoothAdapterService: updateAdapterState state is 13
,08-22 18:30:39.521  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:30:39.521  1015  4193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:39.521  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 18:30:39.521  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:39.521  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:39.521  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:39.521  3143  3234 D BluetoothAdapterService: Autoconnection is available 
08-22 18:30:39.521  3143  3234 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 18:30:39.521  3143  3234 D BluetoothAdapterService: terminating service from this receiver
08-22 18:30:39.521  3143  3143 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-22 18:30:39.521  3143  3143 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b297ee4, channel: 19, state: LISTENING
,08-22 18:30:39.521  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-22 18:30:39.521  3143  3143 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b297ee4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c79324c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dacaf4dmSocket: android.net.LocalSocket@27e4a02 impl:android.net.LocalSocketImpl@9de4f13 fd:FileDescriptor[74]
08-22 18:30:39.521  3143  3143 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27e4a02 impl:android.net.LocalSocketImpl@9de4f13 fd:FileDescriptor[74]
,08-22 18:30:39.531  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.531  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:39.531  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:39.531  1015  4218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:39.531  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:39.531  3143  3234 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 18:30:39.531  3143  3234 D BluetoothAdapterProperties: mDiscovering is false
08-22 18:30:39.531  1015  1486 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-22 18:30:39.531  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:39.531  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.531  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:30:39.531  3143  3234 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-22 18:30:39.531  1300  1300 D BluetoothPbap: Proxy object disconnected
08-22 18:30:39.531  1300  1300 D PbapServerProfile: Bluetooth service disconnected
,08-22 18:30:39.541  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-22 18:30:39.541  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.541  3143  3240 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 18:30:39.541  3143  3240 D BluetoothAdapterProperties: Scan Mode:20
,08-22 18:30:39.541  3143  3234 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 18:30:39.541  3143  3234 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 18:30:39.541  3143  3234 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-22 18:30:39.541  3143  3234 E bt-btif : cmd socket is not created
08-22 18:30:39.541  3143  5174 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-22 18:30:39.541  3143  3272 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-22 18:30:39.541  3143  3272 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-22 18:30:39.541  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:39.541  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:39.541  3143  3272 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 18:30:39.541  3143  3234 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-22 18:30:39.551  6695  6813 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@b7998dd, channel: -1, state: INIT,
08-22 18:30:39.551  6695  6813 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@b7998dd, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@7479c52, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@248abb23mSocket: android.net.LocalSocket@34288820 impl:android.net.LocalSocketImpl@377be5d9 fd:FileDescriptor[106]
08-22 18:30:39.551  6695  6813 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@34288820 impl:android.net.LocalSocketImpl@377be5d9 fd:FileDescriptor[106]
08-22 18:30:39.551  6695  6813 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1289)
,08-22 18:30:39.551  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 18:30:39.551  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-22 18:30:39.561  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:39.561  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-22 18:30:39.561  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.561  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:39.571  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-22 18:30:39.571  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-22 18:30:39.581  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 18:30:39.581  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:39.581  1170  1170 D BluetoothTile:  getBluetoothState : 13
,08-22 18:30:39.581  1863  1863 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:39.581  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:39.581  3143  3143 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@ba1f349, channel: 5, state: LISTENING
08-22 18:30:39.581  3143  3143 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@ba1f349, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fb5c295, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3f8b044emSocket: android.net.LocalSocket@bd4c96f impl:android.net.LocalSocketImpl@19d3c67c fd:FileDescriptor[76]
08-22 18:30:39.581  3143  3143 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@bd4c96f impl:android.net.LocalSocketImpl@19d3c67c fd:FileDescriptor[76]
,08-22 18:30:39.581  3143  3143 I BtOppRfcommListener: stopping Accept Thread
,08-22 18:30:39.581  3143  3143 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@58d7b05, channel: 12, state: LISTENING
08-22 18:30:39.581  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:39.581  3143  3143 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@58d7b05, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36160277, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2397175amSocket: android.net.LocalSocket@1a0e8d8b impl:android.net.LocalSocketImpl@bd4ce68 fd:FileDescriptor[80]
,08-22 18:30:39.581  3143  3143 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1a0e8d8b impl:android.net.LocalSocketImpl@bd4ce68 fd:FileDescriptor[80]
,08-22 18:30:39.581  3143  5174 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-22 18:30:39.591  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:39.591  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:39.591  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:39.591  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 18:30:39.591  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:39.591  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:39.591  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:39.591  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:39.591  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:39.601  1015  1478 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:39.601  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 18:30:39.601  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 18:30:39.601  1015  1446 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 18:30:39.601  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:39.601  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:39.601  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:39.601  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 18:30:39.601  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 18:30:39.601  2029  6816 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
,08-22 18:30:39.601  3143  3143 V BluetoothOppManager: cleanUp...
,08-22 18:30:39.611  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:39.611  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:39.621  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:39.621  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 18:30:39.621  1015  4218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 18:30:39.631  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:39.631  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:39.631  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:39.631  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:39.641  6828  6828 E Zygote  : MountEmulatedStorage(),
08-22 18:30:39.641  1015  4218 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6828 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-22 18:30:39.641  6828  6828 E Zygote  : v2
08-22 18:30:39.641  6828  6828 I libpersona: KNOX_SDCARD checking this for 10055
08-22 18:30:39.641  6828  6828 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:39.641  6828  6828 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:39.651  6828  6828 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:39.651  6828  6828 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:39.681  6828  6828 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:39.681  6828  6828 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:39.711  6828  6828 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 18:30:39.741  6828  6828 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 18:30:39.741  6828  6828 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-22 18:30:39.741  6828  6828 D UserAnalysis: Create SecureDbHelper
,08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:39.751  3143  3272 W bt-btif : ag scb idx 1 not allocated
08-22 18:30:39.751  3143  3272 W bt-btif : ag scb idx 2 not allocated
08-22 18:30:39.751  3143  3272 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 18:30:39.751  6828  6828 D IntelligenceServiceApplication: onCreate()
,08-22 18:30:39.751  3143  3324 I bt_userial_mct: exiting userial_read_thread
08-22 18:30:39.751  3143  3324 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 18:30:39.751  3143  3240 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,08-22 18:30:39.751  3143  3275 I bt_vendor: hw_epilog_process
08-22 18:30:39.751  3143  3240 D bt_userial_mct: userial_close
,08-22 18:30:39.751  3143  3240 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-22 18:30:39.751  1015  1027 I ActivityManager: Killing 6366:com.samsung.helphub/1000 (adj 15): empty #21
,08-22 18:30:39.761  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-22 18:30:39.761  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:39.761  6828  6828 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-22 18:30:39.761  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:39.761  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:39.761  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:39.771  6847  6847 E Zygote  : MountEmulatedStorage()
08-22 18:30:39.771  6847  6847 I libpersona: KNOX_SDCARD checking this for 10105
08-22 18:30:39.771  6847  6847 E Zygote  : v2
08-22 18:30:39.771  6847  6847 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:39.771  6847  6847 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:39.771  1015  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6847 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-22 18:30:39.771  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-22 18:30:39.781  6847  6847 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:39.781  6828  6828 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 18:30:39.781  6847  6847 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-22 18:30:39.781  6828  6828 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 18:30:39.791  6847  6847 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:39.791  6847  6847 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:39.801   305   305 I art     : Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 613us total 29.265ms,
,08-22 18:30:39.821   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 17.550ms
,08-22 18:30:39.841   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 582us total 16.812ms
,08-22 18:30:39.911   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 18:30:39.911   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:39.911  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-22 18:30:39.921  6847  6866 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 18:30:39.921   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 18:30:39.921   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:39.921  6847  6866 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 18:30:40.031  3143  3240 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 18:30:40.031  3143  3240 I bt_vendor: bluetooth satus is on
08-22 18:30:40.031  3143  3240 I bt_vendor: bt-vendor : resetting BT status
08-22 18:30:40.031  3143  3240 I bt_vendor: Starting hciattach daemon
08-22 18:30:40.031  3143  3240 I bt_vendor: try to set false
,08-22 18:30:40.031  3143  3240 I bt_vendor: Starting hciattach daemon
08-22 18:30:40.031  3143  3240 I bt_vendor: try to set false
,08-22 18:30:40.031  3143  3240 I bt_vendor: cleanup
,08-22 18:30:40.031  3143  3272 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-22 18:30:40.031  3143  3240 I GKI_LINUX: GKI_exit_task 0 done
08-22 18:30:40.031  3143  3240 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-22 18:30:40.031  3143  3234 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-22 18:30:40.031  3143  3234 D BtConfig.SecureMode: isSecureModeOn:false
08-22 18:30:40.031  3143  3234 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-22 18:30:40.031  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 18:30:40.031  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-22 18:30:40.031  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-22 18:30:40.031  1015  4193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.031  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.031  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-22 18:30:40.031  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.031  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:40.041  1015  1446 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.031  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 18:30:40.041  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-22 18:30:40.031  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 18:30:40.031  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 18:30:40.041  3143  3143 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:40.041  3143  3143 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:30:40.041  3143  3143 D BtGatt.GattService: stop()
08-22 18:30:40.041  3143  3143 D BtGatt.AdvertiseManager: advertise clients cleared
08-22 18:30:40.041  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.041  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:40.041  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:40.041  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-22 18:30:40.041  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 18:30:40.041  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.041  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-22 18:30:40.041  1015  4194 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.041  3143  3143 D HeadsetService: Received stop request...Stopping profile...
08-22 18:30:40.041  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:40.041  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.041  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.041  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:40.041  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-22 18:30:40.041  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:40.041  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.051  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-22 18:30:40.051  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.051  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 18:30:40.051  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-22 18:30:40.051  1300  1300 D HeadsetProfile: Bluetooth service disconnected
,08-22 18:30:40.051  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.051  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.051  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:40.051  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-22 18:30:40.051  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 18:30:40.051  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 18:30:40.051  1015  4218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:40.051  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-22 18:30:40.051  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.051  1015  4218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.051  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:40.051  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-22 18:30:40.051  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 18:30:40.051  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 18:30:40.051  1015  4193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.051  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 18:30:40.061  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.061  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:40.061  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:40.061  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.061  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:40.061  3143  3234 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:40.061  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:40.061  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 18:30:40.061  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:40.061  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:40.061  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:40.061  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-22 18:30:40.061  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-22 18:30:40.061  3143  3234 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 18:30:40.061  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:40.061  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.061  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 18:30:40.061  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.061  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:40.061  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:40.071  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:40.071  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 18:30:40.071  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 18:30:40.071  3143  3234 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-22 18:30:40.071  3143  3234 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 18:30:40.071  3143  3234 D BluetoothAdapterState: Stopping profile services that were post enabled
08-22 18:30:40.071  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-22 18:30:40.071  3143  3143 D A2dpService: Received stop request...Stopping profile...
,08-22 18:30:40.071  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.071  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:40.071  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 18:30:40.081  1300  1300 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:40.081  1300  1300 D A2dpProfile: Bluetooth service disconnected
08-22 18:30:40.081  3143  3260 D A2dpStateMachine: Exit Disconnected: -1
,08-22 18:30:40.081  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-22 18:30:40.081  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 18:30:40.081  3143  3143 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 18:30:40.081  3143  3143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-22 18:30:40.081  3143  3143 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-22 18:30:40.081  3143  3143 D HidService: Received stop request...Stopping profile...
,08-22 18:30:40.081  3143  3143 D HidService: Stopping Bluetooth HidService
08-22 18:30:40.091  3143  3143 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:30:40.091  3143  3143 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 18:30:40.091  3143  3143 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:30:40.091  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.091  3143  3143 D HealthService: Received stop request...Stopping profile...
,08-22 18:30:40.091  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.091  1300  1300 D BluetoothInputDevice: Proxy object disconnected
08-22 18:30:40.091  1300  1300 D HidProfile: Bluetooth service disconnected
,08-22 18:30:40.091  3143  3143 D PanService: Received stop request...Stopping profile...
,08-22 18:30:40.091  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.091  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 18:30:40.091  3143  3143 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:30:40.091  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 18:30:40.091  1300  1300 D PanProfile: Bluetooth service disconnected
,08-22 18:30:40.101  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.101  3143  3143 D SapService: Received stop request...Stopping profile...
,08-22 18:30:40.101  3143  3143 D SapService: Stopping Bluetooth SapService
08-22 18:30:40.101  3143  3143 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:40.101  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-22 18:30:40.101  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:40.101  3143  3143 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 18:30:40.101  3143  3143 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:40.101  3143  3143 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 18:30:40.101  3143  3261 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-22 18:30:40.101  1300  1300 D BluetoothMap: Proxy object disconnected
08-22 18:30:40.101  1300  1300 D MapProfile: Bluetooth service disconnected
08-22 18:30:40.101  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 18:30:40.101  1300  1300 D SapProfile: Bluetooth service disconnected
,08-22 18:30:40.101  3143  3143 I GKI_LINUX: GKI_exit_task 2 done
08-22 18:30:40.101  3143  3143 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-22 18:30:40.101  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 18:30:40.101  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:40.101  3143  3143 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.111  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.111  3143  3143 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 18:30:40.111  6847  6847 D ,StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	a,t android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 18:30:40.111  1015  1446 I ActivityManager: Killing 6398:com.google.android.apps.plus/u0a117 (adj 15): empty #21
08-22 18:30:40.111  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:30:40.111  3143  3143 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 18:30:40.111  6847  6847 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at a,ndroid.os.Looper.loop(Looper.java:145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:40.111  6847  6847 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:40.111  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-22 18:30:40.111  3143  3143 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:40.111  3143  3143 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 18:30:40.111  3143  3143 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 18:30:40.111  3143  3143 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 18:30:40.111  3143  3143 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-22 18:30:40.111  3143  3234 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 18:30:40.111  3143  3234 D BluetoothAdapterProperties: Setting state to 10
08-22 18:30:40.111  3143  3234 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 18:30:40.111  3143  3234 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:40.111  3143  3234 D BluetoothAdapterService: updateAdapterState state is 10
08-22 18:30:40.121  3143  3234 D BluetoothAdapterService: Autoconnection is available 
08-22 18:30:40.121  3143  3234 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 18:30:40.121  3143  3234 I BluetoothAdapterState: Entering OffState
08-22 18:30:40.121  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 18:30:40.121  1450  3303 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.121  1450  3303 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.121  1438  1449 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.121  1438  1449 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.121  1300  1310 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:30:40.121  1300  1315 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:40.121  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-22 18:30:40.121  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.121  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.121  1300  1310 D Bluetoothsap: onBluetoothStateChange: up=false
08-22 18:30:40.121  1300  1310 D Bluetoothsap: Unbinding service...
08-22 18:30:40.131  1300  1315 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:30:40.131  3143  3335 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:40.131  3143  3152 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.131  3143  3152 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.131  6695  6703 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.131  6695  6703 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.131  6695  6703 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 18:30:40.131  6695  6703 D BluetoothLeAdvertiser: Exit stop advertising
08-22 18:30:40.131  6695  6703 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-22 18:30:40.131  6695  6703 D BluetoothLeScanner: Exiting stopAllScan
08-22 18:30:40.131  1431  1467 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.131  1431  1467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.131  1300  1315 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.131  1300  1315 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.131  1170  1181 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.131  1170  1181 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.131  1300  1315 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:30:40.141  2029  2039 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:40.141  2029  2039 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:40.141  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:40.141  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-22 18:30:40.141  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 18:30:40.151  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:40.151  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-22 18:30:40.151  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-22 18:30:40.151  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.151  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 18:30:40.151  1170  1738 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:40.161  1170  1170 D BluetoothTile:  getBluetoothState : 10
08-22 18:30:40.161  1170  1738 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  3143  3240 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-22 18:30:40.161  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  1015  4194 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 18:30:40.161  2029  2221 D BluetoothAdapter: 931053858: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  2029  2221 D BluetoothAdapter: 931053858: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:40.161  1863  1863 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 18:30:40.161  1015  4218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-22 18:30:40.161  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-22 18:30:40.161  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:40.171  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.171  3143  3143 I GKI_LINUX: GKI_exit_task 1 done
08-22 18:30:40.171  3143  3143 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-22 18:30:40.171  3143  3143 I BluetoothServiceJni: cleanupNative: return from cleanup
08-22 18:30:40.171  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:40.171  1015  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:40.171  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-22 18:30:40.171  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.171  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:40.171  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-22 18:30:40.171  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 18:30:40.171  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 18:30:40.171  1015  1216 D ActivityManager: retrieveServiceLocked(): compon,ent = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
08-22 18:30:40.181  3143  3143 I art     : System.exit called, status: 0
08-22 18:30:40.181  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.181  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.181  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
08-22 18:30:40.181  3143  3143 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 18:30:40.191  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:40.191  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive,
,08-22 18:30:40.191  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:40.191  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 18:30:40.191  6847  6865 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-22 18:30:40.211  1015  1509 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:40.211  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:40.211  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:40.211  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 18:30:40.261  1015  1219 I ActivityManager: Process com.android.bluetooth (pid 3143)(adj 0) has died(25,726)
,08-22 18:30:40.261  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 18:30:40.271  1015  1028 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:40.271  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 18:30:40.271  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.271  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-22 18:30:40.271  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:40.281  2029  6885 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-22 18:30:40.281  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:40.281  1015  1446 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:40.281  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:40.281  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:40.281  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:40.291  1350  1350 I wpa_supplicant: nl80211: Received scan results (12 BSSes),
,08-22 18:30:40.291  1015  1124 D WifiP2pService: InactiveState{ what=147461 }
,08-22 18:30:40.291  1015  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-22 18:30:40.291  1015  1124 D WifiP2pService: DefaultState{ what=147461 }
,08-22 18:30:40.291  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-22 18:30:40.291  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 18:30:40.301   277   994 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:40.301  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:30:40.301  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.301  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-22 18:30:40.301  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 18:30:40.301  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
08-22 18:30:40.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.301  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-22 18:30:40.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:40.311  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-22 18:30:40.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.301  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:40.301  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:40.301  2029  2998 V NativeCrypto: Read error: ssl=0xb7f354d8: I/O error during system call, Connection timed out
08-22 18:30:40.311  2029  2998 V NativeCrypto: SSL shutdown failed: ssl=0xb7f354d8: I/O error during system call, Broken pipe
08-22 18:30:40.311  2029  6816 I qtaguid : Untagging socket 66
08-22 18:30:40.311  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 18:30:40.311  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:40.311  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.311  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
,08-22 18:30:40.311  2029  2998 E GCM     : Wifi connection closed with errorCode 20
,08-22 18:30:40.321  1015  4218 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-22 18:30:40.321  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:40.321  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:40.321  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-22 18:30:40.321  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:40.321  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,08-22 18:30:40.321  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.321  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:40.321  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.321  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
,08-22 18:30:40.321  1015  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:30:40.321  1015  1712 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:40.321  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.321  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.321  1015  1712 I qtaguid : Tagging socket 348 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1015, getuid(): 1000
08-22 18:30:40.321  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:40.331  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-22 18:30:40.331  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:40.331  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 18:30:40.331  1015  1446 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:40.331  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.331  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:40.331  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:40.341  1015  4194 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:40.341  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:40.341  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:30:40.341  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 18:30:40.351  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:40.351  2029  6885 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-22 18:30:40.351  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:40.351  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 18:30:40.351  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 18:30:40.351  1614  1614 I Hs20UtilService: Starting #8
08-22 18:30:40.351  1614  1635 I Hs20UtilService: Message received 5007
08-22 18:30:40.351  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 18:30:40.361  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 18:30:40.361  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 18:30:40.361  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 18:30:40.361  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 18:30:40.361  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 18:30:40.361  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:40.361  1015  1046 D WifiDisplayController: disconnect
08-22 18:30:40.361  1015  1046 D WifiDisplayController: updateConnection
08-22 18:30:40.361  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:40.361  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 18:30:40.361  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:40.361  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-22 18:30:40.361  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:40.361  1015  1124 D WifiP2pService: P2pDisablingState
,08-22 18:30:40.361  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:30:40.361  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:40.371  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-22 18:30:40.371  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 18:30:40.371  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 18:30:40.371  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 18:30:40.371  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 18:30:40.371  1015  1124 D WifiP2pService: p2p socket connection lost
08-22 18:30:40.371  1015  1125 E WifiNative-wlan0: do suspend true
08-22 18:30:40.371  1015  1124 D WifiP2pService: P2pDisabledState
,08-22 18:30:40.371  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 18:30:40.391  1015  1712 I qtaguid : Untagging socket 348,
08-22 18:30:40.391  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
08-22 18:30:40.391  1015  1712 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:40.391  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
,08-22 18:30:40.391   277   994 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:40.391  1015  4194 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 18:30:40.391   277   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 18:30:40.391  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 18:30:40.391   277   990 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-22 18:30:40.401  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-22 18:30:40.391  2029  6816 I qtaguid : Untagging socket 47
08-22 18:30:40.401  1015  1127 V NetworkStats: updateIfacesLocked(),
08-22 18:30:40.391  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:40.401  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-22 18:30:40.391  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.401  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
08-22 18:30:40.401  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.401  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:40.401  2029  6816 I qtaguid : Untagging socket 47
08-22 18:30:40.401  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:40.401  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:40.401  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.401  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:40.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.401  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.401  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
08-22 18:30:40.401  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-22 18:30:40.401  1015  1127 V NetworkStats: performPollLocked() took 6ms
08-22 18:30:40.401  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
08-22 18:30:40.401  2029  6816 I qtaguid : Untagging socket 47
08-22 18:30:40.401  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:30:40.401  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.401  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
08-22 18:30:40.401  2029  6816 I qtaguid : Untagging socket 47
08-22 18:30:40.401  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:40.401  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.401  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
08-22 18:30:40.401  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 18:30:40.401  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.401  2029  6816 I qtaguid : Untagging socket 47
,08-22 18:30:40.401  2029  6816 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-22 18:30:40.401  2029  6816 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-22 18:30:40.401  2029  6816 I qtaguid : Tagging socket 47 with tag 1000310500000000{268448005,0} for uid 10011, pid: 2029, getuid(): 10011
08-22 18:30:40.401  2029  6816 I qtaguid : Untagging socket 47
,08-22 18:30:40.401  1350  1350 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 18:30:40.411  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.411  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 18:30:40.411  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:30:40.411  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.411  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:40.411  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.411  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-22 18:30:40.411  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.411  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:40.421  1170  1729 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 18:30:40.421  1015  1712 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:40.421  4801  6757 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-22 18:30:40.421  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 18:30:40.421  1015  1127 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:30:40.421  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 18:30:40.421  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-22 18:30:40.421  1015  1127 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-22 18:30:40.421  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-22 18:30:40.421  1450  1450 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-22 18:30:40.421  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-22 18:30:40.421  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:40.421  1015  1125 D SecContentProvider2: mCursor = null
08-22 18:30:40.421  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.421  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:40.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.421  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:40.421  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-22 18:30:40.421  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 18:30:40.421  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:40.431  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:40.431  1170  1170 D HotspotTile: onReceive : 0, 0
,08-22 18:30:40.431  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-22 18:30:40.431  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 18:30:40.431  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:40.441  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 18:30:40.441  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-22 18:30:40.441  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:40.441  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.441  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:40.441  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED,
08-22 18:30:40.441  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.441  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 18:30:40.441  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.441  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:40.441  1015  1122 V NetworkStats: updateIfacesLocked()
08-22 18:30:40.441  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.441  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 18:30:40.441  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-22 18:30:40.441  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:40.441  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:40.441  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:30:40.441  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:40.441  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:40.441  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit()
08-22 18:30:40.441  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-22 18:30:40.441  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:40.441  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:40.441  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:30:40.441  1015  1045 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-22 18:30:40.441  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
08-22 18:30:40.441  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: updateDataNetType()
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-22 18:30:40.451  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 18:30:40.451  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.451  1015  1535 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-22 18:30:40.451  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.451  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.451  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.451  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 18:30:40.451  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.451  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.451  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.451  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.451  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.451  1015  1122 V NetworkStats: performPollLocked() took 11ms
,08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:40.451  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:40.451  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:40.461  6892  6892 E Zygote  : MountEmulatedStorage()
,08-22 18:30:40.461  6892  6892 I libpersona: KNOX_SDCARD checking this for 10064
08-22 18:30:40.461  6892  6892 E Zygote  : v2
08-22 18:30:40.461  6892  6892 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:40.471  6892  6892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 18:30:40.471  1015  1535 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6892 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:30:40.471  6892  6892 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:40.471  6892  6892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:40.481  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:40.481  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:40.491  1350  1350 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 18:30:40.491  2029  2029 E ctxmgr  : [BaseServerTask]Server task (FetchAclSet) got error response.
08-22 18:30:40.491  2029  2029 E ctxmgr  : com.android.volley.NoConnectionError: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:151)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at iss.performRequest(:com.google.android.gms:64)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.volley.NetworkDispatcher.run(:com.google.android.gms:113)
08-22 18:30:40.491  2029  2029 E ctxmgr  : Caused by: java.net.ConnectException: failed to connect to www.googleapis.com/216.58.208.42 (port 443) after 60000ms: connect failed: ENETUNREACH (Network is unreachable)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:124)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:183)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at java.net.PlainSocketImpl.connect(PlainSocketImpl.java:456)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at java.net.Socket.connect(Socket.java:882)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.Platform.connectSocket(Platform.java:139)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.Connection.connect(Connection.java:1194)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.connect(HttpEngine.java:393)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpEngine.sendRequest(HttpEngine.java:296)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.execute(HttpURLConnectionImpl.java:399)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.connect(HttpURLConnectionImpl.java:110)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpURLConnectionImpl.getOutputStream(HttpURLConnectionImpl.java:221)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.DelegatingHttpsURLConnection.getOutputStream(DelegatingHttpsURLConnection.java:218)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.okhttp.internal.http.HttpsURLConnectionImpl.getOutputStream(HttpsURLConnectionImpl.java:25)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:943)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.a(:com.google.android.gms:761)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:669)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.google.android.gms.http.GoogleHttpClient.execute(:com.google.android.gms:653)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.volley.toolbox.HttpClientStack.performRequest(:com.google.android.gms:87)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at isr.performRequest(:com.google.android.gms:63)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(:com.google.android.gms:96)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	... 2 more
08-22 18:30:40.491  2029  2029 E ctxmgr  : Caused by: android.system.ErrnoException: connect failed: ENETUNREACH (Network is unreachable)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at libcore.io.Posix.connect(Native Method)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at libcore.io.BlockGuardOs.connect(BlockGuardOs.java:111)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at libcore.io.IoBridge.connectErrno(IoBridge.java:154)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	at libcore.io.IoBridge.connect(IoBridge.java:122)
08-22 18:30:40.491  2029  2029 E ctxmgr  : 	... 21 more
,08-22 18:30:40.501  2029  2223 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-22 18:30:40.501  6892  6892 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:40.501  6892  6892 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:40.521  6892  6892 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-22 18:30:40.531  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.531  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.541  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.541  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.541  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.541  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:30:40.541  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 18:30:40.541  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.541  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.541  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.541  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 18:30:40.551  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.551  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.551  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.551  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.551  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.551  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.551  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.561  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.561  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.561  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.561  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 18:30:40.561  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 18:30:40.561  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 18:30:40.561  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 18:30:40.561  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-22 18:30:40.561  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.571  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.571  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-22 18:30:40.571  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.571  1450  1450 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-22 18:30:40.571  1450  1450 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-22 18:30:40.581  6892  6892 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 18:30:40.581  1015  4218 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-22 18:30:40.581  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:40.581  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.581  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.581  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:40.591  6922  6922 E Zygote  : MountEmulatedStorage()
,08-22 18:30:40.591  6922  6922 E Zygote  : v2
08-22 18:30:40.591  6922  6922 I libpersona: KNOX_SDCARD checking this for 10065
08-22 18:30:40.591  1015  4218 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6922 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:30:40.591  6922  6922 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:40.591  6922  6922 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:40.601  1350  1350 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-22 18:30:40.601  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:40.601  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:40.601  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 18:30:40.601  6922  6922 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:40.601  6922  6922 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:40.611  6922  6922 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:40.611  6922  6922 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:40.631  1350  1350 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-22 18:30:40.631  1350  1350 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-22 18:30:40.631  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.631  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.631  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:40.631  1350  1350 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-22 18:30:40.631  1350  1350 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 18:30:40.631  1350  1350 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 18:30:40.631  1015  1128 D Tethering: InitialState.processMessage what=4
08-22 18:30:40.631  1015  1128 E Tethering: No numeric data
08-22 18:30:40.631  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.631  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 18:30:40.641  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:40.641  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.641  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:30:40.641  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:40.641  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-22 18:30:40.641  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:40.641  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:40.641  1170  1170 D HotspotTile: updateTetherState():false, false
08-22 18:30:40.641  1015  1128 D Tethering: clearTetheredNotification()
,08-22 18:30:40.641  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.641  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.641  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:40.651  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.651  1015  1122 V NetworkStats: performPollLocked() took 9ms
,08-22 18:30:40.651  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:40.651  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:40.661  6922  6922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:30:40.671  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:40.671  1015  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:40.671  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,08-22 18:30:40.671  1015  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-22 18:30:40.671  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:40.671  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:40.671  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:40.671  1015  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:40.681   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb7c787c8
08-22 18:30:40.681   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-22 18:30:40.681   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-22 18:30:40.681   271   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1211660152)
,08-22 18:30:40.691  6938  6938 E Zygote  : MountEmulatedStorage()
08-22 18:30:40.691  6938  6938 I libpersona: KNOX_SDCARD checking this for 10102,
08-22 18:30:40.691  6938  6938 E Zygote  : v2
08-22 18:30:40.691  6938  6938 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:40.691  6938  6938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:40.691  1015  1475 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6938 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a,
08-22 18:30:40.691  6938  6938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:40.691  1015  1475 I ActivityManager: Killing 6437:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-22 18:30:40.691  6938  6938 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:30:40.731  6938  6938 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:40.731  6938  6938 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:40.741   271   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-22 18:30:40.741   271   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-22 18:30:40.741   271   359 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1211660152) wakelock released: 1, error no: 0
08-22 18:30:40.741   271   359 I rmt_storage: 
,08-22 18:30:40.741   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb7c787c8
,08-22 18:30:40.751  6938  6938 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-22 18:30:40.891  1350  1350 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 18:30:40.941  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:40.941  1015  1015 I ApplicationPolicy: updateDataUsageMap
,08-22 18:30:40.951  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:40.961  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:40.961  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:40.961  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:40.961  6938  6958 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-22 18:30:40.971  6938  6958 I Babel_SMS: MmsConfig.loadMmsSettings,
,08-22 18:30:40.971  6938  6958 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
08-22 18:30:40.971  6938  6958 I Babel_SMS: MmsConfig.loadFromDatabase
,08-22 18:30:40.991  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.991  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:40.991  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:40.991  1350  1350 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-22 18:30:41.001  6938  6958 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-22 18:30:41.011  6938  6958 I Babel_SMS: MmsConfig.loadFromResources
,08-22 18:30:41.011  6938  6958 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-22 18:30:41.011  6938  6958 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-22 18:30:41.011   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:41.031  1015  1509 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-22 18:30:41.031  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-22 18:30:41.031  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:41.031  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:41.031  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 18:30:41.051  6938  6938 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:30:41.051  6938  6938 I Babel_Crash: startup - clean
,08-22 18:30:41.081  1015  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:41.081  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:41.081  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.081  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.081  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:41.081  1614  1614 I Hs20UtilService: Starting #9
,08-22 18:30:41.091  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:30:41.091  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 18:30:41.091  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:41.091  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:41.091  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:30:41.091  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:41.091  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:30:41.091  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:41.101  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-22 18:30:41.101  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 18:30:41.101  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 18:30:41.101  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-22 18:30:41.111  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:41.111  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:41.111  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:41.111  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:41.111  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:41.111  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-22 18:30:41.111  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:41.111  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 18:30:41.111  6938  6938 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 18:30:41.111  2029  2221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:30:41.111  1170  1170 D HotspotTile: onReceive : 1, 0
,08-22 18:30:41.111  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:41.111  6938  6938 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 18:30:41.111  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:41.121  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:41.121  6938  6938 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 18:30:41.121  1015  1535 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:41.121  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:41.121  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:41.121  1015  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.121  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:41.131  1614  1614 I Hs20UtilService: Starting #10
,08-22 18:30:41.131  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:41.131  6938  6938 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-22 18:30:41.131  6938  6938 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-22 18:30:41.131  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:30:41.131  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 18:30:41.131  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 18:30:41.131  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-22 18:30:41.131  6938  6938 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-22 18:30:41.131  6938  6938 W AudioCapabilities: Unsupported mime audio/x-ima
,08-22 18:30:41.141  6938  6938 W AudioCapabilities: Unsupported mime audio/qcelp
,08-22 18:30:41.141  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:41.141  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.141  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.151  6938  6938 W AudioCapabilities: Unsupported mime audio/evrc
,08-22 18:30:41.151  6938  6938 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 18:30:41.161  6938  6938 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 18:30:41.161  6938  6938 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-22 18:30:41.171  6938  6938 W VideoCapabilities: Unsupported mime video/wvc1
,08-22 18:30:41.171  6938  6938 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-22 18:30:41.171  6938  6938 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-22 18:30:41.171  6938  6938 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-22 18:30:41.171  6938  6938 W VideoCapabilities: Unsupported mime video/mp43
,08-22 18:30:41.181  6938  6938 W VideoCapabilities: Unsupported mime video/sorenson
,08-22 18:30:41.181  6938  6938 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-22 18:30:41.191  6938  6938 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-22 18:30:41.221  6938  6938 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 18:30:41.221  6938  6938 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 18:30:41.221  6938  6938 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 18:30:41.221  6938  6938 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-22 18:30:41.231  1015  1027 I ActivityManager: Killing 6478:com.samsung.android.sm/1000 (adj 15): empty #21
,08-22 18:30:41.231  6938  6938 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:30:41.231  6938  6938 I vclib   : onServiceConnected
,08-22 18:30:41.331  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.331  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.331  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.331  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.331  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.341  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.341  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.341  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.341  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.341  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.351  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.351  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.351  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.351  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.361  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.371  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.371  1015  1015 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:41.371  1015  1015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-22 18:30:41.381  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
08-22 18:30:41.381  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.381  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.381  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.381  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.401  6961  6961 E Zygote  : MountEmulatedStorage(),
08-22 18:30:41.401  6961  6961 E Zygote  : v2
,08-22 18:30:41.401  6961  6961 I libpersona: KNOX_SDCARD checking this for 1000
08-22 18:30:41.401  6961  6961 I libpersona: KNOX_SDCARD not a persona,
,08-22 18:30:41.411  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6961 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 18:30:41.411  6961  6961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.411  6961  6961 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:41.421  6961  6961 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 18:30:41.431   287   287 E SMD     : DCD OFF
,08-22 18:30:41.441  6961  6961 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.451  6961  6961 D ActivityThread: Added TimaKeyStore provider,
,08-22 18:30:41.471  6961  6961 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-22 18:30:41.471  6961  6961 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,08-22 18:30:41.481  6961  6961 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 18:30:41.501  6961  6961 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-22 18:30:41.501  6961  6961 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-22 18:30:41.501  6961  6961 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 18:30:41.501  6961  6961 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:41.501  1015  1478 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
,08-22 18:30:41.501  1015  1478 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-22 18:30:41.511  6961  6976 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-22 18:30:41.511  1015  1478 I ActivityManager: Killing 6426:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 18:30:41.531  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-22 18:30:41.531  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.531  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.531  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.531  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.541  6978  6978 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.541  6978  6978 I libpersona: KNOX_SDCARD checking this for 10031
08-22 18:30:41.541  6978  6978 E Zygote  : v2
08-22 18:30:41.541  6978  6978 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:41.541  6978  6978 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.551  6978  6978 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:41.551  1015  1028 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6978 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-22 18:30:41.551  6978  6978 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.561  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-22 18:30:41.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.561  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.561  1810  1810 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 18:30:41.571  6990  6990 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.571  6990  6990 E Zygote  : v2
08-22 18:30:41.571  6990  6990 I libpersona: KNOX_SDCARD checking this for 10121
08-22 18:30:41.571  6990  6990 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:41.581  1015  1041 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6990 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-22 18:30:41.581  6990  6990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.581  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-22 18:30:41.581  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.581  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.581  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.581  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.581  6990  6990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:41.581  6990  6990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.581  6978  6978 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.581  6978  6978 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.591  6990  6990 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.591  6990  6990 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.601  7003  7003 E Zygote  : MountEmulatedStorage(),
08-22 18:30:41.601  7003  7003 E Zygote  : v2
08-22 18:30:41.601  7003  7003 I libpersona: KNOX_SDCARD checking this for 10001
08-22 18:30:41.601  7003  7003 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:41.601  7003  7003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.601  1015  1015 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7003 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:30:41.601  7003  7003 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:41.601  7003  7003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.621  7003  7003 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:41.621  7003  7003 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.631  1846  5978 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-22 18:30:41.631  1810  1810 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-22 18:30:41.641  1810  1810 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-22 18:30:41.641  1810  1810 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,08-22 18:30:41.641  1810  1810 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-22 18:30:41.641  6990  6990 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:30:41.641  6990  6990 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-22 18:30:41.641  6990  6990 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:30:41.651  1810  1810 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-22 18:30:41.651  1810  1810 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-22 18:30:41.651  1015  1532 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-22 18:30:41.651  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.651  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.651  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.651  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.661  6990  6990 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
,08-22 18:30:41.671  7023  7023 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.671  7023  7023 I libpersona: KNOX_SDCARD checking this for 10077
08-22 18:30:41.671  7023  7023 E Zygote  : v2
08-22 18:30:41.671  7023  7023 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:41.671  7023  7023 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.671  7023  7023 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:41.671  7023  7023 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
08-22 18:30:41.671  1015  1532 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7023 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:30:41.691  6978  6978 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-22 18:30:41.701  7023  7023 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.701  7023  7023 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.701  6990  6990 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-22 18:30:41.701  6990  6990 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-22 18:30:41.711  1015  1486 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-22 18:30:41.711  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.711  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.711  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.711  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.721  7038  7038 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.721  7038  7038 E Zygote  : v2
08-22 18:30:41.721  7038  7038 I libpersona: KNOX_SDCARD checking this for 10141
08-22 18:30:41.721  7038  7038 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:41.721  7038  7038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:41.731  7038  7038 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:41.731  7038  7038 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.731  1015  1486 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7038 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-22 18:30:41.731  1015  1486 I ActivityManager: Killing 6527:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-22 18:30:41.741  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 18:30:41.741  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.741  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.751  7038  7038 D TimaKeyStoreProvider: TimaSignature is unavailable,
,08-22 18:30:41.751  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.751  2738  7046 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-22 18:30:41.751  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.751  7038  7038 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.761  2738  7046 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
08-22 18:30:41.761  2738  7046 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
08-22 18:30:41.761  2738  7046 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
08-22 18:30:41.761  7056  7056 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.761  7056  7056 E Zygote  : v2
08-22 18:30:41.761  7056  7056 I libpersona: KNOX_SDCARD checking this for 10032
08-22 18:30:41.761  7056  7056 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:41.761  2738  7046 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-22 18:30:41.761  7056  7056 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:41.761  1015  1216 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7056 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:30:41.771  7056  7056 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:41.771  7056  7056 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.771  1015  1027 I art     : Explicit concurrent mark sweep GC freed 47846(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 23MB/35MB, paused 2.923ms total 166.445ms
,08-22 18:30:41.791  7038  7038 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-22 18:30:41.791  7038  7038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:30:41.791  7038  7038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 18:30:41.801  7038  7038 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-22 18:30:41.801  1015  1043 D Tethering: interfaceRemoved wlan0,
08-22 18:30:41.801  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 18:30:41.811  7056  7056 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.811  1015  1486 I ActivityManager: Killing 6546:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 18:30:41.811  7056  7056 D ActivityThread: Added TimaKeyStore provider
08-22 18:30:41.811  1015  1094 V AlarmManager: waitForAlarm result :4
,08-22 18:30:41.811  2029  2223 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-22 18:30:41.811  2029  2223 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-22 18:30:41.831  1015  4193 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
08-22 18:30:41.831  1015  4193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.831  1015  4193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.831  1015  4193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.831  1015  4193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.841  7073  7073 E Zygote  : MountEmulatedStorage()
,08-22 18:30:41.841  7073  7073 E Zygote  : v2
08-22 18:30:41.841  7073  7073 I libpersona: KNOX_SDCARD checking this for 1000
08-22 18:30:41.841  7073  7073 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:41.841  7073  7073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.851  7073  7073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:41.851  1015  4193 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 18:30:41.851  1015  4193 I ActivityManager: Killing 6563:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
08-22 18:30:41.851  7073  7073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.861  1015  1535 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:41.871   305   305 I art     : Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 24.201ms
,08-22 18:30:41.881  7073  7073 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:41.881  7073  7073 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:41.881  7056  7085 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-22 18:30:41.881  7056  7085 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-22 18:30:41.881  1015  1535 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:41.891   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 587us total 16.907ms,
,08-22 18:30:41.901  7056  7085 D SPPClientService: PushLog.txt file is not deleted.
08-22 18:30:41.901  7056  7085 D SPPClientService: PushLog.txt file is not deleted.
08-22 18:30:41.901  7056  7085 D SPPClientService: ============PushLog. stop!
,08-22 18:30:41.911  1015  1043 D Tethering: interfaceRemoved p2p0
08-22 18:30:41.911  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 18:30:41.911  7056  7056 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-22 18:30:41.911   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 20.148ms
,08-22 18:30:41.911  1015  1509 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-22 18:30:41.921  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.921  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.921  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:41.921  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:41.921  1015  4218 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:41.931  7095  7095 E Zygote  : MountEmulatedStorage()
08-22 18:30:41.931  7095  7095 E Zygote  : v2
08-22 18:30:41.931  7095  7095 I libpersona: KNOX_SDCARD checking this for 10036
08-22 18:30:41.931  7095  7095 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:41.931  7095  7095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:41.931  7095  7095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:41.931  7095  7095 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-22 18:30:41.931  1015  1509 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7095 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-22 18:30:41.931  1015  1509 I ActivityManager: Killing 6487:com.android.providers.calendar/u0a37 (adj 15): empty #21
,08-22 18:30:41.941  1015  1535 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-22 18:30:41.941  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-22 18:30:41.941  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:41.941  1015  1535 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-22 18:30:41.941  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-22 18:30:41.951  1015  1475 D RCPManagerService: exchangeData() failure , invalid userId
08-22 18:30:41.951  7073  7073 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-22 18:30:41.961  7095  7095 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:41.961  7095  7095 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:42.001  7056  7106 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-22 18:30:42.021   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:42.021  7095  7095 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@294dc8ea
,08-22 18:30:42.021  1015  1478 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:42.031  1015  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:42.031  1015  1219 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-22 18:30:42.031  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:42.031  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.031  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.031  1015  1219 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:42.041  7095  7095 I SA      : [SSP] onCreated
,08-22 18:30:42.051  7116  7116 E Zygote  : MountEmulatedStorage(),
08-22 18:30:42.051  7116  7116 E Zygote  : v2
08-22 18:30:42.051  7116  7116 I libpersona: KNOX_SDCARD checking this for 10068
08-22 18:30:42.051  7116  7116 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:42.051  7116  7116 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:42.051  7116  7116 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-22 18:30:42.051  1015  1219 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7116 uid=10068 gids={50068, 9997} abi=armeabi-v7a
08-22 18:30:42.051  7116  7116 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 18:30:42.081  7116  7116 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:42.081  7116  7116 D ActivityThread: Added TimaKeyStore provider
08-22 18:30:42.081  7095  7095 I SA      : [TPM] There is no property file
,08-22 18:30:42.081  1015  1532 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:42.091  7095  7095 I SA      : [SCU] isHaveSA() - false
,08-22 18:30:42.091  7095  7095 I SA      : [TPM] getModelProperty : null
08-22 18:30:42.091  7095  7095 I SA      : [TPM] getCSCProperty : null
,08-22 18:30:42.091  7095  7095 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-22 18:30:42.091  7095  7095 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-22 18:30:42.091  7095  7095 I SA      : [DM] TFT FEATURE: false
,08-22 18:30:42.101  7095  7095 I SA      : [DM] init START
,08-22 18:30:42.101  1015  1446 D RCPManagerService: exchangeData() failure , invalid userId
,08-22 18:30:42.101  1015  1486 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-22 18:30:42.101  7095  7095 I SA      : [DM] This device is not a Vodafone
,08-22 18:30:42.111  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.111  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.111  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.111  1015  1486 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:42.111  7073  7073 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0,
,08-22 18:30:42.121  7135  7135 E Zygote  : MountEmulatedStorage(),
08-22 18:30:42.121  7135  7135 I libpersona: KNOX_SDCARD checking this for 10009
,08-22 18:30:42.121  7135  7135 E Zygote  : v2
08-22 18:30:42.121  7135  7135 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:42.121  7135  7135 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:42.121  7135  7135 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:42.131  1015  1486 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7135 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
08-22 18:30:42.131  7116  7116 D BadgeProvider: onCreate
,08-22 18:30:42.131  7135  7135 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 18:30:42.131  1015  1486 I ActivityManager: Killing 6027:com.android.mms/u0a41 (adj 15): empty #21
,08-22 18:30:42.131  7116  7116 D BadgeProvider: DatabaseHelper
08-22 18:30:42.131  1015  1486 I ActivityManager: Killing 6584:com.qualcomm.timeservice/1000 (adj 15): empty #22
,08-22 18:30:42.131  7073  7073 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-22 18:30:42.131  7073  7073 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:42.131  7073  7073 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-22 18:30:42.131  7073  7073 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-22 18:30:42.141  7073  7073 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-22 18:30:42.141  1015  1446 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-22 18:30:42.141  7095  7095 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-22 18:30:42.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:42.141  7095  7095 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-22 18:30:42.151  7095  7095 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-22 18:30:42.151  7095  7095 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-22 18:30:42.161  7116  7125 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75),
08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-22 18:30:42.161  1015  1446 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7147 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:30:42.161  7135  7135 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-22 18:30:42.161  1015  1446 I ActivityManager: Killing 6604:com.sec.esdk.elm/u0a90 (adj 15): empty #21
08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-22 18:30:42.161  7135  7135 D ActivityThread: Added TimaKeyStore provider
08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-22 18:30:42.161  7095  7095 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
,08-22 18:30:42.171  7147  7147 E Zygote  : MountEmulatedStorage()
08-22 18:30:42.171  7147  7147 E Zygote  : v2
08-22 18:30:42.171  7147  7147 I libpersona: KNOX_SDCARD checking this for 10008
08-22 18:30:42.171  7147  7147 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-22 18:30:42.171  7147  7147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-22 18:30:42.171  7095  7095 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-22 18:30:42.181  7147  7147 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:42.181  7147  7147 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 18:30:42.181  7095  7095 I SA      : [SCU] isHaveSA() - false
08-22 18:30:42.181  7095  7095 I SA      : support phone number id : false
08-22 18:30:42.181  7095  7095 I SA      : [DM] Supports Ref Jpn : true
,08-22 18:30:42.191  7095  7095 I SA      : [DM] init END
08-22 18:30:42.191  7095  7095 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-22 18:30:42.191  7095  7095 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-22 18:30:42.191  7095  7095 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-22 18:30:42.201  7116  7125 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-22 18:30:42.201  7116  7125 D BadgeProvider: sendNotify, [notify] : null
08-22 18:30:42.201  7116  7125 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-22 18:30:42.201  7116  7125 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-22 18:30:42.201  7116  7125 D BadgeProvider: update, [UpdateCount] : 1
08-22 18:30:42.201  1479  1479 D Launcher.Model: reloadBadges entered.
,08-22 18:30:42.211  1015  1219 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-22 18:30:42.211  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.211  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:42.211  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:42.211  1015  1509 D CountryDetector: No listener is left
08-22 18:30:42.211  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-22 18:30:42.221  1015  4218 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-22 18:30:42.221  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.221  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.221  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:42.221  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:42.221  7147  7147 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:42.221  7147  7147 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:42.231  7095  7095 I SA      : [SLFUCHKMGR] constructor called,
,08-22 18:30:42.241  7168  7168 E Zygote  : MountEmulatedStorage()
08-22 18:30:42.241  7168  7168 E Zygote  : v2
08-22 18:30:42.241  7168  7168 I libpersona: KNOX_SDCARD checking this for 10110
08-22 18:30:42.241  7168  7168 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:42.241  7168  7168 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:42.241  7095  7095 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-22 18:30:42.241  7095  7095 I SA      : [OR] == isSIMCardReady false ==
,08-22 18:30:42.241  7095  7095 I SA      : [SCU] == networkStateCheck == false
,08-22 18:30:42.241  7095  7095 I SA      : [OR] onReceive END
,08-22 18:30:42.241  7168  7168 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:42.241  1015  4218 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7168 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-22 18:30:42.251  7168  7168 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-22 18:30:42.251  1015  4194 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,08-22 18:30:42.251  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-22 18:30:42.251  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:42.251  1015  4194 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:42.251  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,08-22 18:30:42.261  6938  7165 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-22 18:30:42.261  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:30:42.271  1015  1216 I ActivityManager: Killing 6621:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-22 18:30:42.271  1015  1219 I ActivityManager: Killing 6455:com.android.calendar/u0a131 (adj 15): empty #21
,08-22 18:30:42.271  7168  7168 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:42.281  7168  7168 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:42.301  1015  4218 I ActivityManager: Killing 6636:com.google.android.gms:car/u0a11 (adj 15): empty #21
,08-22 18:30:42.301  1015  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:42.301  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.301  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:42.301  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:42.301  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:42.321  4801  7185 I iu.SyncManager: SYNC; picasa accounts
,08-22 18:30:42.331  4801  4801 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-22 18:30:42.341  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.341  1015  1219 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-22 18:30:42.351  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.351  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.351  1015  1478 I ActivityManager: Killing 5989:com.android.defcontainer/u0a3 (adj 15): empty #21
,08-22 18:30:42.361  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 18:30:42 GMT+02:00 2016
,08-22 18:30:42.361  1015  1219 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-22 18:30:42.361  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 18:30:42.361  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:42.361  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:42.361  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 18:30:42.371  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 18:30:42.371  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 18:30:42.381  2852  2852 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-22 18:30:42.381  2852  2852 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 18:30:42.381  2852  7186 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-22 18:30:42.381  2852  7186 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-22 18:30:42.391  2852  7186 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-22 18:30:42.391  2852  7186 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-22 18:30:42.391  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 18:30:42.421  1015  1040 W libprocessgroup: failed to kill pid 5989: No such process
,08-22 18:30:42.451  1015  1486 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 18:30:42.531  1015  1219 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-22 18:30:42.531  1015  1219 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 18:30:42.531  1015  1219 D SecContentProvider2: mCursor = null
,08-22 18:30:42.531  1015  1219 D WifiService: setWifiEnabled: true pid=6695, uid=10171
08-22 18:30:42.531  1015  1219 W ActivityManager: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 18:30:42.531  1015  1219 W WifiService: Failed getting userId using ActivityManagerNative
08-22 18:30:42.531  1015  1219 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 18:30:42.531  1015  1219 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 18:30:42.531  1015  1219 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 18:30:42.531  1015  1219 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 18:30:42.531  1015  1219 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 18:30:42.531  1015  1219 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-22 18:30:42.531  1015  1219 D SettingsProvider: name = wifi_on
,08-22 18:30:42.561  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1,
08-22 18:30:42.561   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 18:30:42.561  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
08-22 18:30:42.561   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:42.571  7168  7192 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 18:30:42.571   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 18:30:42.571   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:42.571  7168  7192 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 18:30:42.581   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-22 18:30:42.581   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:42.581  7168  7193 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-22 18:30:42.581   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-22 18:30:42.581   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:42.581  7168  7193 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-22 18:30:42.591  1015  4193 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 18:30:42.591  1015  4193 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4308, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 18:30:42.591  1015  4193 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 18:30:42.591  1015  4193 D BatteryService: stay LED for fully charged
08-22 18:30:42.591  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 18:30:42.591  1015  1015 I MotionRecognitionService: Plugged
,08-22 18:30:42.601  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 18:30:42.601  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-22 18:30:42.601  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 18:30:42.601  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-22 18:30:42.601  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 18:30:42.611  7168  7168 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-22 18:30:42.611  7168  7168 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-22 18:30:42.611  7168  7168 I GAv4    :   adb logcat -s GAv4
,08-22 18:30:42.631  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
08-22 18:30:42.631  1170  1170 D SViewCoverView: level :100 plugged : 2
,08-22 18:30:42.631  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:42.631  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:42.631  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:42.641  7168  7168 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:42.641  1015  1475 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 18:30:42.651  7168  7168 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:42.661  7168  7195 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-22 18:30:42.871  1015  1219 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:42.881  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:42.881  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:42.881  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-22 18:30:42.941  7168  7168 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-22 18:30:42.951  1015  1043 D Tethering: interfaceAdded wlan0
,08-22 18:30:42.961  7168  7168 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 6621-6623),
08-22 18:30:42.961  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:42.961  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:42.961  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:42.961  7168  7168 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-22 18:30:42.961  1015  1128 E Tethering: No numeric data,
,08-22 18:30:42.961  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 18:30:42.961  1015  1128 D Tethering: clearTetheredNotification()
08-22 18:30:42.971  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 18:30:42.961  1015  1128 D Tethering: InitialState.processMessage what=4
08-22 18:30:42.971  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-22 18:30:42.971  1015  1043 D Tethering: interfaceAdded p2p0
08-22 18:30:42.971  1170  1170 D HotspotTile: updateTetherState():false, false
08-22 18:30:42.971  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:42.971  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 18:30:42.971  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:42.971   277   994 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-22 18:30:42.971   277   994 D SoftapController: Softap fwReload - Ok
08-22 18:30:42.971  1015  1128 E Tethering: No numeric data
08-22 18:30:42.971  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-22 18:30:42.971  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:30:42.971  1015  1128 D Tethering: clearTetheredNotification()
,08-22 18:30:42.971  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:42.971  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 18:30:42.971  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 18:30:42.971  1015  1122 V NetworkStats: performPollLocked() took 6ms
08-22 18:30:42.971  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:42.971   277   994 D CommandListener: Setting iface cfg
08-22 18:30:42.971   277   994 D CommandListener: Trying to bring down wlan0
,08-22 18:30:42.971   277   994 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:42.981  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:42.981  1170  1170 D HotspotTile: updateTetherState():false, false
,08-22 18:30:42.981  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:42.981  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:30:42.981  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:42.981  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:30:42.981  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
,08-22 18:30:42.981  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:42.981  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:42.981  1015  1122 V NetworkStats: performPollLocked() took 3ms
08-22 18:30:42.981  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:42.981  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 18:30:42.981  1015  1125 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-22 18:30:42.991  7168  7168 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3dacaf4d}
,08-22 18:30:42.991  7168  7168 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-22 18:30:42.991  7168  7168 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-22 18:30:42.991  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:42.991  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:42.991  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:42.991  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:42.991  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 18:30:42.991  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:42.991  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:42.991  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:42.991  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:42.991  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-22 18:30:43.001  1170  1170 D HotspotTile: onReceive : 2, 0
08-22 18:30:43.001  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:43.001  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:43.001  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:43.001  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:43.001  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:43.011  7168  7168 I cr.BrowserStartup: Initializing chromium process, singleProcess=true,
,08-22 18:30:43.011  7168  7168 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 18:30:43.011  7168  7168 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-22 18:30:43.021   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:43.031  7219  7219 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-22 18:30:43.031  7219  7219 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-22 18:30:43.031  7219  7219 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 18:30:43.031  7168  7168 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-22 18:30:43.031  7168  7168 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-22 18:30:43.031  7168  7168 I Adreno-EGL: Build Date: 04/06/15 Mon
08-22 18:30:43.031  7168  7168 I Adreno-EGL: Local Branch: 
08-22 18:30:43.031  7168  7168 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-22 18:30:43.031  7168  7168 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-22 18:30:43.031  7168  7168 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-22 18:30:43.061  7219  7219 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-22 18:30:43.061   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7219,
08-22 18:30:43.061   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
,08-22 18:30:43.061  7219  7219 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-22 18:30:43.061  7219  7219 I wpa_supplicant: ssSupport state is = 1
08-22 18:30:43.061  7219  7219 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-22 18:30:43.061  7219  7219 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-22 18:30:43.061   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7219
08-22 18:30:43.061   374   374 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-22 18:30:43.101  7168  7232 W cr.media: Requires BLUETOOTH permission
,08-22 18:30:43.111  7168  7168 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-22 18:30:43.121  7168  7168 I NSApplication: Starting up...,
08-22 18:30:43.121  1015  1027 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 18:30:43.121  1015  1535 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-22 18:30:43.131  1015  4218 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast,
,08-22 18:30:43.131  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:43.131  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:43.131  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:43.131  1015  4218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:43.141  7237  7237 E Zygote  : MountEmulatedStorage(),
,08-22 18:30:43.141  1015  4218 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7237 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-22 18:30:43.141  7237  7237 E Zygote  : v2
08-22 18:30:43.141  7237  7237 I libpersona: KNOX_SDCARD checking this for 10117
08-22 18:30:43.141  7237  7237 I libpersona: KNOX_SDCARD not a persona
08-22 18:30:43.151  1015  4218 I ActivityManager: Killing 5780:com.android.vending/u0a26 (adj 15): empty #21
,08-22 18:30:43.151  7237  7237 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:43.151  7237  7237 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:43.151  7237  7237 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:30:43.171  7237  7237 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-22 18:30:43.171  7237  7237 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:43.191  7237  7237 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-22 18:30:43.251   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-22 18:30:43.251  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-22 18:30:43.301  7219  7219 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 18:30:43.301  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 18:30:43.311  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 18:30:43.311   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7219,
08-22 18:30:43.311   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 18:30:43.311  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 18:30:43.311  7219  7219 I wpa_supplicant: ssSupport state is = 1
,08-22 18:30:43.311  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 18:30:43.311  7219  7219 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:43.311  7219  7219 E wpa_supplicant: SIM READ ERROR
08-22 18:30:43.311  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:43.311  7219  7219 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:43.311  7219  7219 E wpa_supplicant: SIM READ ERROR
,08-22 18:30:43.311  7219  7219 I wpa_supplicant: Blacklist: Clear (all) 
08-22 18:30:43.311  7219  7219 I wpa_supplicant: wpa_default_ap_write_once
08-22 18:30:43.311  7219  7219 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 18:30:43.311  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:43.311  7219  7219 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-22 18:30:43.311  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:43.311  7219  7219 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 18:30:43.321  7219  7219 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-22 18:30:43.321  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:43.321  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 18:30:43.321  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:43.411  7219  7219 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-22 18:30:43.531  1015  4218 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-22 18:30:43.541  1015  4218 I ActivityManager: Killing 6828:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-22 18:30:43.541  1015  1535 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:43.541  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:43.541  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:43.551  1015  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:43.551  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:43.551  1614  1614 I Hs20UtilService: Starting #11
,08-22 18:30:43.551  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:43.551  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:30:43.551  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 18:30:43.551  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
08-22 18:30:43.551  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:43.571  1015  1219 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:43.571  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:43.571  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:43.571  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:43.571  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:43.571  1614  1614 I Hs20UtilService: Starting #12
,08-22 18:30:43.571  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:43.571  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:30:43.581  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 18:30:43.581  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
08-22 18:30:43.581  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:43.611  7219  7219 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 18:30:43.611  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 18:30:43.621  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 18:30:43.621   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7219
08-22 18:30:43.621   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 18:30:43.621  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 18:30:43.621  7219  7219 I wpa_supplicant: ssSupport state is = 1
,08-22 18:30:43.621  7219  7219 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-22 18:30:43.621  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-22 18:30:43.631  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
08-22 18:30:43.631   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7219
08-22 18:30:43.631   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C,
08-22 18:30:43.631  7219  7219 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-22 18:30:43.631  7219  7219 I wpa_supplicant: ssSupport state is = 1
08-22 18:30:43.631  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:43.641  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 18:30:43.631  7219  7219 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:43.631  7219  7219 E wpa_supplicant: SIM READ ERROR
08-22 18:30:43.631  7219  7219 I wpa_supplicant: wpa_default_ap_write_once
08-22 18:30:43.631  7219  7219 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 18:30:43.631  7219  7219 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-22 18:30:43.641  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:43.641  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:30:43.641  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 18:30:43.641  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:43.641  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:30:43.771  7219  7219 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-22 18:30:43.771  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 18:30:43.891  7219  7219 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-22 18:30:43.891  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-22 18:30:43.891  7219  7219 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 18:30:43.961  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-22 18:30:43.961  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:43.961  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:30:43.991  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-22 18:30:43.991  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-22 18:30:43.991  7219  7219 I wpa_supplicant: HOTSPOT20_ENABLE called
08-22 18:30:43.991  7219  7219 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:43.991  7219  7219 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:43.991  7219  7219 E wpa_supplicant: SIM READ ERROR
08-22 18:30:43.991  7219  7219 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 18:30:44.031   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:44.031  7219  7219 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-22 18:30:44.041  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 18:30:44.041  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:44.041  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:44.041  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:30:44.041  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:44.041  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:44.041  7219  7219 I wpa_supplicant: Skip scan - bUseNetwork false,
08-22 18:30:44.051  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:44.051  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-22 18:30:44.051  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 18:30:44.051  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
,08-22 18:30:44.051  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
,08-22 18:30:44.051  1170  1170 D HotspotTile: onReceive : 3, 0
,08-22 18:30:44.051  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-22 18:30:44.061  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:44.061  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:44.061  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:44.061  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:44.061  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:44.061  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:44.061  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:30:44.061  1015  1125 E WifiConfigStore: Not a HS20
08-22 18:30:44.071  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:30:44.071  1015  1446 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:44.071  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
08-22 18:30:44.071  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:44.071  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:44.071  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:44.071  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:44.071  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 18:30:44.071  7219  7219 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 18:30:44.071  7219  7219 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 18:30:44.071  7219  7219 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 18:30:44.071  7219  7219 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 18:30:44.071  7219  7219 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 18:30:44.071  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 18:30:44.071  7219  7219 I wpa_supplicant: First Scan Start
,08-22 18:30:44.081  7219  7219 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-22 18:30:44.081  1614  1614 I Hs20UtilService: Starting #13
,08-22 18:30:44.081  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:44.081  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-22 18:30:44.081  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:30:44.081  1015  1125 I WifiNative-HAL: startHal
08-22 18:30:44.081  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d67d88c
08-22 18:30:44.081  1015  1125 I WifiNative-HAL: Could not start hal
08-22 18:30:44.081  6938  6938 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:30:44.081  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 18:30:44.081  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 18:30:44.081  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
08-22 18:30:44.081  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:44.081  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 18:30:44.091  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 18:30:44.091  1015  4193 I ActivityManager: Killing 6847:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-22 18:30:44.091   277   994 D CommandListener: Setting iface cfg
08-22 18:30:44.091   277   994 D CommandListener: Trying to bring up p2p0
,08-22 18:30:44.091  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 18:30:44.091  1015  1124 D WifiP2pService: P2pEnablingState
,08-22 18:30:44.091  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 18:30:44.091  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-22 18:30:44.091  1015  1124 D WifiP2pService: P2p socket connection successful
08-22 18:30:44.091  1015  1124 D WifiP2pService: P2pEnabledState
08-22 18:30:44.091  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 18:30:44.091  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 18:30:44.091  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-22 18:30:44.091  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3
,08-22 18:30:44.101  1015  1147 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:30:44.101  1015  1147 I WifiNative-HAL: startHal
08-22 18:30:44.101  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e3159bc
08-22 18:30:44.101  1015  1147 I WifiNative-HAL: Could not start hal
08-22 18:30:44.101  1015  1147 E WifiScanningService: could not start HAL
08-22 18:30:44.101  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 18:30:44.101  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 18:30:44.101  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-22 18:30:44.101  1015  1015 D RttService: SCAN_AVAILABLE : 3
,08-22 18:30:44.101  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 18:30:44.101  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:30:44.101  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 18:30:44.101  7219  7219 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-22 18:30:44.101  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 18:30:44.101  1015  1125 E WifiStateMachine: Failed to set frequency band 0
08-22 18:30:44.101  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 18:30:44.101  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:44.101  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:44.101  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-22 18:30:44.111  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,08-22 18:30:44.111  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:44.111  1015  1046 D WifiDisplayController: disconnect
08-22 18:30:44.111  1015  1046 D WifiDisplayController: updateConnection
08-22 18:30:44.111  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:44.111  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 18:30:44.111  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-22 18:30:44.111  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-22 18:30:44.111  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:44.111  1015  1125 D SecContentProvider2: mCursor = null
08-22 18:30:44.111  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-22 18:30:44.111  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:44.111  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:44.111  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 18:30:44.121  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-22 18:30:44.121  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-22 18:30:44.121  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:30:44.121  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 18:30:44.121  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 18:30:44.121  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 18:30:44.121  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  secondary type: null
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  wps: 0
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  grpcapab: 0
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  devcapab: 0
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  status: 3
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  wfdInfo: null
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-22 18:30:44.121  1015  1046 D WifiDisplayController:  SConnectInfo : null
08-22 18:30:44.121  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 18:30:44.121  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:44.121  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 18:30:44.121  1015  1509 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 18:30:44.121  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 18:30:44.121  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:30:44.121  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 18:30:44.121  6892  6892 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 18:30:44.131  6922  6922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:30:44.141  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 18:30:44.141  1015  1124 D WifiP2pService: InactiveState
,08-22 18:30:44.141  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-22 18:30:44.141  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 18:30:44.141  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-22 18:30:44.141  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-22 18:30:44.141  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 18:30:44.431   287   287 E SMD     : DCD OFF
,08-22 18:30:45.021   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:45.211  7219  7219 I wpa_supplicant: nl80211: Received scan results (29 BSSes),
,08-22 18:30:45.211  7219  7219 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,08-22 18:30:45.211  7219  7219 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-22 18:30:45.211  1015  7264 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-22 18:30:45.211  7219  7219 I wpa_supplicant: Trying to associate with  'G700',
08-22 18:30:45.211  7219  7219 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING,
,08-22 18:30:45.211  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-22 18:30:45.221  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:30:45.221  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:45.331  7219  7219 E wpa_supplicant: Cmd 35605 not handled
08-22 18:30:45.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:45.331  7219  7219 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-22 18:30:45.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-22 18:30:45.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:45.331  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 18:30:45.331  7219  7219 I wpa_supplicant: Associated with F4.99.3E
08-22 18:30:45.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.331  7219  7219 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-22 18:30:45.331  7219  7219 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-22 18:30:45.331  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-22 18:30:45.331  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
08-22 18:30:45.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:45.331  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-22 18:30:45.331  1015  1043 D Tethering: interfaceStatusChanged wlan0, true,
08-22 18:30:45.331  1015  1128 E Tethering: No numeric data
08-22 18:30:45.331  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
08-22 18:30:45.331  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 18:30:45.341  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:45.331  1015  1128 D Tethering: clearTetheredNotification()
08-22 18:30:45.341  1170  1170 D HotspotTile: updateTetherState():false, false
08-22 18:30:45.331  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.341  7219  7219 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 18:30:45.341  7219  7219 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-22 18:30:45.341  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:45.341  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:45.341  7219  7219 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 18:30:45.341  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-22 18:30:45.341  7219  7219 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:30:45.341  7219  7219 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 18:30:45.341  7219  7219 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-22 18:30:45.341  7219  7219 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 18:30:45.341  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 18:30:45.341  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-22 18:30:45.341  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
08-22 18:30:45.341  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-22 18:30:45.351  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:45.351  1015  1125 D SecContentProvider2: mCursor = null
08-22 18:30:45.351  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.351  1015  1122 V NetworkStats: performPollLocked() took 12ms
,08-22 18:30:45.351  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-22 18:30:45.361  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.361  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:45.361  1015  1028 I ActivityManager: Killing 6961:com.sec.pcw.device/1000 (adj 15): empty #21
,08-22 18:30:45.361  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 18:30:45.371  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 18:30:45.371  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 18:30:45.371  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:45.371  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-22 18:30:45.371  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 18:30:45.371  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:45.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.371  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.371  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:45.371  1015  1446 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:45.371  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:45.381  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:45.381  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:45.381  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:45.381  1614  1614 I Hs20UtilService: Starting #14
,08-22 18:30:45.381  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:30:45.381  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 18:30:45.381  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:45.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:45.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-22 18:30:45.381  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:45.381  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 18:30:45.381  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:45.391  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:45.401   277   994 D CommandListener: Setting iface cfg,
,08-22 18:30:45.401  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,08-22 18:30:45.401  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:45.411  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:45.411  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:30:45.411  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:45.421  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 18:30:45.421  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 18:30:45.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.421  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.421  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:30:45.421  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:45.431  1015  1125 E WifiNative-wlan0: do suspend false
,08-22 18:30:45.431  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
08-22 18:30:45.431  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 18:30:45.551  1015  1446 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 18:30:45.551  1015  1446 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 18:30:45.551  1015  1446 D SecContentProvider2: mCursor = null
,08-22 18:30:45.551  1015  1446 D WifiService: setWifiEnabled: false pid=6695, uid=10171
,08-22 18:30:45.551  1015  1446 D SettingsProvider: name = wifi_on
,08-22 18:30:45.551  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:30:45.571  1015  1125 E WifiNative-wlan0: do suspend true,
,08-22 18:30:45.591  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
,08-22 18:30:45.591  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 18:30:45.601   277   994 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:45.601  1015  1127 E ConnectivityService: updateNetworkInfo(),
08-22 18:30:45.601  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:30:45.601  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 18:30:45.601  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-22 18:30:45.601  1015  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-22 18:30:45.601  1015  1124 D WifiP2pService: InactiveState{ what=131204 }
,08-22 18:30:45.601   277   994 E Netd    : no such netId 503
08-22 18:30:45.601  1015  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
08-22 18:30:45.611  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-22 18:30:45.611  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:45.611  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:45.611  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.611  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.611  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.611  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.611  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-22 18:30:45.611  1015  1127 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '78 network destroy 503' failed with '400 78 destroyNetwork() failed (Machine is not on the network)'
,08-22 18:30:45.611  1015  1127 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-22 18:30:45.611  1015  1127 V NetworkStats: updateIfacesLocked()
08-22 18:30:45.611  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.611  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:30:45.611  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:45.611  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:30:45.621  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 1
08-22 18:30:45.621  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:45.621  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:45.621  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:30:45.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.621  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.621  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.621  1015  1127 V NetworkStats: performPollLocked() took 10ms
,08-22 18:30:45.621  1015  1015 D RttService: SCAN_AVAILABLE : 1
,08-22 18:30:45.621  1015  1148 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-22 18:30:45.631  1015  1127 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-22 18:30:45.631  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 18:30:45.631  1015  1127 D ConnectivityService: nai.networkMonitor.doQuit(),
08-22 18:30:45.631  1015  1127 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-22 18:30:45.631  1015  1127 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-22 18:30:45.631  1015  1124 D WifiP2pService: P2pDisablingState
08-22 18:30:45.631  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:30:45.631  1015  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
08-22 18:30:45.631  1015  1127 E ConnectivityService: updateNetworkInfo()
,08-22 18:30:45.631  1015  1124 D WifiP2pService: p2p socket connection lost
08-22 18:30:45.631  1015  1124 D WifiP2pService: P2pDisabledState
,08-22 18:30:45.631  1015  4194 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:45.631  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 18:30:45.641  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 18:30:45.641  1015  4194 W ActivityManager: userId = 0, bbcId = -10000,
08-22 18:30:45.641  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:45.641  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 18:30:45.641  1614  1614 I Hs20UtilService: Starting #15
08-22 18:30:45.641  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:30:45.651  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-22 18:30:45.651  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
,08-22 18:30:45.651  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 18:30:45.651  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
08-22 18:30:45.651  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 18:30:45.651  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.651  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-22 18:30:45.651  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 18:30:45.651  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:45.651  1015  1046 D WifiDisplayController: disconnect
08-22 18:30:45.651  1015  1046 D WifiDisplayController: updateConnection
08-22 18:30:45.651  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:30:45.651  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 18:30:45.661  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 18:30:45.661  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:45.661  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:45.661  7271  7271 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-22 18:30:45.661  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:30:45.661  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:45.661  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:30:45.671  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-22 18:30:45.671  1015  1509 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 18:30:45.671  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-22 18:30:45.671  7271  7271 I dhcpcd  : version 5.5.6 starting
,08-22 18:30:45.671  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 18:30:45.671  1015  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-22 18:30:45.671  1015  1124 D WifiP2pService: DefaultState{ what=143375 }
08-22 18:30:45.671  7271  7271 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-22 18:30:45.671   277   994 D CommandListener: Clearing all IP addresses on wlan0,
,08-22 18:30:45.681  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:45.681  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 18:30:45.681  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.681  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.681  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.681  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.681  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 18:30:45.681  7219  7219 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-22 18:30:45.691  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-22 18:30:45.691  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:30:45.691  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.691  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.691  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.691  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.691  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-22 18:30:45.691  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:45.701  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:30:45.701  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:30:45.701  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:45.701  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:45.701  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.701  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:45.701  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.701  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:45.701  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:45.701  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:45.701  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-22 18:30:45.711  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 18:30:45.711  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:45.711  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:30:45.711  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:45.711  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 18:30:45.711  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:45.711  1170  1170 D HotspotTile: onReceive : 0, 0
08-22 18:30:45.711  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:45.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:30:45.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:45.711  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:45.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:45.711  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:45.711  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:45.711  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:45.721  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-22 18:30:45.721  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-22 18:30:45.721  6892  6892 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 18:30:45.731  6922  6922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:30:45.741  1015  1446 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:45.741  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:45.741  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:45.741  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:45.741  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:45.751  1614  1614 I Hs20UtilService: Starting #16
08-22 18:30:45.751  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:30:45.751  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-22 18:30:45.751  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:30:45.751  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:30:45.761  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:30:45.761  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:30:45.761  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:30:45.761  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:30:45.761  7271  7271 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-22 18:30:45.771  7271  7271 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 18:30:45.771  7271  7271 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-22 18:30:45.771  1015  1216 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:45.771  7271  7271 I dhcpcd  : bssid match
08-22 18:30:45.771  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:45.771  7271  7271 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-22 18:30:45.771  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:45.771  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:45.771  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:45.771  1614  1614 I Hs20UtilService: Starting #17
,08-22 18:30:45.771  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:45.771  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:30:45.781  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 18:30:45.781  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 18:30:45.781  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:45.811  7219  7219 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 18:30:45.841  7271  7271 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-22 18:30:45.931  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false,
08-22 18:30:45.931  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:45.931  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
08-22 18:30:45.931  7219  7219 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-22 18:30:45.951  7219  7219 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1,
08-22 18:30:45.951  7219  7219 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-22 18:30:45.961  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.961  7219  7219 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
,08-22 18:30:45.961  7219  7219 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-22 18:30:45.961  7219  7219 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-22 18:30:45.961  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.961  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
08-22 18:30:45.961  1015  1128 D Tethering: InitialState.processMessage what=4
08-22 18:30:45.961  1015  1128 E Tethering: No numeric data
08-22 18:30:45.961  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:30:45.961  1015  1128 D Tethering: clearTetheredNotification()
,08-22 18:30:45.961  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:45.961  1015  1122 V NetworkStats: performPollLocked(flags=0x1),
08-22 18:30:45.961  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-22 18:30:45.971  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:45.971  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 18:30:45.971  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.971  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:45.971  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:30:45.971  1170  1170 D HotspotTile: updateTetherState():false, false
08-22 18:30:45.971  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.971  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:45.971  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:45.971  1015  1122 V NetworkStats: performPollLocked() took 9ms
,08-22 18:30:45.971  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:45.981  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:45.981  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:46.031   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-22 18:30:46.051  7271  7271 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-22 18:30:46.211  7219  7219 I wpa_supplicant: Blacklist: Clear (all) ,
,08-22 18:30:46.321  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 18:30:46.321  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 18:30:46.321  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:46.351  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 18:30:46.351  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-22 18:30:46.351  1015  1043 D Tethering: interfaceStatusChanged wlan0, false,
,08-22 18:30:46.351  7219  7219 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-22 18:30:46.461  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
,08-22 18:30:46.461  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-22 18:30:46.471  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:46.471  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:46.471  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:46.471  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:46.471  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:46.471  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:46.471  6938  6938 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:30:46.471  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:46.471  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-22 18:30:46.471  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 18:30:46.471  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:46.471  1170  1170 D HotspotTile: onReceive : 1, 0
08-22 18:30:46.471  2029  2221 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-22 18:30:46.471  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:46.481  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-22 18:30:46.481  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:30:46.481  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:46.481  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:46.481  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:46.481  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 18:30:46.481  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:30:46.491  1614  1614 I Hs20UtilService: Starting #18
08-22 18:30:46.491  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:46.491  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:30:46.491  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 18:30:46.491  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
,08-22 18:30:46.501  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:47.091   277   988 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-22 18:30:47.091  1015  1043 D Tethering: interfaceRemoved wlan0
08-22 18:30:47.091  1015  1043 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-22 18:30:47.341  1015  1043 D Tethering: interfaceRemoved p2p0
,08-22 18:30:47.341  1015  1043 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-22 18:30:47.441   287   287 E SMD     : DCD OFF,
,08-22 18:30:48.161  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-22 18:30:48.551  6695  6749 D BluetoothAdapter: enable(),
,08-22 18:30:48.561  1015  1219 W ActivityManager: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS,
,08-22 18:30:48.561  1015  1219 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256),
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 18:30:48.561  1015  1219 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446),
,08-22 18:30:48.561  1015  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-22 18:30:48.561  1015  1219 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-22 18:30:48.571  1015  1219 D SettingsProvider: name = bluetooth_on,
,08-22 18:30:48.571  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
08-22 18:30:48.571  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 18:30:48.581  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-22 18:30:48.581  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-22 18:30:48.581  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:48.581  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:48.581  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:48.581  1015  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:48.601  7302  7302 E Zygote  : MountEmulatedStorage()
,08-22 18:30:48.601  7302  7302 E Zygote  : v2
08-22 18:30:48.601  7302  7302 I libpersona: KNOX_SDCARD checking this for 1002
08-22 18:30:48.601  7302  7302 I libpersona: KNOX_SDCARD not a persona,
08-22 18:30:48.601  1015  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7302 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-22 18:30:48.601  7302  7302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 18:30:48.611  7302  7302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:48.611  7302  7302 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:48.641  7302  7302 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:48.641  7302  7302 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:48.661  7302  7302 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 18:30:48.661  7302  7302 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:30:48.691  7302  7302 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-22 18:30:48.731  7302  7302 D BtSettings.ProfileConfig: Adding GattService
,08-22 18:30:48.731  7302  7302 D BtSettings.ProfileConfig: Adding HeadsetService
,08-22 18:30:48.731  7302  7302 D BtSettings.ProfileConfig: Adding A2dpService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding HidService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding HealthService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding PanService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding SapService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding SapClientService
,08-22 18:30:48.741  7302  7302 D BtSettings.ProfileConfig: Adding HidDevService
,08-22 18:30:48.741  7302  7302 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-22 18:30:48.741  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-22 18:30:48.751  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.751  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.751  1015  1216 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  1216 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.751  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.751  1015  1216 D SettingsProvider: ret = -1
,08-22 18:30:48.751  1015  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-22 18:30:48.751  1015  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.751  1015  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.751  1015  1509 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  1509 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.751  1015  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.751  1015  1509 D SettingsProvider: ret = -1
08-22 18:30:48.751  1015  1532 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-22 18:30:48.751  1015  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:48.751  1015  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.751  1015  1532 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  1532 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.751  1015  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.751  1015  1532 D SettingsProvider: ret = -1
,08-22 18:30:48.751  1015  4193 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-22 18:30:48.751  1015  4193 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:48.751  1015  4193 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.751  1015  4193 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  4193 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.751  1015  4193 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.751  1015  4193 D SettingsProvider: ret = -1
,08-22 18:30:48.751  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-22 18:30:48.751  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:48.751  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.751  1015  1478 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  1478 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:48.751  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:48.751  1015  1478 D SettingsProvider: ret = -1
,08-22 18:30:48.751  1015  4194 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-22 18:30:48.751  1015  4194 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.751  1015  4194 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.751  1015  4194 D SettingsProvider: selectionArgs: false
08-22 18:30:48.751  1015  4194 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:48.761  1015  4194 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:48.761  1015  4194 D SettingsProvider: ret = -1
,08-22 18:30:48.761  1015  1446 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:48.761  1015  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.761  1015  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.761  1015  1446 D SettingsProvider: selectionArgs: false
08-22 18:30:48.761  1015  1446 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:48.761  1015  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:48.761  1015  1446 D SettingsProvider: ret = -1
,08-22 18:30:48.761  1015  1028 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-22 18:30:48.761  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.761  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.761  1015  1028 D SettingsProvider: selectionArgs: false
08-22 18:30:48.761  1015  1028 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:48.761  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:48.761  1015  1028 D SettingsProvider: ret = -1
,08-22 18:30:48.761  1015  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 18:30:48.761  1015  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.761  1015  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.761  1015  1027 D SettingsProvider: selectionArgs: false,
08-22 18:30:48.771  1015  1027 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:48.771  1015  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.771  1015  1027 D SettingsProvider: ret = -1
08-22 18:30:48.771  1015  1475 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:48.771  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:48.771  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.771  1015  1475 D SettingsProvider: selectionArgs: false
08-22 18:30:48.771  1015  1475 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.771  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 18:30:48.771  1015  1475 D SettingsProvider: ret = -1
08-22 18:30:48.771  1015  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-22 18:30:48.771  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.771  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.771  1015  1535 D SettingsProvider: selectionArgs: false
08-22 18:30:48.771  1015  1535 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.771  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.771  1015  1535 D SettingsProvider: ret = -1
08-22 18:30:48.771  1015  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-22 18:30:48.771  1015  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:48.771  1015  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:48.771  1015  1219 D SettingsProvider: selectionArgs: false
08-22 18:30:48.771  1015  1219 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.771  1015  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.771  1015  1219 D SettingsProvider: ret = -1
,08-22 18:30:48.791  7302  7302 D BluetoothAdapterState: make,
,08-22 18:30:48.791  7302  7302 I bluedroid: init,
08-22 18:30:48.791  7302  7317 I BluetoothAdapterState: Entering OffState
,08-22 18:30:48.801  7302  7302 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,08-22 18:30:48.801  7302  7302 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 18:30:48.801  7302  7302 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:30:48.801  7302  7302 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 18:30:48.801  7302  7302 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-22 18:30:48.801  7302  7302 I bluedroid: get_profile_interface socket
08-22 18:30:48.801  7302  7302 I bluedroid: get_profile_interface map_client
,08-22 18:30:48.811  7302  7302 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,08-22 18:30:48.811  7302  7320 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting,
08-22 18:30:48.811  7302  7320 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-22 18:30:48.811  7302  7320 E BluetoothServiceJni: populateRssiValuesNative
08-22 18:30:48.811  7302  7320 I bluedroid: getModelRssiValues
08-22 18:30:48.811  7302  7320 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 18:30:48.811  7302  7320 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 18:30:48.811  1015  1015 D SettingsProvider: name = bluetooth_name
08-22 18:30:48.811  7302  7320 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 18:30:48.821  7302  7302 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
08-22 18:30:48.821  1015  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:48.821  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.821  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.821  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.821  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.831  7302  7310 I bluedroid: config_hci_snoop_log
,08-22 18:30:48.831  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-22 18:30:48.831  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-22 18:30:48.831  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-22 18:30:48.831  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-22 18:30:48.831  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 18:30:48.841  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:48.841  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:48.841  7302  7302 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-22 18:30:48.851  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 18:30:48.851  7302  7317 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-22 18:30:48.851  7302  7317 D BluetoothAdapterProperties: Setting state to 11
,08-22 18:30:48.851  7302  7317 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 18:30:48.851  7302  7317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:48.851  7302  7317 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 18:30:48.851  7302  7317 D BluetoothAdapterService: Autoconnection is available 
,08-22 18:30:48.851  7302  7317 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-22 18:30:48.861  7302  7317 D BluetoothSecureManager: getInstant: null
,08-22 18:30:48.861  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-22 18:30:48.861  7302  7317 D BluetoothSecureManager: calling getMethod for getService
,08-22 18:30:48.861  7302  7317 D BluetoothSecureManager: calling getService
,08-22 18:30:48.861  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:48.861  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-22 18:30:48.871  7302  7317 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@1e2409a
,08-22 18:30:48.871  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 18:30:48.871  1015  4193 D BluetoothSecureManagerService: isSecureModeEnabled
08-22 18:30:48.871  1015  4193 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-22 18:30:48.871  7302  7317 D BtConfig.SecureMode: isSecureModeOn:false
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-22 18:30:48.871  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:48.871  1170  1170 D BluetoothTile:  getBluetoothState : 11
,08-22 18:30:48.871  1863  1863 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-22 18:30:48.871  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 18:30:48.871  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-22 18:30:48.871  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 18:30:48.871  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:48.871  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 18:30:48.871  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-22 18:30:48.871  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:48.881  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:48.881  1015  1509 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:48.881  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.881  1015  1475 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:48.881  1015  4218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:48.881  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:48.881  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-22 18:30:48.881  7302  7317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:48.881  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
08-22 18:30:48.881  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 18:30:48.881  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 18:30:48.891  7302  7317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
08-22 18:30:48.891  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.891  1015  1509 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:48.891  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:48.891  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:48.891  7302  7317 D BluetoothBondStateMachine: make
,08-22 18:30:48.901  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 18:30:48.901  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 18:30:48.901  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 18:30:48.901  7302  7323 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 18:30:48.901  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 18:30:48.901  1015  4194 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.901  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.901  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.901  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.901  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:48.901  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:48.901  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 18:30:48.901  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 18:30:48.901  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 18:30:48.901  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-22 18:30:48.901  7302  7302 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:48.901  7302  7302 D BtGatt.GattService: Received start request. Starting profile...
08-22 18:30:48.901  7302  7302 D BtGatt.GattService: start()
08-22 18:30:48.901  7302  7302 D BtGatt.GattService: start()
08-22 18:30:48.901  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.901  7302  7302 I bluedroid: get_profile_interface gatt
08-22 18:30:48.901  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.901  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:48.901  7302  7302 D BtGatt.AdvertiseManager: advertise manager created
,08-22 18:30:48.911  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:48.911  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:48.911  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.911  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 18:30:48.911  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 18:30:48.911  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-22 18:30:48.911  1015  1535 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-22 18:30:48.911  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:48.911  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:48.911  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:48.911  1015  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:48.931  1015  1535 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7325 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-22 18:30:48.931  7325  7325 E Zygote  : MountEmulatedStorage()
08-22 18:30:48.931  7325  7325 I libpersona: KNOX_SDCARD checking this for 10055
08-22 18:30:48.931  7325  7325 E Zygote  : v2
08-22 18:30:48.931  7325  7325 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:48.931  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:48.931  1015  1509 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.931  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.931  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 18:30:48.931  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.931  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.931  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:48.941  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-22 18:30:48.931  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:48.931  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 18:30:48.931  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-22 18:30:48.931  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:48.931  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 18:30:48.941  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.941  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.941  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.941  7302  7302 D BtGatt.GattService: mStartError = false
08-22 18:30:48.941  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:48.941  7302  7302 D HeadsetService: Received start request. Starting profile...
08-22 18:30:48.941  7302  7302 D HeadsetService: start()
08-22 18:30:48.941  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 18:30:48.941  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 18:30:48.941  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-22 18:30:48.941  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.941  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.941  7302  7302 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-22 18:30:48.941  7302  7302 D HeadsetStateMachine: make
,08-22 18:30:48.941  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.941  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.941  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.951  7302  7302 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 18:30:48.951  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-22 18:30:48.951  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 18:30:48.951  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 18:30:48.951  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.951  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.951  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.951  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.951  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.951  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 18:30:48.951  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:48.951  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:48.961  1015  1475 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 18:30:48.961  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.961  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.961  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:48.961  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-22 18:30:48.961  1015  1216 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.961  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-22 18:30:48.961  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.961  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.961  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.961  1015  4194 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-22 18:30:48.961  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-22 18:30:48.961  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-22 18:30:48.961  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:48.961  7302  7317 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-22 18:30:48.961  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:30:48.961  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.961  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.961  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 18:30:48.961  7302  7302 I bluedroid: get_profile_interface handsfree
08-22 18:30:48.961  1015  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:48.961  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 18:30:48.961  7325  7325 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:48.971  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:48.971  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:48.971  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 18:30:48.971  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:48.971  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 18:30:48.971  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,08-22 18:30:48.971  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 18:30:48.971  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 18:30:48.971  7302  7317 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 18:30:48.991  7302  7302 I DualScoManager: Instantiating Dual Sco Manager
08-22 18:30:48.991  7302  7302 I DualScoManager: Set HeadsetServiceHelper
,08-22 18:30:48.991  7302  7302 D BluetoothAtMessage: createCMTIContentObservers
,08-22 18:30:48.991  1015  1535 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-22 18:30:48.991  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:48.991  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:48.991  1015  1535 D SettingsProvider: selectionArgs: false
,08-22 18:30:48.991  1015  1535 D SettingsProvider: selectionArgs: 1002
08-22 18:30:48.991  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:48.991  1015  1535 D SettingsProvider: ret = -1
,08-22 18:30:48.991  7302  7335 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 18:30:48.991  7302  7302 D HeadsetService: mStartError = false
08-22 18:30:48.991  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:48.991  7302  7335 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-22 18:30:49.001  7302  7302 D A2dpService: Received start request. Starting profile...
08-22 18:30:49.001  7302  7302 D A2dpService: start()
08-22 18:30:49.001  7302  7335 D HeadsetStateMachine: map size, before remove : 0
,08-22 18:30:49.001  7302  7335 D HeadsetStateMachine: map size, after remove: 0
,08-22 18:30:49.001  7302  7302 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-22 18:30:49.001  7302  7302 I bluedroid: get_profile_interface avrcp
,08-22 18:30:49.001  7325  7325 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-22 18:30:49.011  7302  7302 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
08-22 18:30:49.011  7302  7302 D Avrcp   : Initialize Media Controller
08-22 18:30:49.011  7302  7302 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 18:30:49.011  7302  7302 E Avrcp   : getActiveSessions
08-22 18:30:49.011  7302  7302 D Avrcp   : pick active media Controller
08-22 18:30:49.011  7302  7302 D Avrcp   : Get the active Media Controller 
,08-22 18:30:49.021  7302  7302 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 18:30:49.021  7302  7345 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 18:30:49.021  7302  7302 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:30:49.031  7302  7302 D A2dpStateMachine: make
,08-22 18:30:49.031  7302  7302 I bluedroid: get_profile_interface a2dp
,08-22 18:30:49.031  7302  7347 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 18:30:49.031  7302  7302 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 18:30:49.031  7302  7302 D A2dpService: mStartError = false
08-22 18:30:49.031  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:49.031  7302  7346 D A2dpStateMachine: Enter Disconnected: -2
,08-22 18:30:49.031  7302  7302 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 18:30:49.031  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-22 18:30:49.031  7325  7325 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-22 18:30:49.041  7302  7302 D HidService: Received start request. Starting profile...
08-22 18:30:49.041  7302  7302 D HidService: start()
08-22 18:30:49.041  7302  7302 I bluedroid: get_profile_interface hidhost
08-22 18:30:49.041  7302  7302 D HidService: setHidService(): set to: null
08-22 18:30:49.041  7302  7302 D HidService: mStartError = false
08-22 18:30:49.041  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:49.041  7325  7325 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-22 18:30:49.041  7325  7325 D UserAnalysis: Create SecureDbHelper
,08-22 18:30:49.041  7302  7302 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 18:30:49.041  7302  7302 D HealthService: Received start request. Starting profile...
08-22 18:30:49.041  7302  7302 D HealthService: start()
,08-22 18:30:49.041  7302  7345 D BluetoothMediaBrowser: no now playing list
08-22 18:30:49.041  7302  7345 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-22 18:30:49.041  7302  7302 I bluedroid: get_profile_interface health
08-22 18:30:49.041  7302  7302 D HealthService: mStartError = false
08-22 18:30:49.041  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:49.041  7302  7302 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-22 18:30:49.041  7302  7302 D PanService: Received start request. Starting profile...
08-22 18:30:49.041  7302  7302 D PanService: start()
08-22 18:30:49.041  7325  7325 D IntelligenceServiceApplication: onCreate()
08-22 18:30:49.041  7302  7302 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:30:49.041  7302  7302 I bluedroid: get_profile_interface pan
08-22 18:30:49.041  7302  7302 D PanService: mStartError = false
08-22 18:30:49.041  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:49.041  7302  7302 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 18:30:49.051  1431  3252 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 18:30:49.051  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-22 18:30:49.051  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 18:30:49.051  1431  3252 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 18:30:49.051  1015  1219 I ActivityManager: Killing 6978:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-22 18:30:49.051  7302  7302 D BluetoothMapService: Received start request. Starting profile...
08-22 18:30:49.051  7302  7302 D BluetoothMapService: start()
,08-22 18:30:49.051  7302  7302 D BluetoothMapService: mStartError = false
08-22 18:30:49.051  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:49.051  7302  7302 D HeadsetStateMachine: Proxy object connected
,08-22 18:30:49.051  7302  7302 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-22 18:30:49.061  7302  7302 D SapService: Received start request. Starting profile...
,08-22 18:30:49.061  7302  7302 D SapService: start()
08-22 18:30:49.061  7302  7302 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 18:30:49.061  7302  7302 I bluedroid: get_profile_interface sap
08-22 18:30:49.061  7302  7302 D SapService: mStartError = false
08-22 18:30:49.061  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:49.061  7302  7302 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-22 18:30:49.061  7325  7325 D IntelligenceServiceApplication: no applications having user consent for prediction
08-22 18:30:49.061  7302  7302 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 18:30:49.061  7302  7335 D HeadsetStateMachine: Disconnected process message: 11
08-22 18:30:49.061  7302  7335 D HeadsetStateMachine: Disconnected process message: 18
08-22 18:30:49.061  7302  7302 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-22 18:30:49.061  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 18:30:49.061  7302  7302 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 18:30:49.061  7302  7302 D BluetoothA2dp: Proxy object connected
08-22 18:30:49.061  7302  7302 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 18:30:49.061  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 18:30:49.061  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 18:30:49.061  7302  7335 D HeadsetStateMachine: Disconnected process message: 10
08-22 18:30:49.061  7302  7335 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 18:30:49.061  7302  7335 D HeadsetStateMachine: Disconnected process message: 11
,08-22 18:30:49.061  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-22 18:30:49.061  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-22 18:30:49.061  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 18:30:49.061  7325  7325 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-22 18:30:49.061  1015  1509 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-22 18:30:49.061  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:49.071  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:49.071  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:49.071  1015  1509 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:49.071  7325  7325 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-22 18:30:49.081  7352  7352 E Zygote  : MountEmulatedStorage()
,08-22 18:30:49.081  7352  7352 E Zygote  : v2,
,08-22 18:30:49.081  7352  7352 I libpersona: KNOX_SDCARD checking this for 10105
08-22 18:30:49.081  7352  7352 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:49.081  7352  7352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:49.081  7352  7352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:30:49.081  1015  1509 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7352 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-22 18:30:49.081  7352  7352 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:30:49.111  7352  7352 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:49.111  7352  7352 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:49.111  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-22 18:30:49.111  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 18:30:49.121  7302  7317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-22 18:30:49.121  7302  7317 I bluedroid: enable
,08-22 18:30:49.131  7302  7367 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-22 18:30:49.131  7302  7317 I bt_hci_bdroid: init
,08-22 18:30:49.131  7302  7317 I bt_vendor: bt-vendor : init
,08-22 18:30:49.131  7302  7317 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 18:30:49.131  7302  7317 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 18:30:49.131  7302  7317 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-22 18:30:49.131  7302  7317 D bt_userial_mct: userial_init
08-22 18:30:49.131  7302  7317 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-22 18:30:49.131  7302  7317 I bt_vendor: Starting hciattach daemon
08-22 18:30:49.131  7302  7317 I bt_vendor: try to set false
,08-22 18:30:49.131  7302  7317 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-22 18:30:49.131  7302  7317 I bt_vendor: Starting hciattach daemon
08-22 18:30:49.131  7302  7317 I bt_vendor: try to set true
,08-22 18:30:49.151  7371  7371 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-22 18:30:49.201  7377  7377 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-22 18:30:49.211  7378  7378 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 18:30:49.231  7382  7382 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 18:30:49.241  7383  7383 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-22 18:30:49.251  7384  7384 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 18:30:49.251  7385  7385 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-22 18:30:49.281  1015  3347 D SSRM:n  : SIOP:: AP = 340
,08-22 18:30:49.281   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 18:30:49.281   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:49.281  7352  7390 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 18:30:49.291   256   517 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-22 18:30:49.291   256   517 W Vold    : Returning OperationFailed - no handler for errno 0
,08-22 18:30:49.291  7352  7390 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.k.d(PG:583)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.e.b(PG:170)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.exists(File.java:363)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.431  1015  1219 I ActivityManager: Killing 6990:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
08-22 18:30:49.431  7352  7352 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:30:49.431  7352  7352 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:30:49.441  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-22 18:30:49.441  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:49.461  7400  7400 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
08-22 18:30:49.471  7401  7401 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-22 18:30:49.481  7302  7317 I bt_vendor: bluetooth satus is on
08-22 18:30:49.491  7302  7369 D bt_userial_mct: userial_open(port:0)
08-22 18:30:49.491  7302  7369 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-22 18:30:49.491  7302  7369 I bt_vendor: Done intiailizing UART
08-22 18:30:49.491  7302  7369 I bt_vendor: Done intiailizing UART
08-22 18:30:49.491  7352  7395 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-22 18:30:49.491  7302  7369 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-22 18:30:49.491  7302  7369 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-22 18:30:49.491  7302  7403 D bt_userial_mct: Entering userial_read_thread()
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_HCI
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_AVDT
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_BNEP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_BTM
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_PAN
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_SAP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_SDP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_BTIF
08-22 18:30:49.501  7302  7367 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-22 18:30:49.591  7302  7367 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-22 18:30:49.591  7302  7367 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41f4ed1 
,08-22 18:30:49.591  7302  7367 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41f4ed1 
,08-22 18:30:49.611  7302  7320 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-22 18:30:49.611  7302  7320 E bt-btif : Calling BTA_HhEnable
,08-22 18:30:49.611  7302  7320 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-22 18:30:49.611  7302  7320 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-22 18:30:49.611  7302  7320 E BluetoothServiceJni: populateRssiValuesNative
08-22 18:30:49.611  7302  7320 I bluedroid: getModelRssiValues
08-22 18:30:49.611  7302  7320 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-22 18:30:49.611  7302  7320 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 18:30:49.661  1015  1027 I art     : Explicit concurrent mark sweep GC freed 66429(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 23MB/35MB, paused 2.840ms total 151.276ms
,08-22 18:30:49.671  1015  1446 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:49.671  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.671  1015  1446 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:49.671  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-22 18:30:49.671  7302  7320 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 18:30:49.671  1015  1015 D SettingsProvider: name = bluetooth_name
,08-22 18:30:49.681  7302  7320 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 18:30:49.681  7302  7320 D BluetoothAdapterProperties: Scan Mode:20
08-22 18:30:49.681  7302  7320 D BluetoothAdapterProperties: Discoverable Timeout:120
08-22 18:30:49.681  7302  7320 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-22 18:30:49.681  7302  7320 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-22 18:30:49.681  7302  7320 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-22 18:30:49.681  7302  7320 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-22 18:30:49.681  7302  7320 E bt-btif : btif_sock_init: !vhci_init
,08-22 18:30:49.681  7302  7320 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-22 18:30:49.681  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:49.681  7302  7320 D IOP_DB_BT: db_open: db_open : handle 3028434960l, read 13894 bytes onto local cache
08-22 18:30:49.681  7302  7320 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-22 18:30:49.681  7302  7320 D IOP_DB_BT: db_query: result 1
08-22 18:30:49.681  7302  7320 I         : iop_db_open: iop_db_open status 0
,08-22 18:30:49.681  7302  7320 D bte_conf: Device ID record 1 : primary
08-22 18:30:49.681  7302  7320 D bte_conf:   vendorId            = 0075
08-22 18:30:49.681  7302  7320 D bte_conf:   vendorIdSource      = 0001
08-22 18:30:49.681  7302  7320 D bte_conf:   product             = 0100
08-22 18:30:49.681  7302  7320 D bte_conf:   version             = 0200
08-22 18:30:49.681  7302  7320 D bte_conf:   clientExecutableURL = 
08-22 18:30:49.681  7302  7320 D bte_conf:   serviceDescription  = 
08-22 18:30:49.681  7302  7320 D bte_conf:   documentationURL    = 
08-22 18:30:49.681  7302  7320 D bte_conf: bte_load_did_conf no section named DID2.
08-22 18:30:49.681  7302  7320 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-22 18:30:49.681  7302  7403 E bt_mct  : hci lib postload completed
,08-22 18:30:49.681  7302  7317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-22 18:30:49.681  7302  7317 D BluetoothAdapterProperties: ScanMode =  20
08-22 18:30:49.681  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:49.681  7302  7317 D BluetoothAdapterProperties: State =  11
,08-22 18:30:49.691  1015  4194 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 18:30:49.691  7302  7317 D BluetoothAdapterProperties: Setting state to 12
08-22 18:30:49.691  7302  7317 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 18:30:49.691  7302  7320 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 18:30:49.691  7302  7320 D BluetoothAdapterProperties: Scan Mode:21
08-22 18:30:49.691  7302  7320 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 18:30:49.691  1015  4194 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-22 18:30:49.691  1015  4194 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:49.691  1015  4194 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:49.691  1015  4194 D SettingsProvider: selectionArgs: false
08-22 18:30:49.691  1015  4194 D SettingsProvider: selectionArgs: 1002
08-22 18:30:49.691  1015  4194 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:49.691  1015  4194 D SettingsProvider: ret = -1
,08-22 18:30:49.701  7302  7317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:49.701  7302  7317 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 18:30:49.701  1015  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:49.701  1015  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:49.701  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:49.701  1015  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.701  1015  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.701  1015  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.711  7302  7317 D BluetoothAdapterService: Autoconnection is available 
,08-22 18:30:49.711  7302  7317 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-22 18:30:49.711  7302  7317 D BluetoothAdapterService: starting service from this receiver
,08-22 18:30:49.711  1015  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:49.711  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.711  1450  3303 D BluetoothAdapter: onBluetoothStateChange: up=true,
08-22 18:30:49.711  1450  3303 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:49.721  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.721  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.721  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.721  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:49.721  1438  1805 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.721  1438  1805 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:49.721  7302  7317 I BluetoothAdapterState: Entering On State from state = 11
,08-22 18:30:49.721  1300  7072 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 18:30:49.731  7302  7302 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-22 18:30:49.731  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-22 18:30:49.731  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:49.731  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:49.731  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.731  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.731  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.731  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:49.731  1300  1315 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:30:49.741  1300  1315 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.741  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:49.741  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.741  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.741  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.741  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.741  1300  1300 D BluetoothA2dp: Proxy object connected
,08-22 18:30:49.741  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.741  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:49.741  1300  1300 D A2dpProfile: Bluetooth service connected
,08-22 18:30:49.741  1300  1315 D Bluetoothsap: onBluetoothStateChange: up=true
,08-22 18:30:49.741  1300  1315 D Bluetoothsap: Binding service...
,08-22 18:30:49.751  7302  7302 I BluetoothPbapService: Handler(): got msg=1
,08-22 18:30:49.751  1300  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 ,
08-22 18:30:49.751  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-22 18:30:49.751  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.751  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.751  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.751  1015  1216 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 18:30:49.751  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.751  1300  1315 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-22 18:30:49.751  1015  1045 D BluetoothPan: Binding service...
,08-22 18:30:49.761  7302  7409 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-22 18:30:49.761  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 18:30:49.761  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.761  1300  1300 D BluetoothInputDevice: Proxy object connected
08-22 18:30:49.761  1300  1300 D HidProfile: Bluetooth service connected
,08-22 18:30:49.761  1431  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.761  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:30:49.761  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-22 18:30:49.761  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:49.761  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:49.761  1300  1300 D SapProfile: Bluetooth service connected
,08-22 18:30:49.761  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.761  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.761  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.761  1431  1445 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 18:30:49.761  1300  1300 D Bluetoothsap: getConnectedDevices()
,08-22 18:30:49.761  1300  1315 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 18:30:49.771  7302  7409 D BluetoothSocket: bindListen(): myUserId = 0
08-22 18:30:49.771  7302  7409 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:49.771  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 18:30:49.771  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.771  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.771  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.771  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 18:30:49.771  7302  7409 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-22 18:30:49.771  7302  7409 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:49.771  7302  7409 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,08-22 18:30:49.771  7302  7409 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a60427f
08-22 18:30:49.771  7302  7409 D BluetoothSocket: channel: 19
08-22 18:30:49.771  7302  7409 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-22 18:30:49.771  1300  1300 D BluetoothPbap: Proxy object connected
,08-22 18:30:49.771  1300  1300 D PbapServerProfile: Bluetooth service connected
,08-22 18:30:49.771  1431  3252 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.771  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:49.771  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:49.781  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.781  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.781  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.781  1431  3252 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:49.781  1300  7072 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.781  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 18:30:49.781  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:49.781  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.781  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.781  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.781  1300  7072 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:49.781  1300  1300 D HeadsetProfile: Bluetooth service connected
08-22 18:30:49.781  7352  7360 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.781  7352  7360 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:49.781  6695  6703 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.781  6695  6703 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.791  1431  1467 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.791  1431  1467 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.791  1300  1310 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 18:30:49.791  1300  1310 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.791  7302  7321 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.791  7302  7321 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.791  7302  7316 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:30:49.791  1431  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.791  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset,
08-22 18:30:49.791  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.791  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:49.791  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:49.791  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-22 18:30:49.791  1431  1445 E BluetoothHeadset: BluetoothHeadset service is binded,
08-22 18:30:49.791  1300  1315 D BluetoothPan: Binding service...,
08-22 18:30:49.791  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-22 18:30:49.791  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
08-22 18:30:49.791  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.791  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.791  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 18:30:49.801  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 18:30:49.801  1300  1300 D PanProfile: Bluetooth service connected
08-22 18:30:49.801  1170  1934 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.801  1170  1934 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.801  1300  1310 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 18:30:49.801  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap,
08-22 18:30:49.801  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.801  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0,
08-22 18:30:49.801  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 18:30:49.801  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 18:30:49.801  2029  2999 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:49.801  2029  2999 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:49.801  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 18:30:49.801  1300  1300 D BluetoothMap: Proxy object connected
08-22 18:30:49.801  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:49.801  1300  1300 D MapProfile: Bluetooth service connected
,08-22 18:30:49.801  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:49.801  1300  1300 D BluetoothMap: getConnectedDevices()
08-22 18:30:49.801  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:49.801  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 18:30:49.801  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 18:30:49.801  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:30:49.801  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.801  1450  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:49.801  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:49.811  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:49.811  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.811  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.811  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.811  1450  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:49.811  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 18:30:49.811  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 18:30:49.821  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2268ddab, true
,08-22 18:30:49.821  1431  1431 D BluetoothHeadset: registerMessageListener
,08-22 18:30:49.821  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-22 18:30:49.821  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 18:30:49.821  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:49.821  1170  1170 D BluetoothTile:  getBluetoothState : 12
,08-22 18:30:49.821  1863  1863 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:49.831  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:49.831  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:49.831  1015  1475 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:49.831  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:49.831  1015  1532 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-22 18:30:49.831  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:49.831  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:49.841  1015  4193 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:49.841  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.841  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.841  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:49.841  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:49.841  7302  7316 D HeadsetService: registerMessageListener
,08-22 18:30:49.841  7302  7316 D HeadsetService: registerMessageListener
08-22 18:30:49.841  1015  1015 D BluetoothA2dp: Proxy object connected
,08-22 18:30:49.841  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,08-22 18:30:49.841  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 18:30:49.841  7302  7335 D HeadsetStateMachine: Disconnected process message: 70
,08-22 18:30:49.841  7302  7335 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@c79324c
08-22 18:30:49.841  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:49.851  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:49.851  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:49.851  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-22 18:30:49.851  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 18:30:49.851  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 18:30:49.851  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 18:30:49.851  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 18:30:49.851  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 18:30:49.851  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-22 18:30:49.851  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-22 18:30:49.851  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-22 18:30:49.851  7302  7412 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-22 18:30:49.851  7302  7335 D HeadsetStateMachine: Disconnected process message: 9
,08-22 18:30:49.851  7302  7335 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 18:30:49.861  7302  7412 D BluetoothSocket: bindListen(): myUserId = 0
08-22 18:30:49.861  7302  7412 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:49.861   282  1013 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-22 18:30:49.861  7302  7412 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-22 18:30:49.861  7302  7412 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:49.861  7302  7412 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 18:30:49.861  7302  7412 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fb5c295
,08-22 18:30:49.861   282  1013 V voice   : voice_set_parameters: enter: A2dpSuspended=false,
08-22 18:30:49.861   282  1013 V voice   : voice_set_parameters: exit with code(-2)
08-22 18:30:49.861   282  1013 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 18:30:49.861   282  1013 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 18:30:49.861   282  1013 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-22 18:30:49.861   282  1013 V audio_hw_primary: adev_set_parameters: exit
08-22 18:30:49.861  7302  7412 D BluetoothSocket: channel: 5
,08-22 18:30:49.861  7302  7335 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-22 18:30:49.871  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:49.881  1015  4194 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 18:30:49.881  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.881  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.881  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.881  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 18:30:49.881  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:49.891  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:49.891  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:49.891  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 18:30:49.901  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:49.901  7302  7302 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 18:30:49.901  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:49.901  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.901  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.901  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:49.901  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:49.921  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:49.921  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-22 18:30:49.921  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 18:30:49.931  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.931  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:49.931  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:49.931  1015  1532 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 18:30:49.941  2029  7419 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 18:30:49.941  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:49.941  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:49.941  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:49.941  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:49.941  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:49.961  7302  7422 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 18:30:49.961  7302  7422 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:49.961  1015  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:49.961  7302  7422 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-22 18:30:49.961  7302  7422 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:49.961  7302  7422 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 18:30:49.961  7302  7422 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36160277
,08-22 18:30:49.961  7302  7422 D BluetoothSocket: channel: 12
08-22 18:30:49.961  7302  7422 I BtOppRfcommListener: Accept thread started.
,08-22 18:30:49.971  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:49.971  1015  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:49.971  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:49.971  2029  7419 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-22 18:30:50.451   287   287 E SMD     : DCD OFF
,08-22 18:30:51.581  6695  6749 D BluetoothAdapter: disable()
,08-22 18:30:51.581  1015  1509 D SettingsProvider: name = bluetooth_on
,08-22 18:30:51.591  7302  7317 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF,
08-22 18:30:51.591  1015  1446 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:51.591  7302  7317 D BluetoothAdapterProperties: Setting state to 13
,08-22 18:30:51.591  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0,
08-22 18:30:51.591  7302  7317 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-22 18:30:51.591  7302  7317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:51.591  7302  7317 D BluetoothAdapterService: updateAdapterState state is 13
08-22 18:30:51.591  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:51.591  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:51.591  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:51.591  7302  7302 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-22 18:30:51.591  7302  7317 D BluetoothAdapterService: Autoconnection is available 
08-22 18:30:51.591  7302  7317 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-22 18:30:51.591  7302  7317 D BluetoothAdapterService: terminating service from this receiver
,08-22 18:30:51.591  7302  7302 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1b297ee4, channel: 19, state: LISTENING
08-22 18:30:51.591  7302  7302 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1b297ee4, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2a60427f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3dacaf4dmSocket: android.net.LocalSocket@27e4a02 impl:android.net.LocalSocketImpl@9de4f13 fd:FileDescriptor[74]
08-22 18:30:51.591  7302  7302 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@27e4a02 impl:android.net.LocalSocketImpl@9de4f13 fd:FileDescriptor[74]
,08-22 18:30:51.601  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:51.601  1015  1015 I InputMethodManagerService: [BT Setting State] State =13
,08-22 18:30:51.601  1170  1170 D BluetoothTile:  onBluetoothStateChange:,
,08-22 18:30:51.601  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 18:30:51.611  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:51.611  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:51.611  1170  1170 D BluetoothTile:  getBluetoothState : 13
,08-22 18:30:51.611  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:51.611  1863  1863 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:51.611  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-22 18:30:51.611  1015  4218 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:51.611  1015  4218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 18:30:51.621  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 18:30:51.621  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:51.621  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:51.621  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:51.621  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:51.621  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:51.631  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 18:30:51.631  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:51.631  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:51.631  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:51.631  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:51.631  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth,
08-22 18:30:51.631  6695  6695 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-22 18:30:51.631  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:51.631  7302  7317 D BluetoothAdapterProperties: onBluetoothDisable()
08-22 18:30:51.631  7302  7317 D BluetoothAdapterProperties: mDiscovering is false
,08-22 18:30:51.631  1015  1486 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 18:30:51.631  7302  7317 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-22 18:30:51.631  1015  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:51.631  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:51.641  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:51.641  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:51.641  1015  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:51.641  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:51.651  7302  7320 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 18:30:51.651  7302  7320 D BluetoothAdapterProperties: Scan Mode:20
,08-22 18:30:51.651  1015  1219 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 18:30:51.651  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 18:30:51.651  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:51.651  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:51.651  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 18:30:51.661  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:51.661  7302  7317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-22 18:30:51.661  7302  7317 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-22 18:30:51.661  7302  7317 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-22 18:30:51.661  7302  7317 E bt-btif : cmd socket is not created
,08-22 18:30:51.661  7302  7422 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-22 18:30:51.661  7302  7317 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-22 18:30:51.661  7302  7367 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-22 18:30:51.661  7302  7367 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-22 18:30:51.661  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:51.661  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:51.661  7302  7367 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-22 18:30:51.661  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:51.671  7302  7302 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b71a550, channel: 5, state: LISTENING
,08-22 18:30:51.671  7302  7302 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b71a550, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fb5c295, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@ba1f349mSocket: android.net.LocalSocket@3f8b044e impl:android.net.LocalSocketImpl@bd4c96f fd:FileDescriptor[76]
,08-22 18:30:51.671  7302  7302 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3f8b044e impl:android.net.LocalSocketImpl@bd4c96f fd:FileDescriptor[76]
08-22 18:30:51.681  7302  7302 I BtOppRfcommListener: stopping Accept Thread
08-22 18:30:51.681  1300  1300 D BluetoothPbap: Proxy object disconnected
08-22 18:30:51.681  1300  1300 D PbapServerProfile: Bluetooth service disconnected
,08-22 18:30:51.681  7302  7302 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@19d3c67c, channel: 12, state: LISTENING
,08-22 18:30:51.681  7302  7302 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@19d3c67c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36160277, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@58d7b05mSocket: android.net.LocalSocket@2397175a impl:android.net.LocalSocketImpl@1a0e8d8b fd:FileDescriptor[81]
08-22 18:30:51.681  7302  7302 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2397175a impl:android.net.LocalSocketImpl@1a0e8d8b fd:FileDescriptor[81]
,08-22 18:30:51.681  7302  7422 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-22 18:30:51.681  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:51.691  7302  7302 V BluetoothOppManager: cleanUp...
,08-22 18:30:51.691  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:51.691  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:51.691  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-22 18:30:51.721  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:51.721  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-22 18:30:51.861  7302  7367 W bt-btif : ag scb idx 1 not allocated
08-22 18:30:51.861  7302  7367 W bt-btif : ag scb idx 2 not allocated
08-22 18:30:51.861  7302  7367 E bt-btif : BTA AG is already disabled, ignoring ...
08-22 18:30:51.861  7302  7403 I bt_userial_mct: exiting userial_read_thread
08-22 18:30:51.861  7302  7403 D bt_userial_mct: Leaving userial_evt_read_thread()
08-22 18:30:51.861  7302  7320 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-22 18:30:51.861  7302  7369 I bt_vendor: hw_epilog_process
08-22 18:30:51.861  7302  7320 D bt_userial_mct: userial_close
08-22 18:30:51.861  7302  7320 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-22 18:30:52.651  1015  1486 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-22 18:30:52.651  1015  1486 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-22 18:30:52.651  1015  1486 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-22 18:30:52.651  1015  1486 D BatteryService: stay LED for fully charged
08-22 18:30:52.651  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 18:30:52.661  1015  1015 I MotionRecognitionService: Plugged
,08-22 18:30:52.661  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 18:30:52.661  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 18:30:52.661  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 18:30:52.671  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-22 18:30:52.671  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-22 18:30:52.681  7302  7302 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-22 18:30:52.681  7302  7335 D HeadsetStateMachine: Disconnected process message: 10
,08-22 18:30:52.691  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-22 18:30:52.691  1170  1170 D SViewCoverView: level :100 plugged : 2
,08-22 18:30:52.691  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:52.691  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 18:30:52.691  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:30:52.811  7302  7320 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-22 18:30:52.811  7302  7320 I bt_vendor: bluetooth satus is on
08-22 18:30:52.811  7302  7320 I bt_vendor: bt-vendor : resetting BT status
08-22 18:30:52.811  7302  7320 I bt_vendor: Starting hciattach daemon
08-22 18:30:52.811  7302  7320 I bt_vendor: try to set false
,08-22 18:30:52.811  7302  7320 I bt_vendor: Starting hciattach daemon
08-22 18:30:52.811  7302  7320 I bt_vendor: try to set false
,08-22 18:30:52.811  7302  7320 I bt_vendor: cleanup
,08-22 18:30:52.811  7302  7367 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-22 18:30:52.811  7302  7320 I GKI_LINUX: GKI_exit_task 0 done
08-22 18:30:52.811  7302  7320 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-22 18:30:52.811  7302  7317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-22 18:30:52.811  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:52.811  7302  7317 D BtConfig.SecureMode: isSecureModeOn:false
08-22 18:30:52.811  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-22 18:30:52.811  7302  7317 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-22 18:30:52.811  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.811  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 18:30:52.811  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-22 18:30:52.811  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 18:30:52.811  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-22 18:30:52.811  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.811  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:52.811  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:52.811  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-22 18:30:52.811  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 18:30:52.821  1015  4194 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.811  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 18:30:52.821  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 18:30:52.811  7302  7302 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-22 18:30:52.811  7302  7302 D BtGatt.GattService: Received stop request...Stopping profile...
08-22 18:30:52.821  7302  7302 D BtGatt.GattService: stop()
08-22 18:30:52.821  7302  7302 D BtGatt.AdvertiseManager: advertise clients cleared
08-22 18:30:52.821  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.821  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 18:30:52.821  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:52.821  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 18:30:52.821  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 18:30:52.821  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService,
08-22 18:30:52.821  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
08-22 18:30:52.821  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.821  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 18:30:52.821  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:52.821  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService,
08-22 18:30:52.821  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService,
08-22 18:30:52.821  1015  4193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.821  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 18:30:52.821  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0,
08-22 18:30:52.821  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.821  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-22 18:30:52.821  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:52.831  1015  4218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.831  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 18:30:52.831  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0,
08-22 18:30:52.831  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 18:30:52.831  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 18:30:52.831  1015  4218 W ActivityManager: userId = 0, bbcId = -10000,
,08-22 18:30:52.831  1015  4218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:52.831  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:52.831  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:52.831  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-22 18:30:52.831  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-22 18:30:52.831  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 18:30:52.831  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 18:30:52.831  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.831  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:52.831  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:52.841  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:52.841  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.841  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:52.841  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:52.841  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-22 18:30:52.841  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:52.841  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 18:30:52.841  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.841  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:52.841  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 18:30:52.841  7302  7317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 18:30:52.841  7302  7317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-22 18:30:52.841  7302  7317 D BluetoothAdapterState: Stopping profile services that were post enabled
08-22 18:30:52.841  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-22 18:30:52.841  7302  7302 D HeadsetService: Received stop request...Stopping profile...
08-22 18:30:52.841  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.851  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-22 18:30:52.851  1300  1300 D HeadsetProfile: Bluetooth service disconnected
,08-22 18:30:52.851  7302  7302 D A2dpService: Received stop request...Stopping profile...
,08-22 18:30:52.851  7302  7346 D A2dpStateMachine: Exit Disconnected: -1
,08-22 18:30:52.851  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.851  1015  1015 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:52.851  1015  1015 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-22 18:30:52.861  7302  7302 D HidService: Received stop request...Stopping profile...
08-22 18:30:52.861  7302  7302 D HidService: Stopping Bluetooth HidService
08-22 18:30:52.861  7302  7302 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-22 18:30:52.861  7302  7302 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-22 18:30:52.861  7302  7302 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-22 18:30:52.861  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.861  1300  1300 D BluetoothA2dp: Proxy object disconnected
08-22 18:30:52.861  1300  1300 D A2dpProfile: Bluetooth service disconnected
08-22 18:30:52.861  1300  1300 D BluetoothInputDevice: Proxy object disconnected
08-22 18:30:52.861  1300  1300 D HidProfile: Bluetooth service disconnected
,08-22 18:30:52.861  7302  7302 D HealthService: Received stop request...Stopping profile...
08-22 18:30:52.861  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.861  7302  7302 D PanService: Received stop request...Stopping profile...
,08-22 18:30:52.861  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.861  1015  1015 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-22 18:30:52.861  7302  7302 D BluetoothMapService: Received stop request...Stopping profile...
08-22 18:30:52.861  1300  1300 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-22 18:30:52.861  1300  1300 D PanProfile: Bluetooth service disconnected
,08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.871  7302  7302 D SapService: Received stop request...Stopping profile...
08-22 18:30:52.871  7302  7302 D SapService: Stopping Bluetooth SapService
08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@bc82d8d
,08-22 18:30:52.871  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-22 18:30:52.871  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-22 18:30:52.871  7302  7302 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-22 18:30:52.871  7302  7302 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-22 18:30:52.871  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-22 18:30:52.871  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-22 18:30:52.871  7302  7302 D BluetoothA2dp: Proxy object disconnected,
08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-22 18:30:52.871  7302  7347 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-22 18:30:52.871  7302  7302 I GKI_LINUX: GKI_exit_task 2 done
08-22 18:30:52.871  7302  7302 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-22 18:30:52.871  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-22 18:30:52.871  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:52.871  7302  7302 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.881  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-22 18:30:52.881  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService,
08-22 18:30:52.881  7302  7302 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.881  1300  1300 D BluetoothMap: Proxy object disconnected
08-22 18:30:52.881  1300  1300 D MapProfile: Bluetooth service disconnected
08-22 18:30:52.881  7302  7302 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-22 18:30:52.881  7302  7302 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object,
08-22 18:30:52.881  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-22 18:30:52.881  1300  1300 D SapProfile: Bluetooth service disconnected
08-22 18:30:52.881  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-22 18:30:52.881  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.881  7302  7302 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:52.881  7302  7302 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-22 18:30:52.881  7302  7302 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-22 18:30:52.881  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-22 18:30:52.881  7302  7302 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:52.881  7302  7302 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-22 18:30:52.881  7302  7302 E BluetoothAdapterService(197668237): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-22 18:30:52.881  7302  7302 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-22 18:30:52.881  7302  7302 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-22 18:30:52.881  7302  7317 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-22 18:30:52.881  7302  7317 D BluetoothAdapterProperties: Setting state to 10
,08-22 18:30:52.881  7302  7317 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-22 18:30:52.881  7302  7317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:52.881  7302  7317 D BluetoothAdapterService: updateAdapterState state is 10
08-22 18:30:52.881  7302  7317 D BluetoothAdapterService: Autoconnection is available 
08-22 18:30:52.881  7302  7317 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-22 18:30:52.881  7302  7317 I BluetoothAdapterState: Entering OffState
,08-22 18:30:52.881  1450  1477 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.881  1450  1477 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.881  1438  1805 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.881  1438  1805 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-22 18:30:52.881  1300  1315 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-22 18:30:52.881  1300  7072 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:52.881  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.881  1015  1045 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.881  1300  1310 D Bluetoothsap: onBluetoothStateChange: up=false
08-22 18:30:52.881  1300  1310 D Bluetoothsap: Unbinding service...
08-22 18:30:52.881  1300  1315 D BluetoothPbap: onBluetoothStateChange: up=false
08-22 18:30:52.881  7352  7360 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.881  7352  7360 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  6695  7068 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.891  6695  7068 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  6695  7068 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-22 18:30:52.891  6695  7068 D BluetoothLeAdvertiser: Exit stop advertising
08-22 18:30:52.891  6695  7068 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-22 18:30:52.891  6695  7068 D BluetoothLeScanner: Exiting stopAllScan
08-22 18:30:52.891  1431  1467 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.891  1431  1467 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  1300  1310 D BluetoothAdapter: onBluetoothStateChange: up=false,
08-22 18:30:52.891  1300  1310 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  7302  7316 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.891  7302  7316 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  7302  7410 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-22 18:30:52.891  1170  1934 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.891  1170  1934 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  1300  7072 D BluetoothMap: onBluetoothStateChange: up=false
08-22 18:30:52.891  2029  2039 D BluetoothAdapter: onBluetoothStateChange: up=false
08-22 18:30:52.891  2029  2039 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-22 18:30:52.891  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
08-22 18:30:52.891  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-22 18:30:52.891  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 18:30:52.901  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:52.901  1015  1015 I InputMethodManagerService: [BT Setting State] State =10
08-22 18:30:52.901  1015  1015 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 18:30:52.901  7302  7320 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-22 18:30:52.901  7302  7302 I GKI_LINUX: GKI_exit_task 1 done
08-22 18:30:52.901  7302  7302 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-22 18:30:52.901  7302  7302 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-22 18:30:52.901  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.901  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-22 18:30:52.901  1170  1738 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
,08-22 18:30:52.911  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:52.911  1170  1170 D BluetoothTile:  getBluetoothState : 10
,08-22 18:30:52.911  1170  1738 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.911  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.911  1170  1170 D BluetoothAdapter: 594994116: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.911  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 18:30:52.911  1863  1863 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:52.911  1015  1028 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 18:30:52.911  2029  2221 D BluetoothAdapter: 931053858: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.911  2029  2221 D BluetoothAdapter: 931053858: getState() :  mService = null. Returning STATE_OFF
08-22 18:30:52.911  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:52.911  7302  7302 I art     : System.exit called, status: 0
08-22 18:30:52.911  7302  7302 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-22 18:30:52.911  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 18:30:52.911  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.911  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:52.911  1015  4193 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:52.911  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-22 18:30:52.921  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:52.921  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:52.921  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:52.921  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-22 18:30:52.921  1015  1219 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-22 18:30:52.921  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 18:30:52.921  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:52.921  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:52.921  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 18:30:52.931  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:52.931  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:52.941  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:52.941  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-22 18:30:52.951  1015  1027 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 18:30:52.951  1015  1027 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
08-22 18:30:52.951  1015  1027 W BroadcastQueue: android.os.TransactionTooLargeException
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-22 18:30:52.951  1015  1027 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 18:30:52.951  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-22 18:30:52.961  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:52.961  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:52.961  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:52.961  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:52.971  7438  7438 E Zygote  : MountEmulatedStorage()
08-22 18:30:52.971  7438  7438 E Zygote  : v2
,08-22 18:30:52.971  7438  7438 I libpersona: KNOX_SDCARD checking this for 1002
08-22 18:30:52.971  7438  7438 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:52.971  1015  1027 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7438 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-22 18:30:52.981  7438  7438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:30:52.981  7438  7438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:30:52.981  7438  7438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:30:53.001  7438  7438 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:53.001  7438  7438 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:53.011  7438  7438 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-22 18:30:53.011  7438  7438 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:30:53.041  7438  7438 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding GattService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding HeadsetService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding A2dpService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding HidService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding HealthService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding PanService
08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding SapService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding SapClientService
,08-22 18:30:53.081  7438  7438 D BtSettings.ProfileConfig: Adding HidDevService
,08-22 18:30:53.081  7438  7438 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-22 18:30:53.091  1015  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-22 18:30:53.091  1015  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1219 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1219 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1219 D SettingsProvider: ret = -1
,08-22 18:30:53.091  1015  1509 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-22 18:30:53.091  1015  1509 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1509 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1509 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1509 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1509 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1509 D SettingsProvider: ret = -1
,08-22 18:30:53.091  1015  1219 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-22 18:30:53.091  1015  1219 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1219 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1219 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1219 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1219 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1219 D SettingsProvider: ret = -1
,08-22 18:30:53.091  1015  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-22 18:30:53.091  1015  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-22 18:30:53.091  1015  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:53.091  1015  1535 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1535 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:53.091  1015  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:53.091  1015  1535 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  1532 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService,
08-22 18:30:53.091  1015  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-22 18:30:53.091  1015  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:30:53.091  1015  1532 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1532 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1532 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  1446 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService,
08-22 18:30:53.091  1015  1446 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1446 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1446 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1446 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1446 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1446 D SettingsProvider: ret = -1
,08-22 18:30:53.091  1015  1216 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-22 18:30:53.091  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1216 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1216 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-22 18:30:53.091  1015  1216 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  1475 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-22 18:30:53.091  1015  1475 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1475 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1475 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1475 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:53.091  1015  1475 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1475 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  4193 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:53.091  1015  4193 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  4193 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  4193 D SettingsProvider: selectionArgs: false
,08-22 18:30:53.091  1015  4193 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  4193 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  4193 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  4194 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:53.091  1015  4194 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  4194 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  4194 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  4194 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  4194 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-22 18:30:53.091  1015  4194 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  1028 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-22 18:30:53.091  1015  1028 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1028 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1028 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1028 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1028 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1028 D SettingsProvider: ret = -1
08-22 18:30:53.091  1015  1478 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService,
08-22 18:30:53.091  1015  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:53.091  1015  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:53.091  1015  1478 D SettingsProvider: selectionArgs: false
08-22 18:30:53.091  1015  1478 D SettingsProvider: selectionArgs: 1002
08-22 18:30:53.091  1015  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:53.091  1015  1478 D SettingsProvider: ret = -1
,08-22 18:30:53.111  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:53.111  1015  1532 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:53.111  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 18:30:53.111  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:53.111  1015  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:53.111  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:53.121  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:53.121  2029  7455 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-22 18:30:53.121  1015  4193 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:53.131  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:53.131  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:53.131  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:53.131  2029  7455 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-22 18:30:53.451   287   287 E SMD     : DCD OFF
,08-22 18:30:54.091  1015  1048 I PowerManagerService: [PWL] Off : 75s ago
,08-22 18:30:54.091  1015  1048 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-22 18:30:54.091  1015  1048 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-22 18:30:54.091  1015  1048 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1015, ws=null) (elapsedTime=13646)
,08-22 18:30:54.491  1015  1320 E Watchdog: !@Sync 4
,08-22 18:30:54.591  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:30:54.591  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:30:56.031   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:56.451   287   287 E SMD     : DCD OFF,
,08-22 18:30:57.031   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:30:57.601  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:57.601  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e9f2b9e added. We now have 6 listener(s)
,08-22 18:30:57.601  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:57.601  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:57.601  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@343e67f added. We now have 7 listener(s)
,08-22 18:30:57.601  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:57.601  6695  6749 I System.out: IsBluetoothEnabled
,08-22 18:30:57.601  6695  6749 D BluetoothAdapter: disable()
,08-22 18:30:57.601  1015  1216 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-22 18:30:57.601  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:57.601  6695  6749 D BluetoothAdapter: enable()
,08-22 18:30:57.611  1015  4193 W ActivityManager: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 18:30:57.611  1015  4193 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-22 18:30:57.611  1015  4193 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 18:30:57.611  1015  4193 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 18:30:57.611  1015  4193 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:57.621  1015  4193 D SettingsProvider: name = bluetooth_on,
,08-22 18:30:57.631  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-22 18:30:57.631  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:57.631  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-22 18:30:57.631  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-22 18:30:57.651  7438  7438 D BluetoothAdapterState: make
,08-22 18:30:57.661  7438  7438 I bluedroid: init
,08-22 18:30:57.661  7438  7461 I BluetoothAdapterState: Entering OffState
,08-22 18:30:57.661  7438  7438 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-22 18:30:57.661  7438  7438 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-22 18:30:57.661  7438  7438 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-22 18:30:57.661  7438  7438 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-22 18:30:57.661  7438  7438 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-22 18:30:57.661  7438  7438 I bluedroid: get_profile_interface socket
08-22 18:30:57.661  7438  7438 I bluedroid: get_profile_interface map_client
,08-22 18:30:57.671  7438  7464 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-22 18:30:57.671  7438  7438 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-22 18:30:57.671  7438  7464 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-22 18:30:57.671  7438  7464 E BluetoothServiceJni: populateRssiValuesNative
08-22 18:30:57.671  7438  7464 I bluedroid: getModelRssiValues
08-22 18:30:57.671  7438  7464 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 18:30:57.671  7438  7464 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-22 18:30:57.671  7438  7464 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 18:30:57.671  1015  1015 D SettingsProvider: name = bluetooth_name
,08-22 18:30:57.681  7438  7438 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:57.681  1015  4194 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:57.681  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.681  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:57.681  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.681  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.681  7438  7446 I bluedroid: config_hci_snoop_log
,08-22 18:30:57.681  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-22 18:30:57.691  1015  1045 D BluetoothManagerService: Ble is always on enable gatt
,08-22 18:30:57.691  1015  1045 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-22 18:30:57.691  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-22 18:30:57.691  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 18:30:57.691  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:57.691  7438  7438 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-22 18:30:57.691  1015  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-22 18:30:57.691  1015  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-22 18:30:57.701  1015  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-22 18:30:57.701  7438  7461 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-22 18:30:57.701  7438  7461 D BluetoothAdapterProperties: Setting state to 11
08-22 18:30:57.701  7438  7461 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-22 18:30:57.701  7438  7461 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-22 18:30:57.701  7438  7461 D BluetoothAdapterService: updateAdapterState state is 11
,08-22 18:30:57.701  7438  7461 D BluetoothAdapterService: Autoconnection is available 
,08-22 18:30:57.701  7438  7461 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-22 18:30:57.711  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:57.711  1015  1015 I InputMethodManagerService: [BT Setting State] State =11
,08-22 18:30:57.711  7438  7461 D BluetoothSecureManager: getInstant: null
08-22 18:30:57.711  7438  7461 D BluetoothSecureManager: calling getMethod for getService
08-22 18:30:57.711  7438  7461 D BluetoothSecureManager: calling getService
,08-22 18:30:57.711  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 18:30:57.721  7438  7461 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2e9eecc1
,08-22 18:30:57.721  1015  4218 D BluetoothSecureManagerService: isSecureModeEnabled
08-22 18:30:57.721  1015  4218 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-22 18:30:57.721  7438  7461 D BtConfig.SecureMode: isSecureModeOn:false
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-22 18:30:57.721  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-22 18:30:57.721  1170  1170 D BluetoothTile:  getBluetoothState : 11
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-22 18:30:57.721  1863  1863 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-22 18:30:57.721  1015  1216 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 18:30:57.721  7438  7461 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:57.721  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-22 18:30:57.731  7438  7461 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:57.731  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:57.731  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:57.731  1015  4193 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-22 18:30:57.731  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
08-22 18:30:57.731  7438  7461 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:57.731  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-22 18:30:57.731  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 18:30:57.731  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-22 18:30:57.731  7438  7461 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-22 18:30:57.731  7438  7461 D BluetoothBondStateMachine: make
,08-22 18:30:57.731  1015  4218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:57.731  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.731  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-22 18:30:57.731  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-22 18:30:57.731  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-22 18:30:57.731  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:30:57.731  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.731  1015  4218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:57.731  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:57.731  7438  7465 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-22 18:30:57.731  1015  1486 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:57.741  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.741  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.741  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:57.741  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.741  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-22 18:30:57.741  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-22 18:30:57.741  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-22 18:30:57.741  7438  7438 D BtGatt.DebugUtils: handleDebugAction() action=null
08-22 18:30:57.741  7438  7438 D BtGatt.GattService: Received start request. Starting profile...
08-22 18:30:57.741  7438  7438 D BtGatt.GattService: start()
08-22 18:30:57.741  7438  7438 D BtGatt.GattService: start()
08-22 18:30:57.741  7438  7438 I bluedroid: get_profile_interface gatt
08-22 18:30:57.741  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
08-22 18:30:57.741  7438  7438 D BtGatt.AdvertiseManager: advertise manager created
,08-22 18:30:57.741  1015  1028 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:57.741  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.741  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.741  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:57.741  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.741  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:57.741  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-22 18:30:57.761  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-22 18:30:57.761  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-22 18:30:57.761  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-22 18:30:57.761  1015  1478 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:57.761  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.761  7438  7438 D BtGatt.GattService: mStartError = false
08-22 18:30:57.761  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.761  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:57.761  7438  7438 D HeadsetService: Received start request. Starting profile...
08-22 18:30:57.761  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.761  7438  7438 D HeadsetService: start()
,08-22 18:30:57.761  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.761  7438  7438 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-22 18:30:57.761  7438  7438 D HeadsetStateMachine: make
,08-22 18:30:57.761  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:57.761  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-22 18:30:57.771  7438  7438 E HeadsetStateMachine: # of Max HF connection is 2
,08-22 18:30:57.771  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-22 18:30:57.771  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-22 18:30:57.771  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-22 18:30:57.771  1015  1446 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:57.771  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.771  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:57.771  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.771  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.781  1015  1028 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-22 18:30:57.781  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.781  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.781  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.781  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 18:30:57.781  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-22 18:30:57.781  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-22 18:30:57.781  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-22 18:30:57.781  1015  1509 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-22 18:30:57.781  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-22 18:30:57.791  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.791  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.791  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-22 18:30:57.791  7438  7438 I bluedroid: get_profile_interface handsfree
08-22 18:30:57.791  1015  4193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:57.791  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.791  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.791  1015  4193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.791  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.791  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-22 18:30:57.791  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-22 18:30:57.791  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-22 18:30:57.791  1015  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:57.791  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.791  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:57.791  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.791  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.801  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-22 18:30:57.801  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-22 18:30:57.801  7438  7461 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-22 18:30:57.801  1015  1219 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:57.801  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.801  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.801  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.801  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:57.801  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-22 18:30:57.801  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-22 18:30:57.801  7438  7461 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-22 18:30:57.801  1015  1475 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:57.801  7438  7438 I DualScoManager: Instantiating Dual Sco Manager
08-22 18:30:57.801  7438  7438 I DualScoManager: Set HeadsetServiceHelper
08-22 18:30:57.801  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-22 18:30:57.811  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:57.811  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:57.811  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-22 18:30:57.811  7438  7438 D BluetoothAtMessage: createCMTIContentObservers
,08-22 18:30:57.811  1015  4194 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-22 18:30:57.811  1015  4194 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:57.811  1015  4194 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:57.811  1015  4194 D SettingsProvider: selectionArgs: false
08-22 18:30:57.811  1015  4194 D SettingsProvider: selectionArgs: 1002
08-22 18:30:57.811  1015  4194 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:57.811  1015  4194 D SettingsProvider: ret = -1
,08-22 18:30:57.811  7438  7469 D HeadsetStateMachine: Enter Disconnected: -2
,08-22 18:30:57.811  7438  7438 D HeadsetService: mStartError = false
08-22 18:30:57.811  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:57.811  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:57.811  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-22 18:30:57.811  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-22 18:30:57.811  7438  7461 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-22 18:30:57.811  7438  7461 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-22 18:30:57.811  7438  7469 D HeadsetStateMachine: Clear mHeadsetBrsf
08-22 18:30:57.811  7438  7469 D HeadsetStateMachine: map size, before remove : 0
08-22 18:30:57.811  7438  7469 D HeadsetStateMachine: map size, after remove: 0
08-22 18:30:57.811  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-22 18:30:57.821  7438  7461 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-22 18:30:57.821  7438  7438 D A2dpService: Received start request. Starting profile...
,08-22 18:30:57.821  7438  7438 D A2dpService: start()
,08-22 18:30:57.821  7438  7438 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-22 18:30:57.821  7438  7438 I bluedroid: get_profile_interface avrcp
,08-22 18:30:57.831  7438  7438 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-22 18:30:57.831  7438  7438 D Avrcp   : Initialize Media Controller
,08-22 18:30:57.831  7438  7438 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-22 18:30:57.831  7438  7438 E Avrcp   : getActiveSessions
,08-22 18:30:57.831  7438  7438 D Avrcp   : pick active media Controller
08-22 18:30:57.831  7438  7438 D Avrcp   : Get the active Media Controller 
,08-22 18:30:57.841  7438  7438 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-22 18:30:57.851  7438  7473 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-22 18:30:57.851  7438  7438 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-22 18:30:57.851  7438  7438 D A2dpStateMachine: make
,08-22 18:30:57.851  7438  7438 I bluedroid: get_profile_interface a2dp
,08-22 18:30:57.851  7438  7475 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-22 18:30:57.851  7438  7438 E bt-btif : warning : media task started media_task_refcnt 1 
,08-22 18:30:57.851  7438  7438 D A2dpService: mStartError = false
08-22 18:30:57.851  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.851  7438  7438 I BluetoothHidServiceJni: classInitNative: succeeds
,08-22 18:30:57.851  7438  7474 D A2dpStateMachine: Enter Disconnected: -2
,08-22 18:30:57.861  7438  7438 D HidService: Received start request. Starting profile...
08-22 18:30:57.861  7438  7438 D HidService: start()
08-22 18:30:57.861  7438  7438 I bluedroid: get_profile_interface hidhost
08-22 18:30:57.861  7438  7438 D HidService: setHidService(): set to: null
08-22 18:30:57.861  7438  7438 D HidService: mStartError = false
08-22 18:30:57.861  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.861  7438  7438 D HeadsetStateMachine: Try to query the phonestate on bind
,08-22 18:30:57.861  1431  1467 I Telecom : BluetoothPhoneService: queryPhoneState
,08-22 18:30:57.861  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-22 18:30:57.861  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 18:30:57.861  1431  1467 I Telecom : BluetoothPhoneService: Result of Message : true
,08-22 18:30:57.861  7438  7438 D HeadsetStateMachine: Proxy object connected
,08-22 18:30:57.861  7438  7438 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-22 18:30:57.861  7438  7438 D HealthService: Received start request. Starting profile...
08-22 18:30:57.861  7438  7438 D HealthService: start()
,08-22 18:30:57.861  7438  7473 D BluetoothMediaBrowser: no now playing list
08-22 18:30:57.861  7438  7473 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-22 18:30:57.871  7438  7438 I bluedroid: get_profile_interface health
,08-22 18:30:57.871  7438  7438 D HealthService: mStartError = false
08-22 18:30:57.871  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.871  7438  7438 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-22 18:30:57.871  7438  7438 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-22 18:30:57.871  7438  7469 D HeadsetStateMachine: Disconnected process message: 11
,08-22 18:30:57.871  7438  7438 D PanService: Received start request. Starting profile...
08-22 18:30:57.871  7438  7438 D PanService: start()
08-22 18:30:57.871  7438  7438 D BluetoothPanServiceJni: initializeNative(L110): pan
08-22 18:30:57.871  7438  7438 I bluedroid: get_profile_interface pan
,08-22 18:30:57.871  7438  7438 D PanService: mStartError = false
08-22 18:30:57.871  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.871  7438  7438 D HeadsetPhoneState: sendDeviceDataStateChanged
08-22 18:30:57.871  7438  7438 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-22 18:30:57.871  7438  7469 D HeadsetStateMachine: Disconnected process message: 18
,08-22 18:30:57.871  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:57.871  7438  7438 D BluetoothMapService: Received start request. Starting profile...
08-22 18:30:57.871  7438  7438 D BluetoothMapService: start()
,08-22 18:30:57.881  7438  7438 D BluetoothMapService: mStartError = false
08-22 18:30:57.881  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.881  7438  7438 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-22 18:30:57.881  7438  7438 D SapService: Received start request. Starting profile...
,08-22 18:30:57.881  7438  7438 D SapService: start()
,08-22 18:30:57.881  7438  7438 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-22 18:30:57.881  7438  7438 I bluedroid: get_profile_interface sap
08-22 18:30:57.881  7438  7438 D SapService: mStartError = false
08-22 18:30:57.881  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:30:57.881  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-22 18:30:57.881  7438  7438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 18:30:57.881  7438  7438 D BluetoothA2dp: Proxy object connected
08-22 18:30:57.881  7438  7438 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-22 18:30:57.881  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-22 18:30:57.881  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-22 18:30:57.881  7438  7469 D HeadsetStateMachine: Disconnected process message: 10,
08-22 18:30:57.881  7438  7469 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-22 18:30:57.881  7438  7469 D HeadsetStateMachine: Disconnected process message: 11
,08-22 18:30:57.881  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:57.891  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-22 18:30:57.891  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-22 18:30:57.911  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-22 18:30:57.911  7438  7438 E BluetoothAdapterService(26711891): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-22 18:30:57.911  7438  7461 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-22 18:30:57.911  7438  7461 I bluedroid: enable
,08-22 18:30:57.911  7438  7461 I bt_hci_bdroid: init
,08-22 18:30:57.911  7438  7480 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-22 18:30:57.911  7438  7461 I bt_vendor: bt-vendor : init
08-22 18:30:57.911  7438  7461 I bt_vendor: bt-vendor : get_bt_soc_type
08-22 18:30:57.911  7438  7461 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-22 18:30:57.911  7438  7461 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-22 18:30:57.911  7438  7461 D bt_userial_mct: userial_init
,08-22 18:30:57.911  7438  7461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-22 18:30:57.911  7438  7461 I bt_vendor: Starting hciattach daemon
08-22 18:30:57.911  7438  7461 I bt_vendor: try to set false
,08-22 18:30:57.921  7438  7461 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-22 18:30:57.921  7438  7461 I bt_vendor: Starting hciattach daemon
08-22 18:30:57.921  7438  7461 I bt_vendor: try to set true
,08-22 18:30:57.941  7484  7484 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-22 18:30:57.991  7490  7490 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-22 18:30:58.001  7491  7491 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 18:30:58.021  7493  7493 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-22 18:30:58.021   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:58.021  7494  7494 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-22 18:30:58.031  7495  7495 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-22 18:30:58.041  7496  7496 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-22 18:30:58.231  7499  7499 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-22 18:30:58.241  7500  7500 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-22 18:30:58.271  7438  7461 I bt_vendor: bluetooth satus is on
,08-22 18:30:58.271  7438  7482 D bt_userial_mct: userial_open(port:0)
08-22 18:30:58.271  7438  7482 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-22 18:30:58.281  7438  7482 I bt_vendor: Done intiailizing UART
,08-22 18:30:58.281  7438  7482 I bt_vendor: Done intiailizing UART,
08-22 18:30:58.281  7438  7482 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-22 18:30:58.281  7438  7482 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-22 18:30:58.291  7438  7502 D bt_userial_mct: Entering userial_read_thread()
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_HCI
,08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_AVRC
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_A2D
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_BTM,
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_GAP
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_PAN,
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_SAP
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_SDP
,08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_GATT
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_SMP
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_BTIF
08-22 18:30:58.291  7438  7480 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-22 18:30:58.381  7438  7480 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-22 18:30:58.391  7438  7480 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41eeed1 
,08-22 18:30:58.391  7438  7480 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41eeed1 
,08-22 18:30:58.401  7438  7464 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-22 18:30:58.401  7438  7464 E bt-btif : Calling BTA_HhEnable
,08-22 18:30:58.411  7438  7464 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048,
08-22 18:30:58.411  7438  7464 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-22 18:30:58.411  7438  7464 E BluetoothServiceJni: populateRssiValuesNative
08-22 18:30:58.411  7438  7464 I bluedroid: getModelRssiValues
,08-22 18:30:58.411  7438  7464 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-22 18:30:58.411  7438  7464 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-22 18:30:58.411  7438  7464 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-22 18:30:58.411  1015  1015 D SettingsProvider: name = bluetooth_name,
08-22 18:30:58.411  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:58.421  7438  7464 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-22 18:30:58.421  7438  7464 D BluetoothAdapterProperties: Scan Mode:20
,08-22 18:30:58.421  7438  7464 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 18:30:58.421  7438  7464 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
,08-22 18:30:58.421  7438  7464 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-22 18:30:58.421  7438  7464 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-22 18:30:58.421  7438  7464 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-22 18:30:58.421  7438  7502 E bt_mct  : hci lib postload completed
,08-22 18:30:58.431  7438  7464 E bt-btif : btif_sock_init: !vhci_init,
08-22 18:30:58.431  7438  7464 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-22 18:30:58.431  7438  7464 D IOP_DB_BT: db_open: db_open : handle 2966036496l, read 13894 bytes onto local cache
,08-22 18:30:58.431  7438  7464 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-22 18:30:58.431  7438  7464 D IOP_DB_BT: db_query: result 1
,08-22 18:30:58.431  7438  7464 I         : iop_db_open: iop_db_open status 0
,08-22 18:30:58.431  7438  7464 D bte_conf: Device ID record 1 : primary
,08-22 18:30:58.431  7438  7464 D bte_conf:   vendorId            = 0075
08-22 18:30:58.431  7438  7464 D bte_conf:   vendorIdSource      = 0001
08-22 18:30:58.431  7438  7464 D bte_conf:   product             = 0100
08-22 18:30:58.431  7438  7464 D bte_conf:   version             = 0200
08-22 18:30:58.431  7438  7464 D bte_conf:   clientExecutableURL = 
08-22 18:30:58.431  7438  7464 D bte_conf:   serviceDescription  = 
08-22 18:30:58.431  7438  7464 D bte_conf:   documentationURL    = 
08-22 18:30:58.431  7438  7464 D bte_conf: bte_load_did_conf no section named DID2.
,08-22 18:30:58.431  7438  7464 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-22 18:30:58.431  7438  7461 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-22 18:30:58.441  7438  7461 D BluetoothAdapterProperties: ScanMode =  20
,08-22 18:30:58.441  7438  7461 D BluetoothAdapterProperties: State =  11
,08-22 18:30:58.441  1015  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-22 18:30:58.441  7438  7461 D BluetoothAdapterProperties: Setting state to 12
,08-22 18:30:58.441  7438  7461 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-22 18:30:58.441  7438  7464 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-22 18:30:58.441  7438  7464 D BluetoothAdapterProperties: Scan Mode:21
08-22 18:30:58.441  7438  7464 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-22 18:30:58.451  1015  1216 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-22 18:30:58.451  1015  1216 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:30:58.451  1015  1216 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-22 18:30:58.451  1015  1216 D SettingsProvider: selectionArgs: false
08-22 18:30:58.451  1015  1216 D SettingsProvider: selectionArgs: 1002
,08-22 18:30:58.451  1015  1216 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:30:58.451  1015  1216 D SettingsProvider: ret = -1
08-22 18:30:58.451  7438  7461 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-22 18:30:58.451  7438  7461 D BluetoothAdapterService: updateAdapterState state is 12
,08-22 18:30:58.451  1015  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-22 18:30:58.451  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.451  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:58.451  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:58.451  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.461  1450  3302 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 18:30:58.461  1450  3302 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:58.461  7438  7461 D BluetoothAdapterService: Autoconnection is available 
,08-22 18:30:58.461  1438  1807 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.461  1438  1807 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.461  7438  7461 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-22 18:30:58.461  7438  7461 D BluetoothAdapterService: starting service from this receiver
,08-22 18:30:58.461  1015  4194 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:58.461  1300  1315 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-22 18:30:58.461  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.471  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.471  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.471  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.471  7438  7461 I BluetoothAdapterState: Entering On State from state = 11
08-22 18:30:58.471  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-22 18:30:58.471  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.471  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.471  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:58.471  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 18:30:58.471  1300  1310 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:58.471  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:58.471  1300  1310 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.471  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:58.471  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-22 18:30:58.481  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.481  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.481  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.481  1300  1300 D BluetoothA2dp: Proxy object connected
,08-22 18:30:58.481  1300  1300 D A2dpProfile: Bluetooth service connected
,08-22 18:30:58.481  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:58.481  7438  7453 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.481  7438  7453 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:58.481  1015  1045 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.481  1015  1045 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.481  1300  7072 D Bluetoothsap: onBluetoothStateChange: up=true
08-22 18:30:58.481  1300  7072 D Bluetoothsap: Binding service...
,08-22 18:30:58.481  7438  7438 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-22 18:30:58.481  1300  7072 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-22 18:30:58.491  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-22 18:30:58.491  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-22 18:30:58.491  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.491  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.491  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.491  1300  7072 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-22 18:30:58.491  1015  1045 D BluetoothPan: Binding service...
,08-22 18:30:58.491  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 18:30:58.491  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.491  1431  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.491  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 18:30:58.491  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:58.491  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.491  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:30:58.491  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.501  1431  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:58.501  7438  7453 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-22 18:30:58.501  1300  1310 D BluetoothPbap: onBluetoothStateChange: up=true
,08-22 18:30:58.501  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-22 18:30:58.501  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.501  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.501  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.501  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.501  7438  7438 I BluetoothPbapService: Handler(): got msg=1
,08-22 18:30:58.501  1300  1300 D BluetoothInputDevice: Proxy object connected
08-22 18:30:58.501  1300  1300 D HidProfile: Bluetooth service connected
,08-22 18:30:58.501  1431  3252 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.501  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:58.501  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:58.511  1015  1535 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 18:30:58.511  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.511  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.511  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.511  1431  3252 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:58.511  1300  7072 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.511  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:58.511  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:58.511  7438  7506 V BluetoothPbapService: PBAP Service initSocket try: 0
08-22 18:30:58.511  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.511  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.511  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.511  1015  1015 D BluetoothPan: BluetoothPAN Proxy object connected
08-22 18:30:58.511  1300  1300 D Bluetoothsap: BluetoothSAP Proxy object connected
08-22 18:30:58.511  1300  1300 D SapProfile: Bluetooth service connected
08-22 18:30:58.511  1300  1300 D Bluetoothsap: getConnectedDevices()
08-22 18:30:58.511  1300  7072 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:58.511  7352  7361 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 18:30:58.511  7352  7361 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:58.521  6695  6705 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-22 18:30:58.521  6695  6705 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.521  7438  7506 D BluetoothSocket: bindListen(): myUserId = 0
08-22 18:30:58.521  7438  7506 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:58.521  1431  3252 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.521  1431  3252 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.521  1300  1315 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.521  1300  1315 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.521  7438  7506 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-22 18:30:58.521  7438  7506 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:58.521  7438  7506 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 18:30:58.521  7438  7506 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fb5c295
,08-22 18:30:58.521  7438  7506 D BluetoothSocket: channel: 19
08-22 18:30:58.521  7438  7506 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-22 18:30:58.521  1300  1300 D HeadsetProfile: Bluetooth service connected
,08-22 18:30:58.521  1431  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.521  1015  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:58.521  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:58.521  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.521  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.521  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.521  1431  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:58.521  1300  7072 D BluetoothPan: Binding service...
,08-22 18:30:58.531  1300  1300 D BluetoothPbap: Proxy object connected
08-22 18:30:58.531  1300  1300 D PbapServerProfile: Bluetooth service connected
,08-22 18:30:58.571  1015  3367 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:30:58.631  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:30:58.631  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:30:58.641  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:30:58.641  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@195e064c added. We now have 8 listener(s)
08-22 18:30:58.641  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:30:58.641  1015  4194 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 18:30:58.641  1015  4194 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-22 18:30:58.641  1015  4194 D SecContentProvider2: mCursor = null
,08-22 18:30:58.641  1015  4194 D WifiService: setWifiEnabled: false pid=6695, uid=10171
,08-22 18:30:58.641  1015  4194 D SettingsProvider: name = wifi_on
,08-22 18:30:58.641  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:58.651  1015  4193 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-22 18:30:58.651  1015  4193 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-22 18:30:58.651  1015  4193 D SecContentProvider2: mCursor = null
,08-22 18:30:58.661  1015  4193 D WifiService: setWifiEnabled: true pid=6695, uid=10171
,08-22 18:30:58.661  1015  4193 W ActivityManager: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-22 18:30:58.661  1015  4193 W WifiService: Failed getting userId using ActivityManagerNative
08-22 18:30:58.661  1015  4193 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6695, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-22 18:30:58.661  1015  4193 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-22 18:30:58.661  1015  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-22 18:30:58.661  1015  4193 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-22 18:30:58.661  1015  4193 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-22 18:30:58.661  1015  4193 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-22 18:30:58.661  1015  4193 D SettingsProvider: name = wifi_on
,08-22 18:30:58.671  1015  1125 E WifiHW  : ##################### set firmware type 0 #####################
,08-22 18:30:58.671  1015  1045 I art     : Explicit concurrent mark sweep GC freed 18909(1073KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.737ms total 146.417ms,
08-22 18:30:58.671  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-22 18:30:58.671  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0,
,08-22 18:30:58.681  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.681  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.681  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
08-22 18:30:58.681  1300  1300 D BluetoothPan: BluetoothPAN Proxy object connected
,08-22 18:30:58.681  1300  1300 D PanProfile: Bluetooth service connected
08-22 18:30:58.681  1170  1198 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.681  1170  1198 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-22 18:30:58.681  1300  1310 D BluetoothMap: onBluetoothStateChange: up=true
,08-22 18:30:58.681  1015  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-22 18:30:58.681  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.681  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.681  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.681  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.691  2029  4971 D BluetoothAdapter: onBluetoothStateChange: up=true
08-22 18:30:58.691  2029  4971 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-22 18:30:58.691  1300  1300 D BluetoothMap: Proxy object connected
08-22 18:30:58.691  1300  1300 D MapProfile: Bluetooth service connected
08-22 18:30:58.691  1300  1300 D BluetoothMap: getConnectedDevices()
,08-22 18:30:58.691  1015  1045 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-22 18:30:58.691  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-22 18:30:58.691  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-22 18:30:58.691  1015  1045 E BluetoothHeadset: BluetoothHeadset service is binded
08-22 18:30:58.691  1015  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
08-22 18:30:58.691  1015  1045 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.691  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-22 18:30:58.691  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.691  1450  4118 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-22 18:30:58.691  1015  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-22 18:30:58.691  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-22 18:30:58.691  1015  1045 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.691  1015  1045 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.691  1015  1045 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.691  1450  4118 E BluetoothHeadset: BluetoothHeadset service is binded
,08-22 18:30:58.691  1015  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-22 18:30:58.691  1015  1045 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-22 18:30:58.701  1015  1015 D BluetoothA2dp: Proxy object connected
,08-22 18:30:58.701  1170  1170 D BluetoothTile:  onBluetoothStateChange:
,08-22 18:30:58.701  1170  1170 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-22 18:30:58.711  1170  1170 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:58.711  1170  1170 D BluetoothTile:  getBluetoothState : 12
08-22 18:30:58.711  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3772ac08, true
,08-22 18:30:58.711  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
,08-22 18:30:58.711  1863  1863 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-22 18:30:58.711  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null,
08-22 18:30:58.711  1431  1431 D BluetoothHeadset: registerMessageListener
,08-22 18:30:58.721  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:30:58.721  1015  4193 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:58.721  1015  4193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.721  7438  7453 D HeadsetService: registerMessageListener
08-22 18:30:58.721  1015  4193 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.721  1015  4193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:58.721  1015  4193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:58.721  1170  1738 D BluetoothTile:  handleUpdatestate:false name:null
08-22 18:30:58.721  1015  1015 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-22 18:30:58.721  1015  1015 I InputMethodManagerService: [BT Setting State] State =12
08-22 18:30:58.721  1015  1015 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-22 18:30:58.721  7438  7453 D HeadsetService: registerMessageListener
,08-22 18:30:58.721  7438  7469 D HeadsetStateMachine: Disconnected process message: 70
,08-22 18:30:58.721  7438  7469 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@5eb6faa
08-22 18:30:58.721  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-22 18:30:58.721  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-22 18:30:58.721  1300  1300 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:58.731  1015  4194 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:58.731  1015  1219 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-22 18:30:58.731  7438  7513 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-22 18:30:58.731  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-22 18:30:58.731  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-22 18:30:58.731  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-22 18:30:58.731  1300  1300 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-22 18:30:58.731  1300  1300 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-22 18:30:58.731  1300  1300 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-22 18:30:58.731  1170  1170 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-22 18:30:58.731  1300  1300 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-22 18:30:58.731  7438  7469 D HeadsetStateMachine: Disconnected process message: 9
,08-22 18:30:58.731  7438  7513 D BluetoothSocket: bindListen(): myUserId = 0
08-22 18:30:58.731  7438  7513 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-22 18:30:58.731  7438  7469 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-22 18:30:58.741  7438  7513 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-22 18:30:58.741  7438  7513 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:58.741  7438  7513 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 18:30:58.741  7438  7513 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8c0879b
,08-22 18:30:58.741  7438  7513 D BluetoothSocket: channel: 5
,08-22 18:30:58.741   282   282 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false,
08-22 18:30:58.741  1300  1300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-22 18:30:58.741   282   282 V voice   : voice_set_parameters: enter: A2dpSuspended=false
,08-22 18:30:58.741   282   282 V voice   : voice_set_parameters: exit with code(-2)
08-22 18:30:58.741   282   282 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-22 18:30:58.741   282   282 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-22 18:30:58.741   282   282 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-22 18:30:58.741   282   282 V audio_hw_primary: adev_set_parameters: exit
08-22 18:30:58.741  7438  7469 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-22 18:30:58.751  1015  1216 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-22 18:30:58.751  1015  1216 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.751  1015  1216 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.751  1015  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.751  1015  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-22 18:30:58.761  1300  1300 D DockEventReceiver: finishStartingService: stopping service
,08-22 18:30:58.761  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,08-22 18:30:58.761  1170  1170 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-22 18:30:58.761  1170  1170 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-22 18:30:58.771  7438  7438 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
08-22 18:30:58.771  7438  7438 D BtConfig.SecureMode: isSecureModeOn:false
,08-22 18:30:58.771  1015  1446 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-22 18:30:58.771  1015  1446 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.771  1015  1446 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:58.771  1015  1446 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:58.771  1015  1446 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-22 18:30:58.791  2029  2029 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-22 18:30:58.791  1015  1486 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-22 18:30:58.791  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-22 18:30:58.791  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:58.791  1015  1486 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:58.791  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:58.801  1015  1535 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-22 18:30:58.801  2029  7520 D EasyUnlockInitService: Handling intent for initializer IntentService.,
,08-22 18:30:58.801  2029  2029 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-22 18:30:58.811  1015  1532 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:58.811  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:58.811  1015  1532 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:58.811  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:58.821  7438  7523 D BluetoothSocket: bindListen(): myUserId = 0
,08-22 18:30:58.821  7438  7523 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-22 18:30:58.821  7438  7523 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-22 18:30:58.821  7438  7523 D BluetoothSocket: bindListen(), new LocalSocket 
08-22 18:30:58.821  7438  7523 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-22 18:30:58.821  7438  7523 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@36160277
,08-22 18:30:58.821  7438  7523 D BluetoothSocket: channel: 12
08-22 18:30:58.821  7438  7523 I BtOppRfcommListener: Accept thread started.
,08-22 18:30:58.821  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-22 18:30:58.821  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:30:58.821  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:30:58.821  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-22 18:30:58.831  2029  7520 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-22 18:30:58.961  1015  2071 V SAMP_SPCM_test: CSC File load.. 
,08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-22 18:30:58.971  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-22 18:30:58.981  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-22 18:30:59.011  1015  1043 D Tethering: interfaceAdded wlan0
,08-22 18:30:59.021  1015  1128 E Tethering: No numeric data
,08-22 18:30:59.021  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-22 18:30:59.021  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 18:30:59.021  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:59.031   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application,
,08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-22 18:30:59.041  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory,
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account,
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control,
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-22 18:30:59.031  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
08-22 18:30:59.041  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:59.041  1015  1043 D Tethering: interfaceStatusChanged p2p0, false,
08-22 18:30:59.041   277   994 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-22 18:30:59.041   277   994 D SoftapController: Softap fwReload - Ok
08-22 18:30:59.041  1015  1043 D Tethering: interfaceAdded p2p0
08-22 18:30:59.051  1015  1043 D Tethering: p2p0 is not a tetherable iface, ignoring
08-22 18:30:59.051   277   994 D CommandListener: Setting iface cfg
08-22 18:30:59.051   277   994 D CommandListener: Trying to bring down wlan0
,08-22 18:30:59.051   277   994 D CommandListener: Clearing all IP addresses on wlan0
,08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-22 18:30:59.061  1015  1125 E WifiHW  : supplicant_name : p2p_supplicant
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimes,oftcerts
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location,
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
,08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,08-22 18:30:59.061  1015  2071 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-22 18:30:59.061  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-22 18:30:59.061  1015  1128 D Tethering: clearTetheredNotification()
,08-22 18:30:59.061  1015  1128 D Tethering: InitialState.processMessage what=4
,08-22 18:30:59.071  1015  1128 E Tethering: No numeric data
,08-22 18:30:59.071  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:59.071  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:30:59.071  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:59.071  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:30:59.071  1015  1128 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-22 18:30:59.071  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:59.071  1015  1128 D Tethering: clearTetheredNotification()
08-22 18:30:59.071  1170  1170 D HotspotTile: updateTetherState():false, false
,08-22 18:30:59.071  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-22 18:30:59.071  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:59.081  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:30:59.081  1170  1170 D HotspotTile: updateTetherState():false, false
,08-22 18:30:59.091  1015  2071 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
,08-22 18:30:59.091  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:59.091  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:59.091  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:30:59.091  1015  2071 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:30:59.101  7532  7532 E Zygote  : MountEmulatedStorage()
,08-22 18:30:59.101  7532  7532 E Zygote  : v2
08-22 18:30:59.101  7532  7532 I libpersona: KNOX_SDCARD checking this for 1000
08-22 18:30:59.101  7532  7532 I libpersona: KNOX_SDCARD not a persona
,08-22 18:30:59.111  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 18:30:59.111  1015  2071 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7532 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 18:30:59.111  7532  7532 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:30:59.111  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
08-22 18:30:59.111  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:30:59.111  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:30:59.111  7531  7531 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-22 18:30:59.111  7531  7531 I wpa_supplicant: Successfully initialized wpa_supplicant
08-22 18:30:59.111  7531  7531 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-22 18:30:59.111  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:59.111  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:59.111  7532  7532 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:30:59.111  7532  7532 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 18:30:59.111  1015  1122 V NetworkStats: performPollLocked() took 8ms
08-22 18:30:59.111  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:59.121  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:30:59.121  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:30:59.131  7531  7531 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,08-22 18:30:59.131   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7531
,08-22 18:30:59.131   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-22 18:30:59.131  7531  7531 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
,08-22 18:30:59.131  7531  7531 I wpa_supplicant: ssSupport state is = 1
08-22 18:30:59.131  7531  7531 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-22 18:30:59.131  7531  7531 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-22 18:30:59.131   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7531
08-22 18:30:59.131   374   374 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
08-22 18:30:59.131   305   305 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 701us total 27.280ms
,08-22 18:30:59.151   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 699us total 19.574ms
,08-22 18:30:59.161  1015  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-22 18:30:59.161  7532  7532 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:30:59.161  7532  7532 D ActivityThread: Added TimaKeyStore provider
,08-22 18:30:59.171  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:30:59.171  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-22 18:30:59.171  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:59.171  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:59.171  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:30:59.171  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:30:59.171  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:30:59.171  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-22 18:30:59.171  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-22 18:30:59.171  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:30:59.171  1170  1170 D HotspotTile: onReceive : 2, 0
08-22 18:30:59.171   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 19.030ms
,08-22 18:30:59.171  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-22 18:30:59.181  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-22 18:30:59.191  1015  4194 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:30:59.191  1015  4194 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:30:59.191  1015  4194 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:30:59.191  1015  4194 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:30:59.191  1015  4194 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 18:30:59.191  1614  1614 I Hs20UtilService: Starting #19
08-22 18:30:59.191  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:30:59.191  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-22 18:30:59.191  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-22 18:30:59.191  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
08-22 18:30:59.191  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:30:59.201  7532  7532 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 18:30:59.241  1015  2071 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-22 18:30:59.301   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-22 18:30:59.301  1015  3347 D SSRM:n  : SIOP:: AP = 330
,08-22 18:30:59.311  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,08-22 18:30:59.361  7531  7531 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-22 18:30:59.361  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 18:30:59.371  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-22 18:30:59.371   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7531
08-22 18:30:59.371   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 18:30:59.371  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 18:30:59.371  7531  7531 I wpa_supplicant: ssSupport state is = 1,
08-22 18:30:59.371  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:59.371  7531  7531 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:59.371  7531  7531 E wpa_supplicant: SIM READ ERROR,
08-22 18:30:59.371  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:59.371  7531  7531 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:30:59.371  7531  7531 E wpa_supplicant: SIM READ ERROR,
08-22 18:30:59.371  7531  7531 I wpa_supplicant: Blacklist: Clear (all) 
08-22 18:30:59.371  7531  7531 I wpa_supplicant: wpa_default_ap_write_once
08-22 18:30:59.371  7531  7531 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap,
08-22 18:30:59.371  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:59.371  7531  7531 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-22 18:30:59.371  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 18:30:59.371  7531  7531 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 18:30:59.371  7531  7531 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 18:30:59.371  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 18:30:59.371  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:30:59.371  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:30:59.441   287   287 E SMD     : DCD OFF
08-22 18:30:59.441  7531  7531 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-22 18:30:59.781  7531  7531 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-22 18:30:59.781  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 18:30:59.791  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-22 18:30:59.791   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7531
08-22 18:30:59.791   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-22 18:30:59.791  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 18:30:59.791  7531  7531 I wpa_supplicant: ssSupport state is = 1
08-22 18:30:59.801  7531  7531 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-22 18:30:59.801  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-22 18:30:59.811  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-22 18:30:59.811   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7531
08-22 18:30:59.811   374   374 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
,08-22 18:30:59.821  7531  7531 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-22 18:30:59.821  7531  7531 I wpa_supplicant: ssSupport state is = 1
08-22 18:30:59.821  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-22 18:30:59.821  7531  7531 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-22 18:30:59.821  7531  7531 E wpa_supplicant: SIM READ ERROR
08-22 18:30:59.821  7531  7531 I wpa_supplicant: wpa_default_ap_write_once
08-22 18:30:59.821  7531  7531 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-22 18:30:59.821  7531  7531 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-22 18:30:59.821  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
,08-22 18:30:59.821  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:59.821  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:30:59.821  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:30:59.821  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-22 18:30:59.821  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:30:59.861  7531  7531 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-22 18:30:59.861  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-22 18:30:59.991  1015  1094 V AlarmManager: waitForAlarm result :8
,08-22 18:31:00.001  7531  7531 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-22 18:31:00.001  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-22 18:31:00.001  7531  7531 I wpa_supplicant: Skip scan - bUseNetwork false
,08-22 18:31:00.011  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-22 18:31:00.011  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-22 18:31:00.011  7531  7531 I wpa_supplicant: HOTSPOT20_ENABLE called,
08-22 18:31:00.011  7531  7531 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-22 18:31:00.011  7531  7531 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-22 18:31:00.011  7531  7531 E wpa_supplicant: SIM READ ERROR,
08-22 18:31:00.011  7531  7531 I wpa_supplicant: Blacklist: Clear (all) 
,08-22 18:31:00.021  1015  1043 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
08-22 18:31:00.021  1015  1043 D Tethering: interfaceLinkStateChanged p2p0, false
08-22 18:31:00.021  1015  1043 D Tethering: interfaceStatusChanged p2p0, false
,08-22 18:31:00.031   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-22 18:31:00.041  7531  7531 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-22 18:31:00.051  7531  7531 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-22 18:31:00.051  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:00.051  1170  1170 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:31:00.051  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 18:31:00.051  1170  1738 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-22 18:31:00.051  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:00.051  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:31:00.051  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:00.061  1170  1170 D HotspotTile: onReceive : 3, 0
08-22 18:31:00.051  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:31:00.051  1170  1170 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-22 18:31:00.051  1170  1170 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-22 18:31:00.061  1015  1125 D WifiConfigStore: Loading config and enabling all networks 
08-22 18:31:00.061  1300  1300 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:00.071  6695  6695 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-22 18:31:00.071  1015  1125 E WifiConfigStore: Not a HS20
,08-22 18:31:00.071  1015  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-22 18:31:00.071  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:31:00.071  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:00.071  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
08-22 18:31:00.071  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:00.071  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 18:31:00.071  6695  6695 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:00.071  1015  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-22 18:31:00.071  1614  1614 I Hs20UtilService: Starting #20
,08-22 18:31:00.071  1614  1635 I Hs20UtilService: Message received 5011
,08-22 18:31:00.081  1015  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-22 18:31:00.081  7531  7531 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-22 18:31:00.081  7531  7531 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-22 18:31:00.081  7531  7531 I wpa_supplicant: reset timer : RESET_TIMER 0
08-22 18:31:00.081  7531  7531 I wpa_supplicant: P2P: Current p2p state = IDLE
08-22 18:31:00.081  7531  7531 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-22 18:31:00.081  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-22 18:31:00.081  7531  7531 I wpa_supplicant: First Scan Start
08-22 18:31:00.081  7531  7531 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-22 18:31:00.081  1015  1125 D WifiNative-wlan0: Setting external_sim to 1
,08-22 18:31:00.081  6938  6938 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-22 18:31:00.081  1015  1125 D WifiStateMachine: Setting OUI to DA-A1-19
08-22 18:31:00.081  1015  1125 I WifiNative-HAL: startHal
08-22 18:31:00.081  1015  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9d67d88c
08-22 18:31:00.081  1015  1125 I WifiNative-HAL: Could not start hal
,08-22 18:31:00.081  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-22 18:31:00.081  6509  6509 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-22 18:31:00.081  6509  6509 D SecurityLogAgent: StateMachine : Current State = 1
08-22 18:31:00.081  6509  6509 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-22 18:31:00.091  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 18:31:00.091  1015  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-22 18:31:00.091   277   994 D CommandListener: Setting iface cfg
08-22 18:31:00.091   277   994 D CommandListener: Trying to bring up p2p0
08-22 18:31:00.091  1015  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-22 18:31:00.091  1015  1124 D WifiP2pService: P2pEnablingState
,08-22 18:31:00.091  1015  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-22 18:31:00.091  1015  1124 D WifiP2pService: P2p socket connection successful
,08-22 18:31:00.091  1015  1124 D WifiP2pService: P2pEnabledState
,08-22 18:31:00.091  1015  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-22 18:31:00.091  1015  1015 D WifiScanningService: SCAN_AVAILABLE : 3,
08-22 18:31:00.091  1015  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-22 18:31:00.091  1015  1147 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:00.091  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:31:00.091  1015  1147 I WifiNative-HAL: startHal
08-22 18:31:00.091  1015  1147 E wifi    : getStaticLongField sWifiHalHandle 0x9e3159bc
08-22 18:31:00.091  1015  1147 I WifiNative-HAL: Could not start hal
08-22 18:31:00.091  1015  1147 E WifiScanningService: could not start HAL
08-22 18:31:00.091  1015  1015 D RttService: SCAN_AVAILABLE : 3
08-22 18:31:00.091  1015  1148 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:00.101  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-22 18:31:00.101  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 18:31:00.101  1015  1125 E WifiNative-wlan0: invaild command id : 215
,08-22 18:31:00.101  1015  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-22 18:31:00.101  1015  1015 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-22 18:31:00.101  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:31:00.101  1015  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-22 18:31:00.101  1015  1046 D WifiDisplayController: disconnect
08-22 18:31:00.101  1015  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-22 18:31:00.101  1015  1046 D WifiDisplayController: updateConnection
08-22 18:31:00.101  1015  1125 E WifiNative-wlan0: invaild command id : 215
08-22 18:31:00.101  1015  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-22 18:31:00.101  7531  7531 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-22 18:31:00.101  1015  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-22 18:31:00.101  7531  7531 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-22 18:31:00.101  7531  7531 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
,08-22 18:31:00.101  1015  1125 E WifiStateMachine: Failed to set frequency band 0
,08-22 18:31:00.101  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:31:00.101  1170  1170 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-22 18:31:00.101  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:31:00.111  1015  1535 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-22 18:31:00.111  1170  1170 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-22 18:31:00.111  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress
,08-22 18:31:00.111  1015  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-22 18:31:00.111  1015  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-22 18:31:00.111  1015  1046 D WifiDisplayAdapter: onP2pDisconnected
08-22 18:31:00.111  1015  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-22 18:31:00.111  1015  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-22 18:31:00.111  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-22 18:31:00.111  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 18:31:00.111  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:31:00.111  1015  1124 D WifiP2pService: DeviceAddress: 0a:76:28
,08-22 18:31:00.111  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:31:00.111  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:31:00.121  1015  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  primary type: 10-0050F204-5
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  secondary type: null
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  wps: 0
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  grpcapab: 0
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  devcapab: 0
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  status: 3
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  wfdInfo: null
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  groupownerAddress: null
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  GOdeviceName: null
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  interfaceAddress: 
08-22 18:31:00.121  1015  1046 D WifiDisplayController:  SConnectInfo : null
08-22 18:31:00.121  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:31:00.121  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:31:00.121  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 18:31:00.121  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:31:00.121  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:31:00.121  6892  6892 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-22 18:31:00.121  6892  6892 D FileShare-Client: Outbound.stopDelayTimer - 
,08-22 18:31:00.131  6922  6922 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-22 18:31:00.141  1015  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-22 18:31:00.141  1015  1124 D WifiP2pService: InactiveState
,08-22 18:31:00.141  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
08-22 18:31:00.141  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 18:31:00.141  7531  7531 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-22 18:31:00.141  1015  1124 D WifiP2pService: InactiveState{ what=143376 }
,08-22 18:31:00.141  1015  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:00.681  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:00.681  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:00.681  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-22 18:31:00.681  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-22 18:31:00.691  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2604fb43 Bundle[{}]
,08-22 18:31:00.691  6695  6749 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-22 18:31:00.691  6695  6749 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-22 18:31:00.691  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-22 18:31:00.691  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-22 18:31:00.691  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-22 18:31:00.691  6695  6749 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-22 18:31:00.701  6695  6749 I System.out: Running OutgoingSocketThread
,08-22 18:31:00.701  6695  7555 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1320)
,08-22 18:31:00.701  6695  7555 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 37619
,08-22 18:31:00.701  6695  7555 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-22 18:31:01.031   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-22 18:31:01.241  7531  7531 I wpa_supplicant: nl80211: Received scan results (36 BSSes),
08-22 18:31:01.241  7531  7531 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-22 18:31:01.241  7531  7531 I wpa_supplicant: Trying to associate with SSID '4E47373030',
08-22 18:31:01.241  7531  7531 I wpa_supplicant: Trying to associate with  'G700'
08-22 18:31:01.241  7531  7531 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-22 18:31:01.241  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-22 18:31:01.241  1015  7553 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-22 18:31:01.261  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:31:01.261  1015  1125 D SecContentProvider2: mCursor = null,
,08-22 18:31:01.351  7531  7531 E wpa_supplicant: Cmd 35605 not handled
,08-22 18:31:01.351  7531  7531 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-22 18:31:01.351  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-22 18:31:01.351  7531  7531 I wpa_supplicant: Associated with F4.99.3E
08-22 18:31:01.351  7531  7531 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-22 18:31:01.351  7531  7531 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-22 18:31:01.351  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-22 18:31:01.351  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false
,08-22 18:31:01.351  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-22 18:31:01.351  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
,08-22 18:31:01.361  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, false,
08-22 18:31:01.361  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-22 18:31:01.361  1015  1043 D Tethering: interfaceStatusChanged wlan0, false
08-22 18:31:01.361  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 18:31:01.361  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
,08-22 18:31:01.361  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 18:31:01.361  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:31:01.361  7531  7531 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-22 18:31:01.361  1015  1125 D SecContentProvider2: mCursor = null
08-22 18:31:01.361  7531  7531 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
08-22 18:31:01.361  7531  7531 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-22 18:31:01.361  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-22 18:31:01.361  7531  7531 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-22 18:31:01.361  7531  7531 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-22 18:31:01.371  1015  1128 E Tethering: No numeric data
08-22 18:31:01.371  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:31:01.371  1015  1125 D SecContentProvider2: mCursor = null
08-22 18:31:01.371  1015  1128 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-22 18:31:01.371  1015  1128 D Tethering: clearTetheredNotification()
,08-22 18:31:01.371  7531  7531 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-22 18:31:01.371  7531  7531 I wpa_supplicant: Blacklist: Clear (temp) 
08-22 18:31:01.371  7531  7531 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-22 18:31:01.371  1015  1043 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-22 18:31:01.371  1015  1043 D Tethering: interfaceLinkStateChanged wlan0, true
08-22 18:31:01.371  1015  1043 D Tethering: interfaceStatusChanged wlan0, true
,08-22 18:31:01.371  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:01.371  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:31:01.371  1170  1170 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-22 18:31:01.371  1170  1170 D HotspotTile: updateTetherState():false, false
,08-22 18:31:01.381  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:31:01.381  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:31:01.381  1015  1122 V NetworkStats: performPollLocked() took 8ms
08-22 18:31:01.381  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:01.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:01.381  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:01.391  1015  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-22 18:31:01.391  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-22 18:31:01.401  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-22 18:31:01.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.401  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.401  1015  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,08-22 18:31:01.401  1015  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:31:01.401  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:31:01.401  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:31:01.401  1015  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:01.401  1015  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-22 18:31:01.401  1015  1127 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-22 18:31:01.401  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:31:01.401  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-22 18:31:01.401  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:31:01.401  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,08-22 18:31:01.411  1614  1614 I Hs20UtilService: Starting #21
08-22 18:31:01.411  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:31:01.411  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 18:31:01.411  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-22 18:31:01.411  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:31:01.411  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:31:01.421  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:31:01.421  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-22 18:31:01.421  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:31:01.421  1015  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-22 18:31:01.431   277   994 D CommandListener: Setting iface cfg,
,08-22 18:31:01.431  1015  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,08-22 18:31:01.431  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-22 18:31:01.431  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:31:01.441  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:01.441  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:31:01.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:01.441  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:01.451  1015  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-22 18:31:01.451  1015  1125 D SecContentProvider2: mCursor = null
,08-22 18:31:01.451  1015  1125 E WifiNative-wlan0: do suspend false
,08-22 18:31:01.451  1015  1124 D WifiP2pService: InactiveState{ what=143375 }
,08-22 18:31:01.461  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-22 18:31:01.671  7558  7558 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-22 18:31:01.671  7558  7558 I dhcpcd  : version 5.5.6 starting
,08-22 18:31:01.681  7558  7558 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-22 18:31:01.701  6695  6749 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1321)
08-22 18:31:01.701  6695  6749 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1321)
,08-22 18:31:01.701  6695  6749 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1326)
08-22 18:31:01.711  6695  6749 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-22 18:31:01.711  6695  6749 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1327)
,08-22 18:31:01.711  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-22 18:31:01.711  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dbc0695 added. We now have 2 listener(s)
,08-22 18:31:01.711  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 18:31:01.711  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-22 18:31:01.711  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-22 18:31:01.711  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.711  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4e63aa added. We now have 9 listener(s)
08-22 18:31:01.711  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:01.711  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:01.721  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:01.731  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:01.731  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:01.731  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:01.731  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:01.731  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@388b3b38 added. We now have 3 listener(s)
,08-22 18:31:01.731  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:01.731  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 18:31:01.731  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:01.731  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:01.731  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.731  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a37711 added. We now have 10 listener(s)
08-22 18:31:01.731  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:01.741  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:01.741  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:01.741  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:01.741  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:01.741  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.741  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:01.741  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1dbc0695 removed from the list
08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.741  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4e63aa removed from the list
08-22 18:31:01.741  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:01.741  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:01.741  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.741  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:01.741  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.741  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f4e63aa not in the list
08-22 18:31:01.741  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.741  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:01.741  7558  7558 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-22 18:31:01.741  7558  7558 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-22 18:31:01.751  7558  7558 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E),
08-22 18:31:01.751  7558  7558 I dhcpcd  : bssid match
08-22 18:31:01.751  7558  7558 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4a37711 removed from the list
08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:01.751  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.751  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@388b3b38 removed from the list
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30071076 added. We now have 2 listener(s)
,08-22 18:31:01.751  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 18:31:01.751  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:01.751  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.751  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4a2677 added. We now have 9 listener(s)
08-22 18:31:01.751  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:01.751  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:01.761  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:01.761  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:01.761  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:01.761  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:31:01.761  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:01.761  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b7734d added. We now have 3 listener(s)
,08-22 18:31:01.761  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:01.761  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:31:01.761  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:01.761  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:01.771  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.771  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecbbe02 added. We now have 10 listener(s)
08-22 18:31:01.771  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:01.771  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:01.771  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:01.771  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:01.771  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:01.771  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:31:01.771  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:01.771  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:01.771  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:31:01.771  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:01.781  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 18:31:01.781  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:31:01.781  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:31:01.781  7438  7453 D BtGatt.GattService: registerClient() - UUID=438cc282-7713-4524-86c1-a8a732375d37
,08-22 18:31:01.831  7438  7464 D BtGatt.GattService: onClientRegistered() - UUID=438cc282-7713-4524-86c1-a8a732375d37, clientIf=6
,08-22 18:31:01.831  6695  6705 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 18:31:01.831  7438  7446 D BtGatt.GattService: start scan with filters
,08-22 18:31:01.831  7438  7468 D BtGatt.ScanManager: handling starting scan
,08-22 18:31:01.831  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:31:01.831  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-22 18:31:01.831  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:31:01.841  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:31:01.841  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-22 18:31:01.841  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:01.841  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-22 18:31:01.841  7438  7468 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1979753
,08-22 18:31:01.851  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:31:01.851  7438  7464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-22 18:31:01.851  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.851  7438  7468 D BtGatt.ScanManager: allow scan with filters
08-22 18:31:01.851  7438  7468 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-22 18:31:01.851  7438  7468 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
08-22 18:31:01.851  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-22 18:31:01.851  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-22 18:31:01.851  7438  7468 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:01.851  7438  7468 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-22 18:31:01.861  7438  7464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-22 18:31:01.861  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.861  6695  6749 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-22 18:31:01.861  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:01.861  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-22 18:31:01.861  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.861  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:31:01.861  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-22 18:31:01.861  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:01.861  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:01.861  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:01.861  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:01.861  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:31:01.861  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 18:31:01.861  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.861  7438  7450 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:31:01.861  7438  7453 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 18:31:01.861  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-22 18:31:01.861  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-22 18:31:01.871  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:31:01.871  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-22 18:31:01.871  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:31:01.871  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:01.871  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-22 18:31:01.871  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:01.871  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-22 18:31:01.871  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:01.871  7438  7468 D BtGatt.ScanManager: filter size is 1
08-22 18:31:01.871  7438  7468 D BtGatt.ScanManager: delete FilterIndex - 3
,08-22 18:31:01.871  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:01.871  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-22 18:31:01.871  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:01.871  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 18:31:01.871  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.871  7438  7468 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:31:01.881  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 18:31:01.881  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:01.881  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:01.881  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:01.881  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.881  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@30071076 removed from the list
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4a2677 removed from the list
08-22 18:31:01.881  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:01.881  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:01.881  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.881  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:01.881  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.881  7438  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.881  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4a2677 not in the list
,08-22 18:31:01.881  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.881  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:01.881  7558  7558 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
08-22 18:31:01.881  7438  7464 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 18:31:01.881  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ecbbe02 removed from the list
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:01.881  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.881  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:01.881  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b7734d removed from the list
,08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:01.881  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53bb84e added. We now have 2 listener(s)
,08-22 18:31:01.891  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:31:01.891  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:31:01.891  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:31:01.891  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.891  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e96d6f added. We now have 9 listener(s)
,08-22 18:31:01.891  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:01.891  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:01.891  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:01.901  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:01.901  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:01.901  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:31:01.901  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:01.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:01.901  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33acbf05 added. We now have 3 listener(s)
,08-22 18:31:01.901  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:01.911  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:31:01.911  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 18:31:01.911  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:31:01.911  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:01.911  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259f0b5a added. We now have 10 listener(s)
,08-22 18:31:01.911  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:01.911  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:31:01.911  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:31:01.911  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:01.911  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:01.911  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:01.911  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-22 18:31:01.911  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:01.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:31:01.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:01.921  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-22 18:31:01.921  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-22 18:31:01.921  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-22 18:31:01.931  7438  7511 D BtGatt.GattService: registerClient() - UUID=1db1471f-57b2-4188-a1a3-e5e0d099df13
,08-22 18:31:01.971  7558  7558 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-22 18:31:01.971  7438  7464 D BtGatt.GattService: onClientRegistered() - UUID=1db1471f-57b2-4188-a1a3-e5e0d099df13, clientIf=6
,08-22 18:31:01.971  6695  7068 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-22 18:31:01.971  7438  7512 D BtGatt.GattService: start scan with filters
,08-22 18:31:01.971  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-22 18:31:01.971  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:31:01.971  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:31:01.971  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-22 18:31:01.971  7438  7468 D BtGatt.ScanManager: handling starting scan
,08-22 18:31:01.981  7438  7464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-22 18:31:01.981  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:01.981  7438  7468 D BtGatt.ScanManager: allow scan with filters
08-22 18:31:01.981  7438  7468 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
08-22 18:31:01.981  7438  7468 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-22 18:31:01.981  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 18:31:01.981  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:01.981  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:01.981  7438  7468 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:01.981  7438  7468 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-22 18:31:01.981  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-22 18:31:01.981  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-22 18:31:01.981  7438  7464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0,
08-22 18:31:01.981  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.981  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-22 18:31:01.991  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 18:31:01.991  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:01.991  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-22 18:31:01.991  6695  6749 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-22 18:31:01.991  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-22 18:31:01.991  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:01.991  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:01.991  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:01.991  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53bb84e removed from the list
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.991  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e96d6f removed from the list
08-22 18:31:01.991  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:01.991  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 18:31:01.991  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:01.991  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e96d6f not in the list
08-22 18:31:01.991  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:01.991  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-22 18:31:02.001  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-22 18:31:02.001  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:31:02.001  7438  7450 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:31:02.001  7438  7468 D BtGatt.ScanManager: filter size is 1,
,08-22 18:31:02.001  7438  7468 D BtGatt.ScanManager: delete FilterIndex - 4
08-22 18:31:02.001  7438  7511 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 18:31:02.001  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-22 18:31:02.001  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:02.001  7438  7468 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:31:02.001  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:02.001  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:31:02.001  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false,
08-22 18:31:02.001  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:31:02.001  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:31:02.011  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-22 18:31:02.011  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:02.011  7438  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 18:31:02.011  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:02.011  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-22 18:31:02.011  7438  7464 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 18:31:02.011  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:02.011  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:02.011  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:02.011  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259f0b5a removed from the list
08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.021  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.021  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33acbf05 removed from the list
08-22 18:31:02.021  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.021  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.021  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb28326 added. We now have 2 listener(s)
,08-22 18:31:02.021  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-22 18:31:02.021  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.021  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.021  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15b9b67 added. We now have 9 listener(s)
08-22 18:31:02.021  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.021  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
,08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:02.031  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:02.031  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-22 18:31:02.031  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 18:31:02.031  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.031  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2318c9bd added. We now have 3 listener(s)
08-22 18:31:02.031  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.031  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27",
08-22 18:31:02.031  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.031  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:31:02.031  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:02.031  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433abb2 added. We now have 10 listener(s)
08-22 18:31:02.031  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 18:31:02.031  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 18:31:02.031  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.031  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-22 18:31:02.031  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-22 18:31:02.031  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 18:31:02.031  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
,08-22 18:31:02.041  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-22 18:31:02.051  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-22 18:31:02.051  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-22 18:31:02.061  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-22 18:31:02.061  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-22 18:31:02.061  6695  6749 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null],
,08-22 18:31:02.061  7438  7511 D BtGatt.GattService: registerClient() - UUID=b07d48e8-24b3-4c23-af35-5bdd14b3de26
,08-22 18:31:02.111  7438  7464 D BtGatt.GattService: onClientRegistered() - UUID=b07d48e8-24b3-4c23-af35-5bdd14b3de26, clientIf=6
,08-22 18:31:02.111  6695  6703 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-22 18:31:02.111  7438  7453 D BtGatt.GattService: start scan with filters,
,08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: handling starting scan
08-22 18:31:02.111  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-22 18:31:02.111  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-22 18:31:02.111  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-22 18:31:02.111  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-22 18:31:02.111  7438  7464 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-22 18:31:02.111  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: allow scan with filters
08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
08-22 18:31:02.111  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:02.111  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,08-22 18:31:02.111  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-22 18:31:02.111  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-22 18:31:02.111  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: Starting BLE batch scan
08-22 18:31:02.111  7438  7468 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-22 18:31:02.111  7438  7464 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-22 18:31:02.111  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-22 18:31:02.121  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-22 18:31:02.121  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-22 18:31:02.121  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:02.131  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:31:02.131  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:02.131  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.131  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-22 18:31:02.131  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cb28326 removed from the list
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.131  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15b9b67 removed from the list
08-22 18:31:02.131  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.131  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-22 18:31:02.131  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.131  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15b9b67 not in the list
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-22 18:31:02.131  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-22 18:31:02.131  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-22 18:31:02.141  7438  7512 D BtGatt.GattService: stopScan() - queue size =1
,08-22 18:31:02.141  7438  7468 D BtGatt.ScanManager: filter size is 1
08-22 18:31:02.141  7438  7468 D BtGatt.ScanManager: delete FilterIndex - 5
,08-22 18:31:02.141  7438  7446 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-22 18:31:02.141  7438  7464 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-22 18:31:02.141  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:02.141  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-22 18:31:02.141  7438  7468 D BtGatt.ScanManager: stopping BLe Batch
,08-22 18:31:02.141  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-22 18:31:02.141  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-22 18:31:02.141  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-22 18:31:02.151  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-22 18:31:02.151  7438  7464 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-22 18:31:02.151  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:02.151  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:02.151  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-22 18:31:02.151  6695  6749 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-22 18:31:02.151  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-22 18:31:02.151  7438  7468 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-22 18:31:02.151  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.161  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.161  6695  6695 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-22 18:31:02.161  6695  6695 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@433abb2 removed from the list
08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.161  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.161  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2318c9bd removed from the list
08-22 18:31:02.161  7438  7464 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-22 18:31:02.161  7438  7464 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22cd0fe added. We now have 2 listener(s)
,08-22 18:31:02.161  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:31:02.161  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.161  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-22 18:31:02.161  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3736905f added. We now have 9 listener(s)
08-22 18:31:02.161  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:02.161  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-22 18:31:02.171  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-22 18:31:02.171  6695  6749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-22 18:31:02.181  6695  6749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-22 18:31:02.181  6695  6749 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-22 18:31:02.181  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.181  6695  6695 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-22 18:31:02.181  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-22 18:31:02.181  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26347375 added. We now have 3 listener(s)
,08-22 18:31:02.181  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-22 18:31:02.181  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-22 18:31:02.181  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-22 18:31:02.191  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-22 18:31:02.191  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@100ff0a added. We now have 10 listener(s)
08-22 18:31:02.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-22 18:31:02.191  6695  6749 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-22 18:31:02.191  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-22 18:31:02.191  6695  6749 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.191  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.191  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22cd0fe removed from the list
,08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-22 18:31:02.191  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3736905f removed from the list
08-22 18:31:02.191  6695  6749 D io.jxcore.node.ConnectivityMonitor: stop
,08-22 18:31:02.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.191  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-22 18:31:02.191  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:31:02.191  6695  6749 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3736905f not in the list
08-22 18:31:02.191  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-22 18:31:02.191  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-22 18:31:02.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-22 18:31:02.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-22 18:31:02.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-22 18:31:02.201  6695  6749 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@100ff0a removed from the list
08-22 18:31:02.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-22 18:31:02.201  6695  6749 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-22 18:31:02.201  6695  6749 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-22 18:31:02.201  6695  6749 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-22 18:31:02.201  6695  6749 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26347375 removed from the list
,08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-22 18:31:02.201  6695  6749 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-22 18:31:02.211  6695  7589 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1334, name: My test thread name)
,08-22 18:31:02.211  6695  7589 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1334, thread name: My test thread name)
08-22 18:31:02.211  6695  7589 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1334, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 18:31:02.211  6695  7590 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1336, name: My test thread name)
,08-22 18:31:02.211  6695  7590 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1336, thread name: My test thread name)
08-22 18:31:02.211  6695  7590 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1336, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-22 18:31:02.211  6695  6749 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-22 18:31:02.211  6695  6749 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-22 18:31:02.211  6695  6749 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-22 18:31:02.211  6695  6749 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-22 18:31:02.211  6695  6749 D com.test.thalitest.ThaliTestRunner: Total duration: 23317 ms
,08-22 18:31:02.211  6695  6749 I jxcore-log: Total number of executed tests:  80
08-22 18:31:02.211  6695  6749 I jxcore-log: 
08-22 18:31:02.211  6695  6749 I jxcore-log: Number of passed tests:  80
08-22 18:31:02.211  6695  6749 I jxcore-log: 
,08-22 18:31:02.211  6695  6749 I jxcore-log: Number of failed tests:  0,
08-22 18:31:02.211  6695  6749 I jxcore-log: 
08-22 18:31:02.221  6695  6749 I jxcore-log: Number of ignored tests:  0
08-22 18:31:02.221  6695  6749 I jxcore-log: 
08-22 18:31:02.221  6695  6749 I jxcore-log: Total duration:  23317
08-22 18:31:02.221  6695  6749 I jxcore-log: 
,08-22 18:31:02.221  6695  6749 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-22 18:31:02.221  6695  6749 I jxcore-log: 
,08-22 18:31:02.221  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.221  6695  6749 I jxcore-log: 
08-22 18:31:02.221  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.221  6695  6749 I jxcore-log: 
08-22 18:31:02.221  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.221  6695  6749 I jxcore-log: 
08-22 18:31:02.221  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.221  6695  6749 I jxcore-log: 
08-22 18:31:02.231  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.231  6695  6749 I jxcore-log: 
08-22 18:31:02.231  6695  6695 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-22 18:31:02.231  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.231  6695  6749 I jxcore-log: 
08-22 18:31:02.231  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-22 18:31:02.231  6695  6749 I jxcore-log: 
08-22 18:31:02.231  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:02.231  6695  6749 I jxcore-log: 
08-22 18:31:02.231  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.231  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
,08-22 18:31:02.241  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.241  6695  6749 I jxcore-log: 
08-22 18:31:02.251  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.251  6695  6749 I jxcore-log: 
,08-22 18:31:02.251  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.251  6695  6749 I jxcore-log: 
08-22 18:31:02.251  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-22 18:31:02.251  6695  6749 I jxcore-log: 
,08-22 18:31:02.261  1015  1125 E WifiNative-wlan0: do suspend true
,08-22 18:31:02.291  1015  1124 D WifiP2pService: InactiveState{ what=143375 },
08-22 18:31:02.291  1015  1124 D WifiP2pService: P2pEnabledState{ what=143375 },
,08-22 18:31:02.291  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-22 18:31:02.291  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:31:02.291  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.291  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:31:02.301  1015  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-22 18:31:02.301  1015  1125 E WifiStateMachine: VerifyingLinkState enter
08-22 18:31:02.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-22 18:31:02.301  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.311  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:31:02.311  1015  1127 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-22 18:31:02.311  1015  1127 D ConnectivityService: Adding iface wlan0 to network 504
,08-22 18:31:02.321  1015  1141 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
08-22 18:31:02.321  1015  1141 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-22 18:31:02.321  1015  1141 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-22 18:31:02.321  1015  1141 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824},
08-22 18:31:02.321  1015  1141 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-22 18:31:02.331  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:02.331  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:31:02.331  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.331  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.331  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.331  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-22 18:31:02.341  1015  4218 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:31:02.341  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:31:02.341  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:02.341  1015  4218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-22 18:31:02.341  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:31:02.351  1614  1614 I Hs20UtilService: Starting #22
08-22 18:31:02.351  1015  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-22 18:31:02.361  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:31:02.361  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 18:31:02.361  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 18:31:02.371  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-22 18:31:02.371  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 18:31:02.371  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:02.371  6695  6749 I jxcore-log: 
,08-22 18:31:02.381  1170  1170 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:02.381  1015  1127 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-22 18:31:02.381  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-22 18:31:02.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.381  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.381  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-22 18:31:02.381  1015  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-22 18:31:02.381  1015  1015 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-22 18:31:02.381  1015  1127 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-22 18:31:02.381  1015  1015 I WifiTrafficPoller: mBoosterFLAG : 0
08-22 18:31:02.381  1015  1015 I WifiTrafficPoller: current booster mode : FullMode
,08-22 18:31:02.391  1015  1127 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-22 18:31:02.391  1015  1127 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-22 18:31:02.391  1015  1127 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-22 18:31:02.391  1015  1127 D ConnectivityService: LTETest block dns file not exists
,08-22 18:31:02.391  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:02.391  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 18:31:02.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.391  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.401  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.401  1015  1127 V NetworkStats: updateIfacesLocked()
08-22 18:31:02.401  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:31:02.401  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:31:02.401  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:31:02.401  1015  1127 V NetworkStats: performPollLocked() took 6ms
08-22 18:31:02.401  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:02.411  1015  1478 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-22 18:31:02.411  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-22 18:31:02.411  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:02.411  1015  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:02.411  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:31:02.421  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.421  1015  1127 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.421  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.421  1015  1127 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-22 18:31:02.421  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:31:02.421  1015  1127 E ConnectivityService: updateNetworkInfo()
08-22 18:31:02.421  1614  1614 I Hs20UtilService: Starting #23
,08-22 18:31:02.421  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.421  1015  1127 V NetworkStats: updateIfacesLocked()
08-22 18:31:02.421  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:31:02.421  1015  1127 V NetworkStats: performPollLocked(flags=0x1)
08-22 18:31:02.421  1015  1127 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-22 18:31:02.421  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:31:02.421  1015  1127 V NetworkStats: performPollLocked() took 4ms
08-22 18:31:02.421  1015  1127 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:02.421  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 18:31:02.421  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-22 18:31:02.421  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-22 18:31:02.421  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-22 18:31:02.421  1015  1127 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.421  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.421  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:02.421  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-22 18:31:02.421  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-22 18:31:02.431  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-22 18:31:02.431  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.431  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-22 18:31:02.431  1015  7556 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-22 18:31:02.431  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-22 18:31:02.431   277   990 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-22 18:31:02.431  1300  1300 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-22 18:31:02.431   277   990 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-22 18:31:02.431  1300  2229 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-22 18:31:02.431  1015  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-22 18:31:02.431  1015  1127 D ConnectivityService:    accepting network in place of null
08-22 18:31:02.441  1015  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-22 18:31:02.441  1450  1450 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-22 18:31:02.441  1450  1450 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-22 18:31:02.441  1015  1127 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-22 18:31:02.441  1015  1127 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-22 18:31:02.441  1015  1509 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-22 18:31:02.441  1015  1509 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-22 18:31:02.441  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-22 18:31:02.441  1015  1509 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:02.441  1015  1509 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:02.441  1015  1509 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-22 18:31:02.441  1614  1614 I Hs20UtilService: Starting #24
08-22 18:31:02.441  1015  1127 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-22 18:31:02.441  1015  1015 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-22 18:31:02.441  1015  1128 D Tethering: MasterInitialState.processMessage what=3
08-22 18:31:02.441  1614  1635 I Hs20UtilService: Message received 5007
,08-22 18:31:02.441   287   287 E SMD     : DCD OFF
08-22 18:31:02.441  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.451  1170  1729 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 18:31:02.451  4801  6757 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 18:31:02.451  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.451  1015  1122 V NetworkStats: updateIfacesLocked()
08-22 18:31:02.451  1015  1122 V NetworkStats: performPollLocked(flags=0x1)
,08-22 18:31:02.451  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:31:02.451  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:31:02.451  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
08-22 18:31:02.451  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-22 18:31:02.451  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 18:31:02.451  1170  1170 D StatusBar.NetworkController: updateDataNetType()
08-22 18:31:02.451  1170  1170 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-22 18:31:02.451  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 18:31:02.461  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1015  1122 V NetworkStats: performPollLocked() took 8ms
,08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1015  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:02.461  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.461  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.461  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-22 18:31:02.471  1015  1028 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-22 18:31:02.471  1015  1446 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-22 18:31:02.471  1015  1446 D SecContentProvider2: mCursor = null
,08-22 18:31:02.471  1015  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
08-22 18:31:02.471  1015  1027 D SecContentProvider2: mCursor = null
08-22 18:31:02.471  1015  1219 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-22 18:31:02.471  1015  1219 D SecContentProvider2: mCursor = null
,08-22 18:31:02.471  1015  4193 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-22 18:31:02.471  1015  4193 D SecContentProvider2: mCursor = null
08-22 18:31:02.481  1015  1535 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-22 18:31:02.481  1015  1535 D SecContentProvider2: mCursor = null
,08-22 18:31:02.481  1015  4194 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-22 18:31:02.481  1015  4194 D SecContentProvider2: mCursor = null
,08-22 18:31:02.501   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-22 18:31:02.521  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 18:31:02.521  1015  1028 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1015
08-22 18:31:02.521  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:02.521  6695  6749 I jxcore-log: 
,08-22 18:31:02.521  1015  7556 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-22 18:31:02.531  1170  1170 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 18:31:02.571  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 22 Aug 2016 16:31:02 GMT], X-Android-Received-Millis=[1471883462588], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471883462562]}
,08-22 18:31:02.571  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-22 18:31:02.571  1015  7556 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-22 18:31:02.581  1015  1127 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.581  1015  1127 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-22 18:31:02.581  1015  1127 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-22 18:31:02.581  1015  1127 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-22 18:31:02.581  1170  1729 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-22 18:31:02.581  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-22 18:31:02.581  4801  6757 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-22 18:31:02.581  7591  7591 D AndroidRuntime: 
08-22 18:31:02.581  7591  7591 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-22 18:31:02.581  7591  7591 D AndroidRuntime: CheckJNI is OFF
,08-22 18:31:02.581  7591  7591 D AndroidRuntime: readGMSProperty: start
08-22 18:31:02.581  7591  7591 D AndroidRuntime: readGMSProperty: already setted!!
08-22 18:31:02.581  7591  7591 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-22 18:31:02.581  7591  7591 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-22 18:31:02.581  7591  7591 D AndroidRuntime: readGMSProperty: end
08-22 18:31:02.581  7591  7591 D AndroidRuntime: addProductProperty: start
,08-22 18:31:02.581  1170  1170 D StatusBar.NetworkController: EthernetConnected: false
,08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: updateDataNetType()
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-22 18:31:02.591  1170  1170 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-22 18:31:02.591  1170  1170 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-22 18:31:02.591  1170  1170 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-22 18:31:02.661  6695  6695 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-22 18:31:02.661  6695  6749 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-22 18:31:02.661  6695  6749 I jxcore-log: 
,08-22 18:31:02.701  7591  7591 E AffinityControl: AffinityControl: registerfunction enter
,08-22 18:31:02.711  1015  4218 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-22 18:31:02.711  1015  4218 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4325, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
08-22 18:31:02.711  1015  4218 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0,
08-22 18:31:02.711  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-22 18:31:02.721  1015  4218 D BatteryService: stay LED for fully charged
,08-22 18:31:02.721  1015  1015 I MotionRecognitionService: Plugged
,08-22 18:31:02.721  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
,08-22 18:31:02.721  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
08-22 18:31:02.721  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
08-22 18:31:02.721  1170  1170 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-22 18:31:02.721  1170  1170 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-22 18:31:02.731  1170  1170 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-22 18:31:02.731  1170  1170 D SViewCoverView: level :100 plugged : 2
,08-22 18:31:02.731  7591  7591 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-22 18:31:02.741  7438  7438 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-22 18:31:02.741  7438  7469 D HeadsetStateMachine: Disconnected process message: 10
,08-22 18:31:02.751  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 18:31:02.751  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-22 18:31:02.751  1170  1170 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-22 18:31:02.761  1015  1216 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-22 18:31:02.761  1015  1216 D PackageManager: START PACKAGE DELETE: observer{269008792}
08-22 18:31:02.761  1015  1216 D PackageManager: pkg{<packageName>}
08-22 18:31:02.761  1015  1216 D PackageManager: user{0}
08-22 18:31:02.761  1015  1216 D PackageManager: caller{2000}
08-22 18:31:02.761  1015  1216 D PackageManager: flags{2}
08-22 18:31:02.761  1015  1216 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
,08-22 18:31:02.761  1015  1216 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-22 18:31:02.761  1015  1216 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
08-22 18:31:02.761  1015  1216 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-22 18:31:02.771  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
08-22 18:31:02.771  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-22 18:31:02.771  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-22 18:31:02.771  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
08-22 18:31:02.771  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-22 18:31:02.781  1015  1055 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-22 18:31:02.801  1015  1041 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,08-22 18:31:02.801  1015  1041 I ActivityManager: Killing 6695:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-22 18:31:02.871  1015  1055 W PackageSettings: Skipping PackageSetting{9e51312 com.example.hello/10168} due to missing metadata
,08-22 18:31:02.901  1015  1041 I ActivityManager:   Force finishing activity ActivityRecord{1a232dc6 u0 com.test.thalitest/.MainActivity t2}
,08-22 18:31:02.901  1015  1041 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 18:31:02.911  1015  1041 D InputDispatcher: Focus left window: 6695
,08-22 18:31:02.911   257   445 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-22 18:31:02.911   257  1037 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-22 18:31:02.931  1015  1041 D InputDispatcher: Focused application released
,08-22 18:31:02.931  1015  1041 D FocusedStackFrame: Set to : 0
08-22 18:31:02.931  1015  1046 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-22 18:31:02.931  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-22 18:31:02.931  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-22 18:31:02.931  1015  1041 W ActivityManager: mDVFSHelper.acquire(),
,08-22 18:31:02.941  1015  1041 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-22 18:31:02.941  1015  1127 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-22 18:31:02.951  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-22 18:31:02.961  1479  1479 D Launcher: onRestart, Launcher: 345445769
,08-22 18:31:02.971  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-22 18:31:02.971  1479  1479 D Launcher: onStart, Launcher: 345445769
,08-22 18:31:02.971  1479  1479 D Launcher.HomeView: onStart
,08-22 18:31:02.981  1479  1479 D Launcher: onResume, Launcher: 345445769
,08-22 18:31:02.981  1015  4193 D SettingsProvider: name = kids_home_mode
,08-22 18:31:02.981  1015  4193 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-22 18:31:02.981  1015  4193 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-22 18:31:02.981  1015  4193 D SettingsProvider: selectionArgs: false
08-22 18:31:02.981  1015  4193 D SettingsProvider: selectionArgs: 10006
,08-22 18:31:02.981  1015  4193 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-22 18:31:02.981  1015  4193 D SettingsProvider: ret = -1
,08-22 18:31:02.981  1479  1479 D Launcher.HomeView: onResume
,08-22 18:31:02.991  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-22 18:31:03.001  2622  2622 I art     : Explicit concurrent mark sweep GC freed 18756(1082KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 890us total 34.900ms
,08-22 18:31:03.011  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,08-22 18:31:03.011  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-22 18:31:03.011  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.011  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-22 18:31:03.011  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-22 18:31:03.021  1015  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-22 18:31:03.031  1863  1863 E SamsungIME: mOCRHelper is null
,08-22 18:31:03.041  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
,08-22 18:31:03.041  4801  4801 I art     : Explicit concurrent mark sweep GC freed 23597(1429KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 12MB/21MB, paused 1.286ms total 79.362ms
,08-22 18:31:03.041  2029  2211 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-22 18:31:03.041  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-22 18:31:03.041  1450  1450 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.,
,08-22 18:31:03.071  1479  1479 D MenuAppsGridFragment: onResume
,08-22 18:31:03.081  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 18:31:03.081  1015  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-22 18:31:03.081  1015  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-22 18:31:03.081  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-22 18:31:03.091  1015  1040 W TextServicesManagerService: no available spell checker services found
,08-22 18:31:03.091  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 22 18:31:03 GMT+02:00 2016
,08-22 18:31:03.091  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-22 18:31:03.091  1015  1532 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-22 18:31:03.101  1015  1532 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.111  1015  1532 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:03.111  1015  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:03.111  1015  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-22 18:31:03.131  1015  1122 V NetworkStats: removeUidsLocked() for UIDs [10171]
08-22 18:31:03.131  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:03.131  1015  1122 V NetworkStats: performPollLocked(flags=0x3)
,08-22 18:31:03.131  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
08-22 18:31:03.131  1015  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-22 18:31:03.131  2852  2852 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-22 18:31:03.131  1015  1122 V NetworkStats: performPollLocked() took 5ms
08-22 18:31:03.131  1015  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:03.131  1015  1509 D ActivityManager: handle home activity for 0
08-22 18:31:03.131  1015  1509 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-22 18:31:03.131  1015  1509 D KnoxTimeoutHandler: post home show event for user 0
08-22 18:31:03.131  1015  1509 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-22 18:31:03.131  1015  1509 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-22 18:31:03.131  1015  1509 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-22 18:31:03.131  1479  1479 D Launcher.HomeView: onPause
,08-22 18:31:03.131  1438  1438 D RegisteredServicesCache: empty dynamic service
,08-22 18:31:03.141  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-22 18:31:03.141  1015  1446 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
08-22 18:31:03.141  1015  1446 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-22 18:31:03.141  1015  1446 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-22 18:31:03.141  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-22 18:31:03.141  1015  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-22 18:31:03.141  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.141  1015  1446 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.151  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-22 18:31:03.151  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-22 18:31:03.151  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.151  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.161  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 18:31:03.161  7611  7611 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.161  7611  7611 E Zygote  : v2
08-22 18:31:03.161  7611  7611 I libpersona: KNOX_SDCARD checking this for 10090
08-22 18:31:03.161  7611  7611 I libpersona: KNOX_SDCARD not a persona
08-22 18:31:03.161  7611  7611 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:31:03.161  7611  7611 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.171  1015  1446 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7611 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-22 18:31:03.171  2852  2852 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true,
,08-22 18:31:03.171  7611  7611 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 18:31:03.171  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 18:31:03.181  1015  1015 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,08-22 18:31:03.181  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.181  2852  2852 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-22 18:31:03.181  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-22 18:31:03.191  1015  1028 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-22 18:31:03.191  1015  1028 D SecContentProvider2: mCursor = null
,08-22 18:31:03.191  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.191  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.191  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.191  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.191  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
08-22 18:31:03.191  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
08-22 18:31:03.191  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-22 18:31:03.201  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-22 18:31:03.201  7626  7626 E Zygote  : MountEmulatedStorage(),
08-22 18:31:03.201  7626  7626 E Zygote  : v2
08-22 18:31:03.201  7626  7626 I libpersona: KNOX_SDCARD checking this for 1000,
08-22 18:31:03.201  7626  7626 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.211  1015  1041 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7626 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 18:31:03.211  7626  7626 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 18:31:03.211  7611  7611 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-22 18:31:03.211  1015  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast,
08-22 18:31:03.211  7611  7611 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.211  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-22 18:31:03.211  7626  7626 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:31:03.211  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.211  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.211  1015  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.221  7626  7626 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 18:31:03.221  1015  1535 I TactileAssist: enable value -1
08-22 18:31:03.221  1015  1535 I TactileAssist: internal enable value -1
08-22 18:31:03.221  1015  1535 I TactileAssist: intensity value -1
08-22 18:31:03.221  1015  1535 I TactileAssist: saveAppList value true
,08-22 18:31:03.231  7635  7635 E Zygote  : MountEmulatedStorage(),
08-22 18:31:03.231  1015  1041 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7635 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 18:31:03.231  7635  7635 E Zygote  : v2
08-22 18:31:03.231  7635  7635 I libpersona: KNOX_SDCARD checking this for 1000
08-22 18:31:03.231  7635  7635 I libpersona: KNOX_SDCARD not a persona
08-22 18:31:03.241  7635  7635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.241  7635  7635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.241  7635  7635 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-22 18:31:03.251  1015  1535 I TactileAssist: List of disabled apps :
,08-22 18:31:03.261  7626  7626 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.261  7626  7626 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.261  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-22 18:31:03.261  1015  1158 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicy: uID is 10171
08-22 18:31:03.261  1015  1015 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
08-22 18:31:03.261  1015  3347 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-22 18:31:03.261  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-22 18:31:03.271  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-22 18:31:03.271  1015  1015 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-22 18:31:03.271  1015  1015 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-22 18:31:03.271  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
08-22 18:31:03.271  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-22 18:31:03.271  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-22 18:31:03.281   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-22 18:31:03.281  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-22 18:31:03.291  7635  7635 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.291  7635  7635 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.291  1015  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-22 18:31:03.301  1015  1478 D InputDispatcher: Focus entered window: 1479
,08-22 18:31:03.311  2852  7610 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-22 18:31:03.311  1015  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-22 18:31:03.311  1015  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-22 18:31:03.311  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-22 18:31:03.311  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,08-22 18:31:03.321  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-22 18:31:03.321  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.321  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.321  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.321  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.321  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1f476995 token=android.os.BinderProxy@2912ae85 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-22 18:31:03.321  1479  1479 D Launcher.HomeView: onStop
,08-22 18:31:03.331  1015  4194 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-22 18:31:03.331  1015  4194 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6695 uid 10171
,08-22 18:31:03.331  1170  1170 I StatusBar: Icon Only
,08-22 18:31:03.331  1170  1170 D PanelView: There is/are notification(s) 
08-22 18:31:03.331  1015  7657 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-22 18:31:03.341  7658  7658 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.341  7658  7658 E Zygote  : v2
08-22 18:31:03.341  7658  7658 I libpersona: KNOX_SDCARD checking this for 10048
08-22 18:31:03.341  7658  7658 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.341  7658  7658 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.341  2852  7610 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-22 18:31:03.341  7658  7658 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.341  7658  7658 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.341  7611  7611 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-22 18:31:03.341  7611  7611 D elm:15121: ELMEngine.ELMEngine( context ).
,08-22 18:31:03.351  7611  7611 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-22 18:31:03.351  1015  1216 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7658 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-22 18:31:03.351  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-22 18:31:03.361  1015  1219 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-22 18:31:03.361  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.361  1863  1863 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-22 18:31:03.371  2852  2852 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-22 18:31:03.381  7635  7635 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.401  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:03.401  1015  1219 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:03.401  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-22 18:31:03.401  7658  7658 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.401  7658  7658 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.411  7611  7611 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-22 18:31:03.411  7611  7611 D elm:15121: ElmAgentService : onCreate()
,08-22 18:31:03.411  1015  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-22 18:31:03.411  7611  7675 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-22 18:31:03.421  7611  7675 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-22 18:31:03.421  7611  7675 D elm:15121: MDMBridge.getInstance()
08-22 18:31:03.421  7611  7675 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 18:31:03.421  7611  7675 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-22 18:31:03.431  1015  1027 D SecContentProvider2: uri = -1 selection = getSealedState
08-22 18:31:03.431  1015  1027 D SecContentProvider2: mCursor = null
,08-22 18:31:03.431  7635  7635 I PopupuiReceiver_KNOX: getSealedState : true
08-22 18:31:03.431  1015  1475 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-22 18:31:03.431  1015  1475 D SecContentProvider2: mCursor = null
,08-22 18:31:03.431  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.431  1015  1041 W ActivityManager: mDVFSHelper.release()
,08-22 18:31:03.431  7626  7626 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-22 18:31:03.431  7635  7635 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,08-22 18:31:03.431  1015  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{31946f70 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:147099
08-22 18:31:03.431  1015  4194 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
08-22 18:31:03.431  1015  4194 D SecContentProvider2: mCursor = null
,08-22 18:31:03.441  7635  7635 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
08-22 18:31:03.441  7635  7635 D PopupuiReceiver: Action package removed
,08-22 18:31:03.441  1015  4218 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-22 18:31:03.441  1015  4218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.441  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 18:31:03.441  1015  4218 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:31:03.441  1015  4218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:03.441  1015  4218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-22 18:31:03.451  1015  1127 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-22 18:31:03.451  1015  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-22 18:31:03.451  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.451  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.451  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.451  1015  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.471  7678  7678 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.471  7678  7678 E Zygote  : v2
08-22 18:31:03.471  7678  7678 I libpersona: KNOX_SDCARD checking this for 1000
08-22 18:31:03.471  7678  7678 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.471  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.471  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-22 18:31:03.471  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.471  1015  1015 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7678 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-22 18:31:03.481  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.481  7658  7658 D Compatibility: onReceive() it will make start service
,08-22 18:31:03.491  7611  7611 D elm:15121: ElmAgentService : onDestroy().
,08-22 18:31:03.491  1015  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-22 18:31:03.491  1015  1055 I art     : Explicit concurrent mark sweep GC freed 84917(5MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 16.918ms total 386.187ms
,08-22 18:31:03.491  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.491  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.491  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.491  1015  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.501  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.501  7678  7678 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.511  7693  7693 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.511  7693  7693 I libpersona: KNOX_SDCARD checking this for 10145
08-22 18:31:03.511  7693  7693 E Zygote  : v2
08-22 18:31:03.511  7693  7693 I libpersona: KNOX_SDCARD not a persona
08-22 18:31:03.511  1015  1216 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7693 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:31:03.511  7693  7693 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.511  1015  1055 D PackageManager: delete codoeFile: 
,08-22 18:31:03.511  1015  1486 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-22 18:31:03.511  1015  1486 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-22 18:31:03.521  7693  7693 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.521  7693  7693 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.531  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-22 18:31:03.531  1015  1055 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-22 18:31:03.531  1015  1055 D PackageManager: result of delete: 1{269008792}
08-22 18:31:03.531  1015  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-22 18:31:03.531  1015  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:31:03.531  1015  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 18:31:03.531  1015  1486 W ActivityManager: userId = 0, bbcId = -10000
08-22 18:31:03.531  1015  1486 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:03.531  1015  1486 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-22 18:31:03.531  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.531  7693  7693 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.531  7693  7693 D ActivityThread: Added TimaKeyStore provider
08-22 18:31:03.531  1015  1486 I ActivityManager: Killing 7003:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-22 18:31:03.551  1015  4194 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-22 18:31:03.551  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.551  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.551  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.551  1015  4194 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.551  7658  7708 D Compatibility: onHandleIntent()
,08-22 18:31:03.561  7658  7708 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-22 18:31:03.561  7658  7708 D Compatibility: found: 2
08-22 18:31:03.571  7710  7710 E Zygote  : MountEmulatedStorage()
,08-22 18:31:03.571  7710  7710 E Zygote  : v2
08-22 18:31:03.571  7710  7710 I libpersona: KNOX_SDCARD checking this for 1000
,08-22 18:31:03.571  7710  7710 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.571  7710  7710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-22 18:31:03.571  1015  4194 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7710 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-22 18:31:03.571  1015  1446 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-22 18:31:03.571  1015  1446 D SecContentProvider2: mCursor = null
,08-22 18:31:03.571  7710  7710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.581  1015  4193 I ActivityManager: Killing 7073:com.sec.android.diagmonagent/1000 (adj 15): empty #21
08-22 18:31:03.581  7710  7710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-22 18:31:03.581  1015  1532 I ActivityManager: Killing 7056:com.sec.spp.push/u0a32 (adj 15): empty #21
,08-22 18:31:03.581  1015  1028 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-22 18:31:03.591  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.591  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.601  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-22 18:31:03.601  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-22 18:31:03.601  7591  7591 D AndroidRuntime: Shutting down VM
08-22 18:31:03.601  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 18:31:03.601  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.601  7710  7710 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:31:03.601  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.601  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.601  1015  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.611  7710  7710 D ActivityThread: Added TimaKeyStore provider,
08-22 18:31:03.611  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 18:31:03.611  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 18:31:03.611  7658  7708 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-22 18:31:03.611  7658  7708 D Compatibility: skipping ResolveInfo{7b44278 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-22 18:31:03.611  7658  7708 D Compatibility: considering ResolveInfo{14d10d51 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-22 18:31:03.611  7658  7708 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-22 18:31:03.611  7658  7708 D Compatibility: enabling receiver ResolveInfo{2cb789b6 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 18:31:03.611  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-22 18:31:03.611  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-22 18:31:03.621  1015  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-22 18:31:03.621  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-22 18:31:03.621  1015  1055 D PackageManager: userId{-1}
08-22 18:31:03.621  1015  1055 D PackageManager: andCode{true}
,08-22 18:31:03.621  7678  7678 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-22 18:31:03.621  7678  7678 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-22 18:31:03.621  7678  7678 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-22 18:31:03.621  7725  7725 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.621  7658  7708 D Compatibility: enabling receiver ResolveInfo{2edf46b7 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-22 18:31:03.621  7725  7725 E Zygote  : v2
08-22 18:31:03.621  7725  7725 I libpersona: KNOX_SDCARD checking this for 10052
,08-22 18:31:03.621  7725  7725 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.621  7725  7725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-22 18:31:03.621  1015  1028 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7725 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-22 18:31:03.631  7725  7725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-22 18:31:03.631  7725  7725 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.631  7658  7708 D Compatibility: enabling receiver ResolveInfo{25270e24 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
08-22 18:31:03.631  1015  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-22 18:31:03.631  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.641  1015  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-22 18:31:03.641  1015  1040 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-22 18:31:03.641  7658  7708 D Compatibility: enabling receiver ResolveInfo{bc82d8d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-22 18:31:03.641  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.641  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.641  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.641  1015  1055 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.641  7658  7708 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-22 18:31:03.651  7678  7678 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-22 18:31:03.651  7678  7678 I PCWCLIENTTRACE_PushUtil: sales region : global
08-22 18:31:03.651  7678  7678 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-22 18:31:03.651  7678  7678 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-22 18:31:03.661  7710  7710 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-22 18:31:03.661  7740  7740 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.661  7740  7740 E Zygote  : v2
08-22 18:31:03.661  7740  7740 I libpersona: KNOX_SDCARD checking this for 10003
08-22 18:31:03.661  7740  7740 I libpersona: KNOX_SDCARD not a persona
08-22 18:31:03.661  7740  7740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.671  1015  1055 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7740 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-22 18:31:03.671  7740  7740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.671  7740  7740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.671  7693  7693 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-22 18:31:03.671  7693  7693 D ThemeInfoUtil: isCurrentFestival = false
,08-22 18:31:03.681  7725  7725 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:31:03.681  1015  1532 D PersonaManager: isKioskContainerExistOnDevice
08-22 18:31:03.681  7725  7725 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.691  7710  7710 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-22 18:31:03.691  1015  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-22 18:31:03.691  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.691  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.691  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.691  1015  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.701  1015  1446 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-22 18:31:03.701  1015  1446 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-22 18:31:03.711  7755  7755 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.711  7755  7755 E Zygote  : v2
08-22 18:31:03.711  7755  7755 I libpersona: KNOX_SDCARD checking this for 10029
08-22 18:31:03.711  7755  7755 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.711  7755  7755 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.711  7740  7740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-22 18:31:03.711  7755  7755 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.711  7740  7740 D ActivityThread: Added TimaKeyStore provider
08-22 18:31:03.711  1015  1027 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7755 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-22 18:31:03.711  1015  1027 I ActivityManager: Killing 7095:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-22 18:31:03.711  7755  7755 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.731  1015  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-22 18:31:03.731  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.731  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.731  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.731  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.741  7755  7755 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.741  7755  7755 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.741  7769  7769 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.741  7769  7769 E Zygote  : v2
08-22 18:31:03.741  7769  7769 I libpersona: KNOX_SDCARD checking this for 10148
08-22 18:31:03.741  7769  7769 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.741  7769  7769 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.751  7769  7769 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.751  7769  7769 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.751  1015  1478 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7769 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
,08-22 18:31:03.761  1015  1478 I ActivityManager: Killing 7116:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-22 18:31:03.771  1015  1478 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,08-22 18:31:03.771  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.771  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.771  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.771  1015  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.771   305   305 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 657us total 21.237ms
08-22 18:31:03.771  7769  7769 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.771  7769  7769 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.791   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.028ms total 19.051ms
,08-22 18:31:03.811   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.085ms total 17.196ms
,08-22 18:31:03.811  7591  7591 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-22 18:31:03.821  7786  7786 E Zygote  : MountEmulatedStorage(),
08-22 18:31:03.821  7786  7786 E Zygote  : v2
,08-22 18:31:03.821  7786  7786 I libpersona: KNOX_SDCARD checking this for 10087
08-22 18:31:03.821  7786  7786 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.821  7786  7786 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:03.831  7786  7786 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.831  7786  7786 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.831  1015  1478 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7786 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
08-22 18:31:03.831  1015  1478 I ActivityManager: Killing 7135:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-22 18:31:03.841  1015  1478 I ActivityManager: Killing 7023:com.android.chrome/u0a77 (adj 15): empty #21
,08-22 18:31:03.851  1015  1216 I ActivityManager: Killing 6938:com.google.android.talk/u0a102 (adj 15): empty #21
,08-22 18:31:03.871  7786  7786 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:03.871  7786  7786 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:03.881  1015  1478 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 18:31:03.881  1015  1478 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.881  1015  1478 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:31:03.881  1015  1478 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:31:03.881  1015  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 18:31:03.891  1015  1219 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-22 18:31:03.891  1015  1219 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.891  1015  1219 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:31:03.891  1015  1219 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-22 18:31:03.891  1015  1219 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-22 18:31:03.901  1015  4194 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-22 18:31:03.901  7769  7769 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
08-22 18:31:03.911  7325  7325 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,08-22 18:31:03.911  1015  1475 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
,08-22 18:31:03.921  1015  1475 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-22 18:31:03.921  1015  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-22 18:31:03.921  1015  1475 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-22 18:31:03.921  1015  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-22 18:31:03.921  1015  1532 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-22 18:31:03.931  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.931  7755  7803 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
08-22 18:31:03.931  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.931  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.931  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.941  1015  1478 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 18:31:03.951  7807  7807 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.951  7807  7807 E Zygote  : v2
08-22 18:31:03.951  7325  7325 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-22 18:31:03.951  7807  7807 I libpersona: KNOX_SDCARD checking this for 10152
08-22 18:31:03.951  7807  7807 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.951  7807  7807 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-22 18:31:03.951  7807  7807 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:03.951  7807  7807 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-22 18:31:03.951  1015  1532 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7807 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-22 18:31:03.961  7325  7325 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/predictor.db" with flag (131138) and mode_t (0) due to error (30)
,08-22 18:31:03.961  1015  1475 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-22 18:31:03.961  7325  7325 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/predictor.db'.
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:31:03.961  7325  7325 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-22 18:31:03.961  7325  7325 D AndroidRuntime: Shutting down VM
,08-22 18:31:03.961  7325  7325 E AndroidRuntime: FATAL EXCEPTION: main
08-22 18:31:03.961  7325  7325 E AndroidRuntime: Process: com.samsung.android.intelligenceservice, PID: 7325
08-22 18:31:03.961  7325  7325 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlaceCategoryManager.removePlaceCategories(PlaceCategoryManager.java:65)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removePlaceCategories(PlacePredictor.java:150)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.predictor.PlacePredictor.removeAllPlaceCategories(PlacePredictor.java:145)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.samsung.android.intelligenceservice.useranalysis.UserAnalysisBroadcastReceiver$2.run(UserAnalysisBroadcastReceiver.java:79)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-22 18:31:03.961  7325  7325 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-22 18:31:03.971  1015  1478 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.intelligenceservice
,08-22 18:31:03.971  1015  1532 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-22 18:31:03.971  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.971  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.971  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-22 18:31:03.971  1015  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-22 18:31:03.981  7755  7803 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-22 18:31:03.981  7755  7803 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:31:03.981  7755  7803 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 18:31:03.981  7755  7803 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-22 18:31:03.981  7755  7803 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-22 18:31:03.991  7823  7823 E Zygote  : MountEmulatedStorage()
08-22 18:31:03.991  7823  7823 E Zygote  : v2
08-22 18:31:03.991  7823  7823 I libpersona: KNOX_SDCARD checking this for 10032
08-22 18:31:03.991  7823  7823 I libpersona: KNOX_SDCARD not a persona
,08-22 18:31:03.991  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-22 18:31:04.001  1015  1532 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7823 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-22 18:31:04.001  1015  1532 I ActivityManager: Killing 7168:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-22 18:31:04.001  7755  7803 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-22 18:31:04.001  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-22 18:31:04.001  1015  7821 E DropBoxManagerService: Can't write: system_app_crash
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop197.tmp: open failed: EROFS (Read-only file system)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15780)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-22 18:31:04.001  1015  7821 E DropBoxManagerService: 	... 5 more
08-22 18:31:04.001  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-22 18:31:04.011  7807  7807 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-22 18:31:04.011  7807  7807 D ActivityThread: Added TimaKeyStore provider
,08-22 18:31:04.011  1479  1479 I Choreographer: Skipped 39 frames!  The application may be doing too much work on its main thread.
08-22 18:31:04.011  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2912ae85 time:147676
,08-22 18:31:04.031  1015  4194 I ActivityManager: Killing 7147:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
,08-22 18:31:04.031  7325  7325 I Process : Sending signal. PID: 7325 SIG: 9
,08-22 18:31:04.031  7532  7532 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)

```
