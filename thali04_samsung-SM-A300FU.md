#### Test 8289468293e136b_thali04_samsung-SM-A300FU Logs


```
--------- beginning of main
08-29 13:12:00.786   287   287 E SMD     : DCD OFF
,08-29 13:12:01.296  6905  6905 D AndroidRuntime: 
08-29 13:12:01.296  6905  6905 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-29 13:12:01.296  6905  6905 D AndroidRuntime: CheckJNI is OFF
08-29 13:12:01.296  6905  6905 D AndroidRuntime: readGMSProperty: start
08-29 13:12:01.296  6905  6905 D AndroidRuntime: readGMSProperty: already setted!!
08-29 13:12:01.306  6905  6905 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 13:12:01.306  6905  6905 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 13:12:01.306  6905  6905 D AndroidRuntime: readGMSProperty: end
08-29 13:12:01.306  6905  6905 D AndroidRuntime: addProductProperty: start
08-29 13:12:01.436  6905  6905 E AffinityControl: AffinityControl: registerfunction enter
08-29 13:12:01.466  6905  6905 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-29 13:12:01.486  1014  1026 E PersonaManagerService: inState():  stateMachine is null !!
08-29 13:12:01.486  1014  1026 I PersonaManagerService: PersonaId don't exist
08-29 13:12:01.486  1014  1026 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-29 13:12:01.486  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-29 13:12:01.506  1014  1026 W ActivityManager: mDVFSHelper.acquire()
08-29 13:12:01.506   257   257 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
08-29 13:12:01.506   257   257 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
08-29 13:12:01.516  1014  1026 D FocusedStackFrame: Set to : 0
08-29 13:12:01.516  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:01.516  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:01.516  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:01.516  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:01.526  1014  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-29 13:12:01.526  1014  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-29 13:12:01.536  6916  6916 E Zygote  : MountEmulatedStorage()
08-29 13:12:01.536  6916  6916 E Zygote  : v2
08-29 13:12:01.536  6916  6916 I libpersona: KNOX_SDCARD checking this for 10171
08-29 13:12:01.536  6916  6916 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:01.536  6916  6916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:01.546  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 13:12:01.546  1014  1026 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6916 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:12:01.546  1014  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-29 13:12:01.546  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-29 13:12:01.546  1014  1026 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 13:12:01.546   257   257 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
08-29 13:12:01.546  6916  6916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:01.546  6916  6916 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 13:12:01.546  1014  1026 D InputDispatcher: Focused application set to: xxxx
08-29 13:12:01.546  1014  1026 D InputDispatcher: Focus left window: 1494
08-29 13:12:01.546  6905  6905 D AndroidRuntime: Shutting down VM
08-29 13:12:01.556  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:12:01.556  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
08-29 13:12:01.566  6916  6916 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:01.566  6916  6916 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:01.566  1014  1533 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-29 13:12:01.576  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-29 13:12:01.586  1014  1014 V ActivityManager: Display changed displayId=0
08-29 13:12:01.596  1014  1533 D PersonaManager: isKioskContainerExistOnDevice
08-29 13:12:01.606  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-29 13:12:01.636   257  6077 I SurfaceFlinger: id=7 Removed Mauncher (5/9)
08-29 13:12:01.636   257  6078 I SurfaceFlinger: id=7 Removed Mauncher (-2/9)
08-29 13:12:01.646  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{3e6de942 token=android.os.BinderProxy@1e3f560f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-29 13:12:01.646  1494  1494 D Launcher: onTrimMemory. Level: 20
08-29 13:12:01.706  6916  6916 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-29 13:12:01.726  6916  6916 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8130-8132)
08-29 13:12:01.726  6916  6916 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 13:12:01.746  6916  6916 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {780a171}
08-29 13:12:01.746  6916  6916 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-29 13:12:01.756  6905  6905 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 13:12:01.766  6916  6916 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:12:01.796  6916  6916 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 13:12:01.806  6916  6916 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:01.816  6916  6916 E SysUtils: ApplicationContext is null in ApplicationStatus,
,08-29 13:12:01.846  6916  6916 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 13:12:01.846  6916  6916 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 13:12:01.846  6916  6916 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 13:12:01.846  6916  6916 I Adreno-EGL: Local Branch: 
08-29 13:12:01.846  6916  6916 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 13:12:01.846  6916  6916 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 13:12:01.846  6916  6916 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 13:12:01.916  6916  6916 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:12:01.916  1014  1332 E Watchdog: !@Sync 3
,08-29 13:12:01.926  6916  6916 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 13:12:01.926  6916  6916 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-29 13:12:01.936  6916  6916 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 13:12:01.936  6916  6916 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-29 13:12:02.036  6916  6916 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:02.046  6916  6916 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 13:12:02.056  6916  6916 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-29 13:12:02.056  6916  6916 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-29 13:12:02.066  6916  6916 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-29 13:12:02.066  6916  6916 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:02.076  6916  6916 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:02.106  1014  1040 W ActivityManager: Activity pause timeout for ActivityRecord{36d31623 u0 com.test.thalitest/.MainActivity t2}
,08-29 13:12:02.116  6916  6956 D OpenGLRenderer: Render dirty regions requested: true
,08-29 13:12:02.126  1014  1533 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 13:12:02.126  1014  1533 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-29 13:12:02.126  1014  1533 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 13:12:02.126  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 13:12:02.126  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 13:12:02.126  6916  6943 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup,
,08-29 13:12:02.136  6916  6916 V ActivityThread: updateVisibility : ActivityRecord{15e7ac51 token=android.os.BinderProxy@67c4bea {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 13:12:02.136  6916  6916 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-29 13:12:02.136  6916  6916 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-29 13:12:02.146   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-29 13:12:02.156  1014  1504 D InputDispatcher: Focus entered window: 6916
,08-29 13:12:02.156  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 13:12:02.156  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:12:02.156  6916  6916 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-29 13:12:02.156  6916  6956 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 13:12:02.166  6916  6956 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096,
08-29 13:12:02.166  6916  6956 D OpenGLRenderer: Enabling debug mode 0
,08-29 13:12:02.186  1014  1026 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 13:12:02.186  1014  6960 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 13:12:02.186  1176  1176 I StatusBar: Icon Only
08-29 13:12:02.186  1176  1176 D PanelView: There is/are notification(s) 
,08-29 13:12:02.186  6916  6916 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@67c4bea time:108597
,08-29 13:12:02.196  6916  6916 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-29 13:12:02.206  1014  1045 I ActivityManager: Displayed Component not be shown by security: +599ms (total +682ms)
,08-29 13:12:02.206  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36d31623 u0 com.test.thalitest/.MainActivity t2} time:108611
08-29 13:12:02.206  1014  1045 W ActivityManager: mDVFSHelper.release()
,08-29 13:12:02.206   257   452 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-29 13:12:02.206   257  1036 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-29 13:12:02.226  1963  1963 I SamsungIME: getCurrentCandidateView
,08-29 13:12:02.326  1963  1963 D SamsungIME: Dismiss ExpandCandiate
,08-29 13:12:02.406  6916  6916 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6916
,08-29 13:12:02.486  1963  1963 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 13:12:02.526  1963  1963 I SamsungIME: getDebugLevel  : 0x4f4c
,08-29 13:12:02.546  1963  1963 I SamsungIME: KeybaordView init() : load resources
,08-29 13:12:02.566  1963  1963 I SamsungIME: getCurrentKeyboard
08-29 13:12:02.566  1963  1963 I SamsungIME: getTextKeyboard
,08-29 13:12:02.586  1963  1963 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-29 13:12:02.656  6916  6916 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 13:12:02.726  6916  6962 D jxcore_app_log: JniHelper::setJavaVM(0xb82262b0), pthread_self() = -1199881200
,08-29 13:12:02.726  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 13:12:02.726  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 13:12:02.726  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 13:12:02.726  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 13:12:02.726  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-29 13:12:02.736  6916  6962 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22f76caf added. We now have 1 listener(s)
08-29 13:12:02.736  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,08-29 13:12:02.736  6916  6962 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 13:12:02.746  6916  6962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:02.746  6916  6962 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 13:12:02.746  6916  6962 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2537839a added. We now have 1 listener(s)
08-29 13:12:02.746  6916  6962 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 13:12:02.756   321   321 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-29 13:12:02.756   321   321 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-29 13:12:02.756  6916  6962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:02.766  6916  6962 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,08-29 13:12:02.766  6916  6962 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:02.766  6916  6962 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:02.766  6916  6962 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 13:12:02.766  6916  6962 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:02.766  6916  6962 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 13:12:02.776  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:02.776  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:02.806  6916  6916 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 13:12:03.296  6916  6969 W jxcore-log: Initializing JXcore engine
08-29 13:12:03.306  6916  6969 W jxcore-log: JXcore engine is ready
,08-29 13:12:03.356  1973  1973 E audit   : type=1400 msg=audit(1472469123.356:205): avc:  denied  { ioctl } for  pid=6969 comm="Thread-1285" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2069 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-29 13:12:03.356  1973  1973 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:03.356  1973  1973 E audit   : type=1300 msg=audit(1472469123.356:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e5f68f8 items=0 ppid=305 ppcomm=main pid=6969 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1285" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-29 13:12:03.356  1973  1973 E audit   : type=1320 msg=audit(1472469123.356:205): 
,08-29 13:12:03.366  6916  6969 W jxcore-log: Starting JXcore engine
,08-29 13:12:03.476  6916  6969 W jxcore-log: Platform android
08-29 13:12:03.476  6916  6969 W jxcore-log: 
08-29 13:12:03.476  6916  6969 W jxcore-log: Process ARCH arm
08-29 13:12:03.476  6916  6969 W jxcore-log: 
,08-29 13:12:03.676  6916  6969 I jxcore-log: JXcore Cordova bridge is ready!
08-29 13:12:03.676  6916  6969 I jxcore-log: 
,08-29 13:12:03.676  6916  6969 W jxcore-log: JXcore engine is started
,08-29 13:12:03.686  6916  6962 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 13:12:03.686  6916  6916 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 13:12:03.786   287   287 E SMD     : DCD OFF
,08-29 13:12:04.056  1014  1534 I art     : Explicit concurrent mark sweep GC freed 27408(1523KB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 2.414ms total 140.618ms
,08-29 13:12:06.756  1014  1047 I PowerManagerService: [PWL] Off : 50s ago
,08-29 13:12:06.786   287   287 E SMD     : DCD OFF
,08-29 13:12:06.826  1014  3371 D SSRM:n  : SIOP:: AP = 340
,08-29 13:12:07.756   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:08.756   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:09.446  5706  5706 D FactoryTest: Not factory mode
,08-29 13:12:09.446  5706  5706 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-29 13:12:09.446  5706  5706 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-29 13:12:09.446  5706  5706 D MTPRx   : still no open session command from host, so toast
,08-29 13:12:09.446  5706  5706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 ,
08-29 13:12:09.446  5706  5706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-29 13:12:09.446  5706  5706 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:115859,
08-29 13:12:09.456  1014  1094 E PersonaManagerService: inState():  stateMachine is null !!
08-29 13:12:09.456  1014  1094 I PersonaManagerService: PersonaId don't exist
08-29 13:12:09.456  1014  1094 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-29 13:12:09.456  1014  1094 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,08-29 13:12:09.456  1014  1094 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:09.456  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:09.456  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-29 13:12:09.466  1014  1094 W ActivityManager: mDVFSHelper.acquire()
,08-29 13:12:09.486  1014  1094 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:12:09.486  1014  1094 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-29 13:12:09.486  1014  1094 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 13:12:09.486  1014  1094 D InputDispatcher: Focused application set to: xxxx
,08-29 13:12:09.486  1014  1094 D InputDispatcher: Focus left window: 6916
,08-29 13:12:09.496  5706  5706 E MTPRx   : started activity for popup
,08-29 13:12:09.496  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:12:09.496  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:12:09.516  5706  5706 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 13:12:09.526  5706  5706 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-29 13:12:09.526  5706  5706 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:12:09.526  5706  5706 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:09.526  5706  5706 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:09.526  5706  5706 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:09.546  5706  5706 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-29 13:12:09.546  1014  4809 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-29 13:12:09.546  1014  4809 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 13:12:09.546  1014  4809 D InputDispatcher: Focused application set to: xxxx
,08-29 13:12:09.546  1014  4809 D InputDispatcher: Focus entered window: 6916
,08-29 13:12:09.556  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-29 13:12:09.556  1014  1094 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 13:12:09.556  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:12:09.556  1014  1094 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@f068c62 attribute=null, token = android.os.BinderProxy@17c812b2
,08-29 13:12:09.596  5706  5706 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-29 13:12:09.606  5706  5706 D PhoneWindow: *FMB* installDecor mIsFloating : true
,08-29 13:12:09.606  5706  5706 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-29 13:12:09.626  6916  6916 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:12:09.636  6916  6916 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-29 13:12:09.636  6916  6916 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:12:09.636  6916  6916 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-29 13:12:09.636  1014  1458 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-29 13:12:09.636  1014  1458 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-29 13:12:09.636  1014  1458 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-29 13:12:09.636  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-29 13:12:09.636  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,08-29 13:12:09.646  6916  6916 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:12:09.646  6916  6916 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-29 13:12:09.656  6916  6916 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e9f4606 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@3b92fecf, 16908290=android.view.AbsSavedState$1@3b92fecf}, android:focusedViewId=100}]}]
08-29 13:12:09.656  6916  6916 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-29 13:12:09.656  6916  6916 V ActivityThread: updateVisibility : ActivityRecord{15e7ac51 token=android.os.BinderProxy@67c4bea {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-29 13:12:09.656  6916  6916 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 13:12:09.656  6916  6916 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-29 13:12:09.656  6916  6916 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@67c4bea time:116066
,08-29 13:12:09.666  1014  1026 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:12:09.756   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:09.786   287   287 E SMD     : DCD OFF
,08-29 13:12:09.816  1014  1504 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:12:09.816  1014  1504 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:12:09.816  1014  1504 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:12:09.816  1014  1504 D BatteryService: stay LED for fully charged
,08-29 13:12:09.816  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 13:12:09.826  1014  1014 I MotionRecognitionService: Plugged
,08-29 13:12:09.826  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:12:09.826  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:12:09.826  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:12:09.826  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 13:12:09.826  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:12:09.836  3171  3171 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:12:09.836  3171  3274 D HeadsetStateMachine: Disconnected process message: 10
,08-29 13:12:09.846  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:09.846  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:09.856  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:09.856  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 13:12:09.856  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-29 13:12:10.756   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:11.566  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-29 13:12:11.756   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:12.466  1014  1040 W ActivityManager: mDVFSHelper.release(),
,08-29 13:12:12.756   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-29 13:12:12.786   287   287 E SMD     : DCD OFF
,08-29 13:12:13.596  1014  1095 V AlarmManager: waitForAlarm result :4,
08-29 13:12:13.596  1014  1095 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-29 13:12:13.606  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,08-29 13:12:13.606  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
08-29 13:12:13.606  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,08-29 13:12:13.606  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-29 13:12:13.606  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,08-29 13:12:13.616  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-29 13:12:13.626  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,08-29 13:12:13.636  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:12:13.636  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-29 13:12:13.636  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,08-29 13:12:13.646  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:12:13.656  1984  1984 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-29 13:12:13.666  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:12:13.676  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:12:13.686  1176  1176 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
,08-29 13:12:13.696  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-29 13:12:13.706  1014  3937 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:13.706  1014  3937 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-29 13:12:13.706  1014  3937 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:13.706  1014  3937 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:13.706  1014  3937 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:13.746  4756  4756 D ConnectivityManager: CallingUid : 10011, CallingPid : 4756
,08-29 13:12:13.746  1014  1026 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 13:12:13.746  1014  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-29 13:12:13.746  1014  1128 D ConnectivityService: apparently satisfied.  currentScore=60
,08-29 13:12:13.746  1014  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-29 13:12:13.746  4756  6978 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 13:12:13.806  4756  6979 W DriveInitializer: Background init thread started
,08-29 13:12:13.836   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-29 13:12:13.836   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:13.836  4756  6979 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-29 13:12:13.876  1984  1984 E NetworkScheduler: Unable to resolve correct action against com.google.android.youtube/com.google.android.apps.youtube.app.task.YouTubeNetworkTaskService to instantiate callback. not executing task.
,08-29 13:12:13.926  1014  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:13.926  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.net.NetworkReportService; callingUser = 0; userId(target) = 0
,08-29 13:12:13.926  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:13.926  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:13.926  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:13.946  4756  6979 W DriveInitializer: Background init thread ended
,08-29 13:12:13.946  4756  5074 D NetworkUsageDbReporter: Started reporting usage
,08-29 13:12:13.956  1014  1094 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-29 13:12:13.956  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.internal.SharedPreferencesService; callingUser = 0; userId(target) = 0
,08-29 13:12:13.956  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:13.956  1014  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:13.956  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:13.966  1014  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:13.966  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-29 13:12:13.966  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:13.966  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:13.966  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:13.986  1014  1310 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-29 13:12:13.986  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2800
,08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: keeping row: 1518
,08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 14907
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: keeping row: 1517
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 102982
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: keeping row: 1516
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 53575
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: keeping row: 1515
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 242142
08-29 13:12:14.026  4756  5074 D NetworkUsageDbReporter: keeping row: 1514
,08-29 13:12:14.036  1984  1984 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 13:12:14.056  1014  1040 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:14.056  1014  1040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:14.056  1014  1040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:14.056  4756  5074 D NetworkUsageDbReporter: Finished reporting usage.
,08-29 13:12:15.576  1014  3400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-29 13:12:15.786   287   287 E SMD     : DCD OFF
,08-29 13:12:16.466  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-29 13:12:16.466  6916  6969 I jxcore-log: 
,08-29 13:12:16.466  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-29 13:12:16.466  6916  6969 I jxcore-log: 
,08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:16.476  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:16.476  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:16.486  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 13:12:16.486  6916  6969 I jxcore-log: 
,08-29 13:12:16.486  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 13:12:16.486  6916  6969 I jxcore-log: 
,08-29 13:12:16.846  1014  3371 D SSRM:n  : SIOP:: AP = 360
,08-29 13:12:17.166  6916  6969 D executeNativeTests: Running unit tests,
,08-29 13:12:17.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:17.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c added. We now have 2 listener(s)
,08-29 13:12:17.266  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:17.266  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:17.266  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:17.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:17.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 added. We now have 2 listener(s)
08-29 13:12:17.266  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:17.266  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:17.266  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:17.276  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:17.276  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:17.276  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.276  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.276  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:12:17.276  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:12:17.276  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 13:12:17.286  6916  6969 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 13:12:17.286  6916  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-29 13:12:17.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 13:12:17.286  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:17.286  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 13:12:17.286  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.286  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.286  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:17.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:17.286  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:17.286  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:17.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:17.286  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c removed from the list
08-29 13:12:17.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.286  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 removed from the list
08-29 13:12:17.286  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.286  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.296  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.296  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:17.296  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.296  6916  6969 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-29 13:12:17.296  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.296  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.296  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.296  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.296  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.296  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.296  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.296  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.296  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.296  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.296  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.296  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.296  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:17.306  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.306  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.306  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.306  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.306  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.306  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.306  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.306  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.306  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.306  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.306  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.306  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.306  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.306  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.306  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.306  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.306  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.306  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.306  6916  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 13:12:17.316  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.316  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:17.316  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.316  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:17.316  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:17.316  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:17.316  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:17.316  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:17.316  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 13:12:17.316  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:17.326  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 13:12:17.326  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:17.326  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 13:12:17.336  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 13:12:17.336  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-29 13:12:17.336  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 13:12:17.336  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:17.336  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:17.336  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 13:12:17.356  3171  3182 D BtGatt.GattService: registerClient() - UUID=bda9010b-164c-4c30-b5b5-2033953bf633
,08-29 13:12:17.396  3171  3267 D BtGatt.GattService: onClientRegistered() - UUID=bda9010b-164c-4c30-b5b5-2033953bf633, clientIf=6
,08-29 13:12:17.396  6916  6930 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:12:17.406  3171  3181 D BtGatt.GattService: start scan with filters
,08-29 13:12:17.406  3171  3271 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:17.406  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:17.406  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:12:17.406  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-29 13:12:17.406  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:17.406  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.406  3171  3271 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:17.416  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:17.416  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.416  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:17.416  3171  3267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:12:17.416  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.416  3171  3271 D BtGatt.ScanManager: allow scan with filters
08-29 13:12:17.416  3171  3271 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:12:17.416  6916  6969 I io.jxcore.node.ConnectionHelper: start: OK
08-29 13:12:17.416  3171  3271 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 13:12:17.426  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.426  6916  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:12:17.426  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:17.426  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:12:17.426  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.426  3171  3271 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:17.426  3171  3271 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:12:17.426  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:17.426  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.426  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left,
08-29 13:12:17.426  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:17.426  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:12:17.426  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:17.426  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:17.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:17.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:17.436  3171  3272 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:17.436  3171  3182 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:12:17.436  3171  3267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:12:17.436  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.436  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:12:17.436  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:17.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:17.436  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:17.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:17.446  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:17.446  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.446  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:17.446  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.446  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.446  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.446  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.446  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.446  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.446  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.446  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:17.446  6916  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:12:17.446  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:12:17.446  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.456  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:17.456  3171  3271 D BtGatt.ScanManager: filter size is 1
,08-29 13:12:17.456  3171  3271 D BtGatt.ScanManager: delete FilterIndex - 3,
,08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.466  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:17.466  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 13:12:17.466  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.466  3171  3271 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:17.466  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:17.466  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:17.476  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:17.476  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:17.476  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:17.476  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:17.476  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:17.476  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:17.476  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.476  3171  3271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:12:17.476  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.476  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:17.476  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.486  3171  3267 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0,
08-29 13:12:17.486  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.486  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:17.486  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:17.486  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:17.486  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:12:17.486  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:17.496  3171  3181 D BtGatt.GattService: registerClient() - UUID=655d70c8-c746-48cd-8f0e-d5e86944bcc2
,08-29 13:12:17.536  3171  3267 D BtGatt.GattService: onClientRegistered() - UUID=655d70c8-c746-48cd-8f0e-d5e86944bcc2, clientIf=6
08-29 13:12:17.536  6916  6929 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-29 13:12:17.536  3171  3272 D BtGatt.GattService: start scan with filters
,08-29 13:12:17.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:17.536  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 13:12:17.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:17.536  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:17.536  3171  3271 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:17.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.546  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:17.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:17.546  3171  3267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:12:17.556  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.556  3171  3271 D BtGatt.ScanManager: allow scan with filters
08-29 13:12:17.556  3171  3271 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:12:17.556  3171  3271 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-29 13:12:17.556  6916  6969 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:12:17.556  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:12:17.556  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.556  3171  3271 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:17.556  3171  3271 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:12:17.566  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.566  6916  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:17.566  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.566  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:17.566  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:17.566  3171  3182 D BtGatt.GattService: stopScan() - queue size =1
08-29 13:12:17.566  3171  3272 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:12:17.566  3171  3267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:12:17.566  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:17.566  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:17.566  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:17.576  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:12:17.576  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-29 13:12:17.576  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:12:17.576  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:17.576  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:12:17.576  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.576  3171  3271 D BtGatt.ScanManager: filter size is 1
,08-29 13:12:17.576  3171  3271 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 13:12:17.586  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:17.586  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.586  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:17.586  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:17.586  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.586  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:17.586  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
,08-29 13:12:17.586  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.586  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.586  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 13:12:17.586  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.586  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 13:12:17.586  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.586  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.586  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.586  3171  3271 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:17.586  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.586  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.586  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:17.586  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.596  6916  6969 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-29 13:12:17.596  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:17.596  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:17.596  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.596  3171  3271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.596  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:17.606  3171  3267 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-29 13:12:17.606  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.606  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:17.606  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:17.606  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.606  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.616  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:17.616  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:17.616  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 13:12:17.616  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:17.616  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:17.616  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:17.626  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:17.626  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:17.626  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:17.626  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:17.626  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:17.626  3171  3182 D BtGatt.GattService: registerClient() - UUID=44e0d637-ce56-4f76-a74c-8c2fd4b09a14
,08-29 13:12:17.666  3171  3267 D BtGatt.GattService: onClientRegistered() - UUID=44e0d637-ce56-4f76-a74c-8c2fd4b09a14, clientIf=6
,08-29 13:12:17.666  6916  6930 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:12:17.666  3171  3272 D BtGatt.GattService: start scan with filters
,08-29 13:12:17.676  3171  3271 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:17.676  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 13:12:17.676  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:17.676  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:17.676  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:17.676  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.676  3171  3267 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:12:17.676  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.676  3171  3271 D BtGatt.ScanManager: allow scan with filters
08-29 13:12:17.676  3171  3271 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-29 13:12:17.676  3171  3271 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 13:12:17.676  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:17.676  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:17.686  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:17.686  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:12:17.686  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.686  3171  3271 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:17.686  3171  3271 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:12:17.686  6916  6969 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 13:12:17.686  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.686  6916  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 13:12:17.686  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.686  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:17.686  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.686  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:12:17.686  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:17.686  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:17.686  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:17.686  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:12:17.696  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:17.696  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:17.696  3171  3267 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:12:17.696  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.696  3171  3181 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:17.696  3171  3182 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:17.696  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:17.696  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:17.696  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:17.696  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:17.696  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:12:17.696  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:17.706  3171  3271 D BtGatt.ScanManager: filter size is 1
,08-29 13:12:17.706  3171  3271 D BtGatt.ScanManager: delete FilterIndex - 5
08-29 13:12:17.706  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.706  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.706  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.706  6916  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:17.706  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.706  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.706  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:17.706  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.706  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.706  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.706  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:17.706  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.706  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.706  6916  6969 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-29 13:12:17.706  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.706  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.706  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.706  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.706  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.706  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.706  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.706  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.706  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.706  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.706  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.706  3171  3267 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:12:17.706  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.716  3171  3271 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.716  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 13:12:17.716  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.716  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.716  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.716  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.716  3171  3267 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:17.716  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.716  3171  3271 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 13:12:17.716  6916  6969 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,08-29 13:12:17.716  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.716  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.716  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.716  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.716  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.716  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.716  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.716  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.726  6916  6969 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,08-29 13:12:17.726  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.726  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.726  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.726  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.726  3171  3267 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.726  3171  3267 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 13:12:17.726  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:17.726  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 13:12:17.726  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 13:12:17.726  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.726  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.726  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.726  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.726  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.726  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.726  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.726  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.726  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:17.726  6916  6969 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:17.726  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-29 13:12:17.736  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 13:12:17.736  6916  6969 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections:, Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 13:12:17.736  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 13:12:17.736  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 13:12:17.736  6916  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:17.736  6916  6969 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-29 13:12:17.736  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:17.736  6916  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:17.736  6916  6969 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 13:12:17.736  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:17.736  6916  6969 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 13:12:17.736  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 13:12:17.746  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 13:12:17.746  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 13:12:17.746  6916  6969 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 13:12:17.746  6916  6969 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,08-29 13:12:17.746  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.746  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.746  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:17.746  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.746  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.746  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-29 13:12:17.746  6916  6995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1349)
,08-29 13:12:17.746  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.746  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.746  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.746  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.746  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.746  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.746  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.746  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.746  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.756  6916  6969 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-29 13:12:17.756  6916  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
,08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:17.756  6916  6995 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-29 13:12:17.756  6916  6969 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 13:12:17.756  6916  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 13:12:17.756  6916  6969 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 13:12:17.756  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.756  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.756  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.756  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.756  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.756  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.756  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.766   321   321 I ServiceManager: Waiting for service AtCmdFwd...
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.766  6916  6995 D BluetoothSocket: connect(): myUserId = 0
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6995 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.766  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1349
08-29 13:12:17.766  6916  6996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1349)
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.766  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.766  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.766  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListen,er: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.766  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6996 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@135810af, channel: -1, state: INIT
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.766  6916  6996 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@135810af, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.766  6916  6996 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1349)
08-29 13:12:17.766  3171  3182 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:17.766  6916  6995 D BluetoothSocket: connect(), SocketState: CLOSED, mPfd: {ParcelFileDescriptor: FileDescriptor[102]}
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-29 13:12:17.766  6916  6995 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@135810af, channel: -1, state: CLOSED
08-29 13:12:17.766  6916  6995 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1349)
,08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.766  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:17.766  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.766  6916  6916 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 13:12:17.766  6916  6916 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-29 13:12:17.766  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:17.766  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.766  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.776  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.776  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:17.776  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.776  6916  6969 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 13:12:17.776  6916  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 13:12:17.776  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 13:12:17.776  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.776  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.776  6916  6997 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 13:12:17.776  6916  6997 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.776  6916  6916 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-29 13:12:17.776  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.776  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.776  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.776  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.776  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.776  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.776  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.786  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:17.786  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:17.786  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:17.786  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:17.786  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.786  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.786  6916  6969 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19b5f88c not in the list
08-29 13:12:17.786  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.786  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:17.786  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.786  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:17.786  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:17.786  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:17.786  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:17.786  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:17.786  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:17.786  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c7dabd5 not in the list
,08-29 13:12:17.786  6916  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:17.786  6916  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 13:12:17.786  6916  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 13:12:17.786  6916  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:17.786  6916  6969 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 13:12:17.786  6916  6969 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 13:12:17.786  6916  6969 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,08-29 13:12:17.786  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:17.786  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27ee9cbc added. We now have 2 listener(s)
08-29 13:12:17.786  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:17.786  6916  6969 D BluetoothAdapter: enable()
,08-29 13:12:17.796  6916  6969 D BluetoothAdapter: enable(): BT is already enabled..!
,08-29 13:12:17.796  1014  1533 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 13:12:17.796  1014  1533 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:12:17.796  1014  1533 D SecContentProvider2: mCursor = null
,08-29 13:12:17.796  1014  1533 D WifiService: setWifiEnabled: true pid=6916, uid=10171
,08-29 13:12:17.796  1014  1533 W ActivityManager: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:12:17.796  1014  1533 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:12:17.796  1014  1533 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:17.796  1014  1533 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:12:17.796  1014  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:12:17.796  1014  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:12:17.796  1014  1533 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:12:17.796  1014  1533 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:12:17.796  1014  1533 D SettingsProvider: name = wifi_on
,08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@29c23445 added. We now have 3 listener(s)
08-29 13:12:17.806  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@25fb779a added. We now have 4 listener(s)
08-29 13:12:17.806  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:17.806  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@259f08cb added. We now have 5 listener(s)
08-29 13:12:17.806  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:17.816  1014  1534 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:12:17.816  1014  1534 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:12:17.816  1014  1534 D SecContentProvider2: mCursor = null
,08-29 13:12:17.816  1014  1534 D WifiService: setWifiEnabled: false pid=6916, uid=10171
,08-29 13:12:17.816  1014  1534 D SettingsProvider: name = wifi_on
,08-29 13:12:17.816  1014  1126 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-29 13:12:17.826  6916  6969 D BluetoothAdapter: disable()
,08-29 13:12:17.826  1358  1358 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:12:17.826  1358  1358 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 13:12:17.826  1358  1358 I wpa_supplicant: P2P: Current p2p state = IDLE
,08-29 13:12:17.826  1014  1094 D SettingsProvider: name = bluetooth_on,
08-29 13:12:17.826  1358  1358 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 13:12:17.836  3171  3264 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-29 13:12:17.836  3171  3264 D BluetoothAdapterProperties: Setting state to 13
,08-29 13:12:17.836  3171  3264 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:12:17.836  3171  3264 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:12:17.836  3171  3264 D BluetoothAdapterService: updateAdapterState state is 13
08-29 13:12:17.836  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:17.836  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:17.836  1014  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:17.836  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:17.836  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:17.836  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:17.836  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:17.846  3171  3171 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 13:12:17.846  3171  3264 D BluetoothAdapterService: Autoconnection is available 
08-29 13:12:17.846  3171  3264 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-29 13:12:17.846  3171  3264 D BluetoothAdapterService: terminating service from this receiver
,08-29 13:12:17.846  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 13:12:17.846  3171  3171 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@49fd6bb, channel: 19, state: LISTENING
08-29 13:12:17.846  3171  3171 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@49fd6bb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e466243, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b1d97d8mSocket: android.net.LocalSocket@38eda731 impl:android.net.LocalSocketImpl@27074e16 fd:FileDescriptor[74]
08-29 13:12:17.846  3171  3171 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38eda731 impl:android.net.LocalSocketImpl@27074e16 fd:FileDescriptor[74]
,08-29 13:12:17.846  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.846  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:17.846  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:17.846  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:17.846  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:17.846  3171  3264 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 13:12:17.846  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:17.846  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.846  3171  3264 D BluetoothAdapterProperties: mDiscovering is false
08-29 13:12:17.846  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:17.846  1014  4809 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 13:12:17.846  3171  3264 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true,
,08-29 13:12:17.846  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,08-29 13:12:17.856  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.856  3171  3267 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:12:17.856  3171  3267 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:12:17.856  3171  3264 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 13:12:17.856  3171  3264 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-29 13:12:17.856  3171  3264 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-29 13:12:17.856  3171  3264 E bt-btif : cmd socket is not created
08-29 13:12:17.856  3171  3288 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 13:12:17.856  3171  3288 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-29 13:12:17.866  3171  5282 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 13:12:17.866  3171  3264 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 13:12:17.866  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:17.866  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:17.866  3171  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 13:12:17.866  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:17.866  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:17.866  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:17.866  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:17.876  1014  1126 E WifiNative-wlan0: do suspend true
08-29 13:12:17.876  1358  1358 I wpa_supplicant: nl80211: Received scan results (20 BSSes)
,08-29 13:12:17.876  1014  1125 D WifiP2pService: InactiveState{ what=147461 }
,08-29 13:12:17.876  1014  1125 D WifiP2pService: P2pEnabledState{ what=147461 }
,08-29 13:12:17.876  1014  1125 D WifiP2pService: DefaultState{ what=147461 }
,08-29 13:12:17.876  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.886  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:17.886  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-29 13:12:17.896  1963  1963 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:17.896  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:12:17.896  3171  3171 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10c05984, channel: 5, state: LISTENING
08-29 13:12:17.896  3171  3171 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10c05984, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18ba70c0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d44856dmSocket: android.net.LocalSocket@162235a2 impl:android.net.LocalSocketImpl@36346233 fd:FileDescriptor[76]
08-29 13:12:17.896  3171  3171 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@162235a2 impl:android.net.LocalSocketImpl@36346233 fd:FileDescriptor[76]
,08-29 13:12:17.896  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:17.896  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:17.896  3171  3171 I BtOppRfcommListener: stopping Accept Thread
08-29 13:12:17.896  3171  3171 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30ab89f0, channel: 12, state: LISTENING
08-29 13:12:17.896  3171  3171 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30ab89f0, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10c8074a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cb10b69mSocket: android.net.LocalSocket@251209ee impl:android.net.LocalSocketImpl@23c8ee8f fd:FileDescriptor[79]
08-29 13:12:17.896  3171  3171 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@251209ee impl:android.net.LocalSocketImpl@23c8ee8f fd:FileDescriptor[79]
08-29 13:12:17.896  3171  5282 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-29 13:12:17.896  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-29 13:12:17.906  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast
08-29 13:12:17.906  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:17.906  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:17.906  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:17.906  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:17.906  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:17.906  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:17.906  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.906  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:12:17.906  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:17.906  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:17.916  1014  1504 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:12:17.916  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:12:17.916  7000  7000 E Zygote  : MountEmulatedStorage()
08-29 13:12:17.916  7000  7000 E Zygote  : v2
08-29 13:12:17.916  7000  7000 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 13:12:17.916  7000  7000 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:17.926  1014  1040 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7000 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:17.926  1014  1094 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:17.926  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:17.926  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:17.926  1014  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:17.926  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:17.926  7000  7000 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:17.926  7000  7000 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:17.926  3171  3171 V BluetoothOppManager: cleanUp...
,08-29 13:12:17.936  7000  7000 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:17.956  7000  7000 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:17.956  7000  7000 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:17.976  7000  7000 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:18.006  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:12:18.006  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:12:18.016  7000  7000 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
,08-29 13:12:18.016   277   998 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:18.016  7000  7000 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal,
08-29 13:12:18.016  7000  7000 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
,08-29 13:12:18.026  1984  3105 V NativeCrypto: Read error: ssl=0xb86da730: I/O error during system call, Connection timed out
,08-29 13:12:18.026  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:18.026  1984  3105 V NativeCrypto: SSL shutdown failed: ssl=0xb86da730: I/O error during system call, Broken pipe
,08-29 13:12:18.026  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:12:18.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:18.026  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:18.026  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:18.026  1984  3105 E GCM     : Wifi connection closed with errorCode 20
08-29 13:12:18.026  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-29 13:12:18.026  1014  1094 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
,08-29 13:12:18.036  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:18.036  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:18.036  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-29 13:12:18.036  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:18.036  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-29 13:12:18.036  1014  1125 D WifiP2pService: InactiveState{ what=131204 }
,08-29 13:12:18.036  1014  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 13:12:18.036  1014  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 13:12:18.036  1014  1741 I qtaguid : Tagging socket 342 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1014, getuid(): 1000
,08-29 13:12:18.036  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-29 13:12:18.036  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:12:18.046  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:12:18.046  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:18.046  1014  1014 D RttService: SCAN_AVAILABLE : 1
,08-29 13:12:18.046  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:18.046  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:18.046  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:18.046  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.046  1014  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 13:12:18.046  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.046  1014  1741 I qtaguid : Untagging socket 342
,08-29 13:12:18.046  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.046  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.046  1014  1741 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 13:12:18.056  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:18.056  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
,08-29 13:12:18.056  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:18.056  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:18.066  7000  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:18.066  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:18.066  3171  3288 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:18.066  3171  3351 I bt_userial_mct: exiting userial_read_thread
08-29 13:12:18.066  3171  3351 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 13:12:18.066  3171  3288 W bt-btif : ag scb idx 1 not allocated
08-29 13:12:18.066  3171  3288 W bt-btif : ag scb idx 2 not allocated
08-29 13:12:18.066  3171  3288 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:12:18.066  3171  3267 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 13:12:18.066  3171  3290 I bt_vendor: hw_epilog_process
08-29 13:12:18.066  3171  3267 D bt_userial_mct: userial_close
08-29 13:12:18.066  3171  3267 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 13:12:18.066  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 13:12:18.066  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:18.066  1014  1045 D WifiDisplayController: disconnect
08-29 13:12:18.066  1014  1045 D WifiDisplayController: updateConnection
08-29 13:12:18.066  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:18.066  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:12:18.066  1014  4809 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:12:18.066  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.066  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.066  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.066  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:18.066  1014  1125 D WifiP2pService: P2pDisablingState
,08-29 13:12:18.066  1014  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-29 13:12:18.066  1014  1125 D WifiP2pService: p2p socket connection lost
08-29 13:12:18.066  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:12:18.066  1014  1126 E WifiNative-wlan0: do suspend true
08-29 13:12:18.066  1014  1125 D WifiP2pService: P2pDisabledState
,08-29 13:12:18.076  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-29 13:12:18.076  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:12:18.076  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:18.076  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:12:18.086  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:12:18.096  1014  1094 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:12:18.096  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:12:18.106  1014  1493 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 13:12:18.106  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.106  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.106  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.106  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.116  7000  7000 D LocalBluetoothProfileManager: PANU : true,
,08-29 13:12:18.116  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:18.116  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.116  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.116  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.116  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:18.126  7000  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-29 13:12:18.126  1014  4809 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 13:12:18.126  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.126  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.126  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.126  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.126  7000  7000 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 13:12:18.126  7000  7000 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 13:12:18.136  7000  7000 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:18.146  7000  7000 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:18.146  7000  7000 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:12:18.146  7000  7000 D PanProfile: Bluetooth service connected
,08-29 13:12:18.146  7000  7000 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-29 13:12:18.146  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:18.146  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 13:12:18.146  7000  7000 D SapProfile: Bluetooth service connected
,08-29 13:12:18.146  1014  1534 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 13:12:18.146  7000  7000 D Bluetoothsap: getConnectedDevices()
,08-29 13:12:18.146  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.146  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.146  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.146  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:18.166  7028  7028 E Zygote  : MountEmulatedStorage()
,08-29 13:12:18.166  7028  7028 E Zygote  : v2
08-29 13:12:18.166  7028  7028 I libpersona: KNOX_SDCARD checking this for 10055
08-29 13:12:18.166  7028  7028 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:18.166  1014  1534 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7028 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
08-29 13:12:18.166  7028  7028 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:18.166  7028  7028 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:18.166  1014  1125 D WifiP2pService: P2pDisabledState{ what=143375 }
08-29 13:12:18.166  1014  1125 D WifiP2pService: DefaultState{ what=143375 }
,08-29 13:12:18.176  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:18.176  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:18.176  7028  7028 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:18.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:18.196  1014  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:18.196   305   305 I art     : Explicit concurrent mark sweep GC freed 8708(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 598us total 31.177ms
,08-29 13:12:18.196  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.196  7028  7028 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:18.196  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.196  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 13:12:18.196  7028  7028 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:18.216   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.775ms
,08-29 13:12:18.226   277   998 D CommandListener: Clearing all IP addresses on wlan0
08-29 13:12:18.226   277   994 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:12:18.226   277   994 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-29 13:12:18.226  1014  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
08-29 13:12:18.226  1014  1128 V NetworkStats: updateIfacesLocked()
08-29 13:12:18.226  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.226  1014  1128 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:18.226  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-29 13:12:18.226  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-29 13:12:18.226  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:18.226  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:18.226  1358  1358 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED,
08-29 13:12:18.236  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.236  1014  1128 V NetworkStats: performPollLocked() took 7ms
,08-29 13:12:18.236  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:12:18.236  7028  7028 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 13:12:18.236   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 738us total 21.386ms
,08-29 13:12:18.246  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 13:12:18.246  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:18.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:18.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:18.246  1014  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,08-29 13:12:18.256  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.256  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:12:18.256  1176  1667 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-29 13:12:18.256  1014  1741 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:18.256  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:18.256  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:18.256  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-29 13:12:18.256  1014  1128 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-29 13:12:18.256  1014  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-29 13:12:18.256  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:12:18.256  1014  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-29 13:12:18.256  1469  1469 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:18.256  1014  1128 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,08-29 13:12:18.266  3171  3267 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:12:18.266  3171  3267 I bt_vendor: bluetooth satus is on
08-29 13:12:18.266  3171  3267 I bt_vendor: bt-vendor : resetting BT status
08-29 13:12:18.266  3171  3267 I bt_vendor: Starting hciattach daemon
08-29 13:12:18.266  3171  3267 I bt_vendor: try to set false
08-29 13:12:18.266  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-29 13:12:18.266  3171  3267 I bt_vendor: Starting hciattach daemon
08-29 13:12:18.266  3171  3267 I bt_vendor: try to set false
,08-29 13:12:18.266  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:18.266  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:18.266  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:12:18.266  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.276  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:12:18.266  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.266  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.276  4756  6978 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-29 13:12:18.276  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:18.276  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 13:12:18.276  6916  6916 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:12:18.276  3171  3267 I bt_vendor: cleanup
08-29 13:12:18.276  3171  3288 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-29 13:12:18.276  3171  3267 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:12:18.276  3171  3267 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 13:12:18.276  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:18.276  7028  7028 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
08-29 13:12:18.276  1176  1176 D HotspotTile: onReceive : 0, 0
,08-29 13:12:18.276  7028  7028 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 13:12:18.276  7028  7028 D UserAnalysis: Create SecureDbHelper
,08-29 13:12:18.286  1014  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:12:18.286  3171  3264 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-29 13:12:18.286  3171  3264 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:12:18.286  3171  3264 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 13:12:18.286  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 13:12:18.286  1014  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.286  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 13:12:18.286  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
08-29 13:12:18.286  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 13:12:18.286  7028  7028 D IntelligenceServiceApplication: onCreate()
08-29 13:12:18.286  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.286  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.286  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.296  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
08-29 13:12:18.296  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:18.296  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 13:12:18.296  3171  3171 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:18.296  3171  3171 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:12:18.296  3171  3171 D BtGatt.GattService: stop()
08-29 13:12:18.296  3171  3171 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 13:12:18.296  1014  1094 I ActivityManager: Killing 6616:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 13:12:18.306  7028  7028 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-29 13:12:18.306  1014  4809 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:18.306  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 13:12:18.306  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.306  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.306  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.306  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:18.306  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:18.306  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-29 13:12:18.316  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.316  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:18.316  1014  1128 D ConnectivityService: nai.networkMonitor.doQuit()
,08-29 13:12:18.316  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.316  1014  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,08-29 13:12:18.316  7028  7028 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
08-29 13:12:18.316  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-29 13:12:18.316  1984  2159 I art     : Explicit concurrent mark sweep GC freed 70746(4MB) AllocSpace objects, 14(224KB) LOS objects, 40% free, 10MB/17MB, paused 1.197ms total 91.328ms
,08-29 13:12:18.316  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:18.316  1014  1128 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-29 13:12:18.316  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:18.316  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 13:12:18.316  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.316  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.316  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:18.326  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 13:12:18.326  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 13:12:18.326  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 13:12:18.326  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:18.326  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-29 13:12:18.326  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:18.326  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:18.326  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 13:12:18.326  1014  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:18.326  7028  7028 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 13:12:18.326  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:18.326  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:18.326  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.326  1014  1123 V NetworkStats: updateIfacesLocked()
08-29 13:12:18.326  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:18.326  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:18.326  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:18.336  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:18.336  1014  1123 V NetworkStats: performPollLocked() took 3ms
08-29 13:12:18.336  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.336  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
,08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 13:12:18.336  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-29 13:12:18.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.336  1014  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:18.336  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.336  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:18.346  1014  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.346  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.346  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.346  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.346  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.346  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:12:18.346  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:12:18.346  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:12:18.346  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.346  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:18.346  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 13:12:18.356  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:18.356  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.356  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.356  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:18.366  7048  7048 E Zygote  : MountEmulatedStorage()
08-29 13:12:18.366  7048  7048 E Zygote  : v2
,08-29 13:12:18.366  7048  7048 I libpersona: KNOX_SDCARD checking this for 10105
08-29 13:12:18.366  7048  7048 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:12:18.366  7048  7048 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:12:18.366  1014  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7048 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-29 13:12:18.366  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:18.366  1014  4809 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.366  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.366  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-29 13:12:18.366  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:18.366  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 13:12:18.366  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:12:18.376  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:12:18.376  7048  7048 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:18.376  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.376  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
08-29 13:12:18.376  7048  7048 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-29 13:12:18.376  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.376  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.376  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:18.376  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.376  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:18.376  3171  3264 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.376  1014  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:18.376  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 13:12:18.376  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.376  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.376  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:18.386  1358  1358 I wpa_supplicant: Blacklist: Clear (all) 
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 13:12:18.386  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:12:18.386  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,08-29 13:12:18.386  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.386  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-29 13:12:18.386  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.386  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:18.386  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:18.386  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:12:18.386  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:12:18.386  3171  3264 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 13:12:18.386  3171  3264 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:12:18.386  3171  3264 D BluetoothAdapterState: Stopping profile services that were post enabled
08-29 13:12:18.386  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-29 13:12:18.386  3171  3171 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:12:18.396  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.396  3171  3171 D A2dpService: Received stop request...Stopping profile...
08-29 13:12:18.396  3171  3279 D A2dpStateMachine: Exit Disconnected: -1
08-29 13:12:18.396  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 13:12:18.406  7048  7048 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:18.406  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.406  1014  1014 D BluetoothA2dp: Proxy object disconnected
,08-29 13:12:18.406  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-29 13:12:18.406  7048  7048 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:18.406  3171  3171 D HidService: Received stop request...Stopping profile...
08-29 13:12:18.406  3171  3171 D HidService: Stopping Bluetooth HidService
08-29 13:12:18.406  3171  3171 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:18.406  3171  3171 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 13:12:18.406  3171  3171 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:12:18.406  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.406  3171  3171 D HealthService: Received stop request...Stopping profile...,
08-29 13:12:18.406  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.406  3171  3171 D PanService: Received stop request...Stopping profile...
08-29 13:12:18.406  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.416  3171  3171 D BluetoothMapService: Received stop request...Stopping profile...
08-29 13:12:18.416  7000  7000 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:18.416  7000  7000 D PanProfile: Bluetooth service disconnected
08-29 13:12:18.416  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:12:18.416  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:18.426  3171  3171 D SapService: Received stop request...Stopping profile...
08-29 13:12:18.426  3171  3171 D SapService: Stopping Bluetooth SapService
08-29 13:12:18.426  3171  3171 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:18.426  7000  7000 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 13:12:18.426  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-29 13:12:18.426  7000  7000 D SapProfile: Bluetooth service disconnected
08-29 13:12:18.426  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:18.426  3171  3171 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 13:12:18.426  3171  3171 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 13:12:18.426  3171  3171 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 13:12:18.426  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 13:12:18.426  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:18.426  3171  3171 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 13:12:18.426  3171  3171 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:18.426  3171  3171 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 13:12:18.426  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 13:12:18.426  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.426  3171  3171 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.426  3171  3281 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-29 13:12:18.436  3171  3171 I GKI_LINUX: GKI_exit_task 2 done
08-29 13:12:18.436  3171  3171 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 13:12:18.436  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-29 13:12:18.436  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.436  3171  3171 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.436  3171  3171 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:12:18.436  3171  3171 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 13:12:18.436  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 13:12:18.436  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.436  3171  3171 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:18.436  3171  3171 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:12:18.436  3171  3171 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 13:12:18.436  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-29 13:12:18.436  3171  3171 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:12:18.436  3171  3171 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 13:12:18.436  3171  3171 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 13:12:18.436  3171  3171 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 13:12:18.436  3171  3171 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 13:12:18.446  3171  3264 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-29 13:12:18.446  3171  3264 D BluetoothAdapterProperties: Setting state to 10
08-29 13:12:18.446  3171  3264 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:12:18.446  3171  3264 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:12:18.446  3171  3264 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 13:12:18.446  3171  3264 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:12:18.446  3171  3264 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-29 13:12:18.446  3171  3264 I BluetoothAdapterState: Entering OffState
,08-29 13:12:18.456  3171  3182 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.456  3171  3182 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:18.456  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.456  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:18.456  1358  1358 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-29 13:12:18.456  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-29 13:12:18.456  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:18.456  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:18.466  6916  6929 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:18.466  6916  6929 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:18.466  6916  6929 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 13:12:18.466  6916  6929 D BluetoothLeAdvertiser: Exit stop advertising
08-29 13:12:18.466  6916  6929 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 13:12:18.466  6916  6929 D BluetoothLeScanner: Exiting stopAllScan
,08-29 13:12:18.466  1455  1483 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.466  1455  1483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:18.466  1446  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.466  1446  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:18.466  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.466  3171  3181 D BluetoothA2dp: onBluetoothStateChange: up=false,
,08-29 13:12:18.466  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 13:12:18.466  7000  7010 D Bluetoothsap: onBluetoothStateChange: up=false
08-29 13:12:18.466  7000  7010 D Bluetoothsap: Unbinding service...
08-29 13:12:18.476  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.476  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.476  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.476  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.476  1984  2160 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.476  1984  2160 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:18.476  1469  1669 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.476  1469  1669 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:18.476  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.476  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.476  7000  7008 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:18.476  7000  7008 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:18.476  1176  1194 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:18.476  1176  1194 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:18.476  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.476  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.486  1358  1358 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 13:12:18.486  1358  1358 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 13:12:18.486  1358  1358 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 13:12:18.486  1358  1358 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:18.486  1358  1358 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-29 13:12:18.486  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.486  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:18.486  1014  1129 D Tethering: InitialState.processMessage what=4
08-29 13:12:18.486  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:12:18.486  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.486  1014  1129 E Tethering: No numeric data
08-29 13:12:18.486  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.486  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:18.486  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:12:18.486  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 13:12:18.486  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.496  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:18.496  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:18.496  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:18.496  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:18.496  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:18.496  1176  1176 D HotspotTile: updateTetherState():false, false
08-29 13:12:18.496  1014  1129 D Tethering: clearTetheredNotification()
08-29 13:12:18.496  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.496  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.496  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.496  1014  1123 V NetworkStats: performPollLocked() took 5ms
08-29 13:12:18.496  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:18.496  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.496  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.496  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:18.496  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-29 13:12:18.496  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.506  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:12:18.506  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:18.506  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.506  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
08-29 13:12:18.506  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:12:18.506  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:12:18.516  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.516  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.516  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:18.516  1176  1723 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
,08-29 13:12:18.516  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:12:18.516  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:18.516  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-29 13:12:18.516  1176  1723 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.516  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.516  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.516  1014  1310 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 13:12:18.516  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.516  1963  1963 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:18.516  1014  1534 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false,
,08-29 13:12:18.516  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:12:18.526  1984  2165 D BluetoothAdapter: 591968253: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.526  1984  2165 D BluetoothAdapter: 591968253: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:18.526  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:12:18.526  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.526  1014  1094 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:18.526  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.526  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:18.526  7000  7000 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:18.526  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.526  1014  1094 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.526  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 13:12:18.526  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:18.526  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.526  3171  3267 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-29 13:12:18.536  3171  3171 I GKI_LINUX: GKI_exit_task 1 done
08-29 13:12:18.536  3171  3171 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-29 13:12:18.536  3171  3171 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:12:18.536  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.536  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.536  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.536  3171  3171 I art     : System.exit called, status: 0
08-29 13:12:18.536  3171  3171 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-29 13:12:18.536  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.536  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.536  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-29 13:12:18.546  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-29 13:12:18.546  1469  1469 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
08-29 13:12:18.546   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb72ee7c8
08-29 13:12:18.546   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
,08-29 13:12:18.546   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-29 13:12:18.546   271   344 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1221663432)
08-29 13:12:18.556  1469  1469 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-29 13:12:18.556  1014  3937 I ActivityManager: Process com.android.bluetooth (pid 3171)(adj 0) has died(30,727)
,08-29 13:12:18.606  1358  1358 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:12:18.606   271   344 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-29 13:12:18.606   271   344 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-29 13:12:18.606   271   344 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1221663432) wakelock released: 1, error no: 0
08-29 13:12:18.606   271   344 I rmt_storage: 
,08-29 13:12:18.606   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb72ee7c8
,08-29 13:12:18.616   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/,
08-29 13:12:18.616   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:12:18.626  7048  7088 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:12:18.626   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:12:18.626   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
08-29 13:12:18.636  7048  7088 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:12:18.646  1358  1358 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-29 13:12:18.656  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-29 13:12:18.656  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-29 13:12:18.656  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.656  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:18.656  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:18.676  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:18.676  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:18.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:18.676  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:18.676  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:18.676  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-29 13:12:18.676  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:12:18.686  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:18.686  1176  1176 D HotspotTile: onReceive : 1, 0
08-29 13:12:18.686  1984  2165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:18.686  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:18.746  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-29 13:12:18.746  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:18.746  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.746  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.746  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:18.756  1014  1310 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:18.756  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.756  1014  1310 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.756  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:18.766   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:18.786   287   287 E SMD     : DCD OFF
,08-29 13:12:18.796  1984  1984 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=3bc0dcfc-574a-4fa7-90fd-3357df1d5fe1
,08-29 13:12:18.806  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:18.816  1014  1014 I ApplicationPolicy: updateDataUsageMap
,08-29 13:12:18.826  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:18.836  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:18.836  1014  1458 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-29 13:12:18.836  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-29 13:12:18.836  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:18.846  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:18.846  1014  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.846  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:18.846  1984  1984 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 13:12:18.846  1984  1984 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=231 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2,
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=229 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=228 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690),
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=225 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.,app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=224 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.ja,va:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=188 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.856  7048  7048 D StrictMode: StrictMode policy violation; ~duration=187 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:18.856  7048  7048 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:18.866  1014  1458 I ActivityManager: Killing 6449:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
08-29 13:12:18.866  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:18.876  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-29 13:12:18.886  1014  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-29 13:12:18.886  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.886  1014  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.886  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 13:12:18.886  1014  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:18.886  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:18.886  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.896  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:18.896  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:18.896  1602  1602 I Hs20UtilService: Starting #8
08-29 13:12:18.896  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:18.906  7000  7000 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
08-29 13:12:18.916  7000  7000 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
08-29 13:12:18.916  7000  7000 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
08-29 13:12:18.916  7000  7000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:12:18.926  7000  7000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:12:18.926  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:18.936  7048  7086 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:12:18.946  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:12:18.946  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:18.946  7000  7000 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:18.946  7000  7101 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:18.956  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.956  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.956  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-29 13:12:18.956  1014  1504 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-29 13:12:18.956  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:18.956  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.956  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:18.956  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:18.966  1014  1504 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7104 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-29 13:12:18.966  7104  7104 E Zygote  : MountEmulatedStorage()
08-29 13:12:18.966  7104  7104 I libpersona: KNOX_SDCARD checking this for 10102
08-29 13:12:18.966  7104  7104 E Zygote  : v2
08-29 13:12:18.966  7104  7104 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:18.966  7104  7104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:18.976  7104  7104 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:18.976  7104  7104 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:18.996  1014  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:18.996  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:18.996  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:18.996  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 13:12:19.006  7104  7104 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:19.006  7104  7104 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:19.016  1984  2153 W GCoreFlp: No location to return for getLastLocation()
,08-29 13:12:19.036  7104  7104 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 13:12:19.056  1984  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 13:12:19.056  4756  7024 D UdcContextInitService: registered all accounts: true
,08-29 13:12:19.066  6486  6498 I art     : Explicit concurrent mark sweep GC freed 1455(62KB) AllocSpace objects, 0(0B) LOS objects, 47% free, 4MB/8MB, paused 671us total 26.889ms
,08-29 13:12:19.076  1984  2170 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-29 13:12:19.136  1014  1042 D Tethering: interfaceRemoved wlan0
08-29 13:12:19.136  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 13:12:19.256  1014  4809 I art     : Explicit concurrent mark sweep GC freed 52085(2MB) AllocSpace objects, 12(240KB) LOS objects, 33% free, 24MB/36MB, paused 2.563ms total 168.005ms
,08-29 13:12:19.266  1014  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:19.266  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.266  1014  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:19.266  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:19.266  1014  1310 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:19.266  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.266  1014  1310 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:19.266  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:19.286  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:19.286  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.286  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:19.286  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:19.316  1984  2170 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-29 13:12:19.336  1984  2170 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: NO_NETWORK_CONNECTIVITY).  Giving up.
,08-29 13:12:19.346  7104  7130 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-29 13:12:19.346  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-29 13:12:19.346  1014  1042 D Tethering: interfaceRemoved p2p0
08-29 13:12:19.346  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 13:12:19.346  7104  7130 I Babel_SMS: MmsConfig.loadMmsSettings
,08-29 13:12:19.356  7104  7130 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 13:12:19.356  7104  7130 I Babel_SMS: MmsConfig.loadFromDatabase
,08-29 13:12:19.366  7104  7130 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
08-29 13:12:19.366  7104  7130 I Babel_SMS: MmsConfig.loadFromResources
,08-29 13:12:19.366  7104  7130 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-29 13:12:19.376  7104  7130 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,08-29 13:12:19.396  1014  4809 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-29 13:12:19.396  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-29 13:12:19.396  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.396  1014  4809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:19.396  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:12:19.416  7104  7104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:19.416  7104  7104 I Babel_Crash: startup - clean
,08-29 13:12:19.446  1014  4809 I ActivityManager: Killing 6650:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #21
,08-29 13:12:19.456  7000  7000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:12:19.456  7000  7000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:19.456  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:19.456  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:19.456  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:19.456  7000  7000 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:19.456  7000  7101 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:19.466  1014  3937 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 13:12:19.466  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:19.466  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:19.466  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.466  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.476  7133  7133 E Zygote  : MountEmulatedStorage(),
08-29 13:12:19.476  7133  7133 E Zygote  : v2
08-29 13:12:19.476  1014  3937 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7133 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:19.476  7133  7133 I libpersona: KNOX_SDCARD checking this for 10064
08-29 13:12:19.476  7133  7133 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:19.476  7133  7133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:19.486  7133  7133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:19.486  7104  7104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:12:19.486  7133  7133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:19.486  7104  7104 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:12:19.486  7104  7104 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 13:12:19.496  7104  7104 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-29 13:12:19.496  7104  7104 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-29 13:12:19.496  7104  7104 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-29 13:12:19.496  7104  7104 W AudioCapabilities: Unsupported mime audio/x-ima
,08-29 13:12:19.506  7104  7104 W AudioCapabilities: Unsupported mime audio/qcelp
,08-29 13:12:19.506  7104  7104 W AudioCapabilities: Unsupported mime audio/evrc
,08-29 13:12:19.506  7133  7133 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:19.506  7133  7133 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:19.516  7104  7104 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 13:12:19.516  7133  7133 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 13:12:19.516  7104  7104 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 13:12:19.526  7104  7104 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-29 13:12:19.526  7104  7104 W VideoCapabilities: Unsupported mime video/wvc1
,08-29 13:12:19.526  7104  7104 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-29 13:12:19.526  7104  7104 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-29 13:12:19.536  7104  7104 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-29 13:12:19.536  7104  7104 W VideoCapabilities: Unsupported mime video/mp43
,08-29 13:12:19.536  7104  7104 W VideoCapabilities: Unsupported mime video/sorenson
,08-29 13:12:19.536  7133  7133 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:19.546  7133  7133 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 13:12:19.546  7104  7104 W VideoCapabilities: Unsupported mime video/mp4v-esdp,
,08-29 13:12:19.556  7104  7104 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-29 13:12:19.576  7133  7133 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:12:19.576  1014  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 13:12:19.576  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.576  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.576  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.576  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.586  7148  7148 E Zygote  : MountEmulatedStorage(),
08-29 13:12:19.586  7148  7148 E Zygote  : v2
,08-29 13:12:19.586  7148  7148 I libpersona: KNOX_SDCARD checking this for 10065
08-29 13:12:19.586  7148  7148 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:19.586  1014  1504 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7148 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:19.586  1014  1504 I ActivityManager: Killing 6680:com.sec.android.fotaclient/u0a8 (adj 15): empty #21
08-29 13:12:19.586  7148  7148 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:19.586  7148  7148 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:19.596  7148  7148 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:12:19.606  7148  7148 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:19.606  7148  7148 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:19.606  7104  7104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:12:19.606  7104  7104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:12:19.616  7104  7104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:12:19.616  7104  7104 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-29 13:12:19.616  1014  1027 I ActivityManager: Killing 6699:com.samsung.android.sm/1000 (adj 15): empty #21
,08-29 13:12:19.626  7104  7104 I vclib   : onServiceConnected
,08-29 13:12:19.636  7148  7148 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:19.636  1014  1493 I ActivityManager: Killing 6718:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-29 13:12:19.646  1014  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:19.646  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:19.646  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.646  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.646  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:19.646  1602  1602 I Hs20UtilService: Starting #9
,08-29 13:12:19.646  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:19.646  7000  7000 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:12:19.646  7000  7000 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:19.646  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:19.656  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:19.656  7000  7000 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:19.656  7000  7000 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:19.656  7000  7101 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:19.656  1014  4809 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:19.656  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:19.656  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.656  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.656  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:19.656  1602  1602 I Hs20UtilService: Starting #10
,08-29 13:12:19.656  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:19.666  1014  1504 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 13:12:19.666  1014  1504 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.samsung.android.securitylogagent/com.samsung.android.securitylogagent.receivers.NetworkReceiver}
08-29 13:12:19.666  1014  1504 W BroadcastQueue: android.os.TransactionTooLargeException
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 13:12:19.666  1014  1504 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:12:19.666  1014  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-29 13:12:19.666  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.666  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.666  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.666  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.676  7164  7164 E Zygote  : MountEmulatedStorage()
,08-29 13:12:19.676  7164  7164 E Zygote  : v2
08-29 13:12:19.676  1014  1504 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=7164 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:12:19.686  7164  7164 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:19.686  7164  7164 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:19.686  7164  7164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:19.686  7164  7164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:19.686  7164  7164 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:12:19.706  7164  7164 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:19.706  7164  7164 D ActivityThread: Added TimaKeyStore provider,
,08-29 13:12:19.716  1014  1039 W libprocessgroup: failed to open /acct/uid_1000/pid_6718/cgroup.procs: No such file or directory
,08-29 13:12:19.736  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:12:19.736  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 13:12:19.736  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:12:19.736  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:19.746  1014  3937 I ActivityManager: Killing 6749:com.osp.app.signin/u0a36 (adj 15): empty #21
,08-29 13:12:19.746  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.746  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.746  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.756  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.756  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.756  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.756  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.766  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.766  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.766  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.766   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:19.766  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.766  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.766  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.776  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.776  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.776  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.776  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.786  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.786  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.786  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.786  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.796  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.796  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.796  1014  1014 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.796  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-29 13:12:19.806  7000  7000 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:19.806  1014  1534 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 13:12:19.806  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:19.806  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:19.806  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:19.806  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:19.816  7000  7000 D DockEventReceiver: finishStartingService: stopping service
08-29 13:12:19.816  7000  7000 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:19.826  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:19.826  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 13:12:19.826  1014  1534 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-29 13:12:19.836  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.836  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.836  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:19.836  1014  1534 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:19.846  7181  7181 E Zygote  : MountEmulatedStorage()
08-29 13:12:19.846  7181  7181 E Zygote  : v2
08-29 13:12:19.846  7181  7181 I libpersona: KNOX_SDCARD checking this for 1002
08-29 13:12:19.846  7181  7181 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:19.846  7181  7181 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:19.846  1014  1534 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7181 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
08-29 13:12:19.846  7181  7181 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:19.856  7181  7181 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:12:19.876  1014  1535 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:12:19.876  1014  1535 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4311, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:12:19.876  1014  1535 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:12:19.876  1014  1535 D BatteryService: stay LED for fully charged
08-29 13:12:19.876  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 13:12:19.886  1014  1014 I MotionRecognitionService: Plugged
08-29 13:12:19.886  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:12:19.886  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:12:19.886  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:12:19.886  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-29 13:12:19.886  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:12:19.906  7181  7181 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:19.906  7181  7181 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:19.916  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 13:12:19.916  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:19.916  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 13:12:19.916  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 13:12:19.916  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-29 13:12:19.926  7181  7181 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 13:12:19.926  7181  7181 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:19.956  7181  7181 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 13:12:19.986  7181  7181 D BtSettings.ProfileConfig: Adding GattService
,08-29 13:12:19.986  7181  7181 D BtSettings.ProfileConfig: Adding HeadsetService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding HidService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding HealthService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding PanService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding SapService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding SapClientService
08-29 13:12:19.996  7181  7181 D BtSettings.ProfileConfig: Adding HidDevService
,08-29 13:12:19.996  7181  7181 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 13:12:19.996  1014  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 13:12:19.996  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:19.996  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:19.996  1014  1493 D SettingsProvider: selectionArgs: false
08-29 13:12:19.996  1014  1493 D SettingsProvider: selectionArgs: 1002
08-29 13:12:19.996  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:19.996  1014  1493 D SettingsProvider: ret = -1
,08-29 13:12:19.996  1014  4809 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:19.996  1014  4809 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:19.996  1014  4809 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:19.996  1014  4809 D SettingsProvider: selectionArgs: false
,08-29 13:12:19.996  1014  4809 D SettingsProvider: selectionArgs: 1002
08-29 13:12:19.996  1014  4809 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:12:19.996  1014  4809 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1458 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 13:12:20.006  1014  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:20.006  1014  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1458 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1458 D SettingsProvider: selectionArgs: 1002
,08-29 13:12:20.006  1014  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1458 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 13:12:20.006  1014  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:20.006  1014  1094 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1094 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1094 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 13:12:20.006  1014  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:20.006  1014  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1535 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1535 D SettingsProvider: selectionArgs: 1002
,08-29 13:12:20.006  1014  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1535 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 13:12:20.006  1014  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1533 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1533 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1533 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-29 13:12:20.006  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1026 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1026 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1026 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  3937 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 13:12:20.006  1014  3937 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  3937 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  3937 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  3937 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  3937 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  3937 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:20.006  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1491 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1491 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1491 D SettingsProvider: ret = -1
,08-29 13:12:20.006  1014  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:20.006  1014  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.006  1014  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:20.006  1014  1504 D SettingsProvider: selectionArgs: false
08-29 13:12:20.006  1014  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.006  1014  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.006  1014  1504 D SettingsProvider: ret = -1
,08-29 13:12:20.016  1014  1534 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 13:12:20.016  1014  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.016  1014  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:20.016  1014  1534 D SettingsProvider: selectionArgs: false
08-29 13:12:20.016  1014  1534 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.016  1014  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.016  1014  1534 D SettingsProvider: ret = -1
,08-29 13:12:20.016  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 13:12:20.016  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:20.016  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:20.016  1014  1027 D SettingsProvider: selectionArgs: false
08-29 13:12:20.016  1014  1027 D SettingsProvider: selectionArgs: 1002
08-29 13:12:20.016  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:20.016  1014  1027 D SettingsProvider: ret = -1
,08-29 13:12:20.016  1014  4809 I ActivityManager: Killing 6764:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #21
,08-29 13:12:20.026  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:20.026  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:20.026  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.026  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.026  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 13:12:20.026  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:20.036  1984  7197 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 13:12:20.036  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:20.046  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:20.046  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:20.046  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:20.046  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:20.046  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 13:12:20.046  1014  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:20.046  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:20.046  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.046  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:20.046  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:20.056  1602  1602 I Hs20UtilService: Starting #11
,08-29 13:12:20.056  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:20.056  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 13:12:20.056  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:20.056  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:12:20.056  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:20.066  1014  1094 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 13:12:20.066  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.066  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.066  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.066  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.076  7198  7198 E Zygote  : MountEmulatedStorage()
,08-29 13:12:20.076  7198  7198 E Zygote  : v2
08-29 13:12:20.076  7198  7198 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:20.076  7198  7198 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.076  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.076  1014  1094 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-29 13:12:20.076  1014  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:20.086  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.086  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.086  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:20.086  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:20.086  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.096  1984  7197 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 13:12:20.096  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.096  7198  7198 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.126  7198  7198 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,08-29 13:12:20.126  7198  7198 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 13:12:20.126  7198  7198 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 13:12:20.136  7198  7198 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-29 13:12:20.136  7198  7198 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 13:12:20.136  7198  7198 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 13:12:20.136  7198  7198 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:20.146  1014  1534 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 13:12:20.146  1014  1534 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 13:12:20.146  7198  7213 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-29 13:12:20.156  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 13:12:20.156  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.156  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.156  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.156  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.176  7215  7215 E Zygote  : MountEmulatedStorage()
08-29 13:12:20.176  7215  7215 E Zygote  : v2
08-29 13:12:20.176  7215  7215 I libpersona: KNOX_SDCARD checking this for 10001
08-29 13:12:20.176  7215  7215 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.176  7215  7215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.176  7215  7215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.176  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7215 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:20.186  7215  7215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 13:12:20.186  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 13:12:20.186  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.186  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.186  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.186  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.196  7227  7227 E Zygote  : MountEmulatedStorage()
08-29 13:12:20.196  7227  7227 E Zygote  : v2
08-29 13:12:20.196  7227  7227 I libpersona: KNOX_SDCARD checking this for 10031
08-29 13:12:20.196  7227  7227 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:20.196  7227  7227 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:12:20.206  7227  7227 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.206  7227  7227 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 13:12:20.206  1014  1026 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7227 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,08-29 13:12:20.206  7215  7215 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:20.216  7215  7215 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.216  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-29 13:12:20.216  1783  1783 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 13:12:20.216  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.216  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.216  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.216  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.236  7242  7242 E Zygote  : MountEmulatedStorage()
,08-29 13:12:20.236  7242  7242 E Zygote  : v2
08-29 13:12:20.236  7242  7242 I libpersona: KNOX_SDCARD checking this for 10121
08-29 13:12:20.236  7242  7242 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.236  7242  7242 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.236  7242  7242 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.236  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7242 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-29 13:12:20.236  7242  7242 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.246  7227  7227 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.246  7227  7227 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.256  2477  2489 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 7
,08-29 13:12:20.256  1783  1783 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,08-29 13:12:20.266  1783  1783 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,08-29 13:12:20.266  1783  1783 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-29 13:12:20.266  7242  7242 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.266  1783  1783 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
08-29 13:12:20.266  7242  7242 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.276  1783  1783 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 13:12:20.276  1783  1783 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 13:12:20.276  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-29 13:12:20.276  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.276  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.276  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.276  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.286  7242  7242 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:20.286  7242  7242 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:12:20.286  7242  7242 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:20.296  7260  7260 E Zygote  : MountEmulatedStorage()
,08-29 13:12:20.296  7260  7260 E Zygote  : v2
08-29 13:12:20.296  7260  7260 I libpersona: KNOX_SDCARD checking this for 10077
08-29 13:12:20.296  7260  7260 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.296  7260  7260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.296  7260  7260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:20.296  1014  1491 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7260 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:20.306  7260  7260 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.316   305   305 I art     : Explicit concurrent mark sweep GC freed 8710(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 22.143ms
,08-29 13:12:20.316  7242  7242 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:20.326  7260  7260 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:20.326  7227  7227 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
08-29 13:12:20.326  7260  7260 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.336  1014  3937 I ActivityManager: Killing 6781:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #21
,08-29 13:12:20.336   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 578us total 16.699ms
,08-29 13:12:20.346  7242  7242 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 13:12:20.346  7242  7242 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 13:12:20.356  1014  1535 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 13:12:20.356   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 600us total 16.697ms
08-29 13:12:20.356  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.356  2830  7275 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-29 13:12:20.356  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.356  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.356  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.356  2830  7275 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-29 13:12:20.366  2830  7275 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-29 13:12:20.366  2830  7275 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-29 13:12:20.366  2830  7275 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-29 13:12:20.376  7278  7278 E Zygote  : MountEmulatedStorage(),
08-29 13:12:20.376  7278  7278 E Zygote  : v2
08-29 13:12:20.376  7278  7278 I libpersona: KNOX_SDCARD checking this for 10032
08-29 13:12:20.376  7278  7278 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:12:20.376  7278  7278 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.376  1014  1535 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7278 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:20.376  1014  1535 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-29 13:12:20.386  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.386  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.386  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.386  1014  1535 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.386  7278  7278 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.386  7278  7278 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.396  7287  7287 E Zygote  : MountEmulatedStorage(),
08-29 13:12:20.396  7287  7287 E Zygote  : v2
08-29 13:12:20.396  7287  7287 I libpersona: KNOX_SDCARD checking this for 10141,
08-29 13:12:20.396  7287  7287 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.396  7287  7287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.406  1014  1535 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7287 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-29 13:12:20.406  1014  1535 I ActivityManager: Killing 6802:com.qualcomm.timeservice/1000 (adj 15): empty #21
,08-29 13:12:20.406  7287  7287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:20.406  7287  7287 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.416  7278  7278 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.416  7278  7278 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.426  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-29 13:12:20.426  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.426  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.426  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.426  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.436  7287  7287 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.436  7287  7287 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.446  7308  7308 E Zygote  : MountEmulatedStorage()
08-29 13:12:20.446  7308  7308 E Zygote  : v2
08-29 13:12:20.446  7308  7308 I libpersona: KNOX_SDCARD checking this for 1000
,08-29 13:12:20.446  7308  7308 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:20.446  1014  1026 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7308 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
08-29 13:12:20.446  7308  7308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.446  1014  1026 I ActivityManager: Killing 6733:com.android.providers.calendar/u0a37 (adj 15): empty #21
08-29 13:12:20.446  7308  7308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:20.456  7308  7308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.476  7308  7308 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.476  7308  7308 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.476  7287  7287 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-29 13:12:20.476  7287  7287 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:20.476  7287  7287 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:20.476  7287  7287 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 13:12:20.476  7278  7323 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-29 13:12:20.476  7278  7323 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 13:12:20.486  7278  7278 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
08-29 13:12:20.486  1014  4809 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-29 13:12:20.486  7278  7323 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:12:20.486  1014  4809 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.486  7278  7323 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:12:20.486  1014  4809 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.486  7278  7323 D SPPClientService: ============PushLog. stop!
08-29 13:12:20.486  1014  4809 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.486  1014  4809 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.506  7326  7326 E Zygote  : MountEmulatedStorage(),
08-29 13:12:20.506  7326  7326 E Zygote  : v2
08-29 13:12:20.506  7326  7326 I libpersona: KNOX_SDCARD checking this for 10036
08-29 13:12:20.506  7326  7326 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.506  7326  7326 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.506  7326  7326 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.506  1014  4809 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7326 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:20.506  7326  7326 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-29 13:12:20.506  1014  4809 I ActivityManager: Killing 6168:com.android.mms/u0a41 (adj 15): empty #21
,08-29 13:12:20.516  1014  1026 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-29 13:12:20.516  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.516  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.516  1014  1026 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 13:12:20.516  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-29 13:12:20.526  7308  7308 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-29 13:12:20.526  7326  7326 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.526  7326  7326 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.536  1014  3937 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.546  1014  1533 D CountryDetector: No listener is left
,08-29 13:12:20.556  1014  1310 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.586  7326  7326 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@4aba439
08-29 13:12:20.586  7278  7334 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-29 13:12:20.596  7326  7326 I SA      : [SSP] onCreated
,08-29 13:12:20.606  1014  1310 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.616  1014  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.626  7326  7326 I SA      : [TPM] There is no property file
,08-29 13:12:20.626  7326  7326 I SA      : [SCU] isHaveSA() - false
,08-29 13:12:20.636  7326  7326 I SA      : [TPM] getModelProperty : null
08-29 13:12:20.636  7326  7326 I SA      : [TPM] getCSCProperty : null
,08-29 13:12:20.636  7326  7326 I SA      : [DM] FLOATING AMOLED FEATURE: true
,08-29 13:12:20.636  7326  7326 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-29 13:12:20.636  7326  7326 I SA      : [DM] TFT FEATURE: false
,08-29 13:12:20.646  7326  7326 I SA      : [DM] init START
,08-29 13:12:20.646  7326  7326 I SA      : [DM] This device is not a Vodafone
,08-29 13:12:20.656  7326  7326 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-29 13:12:20.666  7308  7308 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-29 13:12:20.666  7326  7326 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-29 13:12:20.666  1014  1310 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 13:12:20.666  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
,08-29 13:12:20.666  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
,08-29 13:12:20.666  1014  1310 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:20.666  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
,08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-29 13:12:20.666  7326  7326 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-29 13:12:20.676  1014  1533 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-29 13:12:20.676  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-29 13:12:20.676  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-29 13:12:20.676  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75)
08-29 13:12:20.676  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.676  7326  7326 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
08-29 13:12:20.676  7308  7308 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,08-29 13:12:20.676  7308  7308 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:20.676  7308  7308 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 13:12:20.676  7308  7308 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-29 13:12:20.676  7308  7308 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-29 13:12:20.686  7326  7326 I SA      : [SCU] isHaveSA() - false
08-29 13:12:20.686  7326  7326 I SA      : support phone number id : false
08-29 13:12:20.686  7326  7326 I SA      : [DM] Supports Ref Jpn : true
,08-29 13:12:20.686  7326  7326 I SA      : [DM] init END
08-29 13:12:20.686  7326  7326 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
,08-29 13:12:20.686  7326  7326 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-29 13:12:20.686  7326  7326 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 13:12:20.696  7357  7357 E Zygote  : MountEmulatedStorage(),
08-29 13:12:20.696  7357  7357 I libpersona: KNOX_SDCARD checking this for 10068
08-29 13:12:20.696  7357  7357 E Zygote  : v2
08-29 13:12:20.696  7357  7357 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:20.696  7357  7357 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:20.696  7326  7326 I SA      : [SLFUCHKMGR] constructor called
,08-29 13:12:20.696  1014  1493 D RCPManagerService: exchangeData() failure , invalid userId
08-29 13:12:20.696  7357  7357 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:20.696  7357  7357 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.696  1014  1533 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7357 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,08-29 13:12:20.696  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-29 13:12:20.706  1014  3937 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.706  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.706  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.706  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.706  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.706  7326  7326 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-29 13:12:20.716  7326  7326 I SA      : [OR] == isSIMCardReady false ==
,08-29 13:12:20.716  7326  7326 I SA      : [SCU] == networkStateCheck == false
08-29 13:12:20.716  7326  7326 I SA      : [OR] onReceive END
,08-29 13:12:20.716  7357  7357 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.716  7374  7374 E Zygote  : MountEmulatedStorage()
08-29 13:12:20.716  7374  7374 E Zygote  : v2
08-29 13:12:20.716  7374  7374 I libpersona: KNOX_SDCARD checking this for 10110
08-29 13:12:20.716  7374  7374 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.716  7374  7374 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.726  7357  7357 D ActivityThread: Added TimaKeyStore provider,
,08-29 13:12:20.726  7374  7374 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:20.726  1014  1027 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7374 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:20.726  7374  7374 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.726  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-29 13:12:20.736  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.736  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.736  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.736  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.746  7384  7384 E Zygote  : MountEmulatedStorage(),
08-29 13:12:20.746  7384  7384 E Zygote  : v2
08-29 13:12:20.746  7384  7384 I libpersona: KNOX_SDCARD checking this for 10008
08-29 13:12:20.746  7384  7384 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:20.746  7384  7384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:20.746  1014  1027 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7384 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:20.746  7374  7374 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:20.746  1014  1027 I ActivityManager: Killing 6826:com.sec.esdk.elm/u0a90 (adj 15): empty #21
,08-29 13:12:20.756  7374  7374 D ActivityThread: Added TimaKeyStore provider,
08-29 13:12:20.756  1014  1027 I ActivityManager: Killing 6843:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
,08-29 13:12:20.756  7384  7384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:20.756  7384  7384 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-29 13:12:20.766  1014  1026 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 13:12:20.766  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.766  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:20.766  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:20.766  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:20.766  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:12:20.766   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:20.766  7104  7355 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-29 13:12:20.786  7384  7384 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.786  7384  7384 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:20.786  1014  1504 I ActivityManager: Killing 6660:com.android.calendar/u0a131 (adj 15): empty #21
,08-29 13:12:20.796  1014  1493 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.806  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:20.806  7357  7357 D BadgeProvider: onCreate
,08-29 13:12:20.806  7357  7357 D BadgeProvider: DatabaseHelper
,08-29 13:12:20.816  1014  1094 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-29 13:12:20.816  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.816  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.816  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:20.816  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:20.826  7357  7367 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-29 13:12:20.836  7404  7404 E Zygote  : MountEmulatedStorage()
08-29 13:12:20.836  7404  7404 E Zygote  : v2
08-29 13:12:20.836  7404  7404 I libpersona: KNOX_SDCARD checking this for 10009
08-29 13:12:20.836  7404  7404 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:20.836  7404  7404 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:20.836  7404  7404 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:12:20.836  7404  7404 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-29 13:12:20.846  1014  1094 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7404 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 13:12:20.846  1014  1094 I ActivityManager: Killing 6114:com.android.defcontainer/u0a3 (adj 15): empty #21
08-29 13:12:20.846  1014  1094 I ActivityManager: Killing 6858:com.google.android.gms:car/u0a11 (adj 15): empty #22
,08-29 13:12:20.846  1014  1533 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 13:12:20.846  1014  1533 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:12:20.846  1014  1533 D SecContentProvider2: mCursor = null
08-29 13:12:20.846  1014  1533 D WifiService: setWifiEnabled: true pid=6916, uid=10171
08-29 13:12:20.846  1014  1533 W ActivityManager: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:20.846  1014  1533 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:12:20.846  1014  1533 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:20.846  1014  1533 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:12:20.846  1014  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:12:20.846  1014  1533 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:12:20.846  1014  1533 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:12:20.846  1014  1533 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-29 13:12:20.846  1014  1533 D SettingsProvider: name = wifi_on
,08-29 13:12:20.856  1014  1126 E WifiHW  : ##################### set firmware type 0 #####################
,08-29 13:12:20.886  7404  7404 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:20.886  7404  7404 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:20.886  7357  7370 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-29 13:12:20.886  7357  7370 D BadgeProvider: sendNotify, [notify] : null
08-29 13:12:20.886  7357  7370 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-29 13:12:20.886  7357  7370 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-29 13:12:20.886  7357  7370 D BadgeProvider: update, [UpdateCount] : 1
,08-29 13:12:20.896  1494  1494 D Launcher.Model: reloadBadges entered.
,08-29 13:12:20.936  1014  1504 I ActivityManager: Killing 6465:com.android.vending/u0a26 (adj 15): empty #21
,08-29 13:12:20.936  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 13:12:20 GMT+02:00 2016
,08-29 13:12:20.946  1014  1535 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 13:12:20.946  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.946  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:20.946  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:20.946  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 13:12:20.946  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:12:20.956  2953  2953 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 13:12:20.956  2953  2953 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 13:12:20.966  2953  2953 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 13:12:20.966  2953  7423 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 13:12:20.966  2953  7423 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:20.976  2953  7423 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,08-29 13:12:20.976  2953  7423 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
,08-29 13:12:20.976  2953  2953 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 13:12:20.986  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.986  1014  1094 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-29 13:12:20.986  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-29 13:12:20.996  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-29 13:12:21.036  1014  1458 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:12:21.056  1014  1458 I ActivityManager: Killing 6486:com.google.process.gapps/u0a11 (adj 15): empty #21
,08-29 13:12:21.056  1014  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:21.056  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 13:12:21.056  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:21.056  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:21.056  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:21.076  4756  7424 I iu.SyncManager: SYNC; picasa accounts
,08-29 13:12:21.076  4756  4756 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-29 13:12:21.136  1014  1039 W libprocessgroup: failed to kill pid 6486: No such process
,08-29 13:12:21.186   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 13:12:21.186   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:21.186  7374  7434 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 13:12:21.186   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/,
08-29 13:12:21.186   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:21.196  7374  7434 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 13:12:21.196   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-29 13:12:21.196   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:21.206  7374  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-29 13:12:21.206   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-29 13:12:21.206   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:21.206  7374  7435 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-29 13:12:21.216  7374  7374 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-29 13:12:21.216  7374  7374 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-29 13:12:21.216  7374  7374 I GAv4    :   adb logcat -s GAv4
,08-29 13:12:21.236  7374  7374 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:21.236  1014  1493 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:12:21.246  7374  7374 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:21.256  7374  7437 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-29 13:12:21.286  1014  1042 D Tethering: interfaceAdded wlan0
,08-29 13:12:21.296  1014  1129 E Tethering: No numeric data
,08-29 13:12:21.296  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-29 13:12:21.296  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:21.296  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:21.296  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:21.296  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:21.296  1014  1129 D Tethering: clearTetheredNotification()
,08-29 13:12:21.296  1014  1123 V NetworkStats: performPollLocked() took 3ms
,08-29 13:12:21.296  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:21.296  1176  1176 D HotspotTile: updateTetherState():false, false
,08-29 13:12:21.296  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:21.296  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:21.296  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:21.306  1014  1129 D Tethering: InitialState.processMessage what=4,
08-29 13:12:21.306  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:21.306  1014  1129 E Tethering: No numeric data,
08-29 13:12:21.306  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:21.306  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:21.306  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-29 13:12:21.306  1014  1129 D Tethering: clearTetheredNotification(),
08-29 13:12:21.306  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:21.306  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:21.306  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
08-29 13:12:21.306  1014  1042 D Tethering: interfaceAdded p2p0
08-29 13:12:21.306  1176  1176 D HotspotTile: updateTetherState():false, false
08-29 13:12:21.306  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:21.306  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:21.306  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 13:12:21.306  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:21.306  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 13:12:21.306  1014  1123 V NetworkStats: performPollLocked() took 4ms
,08-29 13:12:21.306  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:21.306  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:21.316  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:21.316  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:21.316   277   998 I WifiHW  : wifi_change_fw_path(): fwpath = sta,
08-29 13:12:21.316   277   998 D SoftapController: Softap fwReload - Ok
,08-29 13:12:21.316   277   998 D CommandListener: Setting iface cfg,
08-29 13:12:21.316   277   998 D CommandListener: Trying to bring down wlan0
,08-29 13:12:21.316   277   998 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:21.326  1014  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 13:12:21.376  1014  1533 D ActivityManager: getContentProviderImpl callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gsf
,08-29 13:12:21.376  7440  7440 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 13:12:21.376  7440  7440 I wpa_supplicant: Successfully initialized wpa_supplicant
08-29 13:12:21.376  7440  7440 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 13:12:21.376  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:21.376  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:21.376  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:21.376  1014  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:21.396  7442  7442 E Zygote  : MountEmulatedStorage(),
08-29 13:12:21.396  7442  7442 E Zygote  : v2
08-29 13:12:21.396  7442  7442 I libpersona: KNOX_SDCARD checking this for 10011
08-29 13:12:21.396  7442  7442 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:21.396  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:21.396  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:21.396  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:21.396  7440  7440 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-29 13:12:21.406   394   394 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7440
08-29 13:12:21.406   394   394 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-29 13:12:21.406  7440  7440 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
08-29 13:12:21.406  7440  7440 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:21.406  7440  7440 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-29 13:12:21.406  7440  7440 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 13:12:21.406   394   394 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 7440
08-29 13:12:21.406   394   394 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
,08-29 13:12:21.406  1014  1533 I ActivityManager: Start proc com.google.process.gapps for content provider com.google.android.gsf/.gservices.GservicesProvider: pid=7442 uid=10011 gids={50011, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-29 13:12:21.416  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:21.416  7442  7442 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:21.426  1014  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 13:12:21.426  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:21.426  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:21.426  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:21.426  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:21.426  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:21.426  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:21.426  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:21.436  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:12:21.426  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 13:12:21.436  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:21.436  1176  1176 D HotspotTile: onReceive : 2, 0
,08-29 13:12:21.436  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:21.436  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:21.456  7442  7442 I GservicesProvider: Gservices pushing to system: true; secure/global: true
,08-29 13:12:21.526  7442  7442 I GoogleHttpClient: GMS http client unavailable, use old client
,08-29 13:12:21.556  7442  7442 I GoogleHttpClient: GMS http client unavailable, use old client
,08-29 13:12:21.576  1984  2170 E ctxmgr  : [BaseServerTask]Failed network request due to no network connectivity.
,08-29 13:12:21.576  1984  2170 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = 1
,08-29 13:12:21.586   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-29 13:12:21.596  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-29 13:12:21.636  7440  7440 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:12:21.636  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 13:12:21.656  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 13:12:21.656   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7440
08-29 13:12:21.656   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:12:21.656  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 13:12:21.656  7440  7440 I wpa_supplicant: ssSupport state is = 1
,08-29 13:12:21.656  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-29 13:12:21.656  7440  7440 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:21.656  7440  7440 E wpa_supplicant: SIM READ ERROR
08-29 13:12:21.656  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:21.656  7440  7440 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:21.656  7440  7440 E wpa_supplicant: SIM READ ERROR
08-29 13:12:21.656  7440  7440 I wpa_supplicant: Blacklist: Clear (all) ,
08-29 13:12:21.656  7440  7440 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:12:21.656  7440  7440 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 13:12:21.656  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:21.656  7440  7440 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
08-29 13:12:21.656  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:21.656  7440  7440 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:21.656  7440  7440 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:12:21.666  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 13:12:21.666  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:21.666  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:21.686  1014  1493 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:21.686  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:21.686  1014  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:21.686  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-29 13:12:21.736  7374  7374 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,08-29 13:12:21.756  7374  7374 I cr.library_loader: Time to load native libraries: 2 ms (timestamps 8158-8160)
,08-29 13:12:21.756  7374  7374 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 13:12:21.756  7374  7374 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b1d97d8}
,08-29 13:12:21.756  7374  7374 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-29 13:12:21.756  7374  7374 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-29 13:12:21.766   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:21.776  7440  7440 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-29 13:12:21.786  7374  7374 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-29 13:12:21.786  7374  7374 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-29 13:12:21.786  7374  7374 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-29 13:12:21.796   287   287 E SMD     : DCD OFF
,08-29 13:12:21.806  7374  7374 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-29 13:12:21.806  7374  7374 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-29 13:12:21.806  7374  7374 I Adreno-EGL: Build Date: 04/06/15 Mon
08-29 13:12:21.806  7374  7374 I Adreno-EGL: Local Branch: 
08-29 13:12:21.806  7374  7374 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-29 13:12:21.806  7374  7374 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-29 13:12:21.806  7374  7374 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-29 13:12:21.866  7374  7489 W cr.media: Requires BLUETOOTH permission
,08-29 13:12:21.876  7374  7374 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-29 13:12:21.886  7374  7374 I NSApplication: Starting up...
,08-29 13:12:21.886  1014  1534 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:12:21.896  1014  1026 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,08-29 13:12:21.896  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-29 13:12:21.896  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:21.896  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:21.896  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:21.906  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:21.906  7442  7461 E SQLiteLog: (283) recovered 900 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,08-29 13:12:21.916  7494  7494 E Zygote  : MountEmulatedStorage()
08-29 13:12:21.916  7494  7494 I libpersona: KNOX_SDCARD checking this for 10117
08-29 13:12:21.916  7494  7494 E Zygote  : v2
08-29 13:12:21.916  7494  7494 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:21.916  7494  7494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:21.916  1014  1027 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7494 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-29 13:12:21.926  7494  7494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:21.926  1014  1027 I ActivityManager: Killing 7148:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
08-29 13:12:21.926  1014  1027 I ActivityManager: Killing 7133:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #22
,08-29 13:12:21.926  7494  7494 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:21.946  7494  7494 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:21.946  7494  7494 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:21.966  7494  7494 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:21.986  7440  7440 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-29 13:12:21.986  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 13:12:22.006  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage,
,08-29 13:12:22.006   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7440,
08-29 13:12:22.006   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-29 13:12:22.006  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
,08-29 13:12:22.006  7440  7440 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:22.006  7440  7440 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:12:22.006  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-29 13:12:22.016  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-29 13:12:22.026   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7440
08-29 13:12:22.026   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-29 13:12:22.026  7440  7440 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-29 13:12:22.026  7440  7440 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:22.026  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:22.026  7440  7440 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-29 13:12:22.026  7440  7440 E wpa_supplicant: SIM READ ERROR
08-29 13:12:22.026  7440  7440 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:12:22.026  7440  7440 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 13:12:22.026  7440  7440 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:12:22.026  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:22.026  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 13:12:22.026  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:22.026  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:22.026  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:22.026  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:22.096  7440  7440 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-29 13:12:22.096  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 13:12:22.156  7440  7440 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-29 13:12:22.156  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 13:12:22.156  7440  7440 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 13:12:22.156  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-29 13:12:22.166  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-29 13:12:22.166  7440  7440 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 13:12:22.166  7440  7440 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 13:12:22.166  7440  7440 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:22.166  7440  7440 E wpa_supplicant: SIM READ ERROR,
08-29 13:12:22.166  7440  7440 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:12:22.196  7440  7440 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-29 13:12:22.206  7440  7440 I wpa_supplicant: Skip scan - bUseNetwork false,
,08-29 13:12:22.206  1014  1126 D WifiConfigStore: Loading config and enabling all networks ,
,08-29 13:12:22.216  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:22.216  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:22.216  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:22.216  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:22.216  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:22.216  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:22.216  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:22.216  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 13:12:22.216  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-29 13:12:22.216  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:12:22.216  1176  1176 D HotspotTile: onReceive : 3, 0
,08-29 13:12:22.216  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:22.216  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:22.216  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:22.216  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:22.216  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:22.226  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:22.226  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:22.226  1014  1126 E WifiConfigStore: Not a HS20
,08-29 13:12:22.226  1014  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 13:12:22.236  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-29 13:12:22.236  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 13:12:22.236  7440  7440 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 13:12:22.236  7440  7440 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-29 13:12:22.236  7440  7440 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:12:22.236  7440  7440 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 13:12:22.236  7440  7440 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 13:12:22.236  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 13:12:22.236  7440  7440 I wpa_supplicant: First Scan Start
,08-29 13:12:22.236  7440  7440 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-29 13:12:22.236  1014  1126 D WifiNative-wlan0: Setting external_sim to 1
,08-29 13:12:22.236  1014  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:22.236  1014  1126 I WifiNative-HAL: startHal
08-29 13:12:22.236  1014  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d43588c
08-29 13:12:22.236  1014  1126 I WifiNative-HAL: Could not start hal
,08-29 13:12:22.236  7104  7104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 13:12:22.236  1014  1126 E WifiNative-wlan0: do suspend true
,08-29 13:12:22.246  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-29 13:12:22.246  1014  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 13:12:22.246  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,08-29 13:12:22.246  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:22.246  1014  1148 I WifiNative-HAL: startHal
08-29 13:12:22.246  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e7e99bc
08-29 13:12:22.246  1014  1148 I WifiNative-HAL: Could not start hal
08-29 13:12:22.246  1014  1148 E WifiScanningService: could not start HAL
,08-29 13:12:22.246   277   998 D CommandListener: Setting iface cfg
,08-29 13:12:22.246   277   998 D CommandListener: Trying to bring up p2p0
08-29 13:12:22.246  7440  7440 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:12:22.246  1014  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-29 13:12:22.246  1014  1125 D WifiP2pService: P2pEnablingState
08-29 13:12:22.246  7440  7440 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:12:22.246  1014  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
08-29 13:12:22.246  1014  1125 D WifiP2pService: P2p socket connection successful
08-29 13:12:22.246  1014  1014 D RttService: SCAN_AVAILABLE : 3
08-29 13:12:22.246  1014  1125 D WifiP2pService: P2pEnabledState
08-29 13:12:22.256  1014  1149 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:22.256  7440  7440 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands,
08-29 13:12:22.256  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-29 13:12:22.256  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:22.256  1014  1126 E WifiStateMachine: Failed to set frequency band 0
08-29 13:12:22.256  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-29 13:12:22.256  1014  1126 D SecContentProvider2: mCursor = null
08-29 13:12:22.256  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-29 13:12:22.256  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 13:12:22.256  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:22.256  1014  1045 D WifiDisplayController: disconnect
08-29 13:12:22.256  1014  1045 D WifiDisplayController: updateConnection
08-29 13:12:22.256  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false,
,08-29 13:12:22.256  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:22.256  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:12:22.256  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:22.266  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:12:22.266  1014  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:12:22.266  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:12:22.266  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress
,08-29 13:12:22.266  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
08-29 13:12:22.266  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-29 13:12:22.266  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:12:22.266  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:22.266  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:12:22.266  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  secondary type: null
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  wps: 0
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  grpcapab: 0
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  devcapab: 0
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  status: 3
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  wfdInfo: null
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-29 13:12:22.266  1014  1045 D WifiDisplayController:  SConnectInfo : null
08-29 13:12:22.266  1014  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-29 13:12:22.296  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:12:22.296  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:22.296  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:22.326  1014  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 13:12:22.326  1014  1125 D WifiP2pService: InactiveState
,08-29 13:12:22.326  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
08-29 13:12:22.326  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:12:22.326  7440  7440 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:12:22.326  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
,08-29 13:12:22.326  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:12:22.346  1014  1491 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-29 13:12:22.346  1014  1491 I ActivityManager: Killing 7000:com.android.settings/1000 (adj 15): empty #21
,08-29 13:12:22.356  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:22.356  1014  1458 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:22.356  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:22.356  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:22.356  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:22.356  1602  1602 I Hs20UtilService: Starting #12
,08-29 13:12:22.356  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:22.366  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 13:12:22.366  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:22.366  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:12:22.366  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:22.376  1014  1310 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:12:22.376  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:22.376  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:22.376  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:22.376  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:22.376  1602  1602 I Hs20UtilService: Starting #13
,08-29 13:12:22.376  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:22.376  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-29 13:12:22.376  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:12:22.376  1014  1126 E WifiNative-wlan0: invaild command id : 215
,08-29 13:12:22.386  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:12:22.386  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:22.386  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:12:22.386  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:22.396  1014  1493 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 13:12:22.396  1014  1493 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.settings/com.android.settings.nearby.MountReceiver}
08-29 13:12:22.396  1014  1493 W BroadcastQueue: android.os.TransactionTooLargeException
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20499)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3280)
08-29 13:12:22.396  1014  1493 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:12:22.396  1014  1493 D ActivityManager: startProcessLocked calleePkgName: com.android.settings, hostingType: broadcast
,08-29 13:12:22.396  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.396  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:22.396  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.396  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.416  1014  1493 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.nearby.MountReceiver: pid=7519 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:22.416  7519  7519 E Zygote  : MountEmulatedStorage()
,08-29 13:12:22.416  7519  7519 E Zygote  : v2
08-29 13:12:22.416  7519  7519 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:22.416  7519  7519 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:22.416  7519  7519 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:22.416  7519  7519 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:22.416  7519  7519 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:22.436   305   305 I art     : Explicit concurrent mark sweep GC freed 8722(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 746us total 25.160ms,
,08-29 13:12:22.436  7519  7519 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:22.446  7519  7519 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:22.456   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 574us total 16.569ms
,08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:22.456  7519  7519 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:22.456  1014  1039 W libprocessgroup: failed to open /acct/uid_1000/pid_7000/cgroup.procs: No such file or directory
,08-29 13:12:22.476   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 662us total 16.362ms
,08-29 13:12:22.486  7519  7519 D MySettingsProvider: DatabaseHelper(Context context):DATABASE_VERSION=1
,08-29 13:12:22.486  7519  7519 E SQLiteLog: (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,08-29 13:12:22.486  7519  7519 D MySettingsProvider: onCreate():(mDB == null)? false:true  =true
,08-29 13:12:22.516  7519  7519 D NearbySettings: MountReceiver.onReceive - Create HandlerThread
,08-29 13:12:22.516  7519  7519 D NearbySettings: MountReceiver.onReceive - Start HandlerThread
08-29 13:12:22.516  7519  7519 D NearbySettings: MountReceiver.onReceive - Create mPrefHandler
,08-29 13:12:22.516  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:12:22.516  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:22.516  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:22.526  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:12:22.526  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:22.526  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:22.526  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:22.526  1014  1458 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-29 13:12:22.526  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.526  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:22.526  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.526  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.536  7540  7540 E Zygote  : MountEmulatedStorage(),
,08-29 13:12:22.536  7540  7540 E Zygote  : v2
08-29 13:12:22.536  7540  7540 I libpersona: KNOX_SDCARD checking this for 10064,
08-29 13:12:22.536  7540  7540 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:22.546  7540  7540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:22.546  1014  1458 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=7540 uid=10064 gids={50064, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-29 13:12:22.546  1014  1458 I ActivityManager: Killing 7028:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 13:12:22.546  7540  7540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:22.546  7540  7540 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:22.576  7540  7540 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:22.576  7540  7540 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:22.586  7540  7540 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 13:12:22.596  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:22.606  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-29 13:12:22.636  7540  7540 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:12:22.636  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-29 13:12:22.636  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.636  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:22.636  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.636  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:22.646  7555  7555 E Zygote  : MountEmulatedStorage(),
08-29 13:12:22.656  7555  7555 E Zygote  : v2
,08-29 13:12:22.656  7555  7555 I libpersona: KNOX_SDCARD checking this for 10065
08-29 13:12:22.656  7555  7555 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:12:22.656  7555  7555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:22.656  1014  1027 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7555 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:22.656  1014  1027 I ActivityManager: Killing 7181:com.android.bluetooth/1002 (adj 15): empty #21
08-29 13:12:22.656  7555  7555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:22.656  7555  7555 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:22.676  7555  7555 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:22.676  7555  7555 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:22.706  7555  7555 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:22.706  1014  1535 I ActivityManager: Killing 7048:com.google.android.apps.maps/u0a105 (adj 15): empty #21
,08-29 13:12:22.766   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-29 13:12:23.456  7440  7440 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-29 13:12:23.456  7440  7440 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 13:12:23.456  7440  7440 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-29 13:12:23.456  7440  7440 I wpa_supplicant: Trying to associate with  'G700'
08-29 13:12:23.456  7440  7440 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-29 13:12:23.456  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,08-29 13:12:23.466  1014  7513 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700',
,08-29 13:12:23.486  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:23.486  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:23.586  7440  7440 E wpa_supplicant: Cmd 35605 not handled
,08-29 13:12:23.586  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:23.586  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:23.586  7440  7440 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:23.586  7440  7440 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
08-29 13:12:23.586  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:12:23.586  7440  7440 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 13:12:23.586  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-29 13:12:23.586  7440  7440 I wpa_supplicant: Associated with F4.99.3E,
,08-29 13:12:23.586  7440  7440 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:23.586  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
,08-29 13:12:23.586  7440  7440 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-29 13:12:23.586  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-29 13:12:23.586  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-29 13:12:23.586  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:12:23.586  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:23.586  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:23.586  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:23.586  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:23.586  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:12:23.586  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 13:12:23.596  1014  1129 E Tethering: No numeric data
08-29 13:12:23.596  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:12:23.596  1014  1129 D Tethering: clearTetheredNotification()
08-29 13:12:23.596  7440  7440 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:23.596  7440  7440 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 13:12:23.596  7440  7440 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-29 13:12:23.596  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:23.596  7440  7440 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:12:23.596  7440  7440 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-29 13:12:23.596  7440  7440 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 13:12:23.596  7440  7440 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 13:12:23.596  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:23.596  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:12:23.596  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 13:12:23.606  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:23.606  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:23.606  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:12:23.606  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:23.606  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:23.606  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:23.606  1176  1176 D HotspotTile: updateTetherState():false, false
,08-29 13:12:23.606  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:23.606  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:23.606  1014  1123 V NetworkStats: performPollLocked() took 8ms
08-29 13:12:23.606  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:23.616  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:23.616  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:23.616  1014  1126 D WifiNative-wlan0: callSECApiVoid - ID [50],
,08-29 13:12:23.616  1014  1126 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-29 13:12:23.626  1014  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 13:12:23.626  1014  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 13:12:23.626  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:23.626  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 13:12:23.626  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:23.626  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:12:23.626  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.626  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.626  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.626  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:23.636  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
08-29 13:12:23.636  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:12:23.636  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:23.636  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:23.636  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:23.636  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:23.636  1602  1602 I Hs20UtilService: Starting #14
,08-29 13:12:23.636  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:23.646  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:23.646  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
08-29 13:12:23.646  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:23.646  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:23.656  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:23.656  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 13:12:23.656  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:12:23.656  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:23.656   277   998 D CommandListener: Setting iface cfg
,08-29 13:12:23.666  1014  1126 E WifiStateMachine: Start Dhcp Watchdog 2
,08-29 13:12:23.666  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:12:23.666  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:23.666  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:12:23.666  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:23.676  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
,08-29 13:12:23.676  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:23.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:12:23.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:23.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:23.676  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:23.686  1014  1126 E WifiNative-wlan0: do suspend false
,08-29 13:12:23.686  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:12:23.696  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:23.696  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:23.696  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:12:23.856  1014  3937 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:12:23.856  1014  3937 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:12:23.856  1014  3937 D SecContentProvider2: mCursor = null
,08-29 13:12:23.866  1014  3937 D WifiService: setWifiEnabled: false pid=6916, uid=10171
,08-29 13:12:23.866  1014  3937 D SettingsProvider: name = wifi_on
,08-29 13:12:23.876  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-29 13:12:23.886  1014  1126 E WifiNative-wlan0: do suspend true,
,08-29 13:12:23.916   277   998 D CommandListener: Clearing all IP addresses on wlan0,
,08-29 13:12:23.916  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
08-29 13:12:23.916  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:23.916  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
08-29 13:12:23.916  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:23.916  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 13:12:23.916  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:23.916  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-29 13:12:23.916  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-29 13:12:23.926  1014  1125 D WifiP2pService: InactiveState{ what=131204 }
08-29 13:12:23.916  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
08-29 13:12:23.926  1014  1125 D WifiP2pService: P2pEnabledState{ what=131204 }
08-29 13:12:23.916   277   998 E Netd    : no such netId 503
08-29 13:12:23.926  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-29 13:12:23.916  1014  1126 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-29 13:12:23.926  1014  1128 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '79 network destroy 503' failed with '400 79 destroyNetwork() failed (Machine is not on the network)'
08-29 13:12:23.926  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.926  1014  1128 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
08-29 13:12:23.926  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.926  1014  1128 V NetworkStats: updateIfacesLocked()
08-29 13:12:23.926  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.926  1014  1128 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:23.926  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.926  7573  7573 I dhcpcd  : version 5.5.6 starting
08-29 13:12:23.926  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 13:12:23.926  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:23.936  7573  7573 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
08-29 13:12:23.936  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:23.936  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:23.936  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
08-29 13:12:23.936  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:23.936  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:23.936  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.936  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.936  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.936  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:23.936  1014  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:23.946  1014  1014 D RttService: SCAN_AVAILABLE : 1
08-29 13:12:23.946  1014  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:23.946  1014  1128 V NetworkStats: performPollLocked() took 16ms
08-29 13:12:23.946  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:23.956  1014  1128 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,08-29 13:12:23.956  1014  1128 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-29 13:12:23.956  1014  1128 D ConnectivityService: nai.networkMonitor.doQuit()
08-29 13:12:23.956  1014  1128 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-29 13:12:23.956  1014  1128 E ConnectivityService: updateNetworkInfo()
,08-29 13:12:23.956  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:23.956  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:12:23.956  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:23.956  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:12:23.956  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:23.956  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 13:12:23.956  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:23.956  1014  1128 E ConnectivityService: updateNetworkInfo()
,08-29 13:12:23.966  1014  1125 D WifiP2pService: P2pDisablingState
,08-29 13:12:23.966  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 13:12:23.966  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-29 13:12:23.966  1014  1125 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-29 13:12:23.966  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:23.966  1014  1126 E WifiNative-wlan0: do suspend true
08-29 13:12:23.966  1014  1045 D WifiDisplayController: disconnect
,08-29 13:12:23.966  1014  1045 D WifiDisplayController: updateConnection
08-29 13:12:23.966  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:23.966  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
08-29 13:12:23.966  1014  1125 D WifiP2pService: p2p socket connection lost
,08-29 13:12:23.966  1014  1125 D WifiP2pService: P2pDisabledState
08-29 13:12:23.966  1014  1504 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
,08-29 13:12:23.966  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:23.976  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:23.976  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-29 13:12:23.976  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:23.976  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:12:23.976  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:23.976  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:23.976  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
08-29 13:12:23.976  1602  1602 I Hs20UtilService: Starting #15
,08-29 13:12:23.976  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-29 13:12:23.976  1014  1094 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:12:23.976  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:12:23.976  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:23.986  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:12:23.986  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:12:23.986  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 13:12:23.986  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:23.986  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:23.986  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:12:23.986  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:23.996  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
08-29 13:12:23.996  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:12:23.996  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:24.006  1014  1125 D WifiP2pService: P2pDisabledState{ what=143375 },
,08-29 13:12:24.006   277   998 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:24.006  1014  1125 D WifiP2pService: DefaultState{ what=143375 }
08-29 13:12:24.006  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:24.006  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:24.006  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.006  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.006  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.006  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:24.016  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:24.016  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:24.016  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:12:24.016  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 13:12:24.016  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 13:12:24.016  7440  7440 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-29 13:12:24.026  7573  7573 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-29 13:12:24.026  7573  7573 E dhcpcd  : wlan0: sendmsg: Network is unreachable
08-29 13:12:24.026  7573  7573 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-29 13:12:24.026  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:24.026  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:24.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.026  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:24.026  7573  7573 I dhcpcd  : bssid match
08-29 13:12:24.026  7573  7573 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 13:12:24.026  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-29 13:12:24.036  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 13:12:24.036  7540  7540 D FileShare-Client: Outbound.stopDelayTimer - 
08-29 13:12:24.036  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:24.036  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:24.036  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:24.036  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:24.036  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.036  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.036  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.036  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:24.036  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:24.036  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-29 13:12:24.036  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-29 13:12:24.036  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:24.036  1176  1176 D HotspotTile: onReceive : 0, 0
,08-29 13:12:24.036  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:24.036  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:24.036  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.036  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:24.046  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:24.046  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:24.046  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:24.046  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:24.046  7555  7555 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:24.056  1014  1310 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:24.056  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:24.056  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:24.056  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:24.056  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:24.056  1602  1602 I Hs20UtilService: Starting #16
,08-29 13:12:24.056  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:12:24.056  1602  1639 I Hs20UtilService: Message received 5007
08-29 13:12:24.056  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:24.056  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:24.066  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:12:24.066  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:24.066  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:12:24.066  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:24.076  1014  4809 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:12:24.076  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:24.076  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:24.076  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:24.076  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:24.076  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:12:24.076  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-29 13:12:24.076  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:12:24.076  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:24.076  1602  1602 I Hs20UtilService: Starting #17
,08-29 13:12:24.076  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:24.106  7573  7573 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1
,08-29 13:12:24.186  7440  7440 I wpa_supplicant: Blacklist: Clear (all) ,
08-29 13:12:24.186  7573  7573 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds
,08-29 13:12:24.286  7440  7440 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-29 13:12:24.286  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:24.286  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:24.286  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:24.306  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 13:12:24.306  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.306  7440  7440 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-29 13:12:24.306  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:24.306  1014  1129 D Tethering: InitialState.processMessage what=4
08-29 13:12:24.306  7440  7440 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-29 13:12:24.306  7440  7440 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-29 13:12:24.306  7440  7440 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:24.306  7440  7440 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-29 13:12:24.306  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 13:12:24.306  1014  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-29 13:12:24.316  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.306  1014  1129 E Tethering: No numeric data
08-29 13:12:24.316  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.316  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:12:24.316  1014  1129 D Tethering: clearTetheredNotification()
08-29 13:12:24.316  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.316  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:24.316  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:12:24.316  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:24.316  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:24.316  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:24.316  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:24.316  1176  1176 D HotspotTile: updateTetherState():false, false
,08-29 13:12:24.326  1014  1123 V NetworkStats: performPollLocked() took 4ms
08-29 13:12:24.326  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:24.326  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:24.326  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:24.546  7440  7440 I wpa_supplicant: Blacklist: Clear (all) 
,08-29 13:12:24.576  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.576  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-29 13:12:24.576  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:24.656  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 13:12:24.656  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:24.656  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:24.666  7440  7440 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-29 13:12:24.766  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0,
08-29 13:12:24.766  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:12:24.766  7104  7104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:24.776  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:24.776  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:24.776  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.776  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:24.776  1984  2165 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
08-29 13:12:24.776  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:24.776  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-29 13:12:24.776  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
08-29 13:12:24.776  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:24.776  1176  1176 D HotspotTile: onReceive : 1, 0
08-29 13:12:24.776  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-29 13:12:24.776  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-29 13:12:24.776  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:24.786  1014  4809 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:24.776  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:24.786  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:24.786  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:24.786  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:24.786  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
,08-29 13:12:24.786  1602  1602 I Hs20UtilService: Starting #18
,08-29 13:12:24.786  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:24.786  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:12:24.786  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:24.786  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:12:24.786  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:24.796   287   287 E SMD     : DCD OFF
,08-29 13:12:25.106  1014  1535 I ActivityManager: Killing 7198:com.sec.pcw.device/1000 (adj 15): empty #21
,08-29 13:12:25.586   277   990 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,08-29 13:12:25.586  1014  1042 D Tethering: interfaceRemoved wlan0
,08-29 13:12:25.586  1014  1042 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-29 13:12:25.816  1014  1042 D Tethering: interfaceRemoved p2p0
08-29 13:12:25.816  1014  1042 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-29 13:12:26.646  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-29 13:12:26.866  1014  3371 D SSRM:n  : SIOP:: AP = 360
,08-29 13:12:26.876  6916  6969 D BluetoothAdapter: enable()
,08-29 13:12:26.876  1014  1535 W ActivityManager: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:12:26.876  1014  1535 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 13:12:26.876  1014  1535 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:12:26.886  1014  1535 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:12:26.886  1014  1535 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:26.886  1014  1535 D SettingsProvider: name = bluetooth_on
,08-29 13:12:26.886  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:26.886  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:26.886  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-29 13:12:26.886  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 13:12:26.896  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:26.896  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:26.896  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:26.896  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:26.906  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7605 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,08-29 13:12:26.906  7605  7605 E Zygote  : MountEmulatedStorage(),
08-29 13:12:26.906  7605  7605 E Zygote  : v2
08-29 13:12:26.906  7605  7605 I libpersona: KNOX_SDCARD checking this for 1002
08-29 13:12:26.906  7605  7605 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:26.916  7605  7605 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:26.916  7605  7605 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:12:26.916  7605  7605 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:12:26.946  7605  7605 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:26.946  7605  7605 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:26.956  7605  7605 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 13:12:26.966  7605  7605 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:26.986  7605  7605 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding GattService
,08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding A2dpService
,08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding HidService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding HealthService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding PanService
,08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding SapService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding SapClientService
08-29 13:12:27.016  7605  7605 D BtSettings.ProfileConfig: Adding HidDevService
08-29 13:12:27.016  7605  7605 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 13:12:27.026  1014  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 13:12:27.026  1014  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.026  1014  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.026  1014  1504 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1504 D SettingsProvider: ret = -1
,08-29 13:12:27.026  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 13:12:27.026  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:27.026  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.026  1014  1027 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1027 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:12:27.026  1014  1027 D SettingsProvider: ret = -1
,08-29 13:12:27.026  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:27.026  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.026  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.026  1014  1026 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1026 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1026 D SettingsProvider: ret = -1
08-29 13:12:27.026  1014  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-29 13:12:27.026  1014  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:27.026  1014  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:27.026  1014  1094 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1094 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1094 D SettingsProvider: ret = -1
08-29 13:12:27.026  1014  1534 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,08-29 13:12:27.026  1014  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.026  1014  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.026  1014  1534 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1534 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1534 D SettingsProvider: ret = -1
08-29 13:12:27.026  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 13:12:27.026  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:27.026  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.026  1014  1491 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1491 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.026  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1491 D SettingsProvider: ret = -1
08-29 13:12:27.026  1014  1535 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-29 13:12:27.026  1014  1535 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.026  1014  1535 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:27.026  1014  1535 D SettingsProvider: selectionArgs: false
08-29 13:12:27.026  1014  1535 D SettingsProvider: selectionArgs: 1002
,08-29 13:12:27.026  1014  1535 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  1535 D SettingsProvider: ret = -1
08-29 13:12:27.026  1014  4809 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 13:12:27.026  1014  4809 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.026  1014  4809 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:27.026  1014  4809 D SettingsProvider: selectionArgs: false
,08-29 13:12:27.026  1014  4809 D SettingsProvider: selectionArgs: 1002,
08-29 13:12:27.026  1014  4809 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.026  1014  4809 D SettingsProvider: ret = -1
08-29 13:12:27.036  1014  1458 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:27.036  1014  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.036  1014  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.036  1014  1458 D SettingsProvider: selectionArgs: false
08-29 13:12:27.036  1014  1458 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.036  1014  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:12:27.036  1014  1458 D SettingsProvider: ret = -1
08-29 13:12:27.036  1014  1310 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:27.036  1014  1310 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.036  1014  1310 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.036  1014  1310 D SettingsProvider: selectionArgs: false
08-29 13:12:27.036  1014  1310 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.036  1014  1310 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.036  1014  1310 D SettingsProvider: ret = -1
,08-29 13:12:27.036  1014  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 13:12:27.036  1014  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.036  1014  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.036  1014  1533 D SettingsProvider: selectionArgs: false
08-29 13:12:27.036  1014  1533 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.036  1014  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.036  1014  1533 D SettingsProvider: ret = -1
08-29 13:12:27.036  1014  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-29 13:12:27.036  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.036  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:27.036  1014  1493 D SettingsProvider: selectionArgs: false
08-29 13:12:27.036  1014  1493 D SettingsProvider: selectionArgs: 1002
08-29 13:12:27.036  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.036  1014  1493 D SettingsProvider: ret = -1
,08-29 13:12:27.046  7605  7605 D BluetoothAdapterState: make
,08-29 13:12:27.056  7605  7605 I bluedroid: init,
08-29 13:12:27.056  7605  7620 I BluetoothAdapterState: Entering OffState
,08-29 13:12:27.056  7605  7605 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 13:12:27.056  7605  7605 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf,
08-29 13:12:27.056  7605  7605 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:12:27.056  7605  7605 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 13:12:27.066  7605  7605 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-29 13:12:27.066  7605  7605 I bluedroid: get_profile_interface socket
,08-29 13:12:27.066  7605  7605 I bluedroid: get_profile_interface map_client
,08-29 13:12:27.066  7605  7605 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 13:12:27.066  7605  7623 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-29 13:12:27.066  7605  7623 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 13:12:27.066  7605  7623 E BluetoothServiceJni: populateRssiValuesNative
,08-29 13:12:27.066  7605  7623 I bluedroid: getModelRssiValues
08-29 13:12:27.066  7605  7623 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 13:12:27.066  7605  7623 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 13:12:27.066  7605  7605 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:27.066  1014  1458 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:12:27.076  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.076  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.076  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.076  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.076  7605  7623 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 13:12:27.076  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 13:12:27.076  7605  7613 I bluedroid: config_hci_snoop_log
,08-29 13:12:27.076  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,08-29 13:12:27.076  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-29 13:12:27.076  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
08-29 13:12:27.076  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 13:12:27.076  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:12:27.086  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:27.086  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:12:27.086  7605  7605 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-29 13:12:27.086  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 13:12:27.086  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 13:12:27.096  7605  7620 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 13:12:27.096  7605  7620 D BluetoothAdapterProperties: Setting state to 11
,08-29 13:12:27.096  7605  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:12:27.096  7605  7620 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 13:12:27.096  7605  7620 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 13:12:27.096  7605  7620 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:12:27.096  7605  7620 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 13:12:27.096  7605  7620 D BluetoothSecureManager: getInstant: null
,08-29 13:12:27.096  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
08-29 13:12:27.096  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
08-29 13:12:27.106  7605  7620 D BluetoothSecureManager: calling getMethod for getService
08-29 13:12:27.106  7605  7620 D BluetoothSecureManager: calling getService
,08-29 13:12:27.106  7605  7620 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@ee10da9
,08-29 13:12:27.106  1014  1534 D BluetoothSecureManagerService: isSecureModeEnabled
,08-29 13:12:27.106  1014  1534 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-29 13:12:27.106  1963  1963 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:27.116  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 13:12:27.116  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:27.116  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-29 13:12:27.116  7605  7620 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 13:12:27.116  7605  7620 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 13:12:27.116  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:12:27.116  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:27.126  7605  7620 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:27.126  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 13:12:27.126  7605  7620 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:27.126  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 13:12:27.126  1014  1534 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:27.126  1014  1310 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 13:12:27.126  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.126  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:27.126  7605  7620 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:27.126  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:12:27.126  7605  7620 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 13:12:27.126  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.126  1014  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:27.126  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:27.126  1014  1535 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:12:27.136  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:12:27.136  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:12:27.136  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:12:27.136  7605  7620 D BluetoothBondStateMachine: make
,08-29 13:12:27.136  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 13:12:27.136  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 13:12:27.136  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 13:12:27.136  7605  7625 I BluetoothBondStateMachine: StableState(): Entering Off State
08-29 13:12:27.136  1014  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.136  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.136  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:27.136  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.136  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
08-29 13:12:27.136  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.136  7605  7605 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:27.136  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:27.146  7605  7605 D BtGatt.GattService: Received start request. Starting profile...
,08-29 13:12:27.146  7605  7605 D BtGatt.GattService: start()
08-29 13:12:27.146  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:12:27.146  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 13:12:27.146  7605  7605 D BtGatt.GattService: start()
08-29 13:12:27.146  7605  7605 I bluedroid: get_profile_interface gatt
,08-29 13:12:27.146  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:27.146  7605  7605 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:12:27.146  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:27.146  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-29 13:12:27.146  1014  1534 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:27.146  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.156  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:27.156  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.156  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.156  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 13:12:27.156  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:12:27.156  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-29 13:12:27.156  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-29 13:12:27.156  7605  7605 D BtGatt.GattService: mStartError = false
08-29 13:12:27.156  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:27.156  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:27.156  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:27.156  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:27.156  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:27.166  7605  7605 D HeadsetService: Received start request. Starting profile...,
08-29 13:12:27.166  7605  7605 D HeadsetService: start()
08-29 13:12:27.166  7605  7605 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 13:12:27.166  7605  7605 D HeadsetStateMachine: make
08-29 13:12:27.166  7605  7605 E HeadsetStateMachine: # of Max HF connection is 2
08-29 13:12:27.166  7629  7629 E Zygote  : MountEmulatedStorage()
08-29 13:12:27.166  7629  7629 I libpersona: KNOX_SDCARD checking this for 10055
08-29 13:12:27.166  7629  7629 E Zygote  : v2
08-29 13:12:27.166  7629  7629 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:27.166  7629  7629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:27.176  7629  7629 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:27.176  7629  7629 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:27.176  1014  1027 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=7629 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 13:12:27.176  1014  1491 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 13:12:27.176  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.176  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.176  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.176  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 13:12:27.186  1014  1504 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.186  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.186  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:27.186  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.186  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.186  1014  1533 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-29 13:12:27.186  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.186  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 13:12:27.186  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:27.186  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.186  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.186  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 13:12:27.186  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 13:12:27.186  7605  7605 I bluedroid: get_profile_interface handsfree
08-29 13:12:27.186  1014  1534 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.186  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 13:12:27.196  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.196  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.196  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.196  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:12:27.196  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:12:27.196  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:12:27.196  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.196  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.196  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:27.206  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.206  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.206  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-29 13:12:27.206  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-29 13:12:27.206  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:12:27.206  1014  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.206  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.206  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.206  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.206  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.216  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:12:27.216  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:27.216  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-29 13:12:27.216  1014  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.216  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.216  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:27.216  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:27.216  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:27.226  7629  7629 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:27.226  7629  7629 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-29 13:12:27.226  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:12:27.226  1014  1534 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:27.226  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:12:27.226  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.226  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:27.226  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:27.226  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:27.226  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:12:27.226  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:12:27.226  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:12:27.226  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:12:27.226  7605  7620 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-29 13:12:27.236  7605  7605 I DualScoManager: Instantiating Dual Sco Manager
08-29 13:12:27.236  7605  7605 I DualScoManager: Set HeadsetServiceHelper
,08-29 13:12:27.236  7605  7605 D BluetoothAtMessage: createCMTIContentObservers
,08-29 13:12:27.236  1014  1493 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 13:12:27.236  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:27.236  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:27.236  1014  1493 D SettingsProvider: selectionArgs: false
08-29 13:12:27.236  1014  1493 D SettingsProvider: selectionArgs: 1002
,08-29 13:12:27.236  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:27.236  1014  1493 D SettingsProvider: ret = -1
,08-29 13:12:27.236  7605  7628 D HeadsetStateMachine: Enter Disconnected: -2
,08-29 13:12:27.236  7605  7605 D HeadsetService: mStartError = false
08-29 13:12:27.236  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:27.236  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-29 13:12:27.236  7605  7605 D HeadsetStateMachine: Try to query the phonestate on bind
08-29 13:12:27.246  7605  7628 D HeadsetStateMachine: Clear mHeadsetBrsf
08-29 13:12:27.246  7605  7628 D HeadsetStateMachine: map size, before remove : 0
08-29 13:12:27.246  7605  7628 D HeadsetStateMachine: map size, after remove: 0
,08-29 13:12:27.246  1446  1482 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:12:27.246  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 13:12:27.246  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:12:27.246  1446  1482 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 13:12:27.246  7605  7605 D A2dpService: Received start request. Starting profile...
08-29 13:12:27.246  7605  7605 D A2dpService: start()
,08-29 13:12:27.246  7605  7605 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 13:12:27.246  7605  7605 I bluedroid: get_profile_interface avrcp
,08-29 13:12:27.256  7605  7605 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:12:27.256  7605  7605 D Avrcp   : Initialize Media Controller
08-29 13:12:27.256  7605  7605 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 13:12:27.256  7605  7605 E Avrcp   : getActiveSessions
08-29 13:12:27.256  7605  7605 D Avrcp   : pick active media Controller
08-29 13:12:27.256  7605  7605 D Avrcp   : Get the active Media Controller 
,08-29 13:12:27.256  7629  7629 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-29 13:12:27.276  7605  7605 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 13:12:27.276  7605  7648 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 13:12:27.276  7605  7605 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:27.276  7605  7605 D A2dpStateMachine: make
,08-29 13:12:27.286  7605  7605 I bluedroid: get_profile_interface a2dp,
08-29 13:12:27.286  7605  7650 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 13:12:27.286  7605  7605 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 13:12:27.286  7605  7605 D A2dpService: mStartError = false
08-29 13:12:27.286  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:27.286  7605  7605 D HeadsetStateMachine: Proxy object connected
08-29 13:12:27.286  7605  7649 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:12:27.286  7605  7605 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:12:27.286  7605  7605 D HidService: Received start request. Starting profile...
08-29 13:12:27.286  7605  7605 D HidService: start()
08-29 13:12:27.286  7605  7605 I bluedroid: get_profile_interface hidhost
08-29 13:12:27.286  7605  7605 D HidService: setHidService(): set to: null
,08-29 13:12:27.286  7605  7605 D HidService: mStartError = false
08-29 13:12:27.286  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:27.286  7629  7629 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
08-29 13:12:27.296  7605  7605 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 13:12:27.296  7605  7628 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:12:27.296  7605  7605 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 13:12:27.296  7605  7605 D HealthService: Received start request. Starting profile...
08-29 13:12:27.296  7605  7605 D HealthService: start()
,08-29 13:12:27.296  7629  7629 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-29 13:12:27.296  7629  7629 D UserAnalysis: Create SecureDbHelper
08-29 13:12:27.296  7605  7648 D BluetoothMediaBrowser: no now playing list
,08-29 13:12:27.296  7605  7648 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-29 13:12:27.296  7605  7605 I bluedroid: get_profile_interface health
08-29 13:12:27.296  7605  7605 D HealthService: mStartError = false
08-29 13:12:27.296  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:27.296  7605  7605 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:12:27.296  7605  7605 D PanService: Received start request. Starting profile...
08-29 13:12:27.296  7605  7605 D PanService: start()
08-29 13:12:27.296  7605  7605 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 13:12:27.296  7605  7605 I bluedroid: get_profile_interface pan
08-29 13:12:27.296  7605  7605 D PanService: mStartError = false
08-29 13:12:27.296  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:27.296  7605  7605 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 13:12:27.296  7605  7605 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-29 13:12:27.296  7605  7628 D HeadsetStateMachine: Disconnected process message: 18
,08-29 13:12:27.306  7629  7629 D IntelligenceServiceApplication: onCreate()
,08-29 13:12:27.306  7605  7605 D BluetoothMapService: Received start request. Starting profile...
08-29 13:12:27.306  7605  7605 D BluetoothMapService: start()
,08-29 13:12:27.306  1014  1094 I ActivityManager: Killing 7215:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 13:12:27.316  7605  7605 D BluetoothMapService: mStartError = false
08-29 13:12:27.316  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:27.316  7629  7629 D IntelligenceServiceApplication: no applications having user consent for prediction
08-29 13:12:27.316  7605  7605 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 13:12:27.316  7605  7605 D SapService: Received start request. Starting profile...
08-29 13:12:27.316  7605  7605 D SapService: start()
08-29 13:12:27.316  7605  7605 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 13:12:27.316  7605  7605 I bluedroid: get_profile_interface sap
08-29 13:12:27.316  7605  7605 D SapService: mStartError = false
08-29 13:12:27.316  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:27.316  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-29 13:12:27.316  7605  7605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:12:27.316  7605  7628 D HeadsetStateMachine: Disconnected process message: 10
08-29 13:12:27.316  7605  7605 D BluetoothA2dp: Proxy object connected
08-29 13:12:27.316  7605  7605 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 13:12:27.316  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 13:12:27.316  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
08-29 13:12:27.316  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-29 13:12:27.316  7629  7629 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-29 13:12:27.316  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 13:12:27.316  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 13:12:27.316  7605  7628 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:12:27.316  7605  7628 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:12:27.316  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-29 13:12:27.316  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:27.326  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:27.326  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:27.326  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:27.326  7629  7629 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-29 13:12:27.336  7655  7655 E Zygote  : MountEmulatedStorage()
08-29 13:12:27.336  7655  7655 I libpersona: KNOX_SDCARD checking this for 10105
08-29 13:12:27.336  7655  7655 E Zygote  : v2
08-29 13:12:27.336  7655  7655 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:27.336  7655  7655 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:27.336  7655  7655 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:27.336  1014  1027 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7655 uid=10105 gids={50105, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-29 13:12:27.336  7655  7655 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:27.366  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 13:12:27.366  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 13:12:27.376  7605  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 13:12:27.376  7605  7620 I bluedroid: enable
,08-29 13:12:27.376  7605  7671 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 13:12:27.376  7605  7620 I bt_hci_bdroid: init
,08-29 13:12:27.376  7605  7620 I bt_vendor: bt-vendor : init
,08-29 13:12:27.376  7605  7620 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:12:27.376  7605  7620 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:12:27.376  7605  7620 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 13:12:27.376  7605  7620 D bt_userial_mct: userial_init
08-29 13:12:27.376  7655  7655 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:27.376  7655  7655 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:27.376  7605  7620 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:12:27.376  7605  7620 I bt_vendor: Starting hciattach daemon
08-29 13:12:27.376  7605  7620 I bt_vendor: try to set false,
,08-29 13:12:27.386  7605  7620 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-29 13:12:27.386  7605  7620 I bt_vendor: Starting hciattach daemon
08-29 13:12:27.386  7605  7620 I bt_vendor: try to set true
,08-29 13:12:27.406  7675  7675 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-29 13:12:27.446  7681  7681 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-29 13:12:27.456  7682  7682 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:27.476  7684  7684 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 13:12:27.486  7685  7685 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-29 13:12:27.496  7686  7686 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 13:12:27.496  7689  7689 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-29 13:12:27.546   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:12:27.546   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:27.546  7655  7693 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:12:27.556   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.maps/files/
08-29 13:12:27.556   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-29 13:12:27.556  7655  7693 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.maps/files
,08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=143 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=141 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:252)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gm,m.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.k.a(PG:2107)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:23)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08,-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.k.d(PG:1187)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.k.c(PG:18147)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.k.d(PG:583)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.v.a.a.dq.<init>(PG:40)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.v.a.a.dq.a(PG:405)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.v.a(PG:1161)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.y.a(PG:2188)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.e.b(PG:170)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.q.e.b(PG:15188)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:253)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8690)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8698)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.exists(File.java:363)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8700)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  7655  7655 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.io.File.lastModified(File.java:571)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1515)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:209)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:177)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-29 13:12:27.696  7655  7655 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-29 13:12:27.696  1014  4809 I ActivityManager: Killing 7227:com.sec.android.soagent/u0a31 (adj 15): empty #21
08-29 13:12:27.696  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:27.706  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-29 13:12:27.716  7704  7704 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 
,08-29 13:12:27.726  7705  7705 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-29 13:12:27.756  7655  7692 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 13:12:27.786  7605  7620 I bt_vendor: bluetooth satus is on
,08-29 13:12:27.786  7605  7673 D bt_userial_mct: userial_open(port:0)
08-29 13:12:27.786  7605  7673 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-29 13:12:27.796  7605  7673 I bt_vendor: Done intiailizing UART
,08-29 13:12:27.796  7605  7673 I bt_vendor: Done intiailizing UART
,08-29 13:12:27.796  7605  7673 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-29 13:12:27.796  7605  7673 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-29 13:12:27.796   287   287 E SMD     : DCD OFF
,08-29 13:12:27.796  7605  7708 D bt_userial_mct: Entering userial_read_thread()
,08-29 13:12:27.936  1014  3937 I art     : Explicit concurrent mark sweep GC freed 75874(4MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.418ms total 149.677ms
,08-29 13:12:27.936  1014  1533 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:27.936  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:27.936  1014  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:27.936  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_HCI
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 13:12:27.936  7605  7671 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 13:12:28.026  7605  7671 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 13:12:28.026  7605  7671 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa423ded1 
,08-29 13:12:28.036  7605  7671 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa423ded1 
,08-29 13:12:28.046  7605  7623 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 13:12:28.046  7605  7623 E bt-btif : Calling BTA_HhEnable
08-29 13:12:28.056  7605  7623 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 13:12:28.056  7605  7623 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
,08-29 13:12:28.056  7605  7623 E BluetoothServiceJni: populateRssiValuesNative
08-29 13:12:28.056  7605  7623 I bluedroid: getModelRssiValues
,08-29 13:12:28.056  7605  7623 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-29 13:12:28.056  7605  7623 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 13:12:28.056  7605  7623 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 13:12:28.056  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 13:12:28.066  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.066  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.066  7605  7623 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 13:12:28.066  7605  7623 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:28.066  7605  7623 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:28.076  7605  7623 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 13:12:28.076  7605  7623 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 13:12:28.076  7605  7623 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 13:12:28.076  7605  7623 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 13:12:28.076  7605  7623 E bt-btif : btif_sock_init: !vhci_init
,08-29 13:12:28.076  7605  7623 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 13:12:28.076  7605  7623 D IOP_DB_BT: db_open: db_open : handle 2965372944l, read 13894 bytes onto local cache
,08-29 13:12:28.076  7605  7623 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 13:12:28.076  7605  7708 E bt_mct  : hci lib postload completed
,08-29 13:12:28.076  7605  7623 D IOP_DB_BT: db_query: result 1
,08-29 13:12:28.076  7605  7623 I         : iop_db_open: iop_db_open status 0
,08-29 13:12:28.076  7605  7623 D bte_conf: Device ID record 1 : primary
,08-29 13:12:28.076  7605  7623 D bte_conf:   vendorId            = 0075
08-29 13:12:28.076  7605  7623 D bte_conf:   vendorIdSource      = 0001
,08-29 13:12:28.076  7605  7623 D bte_conf:   product             = 0100
,08-29 13:12:28.076  7605  7623 D bte_conf:   version             = 0200
08-29 13:12:28.076  7605  7623 D bte_conf:   clientExecutableURL = 
08-29 13:12:28.076  7605  7623 D bte_conf:   serviceDescription  = 
08-29 13:12:28.076  7605  7623 D bte_conf:   documentationURL    = 
08-29 13:12:28.076  7605  7623 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:12:28.076  7605  7623 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:12:28.086  7605  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-29 13:12:28.086  7605  7620 D BluetoothAdapterProperties: ScanMode =  20
,08-29 13:12:28.086  7605  7620 D BluetoothAdapterProperties: State =  11
,08-29 13:12:28.086  1014  1027 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 13:12:28.086  7605  7620 D BluetoothAdapterProperties: Setting state to 12
,08-29 13:12:28.086  7605  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:12:28.096  7605  7623 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:12:28.096  7605  7623 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:12:28.096  7605  7623 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:12:28.096  1014  1534 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-29 13:12:28.096  1014  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:28.096  1014  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:28.096  1014  1534 D SettingsProvider: selectionArgs: false
08-29 13:12:28.096  1014  1534 D SettingsProvider: selectionArgs: 1002
08-29 13:12:28.096  1014  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:28.096  1014  1534 D SettingsProvider: ret = -1
,08-29 13:12:28.096  7605  7620 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:12:28.096  7605  7620 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 13:12:28.096  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:28.096  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.106  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.106  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.106  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.106  7605  7620 D BluetoothAdapterService: Autoconnection is available 
08-29 13:12:28.106  7605  7620 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 13:12:28.106  7605  7620 D BluetoothAdapterService: starting service from this receiver
,08-29 13:12:28.106  7655  7666 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.106  7655  7666 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.106  1014  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:28.106  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.106  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 13:12:28.106  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-29 13:12:28.106  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:28.106  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.106  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:12:28.106  6916  6930 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.106  6916  6930 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:28.106  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:28.116  7605  7620 I BluetoothAdapterState: Entering On State from state = 11
08-29 13:12:28.116  1455  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.116  1455  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:12:28.116  7605  7619 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:28.116  1446  7062 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.116  1446  7062 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.116  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.116  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:28.116  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.116  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:12:28.116  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:28.116  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.116  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:12:28.116  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.116  1014  1014 D BluetoothA2dp: Proxy object connected
,08-29 13:12:28.126  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:28.126  1446  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.126  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:12:28.126  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.126  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.126  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.126  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.126  1446  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:28.136  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:28.136  1446  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.136  7605  7605 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 13:12:28.136  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:28.136  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.136  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.136  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.136  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-29 13:12:28.136  1446  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:28.136  1014  1044 D BluetoothPan: Binding service...
08-29 13:12:28.136  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 13:12:28.136  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.136  7605  7713 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.136  7605  7713 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.136  1984  1992 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:28.136  1984  1992 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.136  1469  1748 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:12:28.136  1469  1748 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.146  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:28.146  1469  1485 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.146  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:12:28.146  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.146  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.146  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:28.146  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.146  1469  1485 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:28.146  1176  1759 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:12:28.146  1176  1759 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:28.156  7605  7605 I BluetoothPbapService: Handler(): got msg=1
,08-29 13:12:28.156  1446  7062 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.156  1014  1504 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 13:12:28.156  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:12:28.156  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.156  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.156  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.156  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.156  1446  7062 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:28.156  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 13:12:28.156  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:12:28.156  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:28.156  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-29 13:12:28.156  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:12:28.166  7605  7714 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-29 13:12:28.166  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@25512c8e, true
,08-29 13:12:28.166  1446  1446 D BluetoothHeadset: registerMessageListener
,08-29 13:12:28.166  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:12:28.176  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-29 13:12:28.176  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:28.176  1176  1176 D BluetoothTile:  getBluetoothState : 12
,08-29 13:12:28.176  1963  1963 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:28.176  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.176  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:28.186  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:28.186  1014  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:28.186  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.186  1014  1094 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:28.186  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.186  1014  1493 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:28.186  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:28.186  7605  7619 D HeadsetService: registerMessageListener
,08-29 13:12:28.186  1014  1533 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 13:12:28.186  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:28.186  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:28.196  7605  7619 D HeadsetService: registerMessageListener
,08-29 13:12:28.196  7605  7628 D HeadsetStateMachine: Disconnected process message: 70
08-29 13:12:28.196  7605  7628 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16daebf2
,08-29 13:12:28.196  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 13:12:28.196  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:12:28.196  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:28.196  7605  7714 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:12:28.196  7605  7714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:28.196  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:12:28.196  7519  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:28.206  7605  7714 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-29 13:12:28.206  7605  7714 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:12:28.206  7605  7714 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:28.206  7605  7714 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e466243
08-29 13:12:28.206  7605  7714 D BluetoothSocket: channel: 19
08-29 13:12:28.206  7605  7714 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 13:12:28.206  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-29 13:12:28.206  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-29 13:12:28.206  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-29 13:12:28.206  1014  4809 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:12:28.206  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.206  7605  7715 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-29 13:12:28.206  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.206  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.206  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:28.216  7605  7628 D HeadsetStateMachine: Disconnected process message: 9
,08-29 13:12:28.216  7605  7628 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 13:12:28.216  7605  7715 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:12:28.216  7605  7715 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:28.216  7605  7715 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 13:12:28.216  7605  7715 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:12:28.216  7605  7715 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:28.216  7605  7715 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18ba70c0
,08-29 13:12:28.226  7605  7715 D BluetoothSocket: channel: 5
,08-29 13:12:28.226   282   689 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-29 13:12:28.226   282   689 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 13:12:28.226   282   689 V voice   : voice_set_parameters: exit with code(-2)
08-29 13:12:28.226   282   689 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 13:12:28.226   282   689 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 13:12:28.226   282   689 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 13:12:28.226   282   689 V audio_hw_primary: adev_set_parameters: exit
,08-29 13:12:28.226  7605  7628 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 13:12:28.236  7519  7519 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-29 13:12:28.246  7519  7519 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.246  1014  1094 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-29 13:12:28.246  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.246  1014  1094 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.246  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.246  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.246  7519  7519 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 13:12:28.246  7519  7519 E BluetoothHeadset: BTStateChangeCB is registed
,08-29 13:12:28.246  7519  7519 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:28.256  1014  1533 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:28.256  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:28.256  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.256  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.256  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.256  7519  7519 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:28.256  7519  7519 D BluetoothMap: Create BluetoothMap proxy object
,08-29 13:12:28.256  1014  1458 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-29 13:12:28.256  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.256  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.256  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.256  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.276  1014  1310 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-29 13:12:28.276  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.276  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.276  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:28.276  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.276  7519  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-29 13:12:28.276  1014  1534 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-29 13:12:28.276  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.286  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.286  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.286  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.286  7519  7519 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-29 13:12:28.286  1014  1458 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-29 13:12:28.286  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.286  1014  1458 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:28.286  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.286  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.296  1014  1310 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 13:12:28.296  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.296  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.296  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:28.296  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.296  7519  7519 D LocalBluetoothProfileManager: PANU : true
,08-29 13:12:28.296  7519  7519 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
,08-29 13:12:28.296  7519  7519 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 13:12:28.306  7519  7519 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:28.306  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
08-29 13:12:28.306  7519  7519 D BluetoothA2dp: Proxy object connected
,08-29 13:12:28.306  7519  7519 D A2dpProfile: Bluetooth service connected
,08-29 13:12:28.316  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:28.316  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 13:12:28.316  7519  7519 D HeadsetProfile: Bluetooth service connected
,08-29 13:12:28.316  7519  7519 D BluetoothMap: Proxy object connected
,08-29 13:12:28.316  7519  7519 D MapProfile: Bluetooth service connected
08-29 13:12:28.316  7519  7519 D BluetoothMap: getConnectedDevices()
,08-29 13:12:28.326  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:28.326  7605  7605 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:12:28.326  7519  7519 D BluetoothPbap: Proxy object connected
08-29 13:12:28.326  7519  7519 D PbapServerProfile: Bluetooth service connected
08-29 13:12:28.326  7519  7519 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 13:12:28.326  7519  7519 D SapProfile: Bluetooth service connected
08-29 13:12:28.326  7519  7519 D Bluetoothsap: getConnectedDevices()
,08-29 13:12:28.326  1014  4809 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:28.326  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.326  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.326  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:28.326  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:28.336  7519  7519 D BluetoothInputDevice: Proxy object connected
08-29 13:12:28.336  7519  7519 D HidProfile: Bluetooth service connected
,08-29 13:12:28.346  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:28.346  1014  1310 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:28.346  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:28.346  7519  7519 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:28.346  7519  7519 D PanProfile: Bluetooth service connected
,08-29 13:12:28.346  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:28.346  1014  1310 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:28.346  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:28.356  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:28.356  1984  7722 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 13:12:28.366  1014  4809 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:28.366  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.366  1014  4809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 13:12:28.366  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:28.386  1014  1026 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 13:12:28.386  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:28.396  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:28.396  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:28.396  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:28.406  7605  7726 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 13:12:28.406  7605  7726 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:28.406  1984  7722 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 13:12:28.406  7605  7726 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
,08-29 13:12:28.406  7605  7726 D BluetoothSocket: bindListen(), new LocalSocket 
,08-29 13:12:28.406  7605  7726 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:28.406  7605  7726 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10c8074a
08-29 13:12:28.406  7605  7726 D BluetoothSocket: channel: 12
08-29 13:12:28.406  7605  7726 I BtOppRfcommListener: Accept thread started.
,08-29 13:12:29.886  6916  6969 D BluetoothAdapter: disable()
08-29 13:12:29.886  1014  1458 D SettingsProvider: name = bluetooth_on
,08-29 13:12:29.906  7605  7620 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-29 13:12:29.906  7605  7620 D BluetoothAdapterProperties: Setting state to 13
08-29 13:12:29.906  7605  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-29 13:12:29.906  7605  7620 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:12:29.906  7605  7620 D BluetoothAdapterService: updateAdapterState state is 13
,08-29 13:12:29.906  1014  1491 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:29.906  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:29.906  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:29.906  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:29.906  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:29.906  7605  7605 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-29 13:12:29.906  7605  7605 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@49fd6bb, channel: 19, state: LISTENING
,08-29 13:12:29.906  7605  7620 D BluetoothAdapterService: Autoconnection is available 
08-29 13:12:29.906  7605  7605 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@49fd6bb, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1e466243, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3b1d97d8mSocket: android.net.LocalSocket@38eda731 impl:android.net.LocalSocketImpl@27074e16 fd:FileDescriptor[74]
08-29 13:12:29.906  7605  7605 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@38eda731 impl:android.net.LocalSocketImpl@27074e16 fd:FileDescriptor[74]
,08-29 13:12:29.906  7605  7620 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,08-29 13:12:29.916  7605  7620 D BluetoothAdapterService: terminating service from this receiver
,08-29 13:12:29.916  7519  7519 D BluetoothPbap: Proxy object disconnected
08-29 13:12:29.916  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 13:12:29.916  7519  7519 D PbapServerProfile: Bluetooth service disconnected
,08-29 13:12:29.916  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:29.916  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:29.916  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:29.926  7605  7620 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 13:12:29.926  7605  7620 D BluetoothAdapterProperties: mDiscovering is false
,08-29 13:12:29.926  1014  1310 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-29 13:12:29.926  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:29.926  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,08-29 13:12:29.926  7605  7620 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-29 13:12:29.936  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:12:29.936  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:29.936  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:29.946  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:29.946  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:29.946  1176  1176 D BluetoothTile:  getBluetoothState : 13
,08-29 13:12:29.946  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:12:29.946  1014  4809 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:12:29.946  1014  4809 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:12:29.946  1014  4809 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
08-29 13:12:29.946  1014  4809 D BatteryService: stay LED for fully charged
08-29 13:12:29.946  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-29 13:12:29.946  1963  1963 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:29.946  1014  1310 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:29.956  1014  1094 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:12:29.956  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:29.956  7519  7519 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:29.956  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:12:29.956  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.956  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:29.956  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-29 13:12:29.956  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:29.966  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:29.966  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:29.966  6916  6916 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 13:12:29.966  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:29.966  1014  1014 I MotionRecognitionService: Plugged
08-29 13:12:29.966  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:12:29.966  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 13:12:29.966  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:12:29.976  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:12:29.976  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:12:29.986  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 13:12:29.986  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:29.986  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-29 13:12:29.986  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-29 13:12:29.986  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-29 13:12:29.986  1014  4809 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:29.986  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:29.986  7605  7623 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:12:29.986  7605  7623 D BluetoothAdapterProperties: Scan Mode:20
,08-29 13:12:29.986  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:29.986  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:29.986  1014  4809 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 13:12:29.996  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:29.996  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:29.996  7605  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-29 13:12:29.996  7605  7620 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-29 13:12:29.996  7605  7620 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-29 13:12:29.996  7605  7620 E bt-btif : cmd socket is not created
,08-29 13:12:29.996  7605  7620 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 13:12:29.996  7605  7671 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-29 13:12:29.996  7605  7671 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 13:12:29.996  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:29.996  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:29.996  7605  7671 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-29 13:12:29.996  7605  7726 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 13:12:30.006  7519  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:30.006  1014  1458 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-29 13:12:30.006  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.006  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.006  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.006  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:30.026  7605  7605 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:12:30.026  7605  7605 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10c05984, channel: 5, state: LISTENING
,08-29 13:12:30.026  7605  7605 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10c05984, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18ba70c0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d44856dmSocket: android.net.LocalSocket@162235a2 impl:android.net.LocalSocketImpl@36346233 fd:FileDescriptor[76]
08-29 13:12:30.026  7605  7605 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@162235a2 impl:android.net.LocalSocketImpl@36346233 fd:FileDescriptor[76]
,08-29 13:12:30.026  7605  7605 I BtOppRfcommListener: stopping Accept Thread
08-29 13:12:30.026  7605  7605 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@30ab89f0, channel: 12, state: LISTENING
,08-29 13:12:30.026  7605  7605 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@30ab89f0, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10c8074a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1cb10b69mSocket: android.net.LocalSocket@251209ee impl:android.net.LocalSocketImpl@23c8ee8f fd:FileDescriptor[79]
08-29 13:12:30.026  7605  7605 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@251209ee impl:android.net.LocalSocketImpl@23c8ee8f fd:FileDescriptor[79]
,08-29 13:12:30.026  7605  7726 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 13:12:30.026  7605  7628 D HeadsetStateMachine: Disconnected process message: 10
,08-29 13:12:30.036  7519  7519 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:30.036  7605  7605 V BluetoothOppManager: cleanUp...
,08-29 13:12:30.036  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:30.046  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:30.046  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-29 13:12:30.066  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:30.066  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-29 13:12:30.196  7605  7671 W bt-btif : ag scb idx 1 not allocated
08-29 13:12:30.196  7605  7671 W bt-btif : ag scb idx 2 not allocated
08-29 13:12:30.196  7605  7671 E bt-btif : BTA AG is already disabled, ignoring ...
08-29 13:12:30.196  7605  7708 I bt_userial_mct: exiting userial_read_thread
08-29 13:12:30.206  7605  7708 D bt_userial_mct: Leaving userial_evt_read_thread()
08-29 13:12:30.206  7605  7623 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-29 13:12:30.206  7605  7673 I bt_vendor: hw_epilog_process
,08-29 13:12:30.206  7605  7623 D bt_userial_mct: userial_close
,08-29 13:12:30.206  7605  7623 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-29 13:12:30.546  7605  7623 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-29 13:12:30.546  7605  7623 I bt_vendor: bluetooth satus is on
,08-29 13:12:30.546  7605  7623 I bt_vendor: bt-vendor : resetting BT status
08-29 13:12:30.546  7605  7623 I bt_vendor: Starting hciattach daemon
08-29 13:12:30.546  7605  7623 I bt_vendor: try to set false
,08-29 13:12:30.546  7605  7623 I bt_vendor: Starting hciattach daemon
,08-29 13:12:30.546  7605  7623 I bt_vendor: try to set false
,08-29 13:12:30.546  7605  7623 I bt_vendor: cleanup,
,08-29 13:12:30.546  7605  7671 I GKI_LINUX: gki_task task_id=0 [BTU] terminating,
,08-29 13:12:30.546  7605  7623 I GKI_LINUX: GKI_exit_task 0 done
08-29 13:12:30.546  7605  7623 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-29 13:12:30.546  7605  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-29 13:12:30.546  7605  7620 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:12:30.556  7605  7620 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 13:12:30.556  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 13:12:30.556  1014  4809 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-29 13:12:30.556  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.556  1014  4809 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:30.556  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:30.556  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.556  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
08-29 13:12:30.556  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:12:30.556  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-29 13:12:30.556  7605  7605 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:30.556  7605  7605 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 13:12:30.556  7605  7605 D BtGatt.GattService: stop()
08-29 13:12:30.556  7605  7605 D BtGatt.AdvertiseManager: advertise clients cleared
08-29 13:12:30.556  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.556  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.556  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:30.556  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:12:30.556  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:30.556  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:30.566  7605  7605 D HeadsetService: Received stop request...Stopping profile...
,08-29 13:12:30.566  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.566  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-29 13:12:30.566  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:30.566  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.566  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:30.566  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.566  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.566  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 13:12:30.566  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:30.566  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 13:12:30.566  1014  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:30.566  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-29 13:12:30.566  7519  7519 D HeadsetProfile: Bluetooth service disconnected
08-29 13:12:30.566  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:30.566  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.566  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.576  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-29 13:12:30.576  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:12:30.576  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-29 13:12:30.576  1014  3937 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:30.576  1014  3937 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.576  1014  3937 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:30.576  1014  3937 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:30.576  1014  3937 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.576  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-29 13:12:30.576  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:12:30.576  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-29 13:12:30.576  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:30.576  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.576  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.576  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.576  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.586  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.586  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.586  7605  7620 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:30.586  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:30.586  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.586  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.586  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:30.586  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.586  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 13:12:30.586  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 13:12:30.586  7605  7620 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:12:30.586  1014  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:30.586  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.586  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.596  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.596  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:12:30.596  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:30.596  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:12:30.596  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:12:30.596  7605  7620 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:12:30.596  7605  7620 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:12:30.596  7605  7620 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-29 13:12:30.596  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-29 13:12:30.596  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,08-29 13:12:30.596  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:30.596  7605  7605 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-29 13:12:30.596  7605  7605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-29 13:12:30.596  7605  7605 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 13:12:30.606  7605  7605 D A2dpService: Received stop request...Stopping profile...
,08-29 13:12:30.606  7605  7649 D A2dpStateMachine: Exit Disconnected: -1
,08-29 13:12:30.606  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.606  1014  1014 D BluetoothA2dp: Proxy object disconnected
,08-29 13:12:30.606  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-29 13:12:30.606  7605  7605 D HidService: Received stop request...Stopping profile...
08-29 13:12:30.606  7605  7605 D HidService: Stopping Bluetooth HidService
08-29 13:12:30.606  7605  7605 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 13:12:30.606  7605  7605 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-29 13:12:30.606  7605  7605 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 13:12:30.606  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.606  7519  7519 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:30.606  7519  7519 D A2dpProfile: Bluetooth service disconnected
,08-29 13:12:30.616  7519  7519 D BluetoothInputDevice: Proxy object disconnected
08-29 13:12:30.616  7519  7519 D HidProfile: Bluetooth service disconnected
,08-29 13:12:30.616  7605  7605 D HealthService: Received stop request...Stopping profile...
,08-29 13:12:30.616  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.616  7605  7605 D PanService: Received stop request...Stopping profile...
,08-29 13:12:30.616  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.616  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-29 13:12:30.616  7605  7605 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 13:12:30.626  7519  7519 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 13:12:30.626  7519  7519 D PanProfile: Bluetooth service disconnected
,08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.626  7605  7605 D SapService: Received stop request...Stopping profile...
08-29 13:12:30.626  7605  7605 D SapService: Stopping Bluetooth SapService
08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:30.626  7519  7519 D BluetoothMap: Proxy object disconnected
08-29 13:12:30.626  7519  7519 D MapProfile: Bluetooth service disconnected
08-29 13:12:30.626  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-29 13:12:30.626  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:30.626  7519  7519 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-29 13:12:30.626  7519  7519 D SapProfile: Bluetooth service disconnected
08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-29 13:12:30.626  7605  7605 D BluetoothA2dp: Proxy object disconnected
08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-29 13:12:30.626  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-29 13:12:30.626  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.626  7605  7650 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-29 13:12:30.626  7605  7605 I GKI_LINUX: GKI_exit_task 2 done
,08-29 13:12:30.626  7605  7605 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-29 13:12:30.626  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-29 13:12:30.626  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.626  7605  7605 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:30.626  7605  7605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 13:12:30.636  7605  7605 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-29 13:12:30.636  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-29 13:12:30.636  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.636  7605  7605 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:30.636  7605  7605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 13:12:30.636  7605  7605 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 13:12:30.636  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-29 13:12:30.636  7605  7605 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:12:30.636  7605  7605 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-29 13:12:30.636  7605  7605 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-29 13:12:30.636  7605  7605 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-29 13:12:30.636  7605  7605 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-29 13:12:30.636  7605  7620 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-29 13:12:30.636  7605  7620 D BluetoothAdapterProperties: Setting state to 10
,08-29 13:12:30.636  7605  7620 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-29 13:12:30.636  7605  7620 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 13:12:30.636  7605  7620 D BluetoothAdapterService: updateAdapterState state is 10
,08-29 13:12:30.636  7605  7620 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:12:30.636  7605  7620 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
,08-29 13:12:30.636  7605  7620 I BluetoothAdapterState: Entering OffState
08-29 13:12:30.636  7655  7666 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:30.636  7655  7666 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.636  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:30.636  1014  1044 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:30.636  7519  7528 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-29 13:12:30.646  6916  6930 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.646  6916  6930 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.646  6916  6930 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-29 13:12:30.646  6916  6930 D BluetoothLeAdvertiser: Exit stop advertising
,08-29 13:12:30.646  6916  6930 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-29 13:12:30.646  6916  6930 D BluetoothLeScanner: Exiting stopAllScan
,08-29 13:12:30.646  1455  1483 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.646  1455  1483 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.646  7605  7613 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:12:30.646  1446  1482 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.646  1446  1482 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.646  7519  7527 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.646  7519  7527 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.646  7519  7528 D Bluetoothsap: onBluetoothStateChange: up=false
,08-29 13:12:30.646  7519  7528 D Bluetoothsap: Unbinding service...
,08-29 13:12:30.646  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:12:30.656  7519  7527 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 13:12:30.656  7519  7528 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-29 13:12:30.656  7605  7713 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.656  7605  7713 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.656  1984  1993 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.656  1984  1993 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.656  1469  1485 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-29 13:12:30.656  1469  1485 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-29 13:12:30.656  7519  7528 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 13:12:30.656  1176  1759 D BluetoothAdapter: onBluetoothStateChange: up=false
08-29 13:12:30.656  1176  1759 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-29 13:12:30.666  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 13:12:30.666  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 13:12:30.676  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:30.676  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,08-29 13:12:30.676  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:12:30.676  7605  7623 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-29 13:12:30.676  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
,08-29 13:12:30.676  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:30.676  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:30.676  1176  1176 D BluetoothTile:  getBluetoothState : 10
08-29 13:12:30.676  1176  1723 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
,08-29 13:12:30.676  1176  1723 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:30.676  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:30.676  7605  7605 I GKI_LINUX: GKI_exit_task 1 done
08-29 13:12:30.676  7605  7605 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-29 13:12:30.676  7605  7605 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 13:12:30.686  1176  1176 D BluetoothAdapter: 721489179: getState() :  mService = null. Returning STATE_OFF
08-29 13:12:30.686  1963  1963 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:30.686  1014  1533 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:30.686  1014  4809 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:12:30.686  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-29 13:12:30.686  1984  2165 D BluetoothAdapter: 591968253: getState() :  mService = null. Returning STATE_OFF
,08-29 13:12:30.686  1984  2165 D BluetoothAdapter: 591968253: getState() :  mService = null. Returning STATE_OFF
,08-29 13:12:30.686  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:30.686  7519  7519 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:30.686  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:30.686  1014  1534 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:30.686  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.686  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:30.686  1014  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:30.686  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:30.696  7519  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:30.696  1014  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 13:12:30.696  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:30.696  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.696  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:30.696  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:30.696  7605  7605 I art     : System.exit called, status: 0
08-29 13:12:30.696  7605  7605 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 13:12:30.706  7519  7519 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:30.706  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:30.706  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:30.706  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-29 13:12:30.796   287   287 E SMD     : DCD OFF
,08-29 13:12:30.826  1014  3937 I ActivityManager: Process com.android.bluetooth (pid 7605)(adj 0) has died(42,723)
,08-29 13:12:30.836  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:30.836  1014  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
08-29 13:12:30.836  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:30.836  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-29 13:12:30.836  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:30.836  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:30.846  1984  7743 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 13:12:30.856  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:30.856  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:30.866  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:30.866  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-29 13:12:30.866  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:30.876  1984  7743 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-29 13:12:31.756  1014  1047 I PowerManagerService: [PWL] Off : 75s ago
,08-29 13:12:31.756  1014  1047 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,08-29 13:12:31.756  1014  1047 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-29 13:12:31.756  1014  1047 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=13444)
,08-29 13:12:31.926  1014  1332 E Watchdog: !@Sync 4
,08-29 13:12:32.776   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:32.906  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop,
08-29 13:12:32.906  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:33.776   321   321 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 13:12:33.806   287   287 E SMD     : DCD OFF,
,08-29 13:12:34.776   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:35.576  1014  3400 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 13:12:35.776   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:35.906  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 13:12:35.906  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13d6cfc1 added. We now have 6 listener(s)
08-29 13:12:35.906  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:35.906  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:35.906  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16097366 added. We now have 7 listener(s)
08-29 13:12:35.906  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:35.906  6916  6969 I System.out: IsBluetoothEnabled
08-29 13:12:35.906  6916  6969 D BluetoothAdapter: disable()
,08-29 13:12:35.916  1014  1504 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-29 13:12:35.916  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:35.916  6916  6969 D BluetoothAdapter: enable()
,08-29 13:12:35.916  1014  1533 W ActivityManager: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:12:35.926  1014  1533 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2256)
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:688)
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-29 13:12:35.926  1014  1533 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-29 13:12:35.926  1014  1533 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:12:35.926  1014  1533 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:35.936  1014  1533 D SettingsProvider: name = bluetooth_on,
,08-29 13:12:35.936  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-29 13:12:35.936  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:35.936  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-29 13:12:35.936  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-29 13:12:35.946  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:35.946  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:35.946  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-29 13:12:35.946  1014  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:35.956  7750  7750 E Zygote  : MountEmulatedStorage()
08-29 13:12:35.956  1014  1044 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=7750 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-29 13:12:35.956  7750  7750 E Zygote  : v2
08-29 13:12:35.956  7750  7750 I libpersona: KNOX_SDCARD checking this for 1002
08-29 13:12:35.956  7750  7750 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:35.956  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:12:35.966  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:12:35.966  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:35.986  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:35.986  7750  7750 D ActivityThread: Added TimaKeyStore provider,
,08-29 13:12:36.006  7750  7750 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-29 13:12:36.006  7750  7750 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:36.026  7750  7750 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding GattService
,08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding HeadsetService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding A2dpService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding HidService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding HealthService
,08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding PanService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding SapService
,08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding SapClientService
08-29 13:12:36.066  7750  7750 D BtSettings.ProfileConfig: Adding HidDevService
08-29 13:12:36.066  7750  7750 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-29 13:12:36.066  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-29 13:12:36.066  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.066  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.066  1014  1491 D SettingsProvider: selectionArgs: false
08-29 13:12:36.066  1014  1491 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.066  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.066  1014  1491 D SettingsProvider: ret = -1
,08-29 13:12:36.066  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-29 13:12:36.066  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.066  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.066  1014  1027 D SettingsProvider: selectionArgs: false
08-29 13:12:36.066  1014  1027 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.066  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.066  1014  1027 D SettingsProvider: ret = -1
,08-29 13:12:36.066  1014  3937 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-29 13:12:36.066  1014  3937 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.066  1014  3937 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.066  1014  3937 D SettingsProvider: selectionArgs: false
08-29 13:12:36.066  1014  3937 D SettingsProvider: selectionArgs: 1002
,08-29 13:12:36.066  1014  3937 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.066  1014  3937 D SettingsProvider: ret = -1
08-29 13:12:36.066  1014  1310 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-29 13:12:36.066  1014  1310 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.066  1014  1310 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-29 13:12:36.066  1014  1310 D SettingsProvider: selectionArgs: false
08-29 13:12:36.066  1014  1310 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.066  1014  1310 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.066  1014  1310 D SettingsProvider: ret = -1
08-29 13:12:36.066  1014  4809 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-29 13:12:36.066  1014  4809 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-29 13:12:36.066  1014  4809 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.066  1014  4809 D SettingsProvider: selectionArgs: false
08-29 13:12:36.066  1014  4809 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.066  1014  4809 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.066  1014  4809 D SettingsProvider: ret = -1
,08-29 13:12:36.066  1014  1504 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-29 13:12:36.066  1014  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.066  1014  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.066  1014  1504 D SettingsProvider: selectionArgs: false
,08-29 13:12:36.066  1014  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1504 D SettingsProvider: ret = -1
,08-29 13:12:36.076  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:36.076  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.076  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1026 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1026 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-29 13:12:36.076  1014  1026 D SettingsProvider: ret = -1
08-29 13:12:36.076  1014  1458 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-29 13:12:36.076  1014  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-29 13:12:36.076  1014  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1458 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1458 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1458 D SettingsProvider: ret = -1
,08-29 13:12:36.076  1014  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:36.076  1014  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.076  1014  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1493 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1493 D SettingsProvider: selectionArgs: 1002,
08-29 13:12:36.076  1014  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1493 D SettingsProvider: ret = -1
08-29 13:12:36.076  1014  1533 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:36.076  1014  1533 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.076  1014  1533 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1533 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1533 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1533 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1533 D SettingsProvider: ret = -1
08-29 13:12:36.076  1014  1534 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-29 13:12:36.076  1014  1534 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.076  1014  1534 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1534 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1534 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1534 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1534 D SettingsProvider: ret = -1
08-29 13:12:36.076  1014  1094 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-29 13:12:36.076  1014  1094 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.076  1014  1094 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.076  1014  1094 D SettingsProvider: selectionArgs: false
08-29 13:12:36.076  1014  1094 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.076  1014  1094 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.076  1014  1094 D SettingsProvider: ret = -1
,08-29 13:12:36.086  7750  7750 D BluetoothAdapterState: make,
,08-29 13:12:36.096  7750  7750 I bluedroid: init,
08-29 13:12:36.096  7750  7765 I BluetoothAdapterState: Entering OffState
,08-29 13:12:36.096  7750  7750 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-29 13:12:36.096  7750  7750 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 13:12:36.096  7750  7750 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 13:12:36.096  7750  7750 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-29 13:12:36.096  7750  7750 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-29 13:12:36.096  7750  7768 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-29 13:12:36.096  7750  7750 I bluedroid: get_profile_interface socket
08-29 13:12:36.096  7750  7750 I bluedroid: get_profile_interface map_client
,08-29 13:12:36.096  7750  7750 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-29 13:12:36.106  7750  7768 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27,
08-29 13:12:36.106  7750  7768 E BluetoothServiceJni: populateRssiValuesNative
08-29 13:12:36.106  7750  7768 I bluedroid: getModelRssiValues
08-29 13:12:36.106  7750  7768 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 13:12:36.106  7750  7768 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127,
08-29 13:12:36.106  7750  7750 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
08-29 13:12:36.106  1014  1534 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:12:36.106  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.106  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:36.106  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.106  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.106  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 13:12:36.106  7750  7768 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 13:12:36.116  7750  7758 I bluedroid: config_hci_snoop_log
,08-29 13:12:36.116  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 13:12:36.116  1014  1044 D BluetoothManagerService: Ble is always on enable gatt
,08-29 13:12:36.116  1014  1044 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-29 13:12:36.116  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-29 13:12:36.116  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:12:36.116  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:36.116  7750  7750 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-29 13:12:36.116  1014  1044 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-29 13:12:36.126  1014  1044 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-29 13:12:36.126  7750  7765 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-29 13:12:36.126  7750  7765 D BluetoothAdapterProperties: Setting state to 11
,08-29 13:12:36.126  1014  1044 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-29 13:12:36.126  7750  7765 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-29 13:12:36.126  7750  7765 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-29 13:12:36.136  7750  7765 D BluetoothAdapterService: updateAdapterState state is 11
,08-29 13:12:36.136  7750  7765 D BluetoothAdapterService: Autoconnection is available 
,08-29 13:12:36.136  7750  7765 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-29 13:12:36.136  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:36.136  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,08-29 13:12:36.136  7750  7765 D BluetoothSecureManager: getInstant: null
08-29 13:12:36.136  7750  7765 D BluetoothSecureManager: calling getMethod for getService
,08-29 13:12:36.136  7750  7765 D BluetoothSecureManager: calling getService
,08-29 13:12:36.146  7750  7765 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@ee10da9
,08-29 13:12:36.146  1014  1458 D BluetoothSecureManagerService: isSecureModeEnabled
,08-29 13:12:36.146  1014  1458 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-29 13:12:36.146  7750  7765 D BtConfig.SecureMode: isSecureModeOn:false
08-29 13:12:36.146  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-29 13:12:36.146  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-29 13:12:36.146  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:36.146  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-29 13:12:36.146  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:36.146  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:36.146  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:36.146  1176  1176 D BluetoothTile:  getBluetoothState : 11
,08-29 13:12:36.146  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:36.146  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-29 13:12:36.146  1963  1963 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:36.156  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-29 13:12:36.156  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-29 13:12:36.156  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-29 13:12:36.156  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:12:36.156  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-29 13:12:36.156  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:36.156  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
08-29 13:12:36.156  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-29 13:12:36.156  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:36.156  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-29 13:12:36.156  7519  7519 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-29 13:12:36.156  1014  1094 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-29 13:12:36.156  7750  7765 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-29 13:12:36.156  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-29 13:12:36.156  1014  1458 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-29 13:12:36.166  7750  7765 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:36.166  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-29 13:12:36.166  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-29 13:12:36.166  7750  7765 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:36.166  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-29 13:12:36.166  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:36.166  7750  7765 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:36.166  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-29 13:12:36.166  7750  7765 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-29 13:12:36.166  1014  1535 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-29 13:12:36.166  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.166  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:36.166  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:36.166  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:36.176  7750  7765 D BluetoothBondStateMachine: make
,08-29 13:12:36.176  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:36.176  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-29 13:12:36.176  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-29 13:12:36.176  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-29 13:12:36.186  7750  7771 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 13:12:36.186  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:36.186  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
08-29 13:12:36.186  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:36.186  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.186  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.186  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.186  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.186  7750  7750 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 13:12:36.186  7750  7750 D BtGatt.GattService: Received start request. Starting profile...
,08-29 13:12:36.186  7750  7750 D BtGatt.GattService: start()
08-29 13:12:36.186  7750  7750 D BtGatt.GattService: start()
,08-29 13:12:36.186  7750  7750 I bluedroid: get_profile_interface gatt
,08-29 13:12:36.196  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:36.196  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-29 13:12:36.196  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-29 13:12:36.196  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-29 13:12:36.196  7750  7750 D BtGatt.AdvertiseManager: advertise manager created
,08-29 13:12:36.196  1014  1534 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:36.196  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.196  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:36.196  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.196  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.206  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-29 13:12:36.206  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-29 13:12:36.206  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-29 13:12:36.206  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:36.206  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.206  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:36.206  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.206  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.216  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-29 13:12:36.216  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-29 13:12:36.216  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-29 13:12:36.216  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:36.216  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.216  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.216  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.216  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.216  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-29 13:12:36.216  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-29 13:12:36.216  7750  7750 D BtGatt.GattService: mStartError = false
08-29 13:12:36.216  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-29 13:12:36.216  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.216  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:36.216  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
08-29 13:12:36.216  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.216  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.216  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.226  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-29 13:12:36.226  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-29 13:12:36.226  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-29 13:12:36.226  1014  1094 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-29 13:12:36.226  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.226  7750  7750 D HeadsetService: Received start request. Starting profile...
08-29 13:12:36.226  7750  7750 D HeadsetService: start()
,08-29 13:12:36.226  7750  7750 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 13:12:36.226  1014  1094 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:36.226  7750  7750 D HeadsetStateMachine: make
08-29 13:12:36.226  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.226  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.226  7750  7750 E HeadsetStateMachine: # of Max HF connection is 2
,08-29 13:12:36.236  1014  2048 V SAMP_SPCM_test: CSC File load.. 
,08-29 13:12:36.236  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:36.236  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-29 13:12:36.236  7750  7765 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-29 13:12:36.246  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
,08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-29 13:12:36.256  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-29 13:12:36.276  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password,
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-29 13:12:36.296  1014  1535 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-29 13:12:36.296  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
,08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-29 13:12:36.286  1014  2048 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-29 13:12:36.296  1014  1535 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:36.296  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.296  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.296  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-29 13:12:36.296  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-29 13:12:36.296  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.296  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.296  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-29 13:12:36.296  1014  2048 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm
08-29 13:12:36.296  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-29 13:12:36.296  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-29 13:12:36.296  7750  7765 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-29 13:12:36.296  1014  2048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:36.296  1014  2048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:36.296  1014  2048 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:36.296  1014  2048 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:36.316  7778  7778 E Zygote  : MountEmulatedStorage(),
,08-29 13:12:36.316  1014  2048 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=7778 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:36.316  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:36.316  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-29 13:12:36.316  7778  7778 E Zygote  : v2
08-29 13:12:36.316  7778  7778 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:36.316  7778  7778 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:36.316  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.316  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.316  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:36.316  1014  1026 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-29 13:12:36.316  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:36.316  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:36.316  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:36.316  7778  7778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:36.316  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:36.316  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:36.316  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-29 13:12:36.316  7750  7750 I bluedroid: get_profile_interface handsfree
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-29 13:12:36.316  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-29 13:12:36.316  7750  7765 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-29 13:12:36.316  7750  7765 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-29 13:12:36.316  7750  7765 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-29 13:12:36.316  7778  7778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:36.316  7778  7778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:36.336  7750  7750 I DualScoManager: Instantiating Dual Sco Manager
,08-29 13:12:36.336  7750  7750 I DualScoManager: Set HeadsetServiceHelper
,08-29 13:12:36.336  7750  7750 D BluetoothAtMessage: createCMTIContentObservers
,08-29 13:12:36.346  1014  1504 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-29 13:12:36.346  1014  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:36.346  1014  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:36.346  1014  1504 D SettingsProvider: selectionArgs: false
,08-29 13:12:36.346  1014  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:12:36.346  1014  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:36.346  1014  1504 D SettingsProvider: ret = -1
,08-29 13:12:36.346  7750  7750 D HeadsetService: mStartError = false
08-29 13:12:36.346  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.346  7750  7777 D HeadsetStateMachine: Enter Disconnected: -2
08-29 13:12:36.346  7750  7750 D A2dpService: Received start request. Starting profile...
08-29 13:12:36.346  7750  7750 D A2dpService: start()
,08-29 13:12:36.346  7778  7778 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:36.346  7750  7750 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 13:12:36.346  7750  7750 I bluedroid: get_profile_interface avrcp
08-29 13:12:36.346  7778  7778 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:36.356  7750  7777 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-29 13:12:36.356  7750  7777 D HeadsetStateMachine: map size, before remove : 0
08-29 13:12:36.356  7750  7777 D HeadsetStateMachine: map size, after remove: 0
,08-29 13:12:36.356  7750  7750 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 13:12:36.356  7750  7750 D Avrcp   : Initialize Media Controller
08-29 13:12:36.356  7750  7750 D Avrcp   : Get the Context Package Name: com.android.bluetooth
,08-29 13:12:36.356  7750  7750 E Avrcp   : getActiveSessions
08-29 13:12:36.356  7750  7750 D Avrcp   : pick active media Controller
08-29 13:12:36.356  7750  7750 D Avrcp   : Get the active Media Controller 
,08-29 13:12:36.366  7778  7778 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:36.376  7750  7750 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-29 13:12:36.376  7750  7793 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-29 13:12:36.376  7750  7750 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 13:12:36.376  7750  7750 D A2dpStateMachine: make
,08-29 13:12:36.376  7750  7750 I bluedroid: get_profile_interface a2dp
,08-29 13:12:36.386  7750  7795 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-29 13:12:36.386  7750  7750 E bt-btif : warning : media task started media_task_refcnt 1 
,08-29 13:12:36.386  7750  7750 D A2dpService: mStartError = false
,08-29 13:12:36.386  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.386  7750  7750 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 13:12:36.386  7750  7794 D A2dpStateMachine: Enter Disconnected: -2
,08-29 13:12:36.386  7750  7750 D HidService: Received start request. Starting profile...
08-29 13:12:36.386  7750  7750 D HidService: start()
08-29 13:12:36.386  7750  7750 I bluedroid: get_profile_interface hidhost
08-29 13:12:36.386  7750  7750 D HidService: setHidService(): set to: null
08-29 13:12:36.386  7750  7750 D HidService: mStartError = false
08-29 13:12:36.386  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.386  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-29 13:12:36.386  7750  7750 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-29 13:12:36.396  7750  7750 D HealthService: Received start request. Starting profile...
08-29 13:12:36.396  7750  7750 D HealthService: start()
,08-29 13:12:36.396  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-29 13:12:36.396  7750  7750 I bluedroid: get_profile_interface health
08-29 13:12:36.396  7750  7750 D HealthService: mStartError = false
08-29 13:12:36.396  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.396  7750  7750 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 13:12:36.396  7750  7750 D PanService: Received start request. Starting profile...
,08-29 13:12:36.396  7750  7750 D PanService: start()
08-29 13:12:36.396  7750  7750 D BluetoothPanServiceJni: initializeNative(L110): pan
,08-29 13:12:36.396  7750  7750 I bluedroid: get_profile_interface pan
,08-29 13:12:36.406  7750  7750 D PanService: mStartError = false
08-29 13:12:36.406  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.406  7750  7793 D BluetoothMediaBrowser: no now playing list
,08-29 13:12:36.406  7750  7793 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-29 13:12:36.406  7750  7750 D BluetoothMapService: Received start request. Starting profile...
,08-29 13:12:36.406  7750  7750 D BluetoothMapService: start()
,08-29 13:12:36.406  7750  7750 D BluetoothMapService: mStartError = false
08-29 13:12:36.406  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:36.406  7750  7750 D HeadsetStateMachine: Try to query the phonestate on bind
,08-29 13:12:36.406  1446  1467 I Telecom : BluetoothPhoneService: queryPhoneState
,08-29 13:12:36.406  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-29 13:12:36.406  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-29 13:12:36.416  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:36.416  1446  1467 I Telecom : BluetoothPhoneService: Result of Message : true
,08-29 13:12:36.416  7750  7750 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-29 13:12:36.416  7750  7750 D HeadsetStateMachine: Proxy object connected
,08-29 13:12:36.416  7750  7750 D SapService: Received start request. Starting profile...
08-29 13:12:36.416  7750  7750 D SapService: start()
08-29 13:12:36.416  7750  7750 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-29 13:12:36.416  7750  7750 I bluedroid: get_profile_interface sap
08-29 13:12:36.416  7750  7750 D SapService: mStartError = false
08-29 13:12:36.416  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:36.416  7750  7750 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-29 13:12:36.416  7750  7750 D HeadsetPhoneState: sendDeviceDataStateChanged
08-29 13:12:36.416  7750  7750 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-29 13:12:36.416  7750  7777 D HeadsetStateMachine: Disconnected process message: 11
08-29 13:12:36.416  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-29 13:12:36.416  7750  7750 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-29 13:12:36.416  7750  7750 D BluetoothA2dp: Proxy object connected
08-29 13:12:36.416  7750  7750 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-29 13:12:36.416  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-29 13:12:36.416  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-29 13:12:36.416  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-29 13:12:36.416  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-29 13:12:36.416  7750  7777 D HeadsetStateMachine: Disconnected process message: 18
08-29 13:12:36.416  7750  7777 D HeadsetStateMachine: Disconnected process message: 10
08-29 13:12:36.416  7750  7777 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 13:12:36.416  7750  7777 D HeadsetStateMachine: Disconnected process message: 11
,08-29 13:12:36.416  1014  2048 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-29 13:12:36.426  1014  1014 I ActivityManager: Killing 7242:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-29 13:12:36.446  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-29 13:12:36.446  7750  7750 E BluetoothAdapterService(1058214680): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-29 13:12:36.446  7750  7765 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-29 13:12:36.446  7750  7765 I bluedroid: enable
08-29 13:12:36.446  7750  7765 I bt_hci_bdroid: init
,08-29 13:12:36.446  7750  7800 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-29 13:12:36.456  7750  7765 I bt_vendor: bt-vendor : init
08-29 13:12:36.456  7750  7765 I bt_vendor: bt-vendor : get_bt_soc_type
08-29 13:12:36.456  7750  7765 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-29 13:12:36.456  7750  7765 I bt_vendor: init: Local BD Address : 27:76:50:a9:ec:08
08-29 13:12:36.456  7750  7765 D bt_userial_mct: userial_init
08-29 13:12:36.456  7750  7765 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-29 13:12:36.456  7750  7765 I bt_vendor: Starting hciattach daemon
08-29 13:12:36.456  7750  7765 I bt_vendor: try to set false
,08-29 13:12:36.456  7750  7765 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-29 13:12:36.456  7750  7765 I bt_vendor: Starting hciattach daemon
,08-29 13:12:36.456  7750  7765 I bt_vendor: try to set true
,08-29 13:12:36.466  7804  7804 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-29 13:12:36.516  7810  7810 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-29 13:12:36.516  7811  7811 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-29 13:12:36.536  7813  7813 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 13:12:36.546  7814  7814 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-29 13:12:36.546  7815  7815 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-29 13:12:36.556  7816  7816 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-29 13:12:36.776   321   321 I ServiceManager: Waiting for service AtCmdFwd...,
,08-29 13:12:36.796  7819  7819 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 08:ec:a9:50:76:27 ,
,08-29 13:12:36.796   287   287 E SMD     : DCD OFF,
,08-29 13:12:36.806  7820  7820 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-29 13:12:36.856  7750  7765 I bt_vendor: bluetooth satus is on,
08-29 13:12:36.856  7750  7802 D bt_userial_mct: userial_open(port:0)
08-29 13:12:36.856  7750  7802 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
08-29 13:12:36.856  7750  7802 I bt_vendor: Done intiailizing UART,
08-29 13:12:36.856  7750  7802 I bt_vendor: Done intiailizing UART
08-29 13:12:36.856  7750  7802 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66,
08-29 13:12:36.866  7750  7802 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-29 13:12:36.866  7750  7822 D bt_userial_mct: Entering userial_read_thread()
,08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 13:12:36.866  7750  7800 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_PAN
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_SAP
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_SDP
,08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_BTIF
08-29 13:12:36.876  7750  7800 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-29 13:12:36.886  1014  3371 D SSRM:n  : SIOP:: AP = 340
,08-29 13:12:36.966  7750  7800 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-29 13:12:36.966  7750  7800 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa41d9ed1 
,08-29 13:12:36.976  7750  7800 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa41d9ed1 
,08-29 13:12:36.986  7750  7768 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-29 13:12:36.986  7750  7768 E bt-btif : Calling BTA_HhEnable
,08-29 13:12:36.986  7750  7768 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-29 13:12:36.996  7750  7768 D BluetoothAdapterProperties: Address is:08:EC:A9:50:76:27
08-29 13:12:36.996  7750  7768 E BluetoothServiceJni: populateRssiValuesNative
08-29 13:12:36.996  7750  7768 I bluedroid: getModelRssiValues
08-29 13:12:36.996  7750  7768 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-29 13:12:36.996  7750  7768 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-29 13:12:36.996  7750  7768 D BluetoothAdapterProperties: Name is: Thali Test (Galaxy A3)
,08-29 13:12:36.996  1014  1014 D SettingsProvider: name = bluetooth_name
,08-29 13:12:36.996  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:37.006  7750  7768 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-29 13:12:37.006  7750  7768 D BluetoothAdapterProperties: Scan Mode:20
08-29 13:12:37.006  7750  7768 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 13:12:37.006  7750  7768 D BluetoothAdapterProperties: LE Address is:C8:D9:53:A0:EC:4E
08-29 13:12:37.006  7750  7768 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-29 13:12:37.006  7750  7768 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-29 13:12:37.006  7750  7768 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-29 13:12:37.006  7750  7768 E bt-btif : btif_sock_init: !vhci_init
08-29 13:12:37.006  7750  7768 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-29 13:12:37.006  7750  7768 D IOP_DB_BT: db_open: db_open : handle 3027726352l, read 13894 bytes onto local cache
08-29 13:12:37.006  7750  7768 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-29 13:12:37.006  7750  7768 D IOP_DB_BT: db_query: result 1
08-29 13:12:37.006  7750  7768 I         : iop_db_open: iop_db_open status 0
08-29 13:12:37.006  7750  7768 D bte_conf: Device ID record 1 : primary
08-29 13:12:37.006  7750  7768 D bte_conf:   vendorId            = 0075
08-29 13:12:37.006  7750  7768 D bte_conf:   vendorIdSource      = 0001
08-29 13:12:37.006  7750  7768 D bte_conf:   product             = 0100
08-29 13:12:37.006  7750  7768 D bte_conf:   version             = 0200
08-29 13:12:37.006  7750  7768 D bte_conf:   clientExecutableURL = 
08-29 13:12:37.006  7750  7768 D bte_conf:   serviceDescription  = 
08-29 13:12:37.006  7750  7768 D bte_conf:   documentationURL    = 
08-29 13:12:37.006  7750  7768 D bte_conf: bte_load_did_conf no section named DID2.
,08-29 13:12:37.006  7750  7768 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 13:12:37.006  7750  7765 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-29 13:12:37.006  7750  7765 D BluetoothAdapterProperties: ScanMode =  20
08-29 13:12:37.006  7750  7765 D BluetoothAdapterProperties: State =  11
,08-29 13:12:37.006  7750  7822 E bt_mct  : hci lib postload completed
,08-29 13:12:37.006  1014  1310 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-29 13:12:37.006  7750  7765 D BluetoothAdapterProperties: Setting state to 12
08-29 13:12:37.006  7750  7765 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:37.016  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:37.016  7750  7768 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-29 13:12:37.016  7750  7768 D BluetoothAdapterProperties: Scan Mode:21
08-29 13:12:37.016  7750  7768 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-29 13:12:37.016  1014  1504 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-29 13:12:37.016  1014  1504 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:37.016  1014  1504 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:37.016  1014  1504 D SettingsProvider: selectionArgs: false
08-29 13:12:37.016  1014  1504 D SettingsProvider: selectionArgs: 1002
08-29 13:12:37.016  1014  1504 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:37.016  1014  1504 D SettingsProvider: ret = -1
08-29 13:12:37.026  7750  7765 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-29 13:12:37.026  7750  7765 D BluetoothAdapterService: updateAdapterState state is 12
,08-29 13:12:37.026  1014  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:37.026  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.026  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.026  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.026  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.026  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:37.026  7750  7765 D BluetoothAdapterService: Autoconnection is available 
08-29 13:12:37.026  7750  7765 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-29 13:12:37.026  7750  7765 D BluetoothAdapterService: starting service from this receiver
,08-29 13:12:37.026  7655  7669 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:12:37.026  1014  1533 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:37.036  7655  7669 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:12:37.036  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-29 13:12:37.036  1014  1044 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.036  1014  1044 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:12:37.036  7519  7527 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 13:12:37.036  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.036  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.036  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.046  7750  7765 I BluetoothAdapterState: Entering On State from state = 11
,08-29 13:12:37.056  7750  7750 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-29 13:12:37.206  1014  1044 I art     : Explicit concurrent mark sweep GC freed 27304(1550KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 24MB/36MB, paused 2.357ms total 166.496ms
08-29 13:12:37.206  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-29 13:12:37.206  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.206  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.206  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.206  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.206  6916  6929 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.206  6916  6929 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.206  1455  1483 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:12:37.206  1455  1483 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.206  1446  1482 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.206  1446  1482 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.206  7519  7528 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.206  7519  7528 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.206  1014  1044 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.206  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:37.206  1014  1044 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:12:37.206  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-29 13:12:37.206  7750  7750 I BluetoothPbapService: Handler(): got msg=1
08-29 13:12:37.206  7519  7527 D Bluetoothsap: onBluetoothStateChange: up=true
,08-29 13:12:37.206  7519  7527 D Bluetoothsap: Binding service...
,08-29 13:12:37.216  1014  1027 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 13:12:37.216  7519  7519 D BluetoothInputDevice: Proxy object connected
,08-29 13:12:37.216  7519  7519 D HidProfile: Bluetooth service connected
,08-29 13:12:37.216  7519  7527 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-29 13:12:37.216  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-29 13:12:37.216  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.216  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.216  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.216  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.226  7519  7527 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-29 13:12:37.226  7750  7827 V BluetoothPbapService: PBAP Service initSocket try: 0
08-29 13:12:37.226  7750  7759 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:37.226  7519  7519 D Bluetoothsap: BluetoothSAP Proxy object connected
08-29 13:12:37.226  7519  7519 D SapProfile: Bluetooth service connected
08-29 13:12:37.226  7519  7519 D Bluetoothsap: getConnectedDevices()
,08-29 13:12:37.226  1014  1044 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 13:12:37.226  1014  1044 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.226  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:12:37.226  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.226  1014  1014 D BluetoothA2dp: Proxy object connected
,08-29 13:12:37.226  7519  7528 D BluetoothMap: onBluetoothStateChange: up=true
,08-29 13:12:37.226  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-29 13:12:37.226  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
08-29 13:12:37.226  7750  7827 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:12:37.226  7750  7827 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:37.226  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.226  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.226  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.226  7519  7519 D BluetoothMap: Proxy object connected
08-29 13:12:37.226  7519  7527 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-29 13:12:37.226  7519  7519 D MapProfile: Bluetooth service connected
,08-29 13:12:37.226  7750  7827 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-29 13:12:37.226  7750  7827 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:12:37.226  7750  7827 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:37.226  7750  7827 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16daebf2
08-29 13:12:37.226  7519  7519 D BluetoothMap: getConnectedDevices()
,08-29 13:12:37.236  7750  7827 D BluetoothSocket: channel: 19
08-29 13:12:37.236  7750  7827 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-29 13:12:37.236  7519  7527 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.236  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-29 13:12:37.236  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.236  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.236  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.236  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.236  1446  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.236  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:37.236  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:37.236  7519  7519 D BluetoothA2dp: Proxy object connected
08-29 13:12:37.236  7519  7519 D A2dpProfile: Bluetooth service connected
08-29 13:12:37.236  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.236  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:37.236  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.236  1446  1467 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:37.236  1446  1482 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.246  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:12:37.246  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:37.246  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.246  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.246  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.246  1446  1482 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:37.246  7519  7826 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.246  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-29 13:12:37.246  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:37.246  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.246  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.246  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.246  7519  7519 D HeadsetProfile: Bluetooth service connected
08-29 13:12:37.246  7519  7826 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:37.246  1014  1044 D BluetoothPan: Binding service...
,08-29 13:12:37.256  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-29 13:12:37.256  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.256  1984  2159 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-29 13:12:37.256  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 13:12:37.256  1984  2159 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.256  1469  1485 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.256  1469  1485 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.256  7519  7527 D BluetoothPbap: onBluetoothStateChange: up=true
,08-29 13:12:37.256  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-29 13:12:37.256  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.256  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.256  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.256  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.256  1469  1486 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.256  1014  1044 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:37.256  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:37.256  7519  7519 D BluetoothPbap: Proxy object connected
08-29 13:12:37.256  7519  7519 D PbapServerProfile: Bluetooth service connected
08-29 13:12:37.256  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.256  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.256  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.256  1469  1486 E BluetoothHeadset: BluetoothHeadset service is binded
,08-29 13:12:37.256  7750  7759 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.256  7750  7759 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-29 13:12:37.256  1176  1194 D BluetoothAdapter: onBluetoothStateChange: up=true
08-29 13:12:37.256  1176  1194 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-29 13:12:37.266  1446  1467 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-29 13:12:37.266  1014  1044 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-29 13:12:37.266  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-29 13:12:37.266  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.266  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.266  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.266  1446  1467 E BluetoothHeadset: BluetoothHeadset service is binded
08-29 13:12:37.266  7519  7826 D BluetoothPan: Binding service...
,08-29 13:12:37.266  1014  1044 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-29 13:12:37.266  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.266  1014  1044 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.266  1014  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.266  1014  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.266  7519  7519 D BluetoothPan: BluetoothPAN Proxy object connected
,08-29 13:12:37.266  7519  7519 D PanProfile: Bluetooth service connected
08-29 13:12:37.266  1014  1044 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-29 13:12:37.266  1014  1044 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-29 13:12:37.266  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:37.276  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
08-29 13:12:37.276  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-29 13:12:37.276  1446  1446 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@22f76caf, true
,08-29 13:12:37.276  1446  1446 D BluetoothHeadset: registerMessageListener
,08-29 13:12:37.276  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,08-29 13:12:37.276  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-29 13:12:37.276  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:37.286  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-29 13:12:37.286  1176  1176 D BluetoothTile:  getBluetoothState : 12
08-29 13:12:37.286  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:37.286  1176  1723 D BluetoothTile:  handleUpdatestate:false name:null
,08-29 13:12:37.286  7519  7519 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:37.286  1963  1963 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-29 13:12:37.286  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:37.286  1014  1535 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:37.286  1014  1094 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-29 13:12:37.296  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-29 13:12:37.296  7750  7758 D HeadsetService: registerMessageListener
08-29 13:12:37.296  7750  7758 D HeadsetService: registerMessageListener
08-29 13:12:37.296  7750  7777 D HeadsetStateMachine: Disconnected process message: 70
08-29 13:12:37.296  7750  7777 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1e466243
,08-29 13:12:37.296  1014  1310 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:37.296  1446  1446 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-29 13:12:37.296  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-29 13:12:37.296  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.296  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.296  1014  1310 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:37.296  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:37.296  7519  7519 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-29 13:12:37.296  7519  7519 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-29 13:12:37.296  7519  7519 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-29 13:12:37.296  7519  7519 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-29 13:12:37.306  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
08-29 13:12:37.306  1446  1446 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-29 13:12:37.306  1446  1446 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-29 13:12:37.306  7750  7829 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-29 13:12:37.306  7750  7777 D HeadsetStateMachine: Disconnected process message: 9
08-29 13:12:37.306  7750  7777 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-29 13:12:37.306   282   712 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-29 13:12:37.306   282   712 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-29 13:12:37.306   282   712 V voice   : voice_set_parameters: exit with code(-2)
08-29 13:12:37.306   282   712 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-29 13:12:37.306   282   712 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-29 13:12:37.306   282   712 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-29 13:12:37.306   282   712 V audio_hw_primary: adev_set_parameters: exit
,08-29 13:12:37.316  7750  7777 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-29 13:12:37.316  7750  7829 D BluetoothSocket: bindListen(): myUserId = 0
,08-29 13:12:37.316  7750  7829 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:37.316  7519  7519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 13:12:37.316  1014  1535 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-29 13:12:37.316  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.316  7750  7829 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-29 13:12:37.316  7750  7829 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:12:37.316  7750  7829 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:37.316  7750  7829 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18ba70c0
,08-29 13:12:37.316  7750  7829 D BluetoothSocket: channel: 5,
,08-29 13:12:37.316  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.316  1014  1535 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.316  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-29 13:12:37.326  7519  7519 D DockEventReceiver: finishStartingService: stopping service
,08-29 13:12:37.336  7519  7519 D BluetoothNotiBroadcastReceiver: onReceive
,08-29 13:12:37.336  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-29 13:12:37.336  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-29 13:12:37.346  7750  7750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
,08-29 13:12:37.346  7750  7750 D BtConfig.SecureMode: isSecureModeOn:false
,08-29 13:12:37.346  1014  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-29 13:12:37.346  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.346  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.346  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:37.346  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-29 13:12:37.366  1984  1984 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-29 13:12:37.366  1014  1534 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:37.366  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:37.366  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.366  1014  1534 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:37.366  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:37.376  1984  7836 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-29 13:12:37.376  1984  1984 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-29 13:12:37.376  1014  1458 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-29 13:12:37.386  1014  3937 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:37.386  1014  3937 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:37.386  1014  3937 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:37.386  1014  3937 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:37.396  1014  1535 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-29 13:12:37.396  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:37.396  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:37.396  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:37.406  7750  7839 D BluetoothSocket: bindListen(): myUserId = 0
08-29 13:12:37.406  7750  7839 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 13:12:37.406  7750  7839 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
08-29 13:12:37.406  7750  7839 D BluetoothSocket: bindListen(), new LocalSocket 
08-29 13:12:37.406  7750  7839 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-29 13:12:37.406  7750  7839 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10c8074a
08-29 13:12:37.406  7750  7839 D BluetoothSocket: channel: 12
08-29 13:12:37.406  7750  7839 I BtOppRfcommListener: Accept thread started.
,08-29 13:12:37.406  1984  7836 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-29 13:12:37.776   321   321 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:37.946  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:37.946  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:37.956  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:37.956  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a1366a7 added. We now have 8 listener(s)
,08-29 13:12:37.956  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:37.956  1014  1533 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-29 13:12:37.956  1014  1533 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-29 13:12:37.956  1014  1533 D SecContentProvider2: mCursor = null
,08-29 13:12:37.956  1014  1533 D WifiService: setWifiEnabled: false pid=6916, uid=10171
,08-29 13:12:37.956  1014  1533 D SettingsProvider: name = wifi_on
,08-29 13:12:37.966  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:37.966  1014  1027 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-29 13:12:37.966  1014  1027 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-29 13:12:37.966  1014  1027 D WifiService: setWifiEnabled: true pid=6916, uid=10171
08-29 13:12:37.966  1014  1027 D SecContentProvider2: mCursor = null
08-29 13:12:37.966  1014  1027 W ActivityManager: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
,08-29 13:12:37.966  1014  1027 W WifiService: Failed getting userId using ActivityManagerNative
08-29 13:12:37.966  1014  1027 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6916, uid=10171 requires android.permission.INTERACT_ACROSS_USERS
08-29 13:12:37.966  1014  1027 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23972)
08-29 13:12:37.966  1014  1027 W WifiService: ,	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-29 13:12:37.966  1014  1027 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-29 13:12:37.966  1014  1027 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-29 13:12:37.966  1014  1027 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446),
08-29 13:12:37.966  1014  1027 D SettingsProvider: name = wifi_on
,08-29 13:12:37.976  1014  1126 E WifiHW  : ##################### set firmware type 0 #####################,
,08-29 13:12:38.316  1014  1042 D Tethering: interfaceAdded wlan0
,08-29 13:12:38.316  1014  1129 E Tethering: No numeric data
,08-29 13:12:38.316  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:12:38.316  1014  1129 D Tethering: clearTetheredNotification()
,08-29 13:12:38.316  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:38.316  1176  1176 D HotspotTile: updateTetherState():false, false
,08-29 13:12:38.326  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:38.326  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:12:38.326  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 13:12:38.326  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:38.326  1014  1123 V NetworkStats: performPollLocked() took 6ms,
,08-29 13:12:38.326  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:12:38.336  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:38.326  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:38.326  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:38.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:38.336  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:38.336  1014  1129 D Tethering: InitialState.processMessage what=4
,08-29 13:12:38.336  1014  1129 E Tethering: No numeric data
,08-29 13:12:38.336  1014  1129 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 13:12:38.336  1014  1129 D Tethering: clearTetheredNotification()
08-29 13:12:38.336  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:38.336  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:38.336  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-29 13:12:38.336  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:38.336  1176  1176 D HotspotTile: updateTetherState():false, false
,08-29 13:12:38.346  1014  1042 D Tethering: interfaceAdded p2p0
,08-29 13:12:38.346  1014  1042 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-29 13:12:38.346  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:38.346  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:38.346  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
08-29 13:12:38.346  1014  1123 V NetworkStats: performPollLocked() took 10ms
08-29 13:12:38.346  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:38.346  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:38.356  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit,
08-29 13:12:38.356  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:38.356   277   998 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-29 13:12:38.356   277   998 D SoftapController: Softap fwReload - Ok
,08-29 13:12:38.356   277   998 D CommandListener: Setting iface cfg
08-29 13:12:38.356   277   998 D CommandListener: Trying to bring down wlan0
,08-29 13:12:38.366   277   998 D CommandListener: Clearing all IP addresses on wlan0
,08-29 13:12:38.366  1014  1126 E WifiHW  : supplicant_name : p2p_supplicant
,08-29 13:12:38.416  7850  7850 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-29 13:12:38.416  7850  7850 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 13:12:38.416  7850  7850 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-29 13:12:38.426  7850  7850 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-29 13:12:38.426   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7850
08-29 13:12:38.426   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
,08-29 13:12:38.426  7850  7850 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-29 13:12:38.426  7850  7850 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:38.426  7850  7850 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-29 13:12:38.426  7850  7850 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-29 13:12:38.426   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 7850
08-29 13:12:38.426   394   394 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-29 13:12:38.476  1014  1126 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
08-29 13:12:38.476  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:38.476  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-29 13:12:38.476  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.476  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:12:38.476  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.476  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.476  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.476  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:38.476  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:38.476  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-29 13:12:38.476  1176  1176 D HotspotTile: onReceive : 2, 0
,08-29 13:12:38.476  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:38.486  1014  4809 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-29 13:12:38.486  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:38.486  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:38.486  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:38.486  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:38.486  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-29 13:12:38.486  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:38.486  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
,08-29 13:12:38.496  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-29 13:12:38.496  1602  1602 I Hs20UtilService: Starting #19
08-29 13:12:38.496  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:38.586   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-29 13:12:38.586  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-29 13:12:38.636  7850  7850 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:12:38.636  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 13:12:38.646  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 13:12:38.646   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7850
08-29 13:12:38.646   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 13:12:38.646  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-29 13:12:38.646  7850  7850 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:38.646  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:38.646  7850  7850 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:38.646  7850  7850 E wpa_supplicant: SIM READ ERROR
08-29 13:12:38.646  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
08-29 13:12:38.646  7850  7850 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:38.646  7850  7850 E wpa_supplicant: SIM READ ERROR
08-29 13:12:38.646  7850  7850 I wpa_supplicant: Blacklist: Clear (all) 
08-29 13:12:38.646  7850  7850 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:12:38.646  7850  7850 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-29 13:12:38.646  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:38.646  7850  7850 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-29 13:12:38.646  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:38.646  7850  7850 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-29 13:12:38.646  7850  7850 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-29 13:12:38.646  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false,
08-29 13:12:38.646  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:38.646  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:38.686  7850  7850 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-29 13:12:38.796  7850  7850 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-29 13:12:38.796  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-29 13:12:38.806  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-29 13:12:38.806   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7850
08-29 13:12:38.806   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C,
08-29 13:12:38.816  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 13:12:38.816  7850  7850 I wpa_supplicant: ssSupport state is = 1
,08-29 13:12:38.816  7850  7850 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-29 13:12:38.816  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-29 13:12:38.826  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
08-29 13:12:38.826   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7850
08-29 13:12:38.826   394   394 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-29 13:12:38.826  7850  7850 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-29 13:12:38.826  7850  7850 I wpa_supplicant: ssSupport state is = 1
08-29 13:12:38.826  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:38.826  7850  7850 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:38.826  7850  7850 E wpa_supplicant: SIM READ ERROR
08-29 13:12:38.826  7850  7850 I wpa_supplicant: wpa_default_ap_write_once
08-29 13:12:38.826  7850  7850 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-29 13:12:38.826  7850  7850 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 13:12:38.826  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:38.826  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:38.826  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:38.836  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
08-29 13:12:38.836  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:38.836  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:38.906  7850  7850 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-29 13:12:38.906  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-29 13:12:38.946  7850  7850 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-29 13:12:38.946  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-29 13:12:38.946  7850  7850 I wpa_supplicant: Skip scan - bUseNetwork false
,08-29 13:12:38.956  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
08-29 13:12:38.956  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-29 13:12:38.956  7850  7850 I wpa_supplicant: HOTSPOT20_ENABLE called
08-29 13:12:38.956  7850  7850 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-29 13:12:38.956  7850  7850 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-29 13:12:38.956  7850  7850 E wpa_supplicant: SIM READ ERROR
08-29 13:12:38.956  7850  7850 I wpa_supplicant: Blacklist: Clear (all) 
08-29 13:12:38.976  7850  7850 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-29 13:12:38.986  7850  7850 I wpa_supplicant: Skip scan - bUseNetwork false
08-29 13:12:38.986  1014  1126 D WifiConfigStore: Loading config and enabling all networks 
08-29 13:12:38.986  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:38.996  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:38.996  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.996  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.996  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.996  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:38.996  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:38.996  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-29 13:12:38.996  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-29 13:12:38.996  1176  1723 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-29 13:12:38.996  1176  1176 D HotspotTile: onReceive : 3, 0
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:39.006  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 13:12:39.006  1014  1126 E WifiConfigStore: Not a HS20
08-29 13:12:39.006  1014  1126 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 13:12:39.016  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:39.016  1014  1493 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:39.016  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:39.016  1014  1126 D WifiNative-wlan0: callSECApiInt - ID [65]
08-29 13:12:39.016  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:39.016  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:39.016  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:39.016  1602  1602 I Hs20UtilService: Starting #20
,08-29 13:12:39.016  1014  1126 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-29 13:12:39.016  7850  7850 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-29 13:12:39.016  7850  7850 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 13:12:39.016  7850  7850 I wpa_supplicant: reset timer : RESET_TIMER 0
08-29 13:12:39.016  7850  7850 I wpa_supplicant: P2P: Current p2p state = IDLE
08-29 13:12:39.016  7850  7850 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-29 13:12:39.016  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-29 13:12:39.016  7850  7850 I wpa_supplicant: First Scan Start
08-29 13:12:39.016  7850  7850 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
,08-29 13:12:39.026  1602  1639 I Hs20UtilService: Message received 5011
,08-29 13:12:39.026  1014  1126 D WifiNative-wlan0: Setting external_sim to 1
08-29 13:12:39.026  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-29 13:12:39.026  7164  7164 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-29 13:12:39.026  7104  7104 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 13:12:39.026  1014  1126 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 13:12:39.026  1014  1126 I WifiNative-HAL: startHal
08-29 13:12:39.026  1014  1126 E wifi    : getStaticLongField sWifiHalHandle 0x9d43588c
08-29 13:12:39.026  1014  1126 I WifiNative-HAL: Could not start hal
,08-29 13:12:39.026  7164  7164 D SecurityLogAgent: StateMachine : Current State = 1
08-29 13:12:39.026  7164  7164 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-29 13:12:39.036  1014  1126 E WifiNative-wlan0: do suspend true
,08-29 13:12:39.036  1014  1125 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-29 13:12:39.036   277   998 D CommandListener: Setting iface cfg
08-29 13:12:39.036   277   998 D CommandListener: Trying to bring up p2p0
,08-29 13:12:39.036  1014  1125 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 13:12:39.036  1014  1125 D WifiP2pService: P2pEnablingState
08-29 13:12:39.036  1014  1125 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-29 13:12:39.036  1014  1126 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-29 13:12:39.036  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
08-29 13:12:39.036  1014  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:39.036  1014  1148 I WifiNative-HAL: startHal
08-29 13:12:39.036  1014  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9e7e99bc
08-29 13:12:39.036  1014  1148 I WifiNative-HAL: Could not start hal
08-29 13:12:39.036  1014  1125 D WifiP2pService: P2p socket connection successful
08-29 13:12:39.036  1014  1148 E WifiScanningService: could not start HAL
08-29 13:12:39.036  1014  1014 D RttService: SCAN_AVAILABLE : 3
,08-29 13:12:39.036  1014  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 13:12:39.046  1014  1126 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-29 13:12:39.046  1014  1125 D WifiP2pService: P2pEnabledState
08-29 13:12:39.046  1014  1126 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-29 13:12:39.046  1014  1126 E WifiNative-wlan0: invaild command id : 215
,08-29 13:12:39.046  7850  7850 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
08-29 13:12:39.046  1014  1125 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-29 13:12:39.046  7850  7850 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:12:39.046  1014  1045 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-29 13:12:39.046  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-29 13:12:39.046  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:39.046  7850  7850 E wpa_supplicant: wpa_driver_nl80211_driver_cmd: failed to issue private commands
08-29 13:12:39.046  1014  1045 D WifiDisplayController: disconnect
08-29 13:12:39.046  1014  1128 E ConnectivityService: updateNetworkInfo()
,08-29 13:12:39.046  1014  1045 D WifiDisplayController: updateConnection
08-29 13:12:39.046  1014  1126 E WifiStateMachine: Failed to set frequency band 0
08-29 13:12:39.046  1014  1045 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-29 13:12:39.046  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:39.046  1014  1045 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-29 13:12:39.046  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:39.056  1014  1045 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-29 13:12:39.056  1014  1045 D WifiDisplayAdapter: onP2pDisconnected
08-29 13:12:39.056  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress
08-29 13:12:39.056  1014  1045 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-29 13:12:39.056  1014  1125 D WifiNative-p2p0: p2pGetDeviceAddress returning 0a:ec:a9:50:76:28
,08-29 13:12:39.056  1014  1045 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-29 13:12:39.056  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-29 13:12:39.056  1014  1491 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-29 13:12:39.056  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-29 13:12:39.056  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-29 13:12:39.056  1014  1125 D WifiP2pService: DeviceAddress: 0a:76:28
,08-29 13:12:39.056  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-29 13:12:39.066  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:12:39.066  1014  1126 D SecContentProvider2: mCursor = null
08-29 13:12:39.066  1014  1045 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Thali Test (Galaxy A3)
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  deviceAddress: 0a:ec:a9:50:76:28
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  primary type: 10-0050F204-5
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  secondary type: null
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  wps: 0
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  grpcapab: 0
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  devcapab: 0
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  status: 3
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  wfdInfo: null
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  groupownerAddress: null
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  GOdeviceName: null
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  interfaceAddress: 
08-29 13:12:39.066  1014  1045 D WifiDisplayController:  SConnectInfo : null,
08-29 13:12:39.066  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-29 13:12:39.066  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-29 13:12:39.066  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-29 13:12:39.066  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:39.066  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-29 13:12:39.066  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:39.076  7540  7540 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-29 13:12:39.076  7540  7540 D FileShare-Client: Outbound.stopDelayTimer - 
,08-29 13:12:39.076  7555  7555 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-29 13:12:39.086  1014  1125 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-29 13:12:39.086  1014  1125 D WifiP2pService: InactiveState
,08-29 13:12:39.086  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
08-29 13:12:39.086  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:12:39.086  7850  7850 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-29 13:12:39.086  1014  1125 D WifiP2pService: InactiveState{ what=143376 }
08-29 13:12:39.086  1014  1125 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-29 13:12:39.326  1014  1042 D Tethering: interfaceLinkStateChanged p2p0, false
,08-29 13:12:39.326  1014  1042 D Tethering: interfaceStatusChanged p2p0, false
,08-29 13:12:39.326  1014  1042 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-29 13:12:39.806   287   287 E SMD     : DCD OFF,
,08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:39.986  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:39.986  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 13:12:39.996  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 13:12:39.996  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 13:12:39.996  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1e9f4606 Bundle[{}]
,08-29 13:12:39.996  6916  6969 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 13:12:39.996  6916  6969 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 13:12:39.996  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-29 13:12:40.006  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-29 13:12:40.006  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 13:12:40.006  6916  6969 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 13:12:40.006  1014  1491 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-29 13:12:40.006  1014  1491 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-29 13:12:40.006  1014  1491 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-29 13:12:40.006  1014  1491 D BatteryService: stay LED for fully charged
08-29 13:12:40.016  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-29 13:12:40.016  6916  6969 I System.out: Running OutgoingSocketThread
,08-29 13:12:40.016  1014  1014 I MotionRecognitionService: Plugged
,08-29 13:12:40.016  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,08-29 13:12:40.016  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-29 13:12:40.016  6916  7859 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1379)
08-29 13:12:40.016  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-29 13:12:40.026  6916  7859 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 58456
,08-29 13:12:40.026  6916  7859 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 13:12:40.026  1427  1427 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-29 13:12:40.026  1427  1427 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-29 13:12:40.036  7750  7750 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-29 13:12:40.046  7750  7777 D HeadsetStateMachine: Disconnected process message: 10
,08-29 13:12:40.046  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:40.046  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:40.046  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-29 13:12:40.046  1176  1176 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
,08-29 13:12:40.046  1176  1176 D SViewCoverView: level :100 plugged : 2
,08-29 13:12:40.216  7850  7850 I wpa_supplicant: nl80211: Received scan results (33 BSSes),
08-29 13:12:40.216  7850  7850 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-29 13:12:40.216  7850  7850 I wpa_supplicant: Trying to associate with SSID '4E47373030'
08-29 13:12:40.216  7850  7850 I wpa_supplicant: Trying to associate with  'G700'
08-29 13:12:40.216  7850  7850 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,08-29 13:12:40.216  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-29 13:12:40.226  1014  7856 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-29 13:12:40.246  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:40.246  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:40.346  7850  7850 E wpa_supplicant: Cmd 35605 not handled
,08-29 13:12:40.346  7850  7850 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:40.346  7850  7850 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
,08-29 13:12:40.346  7850  7850 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-29 13:12:40.346  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:40.346  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
08-29 13:12:40.346  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-29 13:12:40.346  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:40.346  7850  7850 I wpa_supplicant: Associated with F4.99.3E
08-29 13:12:40.346  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:40.346  7850  7850 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:40.346  7850  7850 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-29 13:12:40.346  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030,
,08-29 13:12:40.346  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
08-29 13:12:40.346  1014  1042 D Tethering: interfaceStatusChanged wlan0, false
,08-29 13:12:40.356  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-29 13:12:40.356  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, false
,08-29 13:12:40.356  1014  1042 D Tethering: interfaceStatusChanged wlan0, false,
08-29 13:12:40.356  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:12:40.356  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-29 13:12:40.356  1014  1042 D Tethering: interfaceStatusChanged wlan0, true,
,08-29 13:12:40.356  1014  1129 E Tethering: No numeric data
,08-29 13:12:40.356  1014  1129 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 13:12:40.356  1014  1129 D Tethering: clearTetheredNotification()
08-29 13:12:40.356  7850  7850 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-29 13:12:40.356  7850  7850 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-29 13:12:40.356  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
08-29 13:12:40.356  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:40.366  7850  7850 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,08-29 13:12:40.366  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:40.366  7850  7850 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-29 13:12:40.366  7850  7850 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-29 13:12:40.366  7850  7850 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-29 13:12:40.366  7850  7850 I wpa_supplicant: Blacklist: Clear (temp) 
08-29 13:12:40.366  7850  7850 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-29 13:12:40.366  1014  1042 D Tethering: interfaceLinkStateChanged wlan0, true
08-29 13:12:40.366  1014  1042 D Tethering: interfaceStatusChanged wlan0, true
08-29 13:12:40.366  1014  1042 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-29 13:12:40.366  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:40.366  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:12:40.376  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-29 13:12:40.376  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-29 13:12:40.376  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:40.376  1176  1176 D HotspotTile: updateTetherState():false, false
08-29 13:12:40.376  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-29 13:12:40.376  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:40.376  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:40.376  1014  1123 V NetworkStats: performPollLocked() took 11ms
,08-29 13:12:40.386  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:40.386  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:40.386  1014  1126 D WifiNative-wlan0: callSECApiVoid - ID [50],
08-29 13:12:40.386  1014  1126 E WifiConfigStore: setLastSelectedConfiguration -1
08-29 13:12:40.396  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:40.396  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:40.396  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.396  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.396  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.396  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:40.406  1014  1126 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-29 13:12:40.406  1014  1128 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-29 13:12:40.406  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:40.406  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:40.406  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-29 13:12:40.406  1014  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-29 13:12:40.406  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:40.416  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:40.416  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:40.416  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:40.416  1602  1602 I Hs20UtilService: Starting #21
08-29 13:12:40.416  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:40.416  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE,
,08-29 13:12:40.426  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:12:40.426  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 13:12:40.426  1014  1126 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 13:12:40.426  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:40.426  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:40.426  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-29 13:12:40.426  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002,
,08-29 13:12:40.436   277   998 D CommandListener: Setting iface cfg
,08-29 13:12:40.436  1014  1126 E WifiStateMachine: Start Dhcp Watchdog 3
,08-29 13:12:40.436  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:12:40.436  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:40.446  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:40.446  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:40.446  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.446  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.446  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:40.446  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:40.456  1014  1126 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-29 13:12:40.456  1014  1126 D SecContentProvider2: mCursor = null
,08-29 13:12:40.456  1014  1126 E WifiNative-wlan0: do suspend false
,08-29 13:12:40.456  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:12:40.456  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:12:40.686  7864  7864 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:12:40.686  7864  7864 I dhcpcd  : version 5.5.6 starting,
,08-29 13:12:40.696  7864  7864 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-29 13:12:40.746  7864  7864 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-29 13:12:40.746  7864  7864 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-29 13:12:40.746  7864  7864 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-29 13:12:40.746  7864  7864 I dhcpcd  : bssid match,
08-29 13:12:40.746  7864  7864 I dhcpcd  : wlan0: rebinding lease of 192.168.1.127
,08-29 13:12:40.806  7864  7864 I dhcpcd  : wlan0: acknowledged 192.168.1.127 from 192.168.1.1,
,08-29 13:12:40.886  7864  7864 I dhcpcd  : wlan0: leased 192.168.1.127 for 172800 seconds,
,08-29 13:12:41.016  6916  6969 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1380)
08-29 13:12:41.016  6916  6969 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1380)
08-29 13:12:41.016  6916  6969 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1385)
08-29 13:12:41.016  6916  6969 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-29 13:12:41.016  6916  6969 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1386)
08-29 13:12:41.016  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.016  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fb3c754 added. We now have 2 listener(s)
08-29 13:12:41.016  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.016  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.016  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: ,
08-29 13:12:41.016  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.016  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53fa6fd added. We now have 9 listener(s)
08-29 13:12:41.016  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.026  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:41.036  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true,
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:41.036  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:41.046  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:41.046  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK,
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b85c643 added. We now have 3 listener(s)
08-29 13:12:41.046  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:41.046  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253004c0 added. We now have 10 listener(s)
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.046  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:41.046  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.046  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:41.046  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.046  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:41.046  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fb3c754 removed from the list
08-29 13:12:41.046  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.046  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53fa6fd removed from the list
,08-29 13:12:41.046  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:41.046  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.056  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.056  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@53fa6fd not in the list,
08-29 13:12:41.056  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253004c0 removed from the list
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.056  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b85c643 removed from the list
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2364b5f9 added. We now have 2 listener(s)
,08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 13:12:41.056  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e9893e added. We now have 9 listener(s)
08-29 13:12:41.056  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.056  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:41.066  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 13:12:41.066  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 13:12:41.076  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 13:12:41.076  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:41.076  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-29 13:12:41.076  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d70acec added. We now have 3 listener(s)
,08-29 13:12:41.076  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.076  1014  1126 E WifiNative-wlan0: do suspend true
08-29 13:12:41.076  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.076  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.076  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.076  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 13:12:41.076  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.076  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2831b8b5 added. We now have 10 listener(s)
08-29 13:12:41.076  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.076  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:41.076  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:41.076  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:41.076  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
08-29 13:12:41.076  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:41.086  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:41.086  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
,08-29 13:12:41.086  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:41.086  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 13:12:41.086  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-29 13:12:41.096  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:41.096  7750  7769 D BtGatt.GattService: registerClient() - UUID=96214b51-1dff-4012-a127-6a3dc534fd23
,08-29 13:12:41.106  1014  1125 D WifiP2pService: InactiveState{ what=143375 }
,08-29 13:12:41.106  1014  1125 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-29 13:12:41.106  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-29 13:12:41.106  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-29 13:12:41.106  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.116  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.116  1014  1126 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-29 13:12:41.116  1014  1126 E WifiStateMachine: VerifyingLinkState enter
,08-29 13:12:41.116  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.116  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.116  1014  1128 E ConnectivityService: updateNetworkInfo()
,08-29 13:12:41.116  1014  1128 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-29 13:12:41.116  1014  1128 D ConnectivityService: Adding iface wlan0 to network 504
,08-29 13:12:41.126  1014  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter,
,08-29 13:12:41.126  1014  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:12:41.126  1014  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 13:12:41.126  1014  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-29 13:12:41.126  1014  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-29 13:12:41.136  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:41.136  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:41.136  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.136  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.136  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.136  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.136  7750  7768 D BtGatt.GattService: onClientRegistered() - UUID=96214b51-1dff-4012-a127-6a3dc534fd23, clientIf=6
,08-29 13:12:41.136  6916  6930 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:12:41.136  7750  7758 D BtGatt.GattService: start scan with filters
08-29 13:12:41.146  1014  1310 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:41.146  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:41.146  1014  1126 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-29 13:12:41.146  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:12:41.146  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:41.146  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:41.146  7750  7775 D BtGatt.ScanManager: handling starting scan
08-29 13:12:41.146  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 13:12:41.146  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:41.146  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-29 13:12:41.146  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-29 13:12:41.146  1602  1602 I Hs20UtilService: Starting #22
,08-29 13:12:41.146  7750  7775 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3f131318
08-29 13:12:41.146  1602  1639 I Hs20UtilService: Message received 5007
08-29 13:12:41.146  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:12:41.146  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:41.146  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:12:41.146  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:41.146  7519  7519 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 13:12:41.156  7750  7768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-29 13:12:41.156  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.156  7750  7775 D BtGatt.ScanManager: allow scan with filters
08-29 13:12:41.156  7750  7775 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:12:41.156  7750  7775 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-29 13:12:41.156  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 13:12:41.156  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-29 13:12:41.156  1014  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:12:41.156  1014  1128 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-29 13:12:41.166  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-29 13:12:41.166  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.166  7750  7775 D BtGatt.ScanManager: Starting BLE batch scan
08-29 13:12:41.166  7750  7775 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-29 13:12:41.166  1014  1128 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-29 13:12:41.166  1014  1126 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-29 13:12:41.166  1014  1128 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,08-29 13:12:41.166  1014  1128 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-29 13:12:41.166  1014  1128 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-29 13:12:41.166  1014  1128 D ConnectivityService: LTETest block dns file not exists
,08-29 13:12:41.166  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-29 13:12:41.166  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-29 13:12:41.166  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.166  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.166  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.166  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.176  7750  7768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 13:12:41.176  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.176  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-29 13:12:41.176  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
08-29 13:12:41.176  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
,08-29 13:12:41.176  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
08-29 13:12:41.176  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.176  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:41.176  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:12:41.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.176  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.186  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.186  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.186  1014  1128 V NetworkStats: updateIfacesLocked()
08-29 13:12:41.186  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.186  1014  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:12:41.186  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:41.186  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:41.186  1014  1533 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:41.186  1014  1533 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-29 13:12:41.186  1014  1533 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:41.186  1014  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:41.186  1014  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:41.196  1602  1602 I Hs20UtilService: Starting #23
,08-29 13:12:41.196  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.196  1014  1128 V NetworkStats: performPollLocked() took 5ms
08-29 13:12:41.196  6916  6969 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 13:12:41.196  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.196  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 13:12:41.196  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.196  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:41.196  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 13:12:41.196  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:41.196  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:41.196  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:41.196  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:41.196  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 13:12:41.196  1602  1639 I Hs20UtilService: Message received 5007
,08-29 13:12:41.196  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-29 13:12:41.196  1014  1128 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-29 13:12:41.196  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:41.196  1014  1128 E ConnectivityService: updateNetworkInfo()
08-29 13:12:41.196  1014  1128 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-29 13:12:41.196  1014  1128 V NetworkStats: updateIfacesLocked()
08-29 13:12:41.196  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.196  1014  1128 V NetworkStats: performPollLocked(flags=0x1)
,08-29 13:12:41.196  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:41.196  1014  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:41.196  7750  7769 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:41.196  1014  1128 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.196  1014  1128 V NetworkStats: performPollLocked() took 3ms
08-29 13:12:41.196  7750  7775 D BtGatt.ScanManager: filter size is 1
08-29 13:12:41.196  7750  7775 D BtGatt.ScanManager: delete FilterIndex - 3
08-29 13:12:41.196  7750  7758 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 13:12:41.206  7519  7519 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:41.206  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:41.206  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:41.206  1014  1128 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-29 13:12:41.206  1014  1128 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-29 13:12:41.206  1014  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:41.206  1014  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-29 13:12:41.206  1014  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-29 13:12:41.206  1014  7861 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-29 13:12:41.206  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-29 13:12:41.206  1014  7861 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 13:12:41.206  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-29 13:12:41.206  7519  7519 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-29 13:12:41.206  7519  7519 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-29 13:12:41.206   277   994 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:12:41.206   277   994 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:41.206  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:12:41.206  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.206  7750  7775 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:41.206  1014  1128 D ConnectivityService:    accepting network in place of null
08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:41.206  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 13:12:41.206  7519  7537 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-29 13:12:41.206  1014  1125 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-29 13:12:41.206  1014  1126 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 13:12:41.206  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:41.206  1469  1469 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-29 13:12:41.206  1469  1469 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-29 13:12:41.206  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:41.206  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:41.206  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:41.216  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.216  1014  1128 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-29 13:12:41.216  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.216  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-29 13:12:41.216  1014  1128 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-29 13:12:41.216  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.216  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:41.216  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 13:12:41.216  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.216  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:41.216  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.216  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.216  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:41.216  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.216  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2364b5f9 removed from the list
08-29 13:12:41.216  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.216  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e9893e removed from the list
08-29 13:12:41.216  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:41.216  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.216  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:41.216  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.216  7750  7775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-29 13:12:41.216  1014  1128 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.127/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-29 13:12:41.226  7750  7768 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 13:12:41.226  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-29 13:12:41.226  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.226  1014  1129 D Tethering: MasterInitialState.processMessage what=3
,08-29 13:12:41.226  1014  1128 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,08-29 13:12:41.226  1014  1044 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-29 13:12:41.226  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:41.226  1014  1123 V NetworkStats: updateIfacesLocked()
08-29 13:12:41.226  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:41.226  1014  1123 V NetworkStats: performPollLocked(flags=0x1)
08-29 13:12:41.226  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-29 13:12:41.226  1176  1667 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-29 13:12:41.226  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.226  1014  1123 V NetworkStats: performPollLocked() took 3ms
08-29 13:12:41.226  4756  6978 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-29 13:12:41.226  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
08-29 13:12:41.226  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-29 13:12:41.226  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-29 13:12:41.226  1176  1176 D StatusBar.NetworkController: updateDataNetType()
08-29 13:12:41.226  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-29 13:12:41.226  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-29 13:12:41.236  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.236  1014  1124 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-29 13:12:41.236  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.236  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.236  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:41.246  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.246  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.246  1014  1310 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-29 13:12:41.246  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-29 13:12:41.246  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.246  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:41.246  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:41.246  1014  1310 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:41.246  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte,
08-29 13:12:41.246  1602  1602 I Hs20UtilService: Starting #24
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.246  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38e9893e not in the list
08-29 13:12:41.246  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.246  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.246  1602  1639 I Hs20UtilService: Message received 5007
08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-29 13:12:41.246  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.246  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.246  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2831b8b5 removed from the list
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.246  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.246  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-29 13:12:41.246  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.246  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d70acec removed from the list
08-29 13:12:41.246  7519  7519 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-29 13:12:41.246  7519  7519 I NearbySettings: MountReceiver.onReceive - Keep current state
08-29 13:12:41.246  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
08-29 13:12:41.246  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6922b31 added. We now have 2 listener(s)
,08-29 13:12:41.256  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.256  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.256  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.256  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.256  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4b8216 added. We now have 9 listener(s)
08-29 13:12:41.256  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.256  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 13:12:41.256  1014  1026 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-29 13:12:41.256  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:41.266  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:41.266  1014  3937 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-29 13:12:41.266  1014  3937 D SecContentProvider2: mCursor = null
,08-29 13:12:41.266  1014  1493 D SecContentProvider2: uri = 15 selection = getToastGravity
08-29 13:12:41.266  1014  1493 D SecContentProvider2: mCursor = null
,08-29 13:12:41.266  1014  1504 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-29 13:12:41.266  1014  1504 D SecContentProvider2: mCursor = null
,08-29 13:12:41.266  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.266  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:41.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.266  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b01ad84 added. We now have 3 listener(s)
,08-29 13:12:41.266  1014  1493 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,08-29 13:12:41.266  1014  1493 D SecContentProvider2: mCursor = null
,08-29 13:12:41.276  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.276  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.276  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 13:12:41.276  1014  1026 D SecContentProvider2: uri = 15 selection = getToastEnabledState
08-29 13:12:41.276  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.276  1014  1026 D SecContentProvider2: mCursor = null
,08-29 13:12:41.276  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.276  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 13:12:41.276  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aad496d added. We now have 10 listener(s)
08-29 13:12:41.276  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.276  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:41.276  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:41.276  1014  1534 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
08-29 13:12:41.276  1014  1534 D SecContentProvider2: mCursor = null
,08-29 13:12:41.276  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:41.276  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:41.276  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:41.276  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:41.286  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:41.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:41.286  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:41.296  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:41.296  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:41.296  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:41.296  7750  7759 D BtGatt.GattService: registerClient() - UUID=725e779b-bc56-434f-8556-4f8e882d96d9
,08-29 13:12:41.306   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-29 13:12:41.326  1014  1458 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014,
,08-29 13:12:41.326  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 13:12:41.336  7750  7768 D BtGatt.GattService: onClientRegistered() - UUID=725e779b-bc56-434f-8556-4f8e882d96d9, clientIf=6
,08-29 13:12:41.336  6916  6930 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:12:41.336  7750  7828 D BtGatt.GattService: start scan with filters,
,08-29 13:12:41.346  7750  7775 D BtGatt.ScanManager: handling starting scan
,08-29 13:12:41.346  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:12:41.346  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:41.346  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:41.346  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:41.346  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:41.346  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 13:12:41.346  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-29 13:12:41.356  7750  7768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
08-29 13:12:41.356  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-29 13:12:41.356  7750  7775 D BtGatt.ScanManager: allow scan with filters
,08-29 13:12:41.356  7750  7775 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:12:41.356  7750  7775 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
08-29 13:12:41.356  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
08-29 13:12:41.356  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.356  7750  7775 D BtGatt.ScanManager: Starting BLE batch scan,
08-29 13:12:41.356  7750  7775 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:12:41.356  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
08-29 13:12:41.366  7750  7768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-29 13:12:41.366  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.366  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:41.366  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-29 13:12:41.366  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.366  6916  6969 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-29 13:12:41.376  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:41.376  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.376  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.376  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 13:12:41.376  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6922b31 removed from the list
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:41.376  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4b8216 removed from the list
08-29 13:12:41.376  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:41.376  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:12:41.376  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.376  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4b8216 not in the list
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:41.376  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:41.376  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:41.386  7750  7828 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:41.386  7750  7775 D BtGatt.ScanManager: filter size is 1,
08-29 13:12:41.386  7750  7775 D BtGatt.ScanManager: delete FilterIndex - 4
,08-29 13:12:41.386  7750  7769 D BtGatt.GattService: unregisterClient() - clientIf=6
08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:41.386  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-29 13:12:41.386  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 13:12:41.386  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-29 13:12:41.386  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:41.386  7750  7775 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:41.386  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:12:41.386  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1aad496d removed from the list
08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.396  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.396  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b01ad84 removed from the list
,08-29 13:12:41.396  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e20f69 added. We now have 2 listener(s)
08-29 13:12:41.396  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:41.396  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:41.396  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:41.396  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.396  7750  7775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:12:41.396  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.396  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.396  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.396  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2228bdee added. We now have 9 listener(s)
08-29 13:12:41.396  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.396  7750  7768 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 13:12:41.396  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.396  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:41.406  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:41.406  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 13:12:41.406  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.406  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 13:12:41.416  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.416  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.416  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 13:12:41.416  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f291c added. We now have 3 listener(s)
,08-29 13:12:41.416  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
08-29 13:12:41.416  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.416  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.416  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.416  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36833925 added. We now have 10 listener(s)
08-29 13:12:41.416  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.416  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 13:12:41.416  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 13:12:41.416  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 13:12:41.416  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 13:12:41.416  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-29 13:12:41.426  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 13:12:41.426  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 13:12:41.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 13:12:41.436  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 13:12:41.436  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 13:12:41.436  6916  6969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 13:12:41.436  7750  7828 D BtGatt.GattService: registerClient() - UUID=2c9a1eea-abc3-4082-a820-1021c8913475
,08-29 13:12:41.476  7750  7768 D BtGatt.GattService: onClientRegistered() - UUID=2c9a1eea-abc3-4082-a820-1021c8913475, clientIf=6
,08-29 13:12:41.476  6916  6930 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-29 13:12:41.476  7750  7758 D BtGatt.GattService: start scan with filters
,08-29 13:12:41.486  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: handling starting scan
08-29 13:12:41.486  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 13:12:41.486  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 13:12:41.486  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 13:12:41.486  7750  7768 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-29 13:12:41.486  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: allow scan with filters
,08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-29 13:12:41.486  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-29 13:12:41.486  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 13:12:41.486  7750  7775 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-29 13:12:41.486  7750  7768 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-29 13:12:41.486  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.496  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:41.496  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 13:12:41.496  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 13:12:41.496  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-29 13:12:41.496  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.496  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 13:12:41.496  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:41.496  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.496  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 13:12:41.496  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.496  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.496  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 13:12:41.496  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.496  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e20f69 removed from the list
08-29 13:12:41.496  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.496  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2228bdee removed from the list
08-29 13:12:41.496  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:41.496  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:41.506  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.506  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 13:12:41.506  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.506  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 13:12:41.506  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2228bdee not in the list
08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-29 13:12:41.506  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 13:12:41.506  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 13:12:41.506  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 13:12:41.506  7750  7769 D BtGatt.GattService: stopScan() - queue size =1
,08-29 13:12:41.506  7750  7775 D BtGatt.ScanManager: filter size is 1
,08-29 13:12:41.506  7750  7775 D BtGatt.ScanManager: delete FilterIndex - 5
,08-29 13:12:41.506  7750  7768 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-29 13:12:41.506  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.506  7750  7775 D BtGatt.ScanManager: stopping BLe Batch
,08-29 13:12:41.506  7750  7758 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 13:12:41.516  7750  7768 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-29 13:12:41.516  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-29 13:12:41.516  7750  7775 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 13:12:41.516  7750  7768 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-29 13:12:41.516  7750  7768 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.516  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-29 13:12:41.516  6916  6916 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 13:12:41.516  6916  6916 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.516  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@36833925 removed from the list
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.516  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.516  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.516  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.516  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@256f291c removed from the list
,08-29 13:12:41.516  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.516  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5342a1 added. We now have 2 listener(s)
,08-29 13:12:41.526  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 13:12:41.526  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.526  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 13:12:41.526  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.526  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a469cc6 added. We now have 9 listener(s)
08-29 13:12:41.526  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 13:12:41.526  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 13:12:41.526  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:41.526  6916  6969 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:41.526  6916  6969 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:41.536  6916  6969 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 13:12:41.536  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 13:12:41.536  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166d7fb4 added. We now have 3 listener(s)
,08-29 13:12:41.536  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.536  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 13:12:41.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,08-29 13:12:41.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 13:12:41.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 13:12:41.536  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 13:12:41.536  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c067dd added. We now have 10 listener(s)
08-29 13:12:41.536  6916  6969 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 13:12:41.536  6916  6969 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 13:12:41.536  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 13:12:41.536  6916  6969 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-29 13:12:41.536  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 13:12:41.546  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:41.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.546  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b5342a1 removed from the list
,08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.546  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a469cc6 removed from the list
08-29 13:12:41.546  6916  6969 D io.jxcore.node.ConnectivityMonitor: stop
08-29 13:12:41.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.546  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 13:12:41.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.546  6916  6969 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a469cc6 not in the list
08-29 13:12:41.546  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 13:12:41.546  6916  6969 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22c067dd removed from the list
08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 13:12:41.546  6916  6969 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 13:12:41.546  6916  6969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 13:12:41.546  6916  6969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 13:12:41.546  6916  6969 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@166d7fb4 removed from the list
,08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 13:12:41.546  6916  6969 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-29 13:12:41.556  6916  7901 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1393, name: My test thread name)
,08-29 13:12:41.556  6916  7901 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1393, thread name: My test thread name)
,08-29 13:12:41.556  6916  7901 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1393, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:12:41.556  6916  7902 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1395, name: My test thread name)
,08-29 13:12:41.556  6916  7902 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1395, thread name: My test thread name)
,08-29 13:12:41.556  6916  7902 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1395, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 13:12:41.566  6916  6969 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 13:12:41.566  6916  6969 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 13:12:41.566  6916  6969 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 13:12:41.566  6916  6969 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 13:12:41.566  6916  6969 D com.test.thalitest.ThaliTestRunner: Total duration: 24303 ms
,08-29 13:12:41.566  6916  6969 I jxcore-log: *Native tests were executed*
08-29 13:12:41.566  6916  6969 I jxcore-log: 
,08-29 13:12:41.566  6916  6969 I jxcore-log: Total number of executed tests:  80
08-29 13:12:41.566  6916  6969 I jxcore-log: 
08-29 13:12:41.566  6916  6969 I jxcore-log: Number of passed tests:  80
08-29 13:12:41.566  6916  6969 I jxcore-log: 
08-29 13:12:41.566  6916  6969 I jxcore-log: Number of failed tests:  0
08-29 13:12:41.566  6916  6969 I jxcore-log: 
08-29 13:12:41.566  6916  6969 I jxcore-log: Number of ignored tests:  0
08-29 13:12:41.566  6916  6969 I jxcore-log: 
,08-29 13:12:41.566  6916  6969 I jxcore-log: Total duration:  24303
08-29 13:12:41.566  6916  6969 I jxcore-log: 
08-29 13:12:41.566  6916  6969 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 13:12:41.566  6916  6969 I jxcore-log: 
,08-29 13:12:41.576  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.576  6916  6969 I jxcore-log: 
08-29 13:12:41.576  6916  6916 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 13:12:41.576  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.576  6916  6969 I jxcore-log: 
08-29 13:12:41.576  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.576  6916  6969 I jxcore-log: 
08-29 13:12:41.576  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.576  6916  6969 I jxcore-log: 
08-29 13:12:41.576  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.576  6916  6969 I jxcore-log: 
08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.586  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:41.586  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"},
08-29 13:12:41.596  6916  6969 I jxcore-log: 
08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
,08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:41.596  6916  6969 I jxcore-log: 
08-29 13:12:41.596  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-29 13:12:41.596  6916  6969 I jxcore-log: 
08-29 13:12:41.606  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 13:12:41.606  6916  6969 I jxcore-log: 
,08-29 13:12:41.606  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"},
08-29 13:12:41.606  6916  6969 I jxcore-log: 
,08-29 13:12:41.606  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.606  6916  6969 I jxcore-log: 
,08-29 13:12:41.606  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.606  6916  6969 I jxcore-log: 
,08-29 13:12:41.706  6916  6916 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 13:12:41.716  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:41.716  6916  6969 I jxcore-log: 
,08-29 13:12:41.716  1014  1128 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:41.736  1014  1039 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 13:12:41.746  6916  6916 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 13:12:41.756  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-29 13:12:41.756  6916  6916 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 13:12:41.756  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.756  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.756  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.756  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:41.756  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 13:12:41.756  6916  6969 I jxcore-log: 
,08-29 13:12:41.776  7905  7905 E Zygote  : MountEmulatedStorage()
08-29 13:12:41.776  7905  7905 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:41.776  7905  7905 E Zygote  : v2
08-29 13:12:41.776  7905  7905 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:41.786  7905  7905 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:12:41.786  1014  1040 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7905 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:41.786  7905  7905 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:41.796  7905  7905 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:41.816  1014  1504 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-29 13:12:41.816  1014  1504 D SecContentProvider2: mCursor = null
,08-29 13:12:41.826  7905  7905 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:41.826  7905  7905 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:41.856  7905  7905 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-29 13:12:41.856  7905  7905 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-29 13:12:41.856  7905  7905 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-29 13:12:41.866  7905  7905 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 13:12:41.866  7905  7905 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-29 13:12:41.866  7905  7905 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 13:12:41.866  7905  7905 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:41.866  1014  1534 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=14, mSplitNum[2]=22, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=29
08-29 13:12:41.876  1014  1534 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-29 13:12:41.886  1783  1783 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-29 13:12:41.886  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-29 13:12:41.886  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.886  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.886  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.886  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:41.886  2477  2485 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,08-29 13:12:41.896  6916  6916 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-29 13:12:41.896  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:41.896  6916  6969 I jxcore-log: 
,08-29 13:12:41.906  7921  7921 E Zygote  : MountEmulatedStorage()
,08-29 13:12:41.906  7921  7921 E Zygote  : v2
08-29 13:12:41.906  7921  7921 I libpersona: KNOX_SDCARD checking this for 10001
08-29 13:12:41.906  7921  7921 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:41.906  7903  7903 D AndroidRuntime: 
08-29 13:12:41.906  7903  7903 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-29 13:12:41.906  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:41.906  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7921 uid=10001 gids={50001, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:41.906  1783  1783 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
08-29 13:12:41.906  7903  7903 D AndroidRuntime: CheckJNI is OFF
08-29 13:12:41.906  1783  1783 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
08-29 13:12:41.906  1783  1783 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
08-29 13:12:41.906  7903  7903 D AndroidRuntime: readGMSProperty: start
08-29 13:12:41.906  7903  7903 D AndroidRuntime: readGMSProperty: already setted!!
08-29 13:12:41.906  7903  7903 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-29 13:12:41.906  1783  1783 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE,
08-29 13:12:41.906  7903  7903 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-29 13:12:41.906  7903  7903 D AndroidRuntime: readGMSProperty: end
08-29 13:12:41.906  7903  7903 D AndroidRuntime: addProductProperty: start
08-29 13:12:41.906  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:41.906  1014  1310 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-29 13:12:41.916  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.916  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.916  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:41.916  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:41.916  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:41.936  7930  7930 E Zygote  : MountEmulatedStorage(),
08-29 13:12:41.936  7930  7930 E Zygote  : v2
08-29 13:12:41.936  7930  7930 I libpersona: KNOX_SDCARD checking this for 10031
08-29 13:12:41.936  7930  7930 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:41.936  7930  7930 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:41.936  7930  7930 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:12:41.936  7930  7930 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:41.936  1014  1310 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7930 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
08-29 13:12:41.936  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast,
08-29 13:12:41.936  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.936  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.936  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:41.936  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:41.946  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:41.946  7921  7921 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:41.956  7945  7945 E Zygote  : MountEmulatedStorage(),
08-29 13:12:41.956  7945  7945 E Zygote  : v2
08-29 13:12:41.956  7945  7945 I libpersona: KNOX_SDCARD checking this for 10121
08-29 13:12:41.956  7945  7945 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:41.956  7945  7945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-29 13:12:41.956  1014  1040 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7945 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-29 13:12:41.966  7945  7945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:41.966  1783  1783 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE,
08-29 13:12:41.966  7945  7945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 13:12:41.966  1014  1504 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-29 13:12:41.966  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:41.966  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
08-29 13:12:41.966  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:41.966  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-29 13:12:41.986   305   305 I art     : Explicit concurrent mark sweep GC freed 8700(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 629us total 24.163ms
08-29 13:12:41.986  7930  7930 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:41.986  7930  7930 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:41.986  1783  1783 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-29 13:12:41.996   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 717us total 17.750ms
,08-29 13:12:42.016  6916  6916 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-29 13:12:42.016  6916  6969 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 13:12:42.016  6916  6969 I jxcore-log: 
,08-29 13:12:42.016   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 581us total 17.680ms
,08-29 13:12:42.026  7945  7945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:42.026  7945  7945 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:42.046  1014  1491 D ActivityManager: startService callerProcessName:com.android.chrome, calleePkgName: com.android.chrome
08-29 13:12:42.046  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.chrome/org.chromium.content.browser.BackgroundSyncLauncherService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.046  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:42.046  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:42.046  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.chrome, destAppInfo.processName = com.android.chrome
,08-29 13:12:42.056  1014  1535 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
08-29 13:12:42.056  1014  1535 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.066  7903  7903 E AffinityControl: AffinityControl: registerfunction enter
,08-29 13:12:42.066  1014  1535 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:42.066  1014  1535 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:42.066  1014  1535 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-29 13:12:42.066  7945  7945 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:42.066  7945  7945 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:12:42.066  7945  7945 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:42.086  7903  7903 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 13:12:42.096  7104  7974 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-29 13:12:42.096  7104  7974 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-29 13:12:42.096  7104  7974 I System.out: (HTTPLog)-Static: isShipBuild true
08-29 13:12:42.096  7104  7974 I System.out: (HTTPLog)-Thread-1290-634922187: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 13:12:42.096  7104  7974 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-29 13:12:42.096   277   994 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:12:42.096   277   994 D Netd    : getNetworkForDns: using netid 504 for uid 10102
,08-29 13:12:42.106  7494  7508 W art     : Suspending all threads took: 6.668ms
,08-29 13:12:42.106  7945  7945 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE,
08-29 13:12:42.106  7945  7945 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-29 13:12:42.116  7308  7308 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
08-29 13:12:42.116  7308  7308 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-29 13:12:42.116  7308  7308 I DIAGMON_AGENT: ./extraInfo: "NG700"
08-29 13:12:42.116  7308  7308 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-29 13:12:42.116  1014  1491 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-29 13:12:42.116  1014  1491 D PackageManager: START PACKAGE DELETE: observer{220386142}
08-29 13:12:42.116  1014  1491 D PackageManager: pkg{<packageName>}
08-29 13:12:42.116  1014  1491 D PackageManager: user{0}
08-29 13:12:42.116  1014  1491 D PackageManager: caller{2000}
08-29 13:12:42.116  1014  1491 D PackageManager: flags{2}
08-29 13:12:42.116  1014  1491 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-29 13:12:42.116  1014  1491 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-29 13:12:42.116  1014  1491 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 13:12:42.116  1014  1491 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-29 13:12:42.116  7945  7945 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-29 13:12:42.126  1014  1458 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:42.136  1014  3937 D RCPManagerService: exchangeData() failure , invalid userId
,08-29 13:12:42.146  2830  7983 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-29 13:12:42.146  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-29 13:12:42.146  2830  7983 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
08-29 13:12:42.146  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-29 13:12:42.146  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-29 13:12:42.146  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
08-29 13:12:42.146  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
08-29 13:12:42.146  2830  7983 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-29 13:12:42.146  7278  7278 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-29 13:12:42.156  7326  7326 I SA      : [OR] onReceive log=[SA = 2.1.0296 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXS1BPE1 PSS = 4.497050696380942  ]
08-29 13:12:42.156  7326  7326 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-29 13:12:42.156  7326  7326 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-29 13:12:42.166  1014  1054 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,08-29 13:12:42.186  7326  7326 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 13:12:42.186  1014  1040 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
08-29 13:12:42.186  7326  7326 I SA      : [OR] == isSIMCardReady false ==
,08-29 13:12:42.186  7326  7326 I SA      : [SCU] == networkStateCheck == true
,08-29 13:12:42.196  2830  7983 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-29 13:12:42.196  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy,
,08-29 13:12:42.196  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-29 13:12:42.206  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
08-29 13:12:42.206  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-29 13:12:42.206  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-29 13:12:42.206  2830  7983 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-29 13:12:42.206  2830  7983 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-29 13:12:42.216  1014  1040 I ActivityManager: Killing 6916:com.test.thalitest/u0a171 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-29 13:12:42.216  2830  7983 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-29 13:12:42.226  1014  1128 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-29 13:12:42.226  7326  7326 I SA      : [DM] getCountryCodeFromCSC : PL,
08-29 13:12:42.226  7326  7326 I SA      : isChinaCountryCode : false
08-29 13:12:42.226  7326  7326 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-29 13:12:42.226  7326  7326 I SA      : [OR] == networkStateCheck true ==
,08-29 13:12:42.226  7404  7404 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-29 13:12:42.236  2830  7983 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-29 13:12:42.246  7326  7326 I SA      : [OR] GetMyCountryZoneTask
,08-29 13:12:42.246  7326  7326 I SA      : [OR] onReceive END
,08-29 13:12:42.256  7326  7984 I SA      : [SRS] prepareGetMyCountryZone
,08-29 13:12:42.256  7326  7984 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-29 13:12:42.256  7326  7984 I SA      : [SSP] query invoked
,08-29 13:12:42.266  7326  7984 I SA      : [TPMU] GetMccFromDB : null
,08-29 13:12:42.286  7326  7984 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-29 13:12:42.286  7326  7984 I SA      : [LBE] isSupportCheckDomainRegion : false
08-29 13:12:42.286  7326  7984 I SA      : [TPM] isNoProxy(default) : true
,08-29 13:12:42.296  7326  7984 E File    : fail readDirectory() errno=2
,08-29 13:12:42.316  1014  1054 W PackageSettings: Skipping PackageSetting{118bed81 com.example.hello/10168} due to missing metadata
,08-29 13:12:42.356  1014  1040 I ActivityManager:   Force finishing activity ActivityRecord{36d31623 u0 com.test.thalitest/.MainActivity t2}
,08-29 13:12:42.366  1222  1222 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-29 13:12:42.366  1014  1040 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,08-29 13:12:42.376  1014  1040 D InputDispatcher: Focus left window: 6916
,08-29 13:12:42.376   257   450 I SurfaceFlinger: id=13 Removed NainActivit (6/9)
,08-29 13:12:42.376   257   452 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-29 13:12:42.386  1014  1040 D InputDispatcher: Focused application released
,08-29 13:12:42.396  1014  1027 W WindowManager: Failed looking up window
08-29 13:12:42.396  1014  1027 W WindowManager: java.lang.IllegalArgumentException: Requested window android.os.BinderProxy@17c812b2 does not exist
08-29 13:12:42.396  1014  1027 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11074)
08-29 13:12:42.396  1014  1027 W WindowManager: 	at com.android.server.wm.WindowManagerService.windowForClientLocked(WindowManagerService.java:11065)
08-29 13:12:42.396  1014  1027 W WindowManager: 	at com.android.server.wm.WindowState$DeathRecipient.binderDied(WindowState.java:1644)
08-29 13:12:42.396  1014  1027 W WindowManager: 	at android.os.BinderProxy.sendDeathNotice(Binder.java:551)
,08-29 13:12:42.396  1014  1027 I WindowState: WIN DEATH: null
,08-29 13:12:42.396  1014  1040 D FocusedStackFrame: Set to : 0
,08-29 13:12:42.396  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:12:42.396  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:12:42.396  1014  1040 W ActivityManager: mDVFSHelper.acquire()
,08-29 13:12:42.406  1014  1040 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-29 13:12:42.416  1014  4809 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-29 13:12:42.416  1014  4809 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.416  1014  4809 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:42.416  1014  4809 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:42.416  1014  4809 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-29 13:12:42.416  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,08-29 13:12:42.436  1494  1494 D Launcher: onRestart, Launcher: 1068648644
,08-29 13:12:42.446  1014  1533 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
08-29 13:12:42.446  1014  1533 D SecContentProvider2: mCursor = null
,08-29 13:12:42.466  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-29 13:12:42.486  2709  2709 I art     : Explicit concurrent mark sweep GC freed 22377(1244KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 988us total 49.095ms
,08-29 13:12:42.516  1494  1494 D Launcher: onStart, Launcher: 1068648644
,08-29 13:12:42.516  1494  1494 D Launcher.HomeView: onStart
,08-29 13:12:42.516  1494  1494 D Launcher: onResume, Launcher: 1068648644
,08-29 13:12:42.516  1014  1027 D SettingsProvider: name = kids_home_mode
08-29 13:12:42.516  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-29 13:12:42.516  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-29 13:12:42.516  1014  1027 D SettingsProvider: selectionArgs: false
08-29 13:12:42.516  1014  1027 D SettingsProvider: selectionArgs: 10006
08-29 13:12:42.516  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-29 13:12:42.516  1014  1027 D SettingsProvider: ret = -1
,08-29 13:12:42.516  1494  1494 D Launcher.HomeView: onResume
08-29 13:12:42.516  1014  4809 I ActivityManager: Killing 7357:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
,08-29 13:12:42.526  1494  1494 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 13:12:42.536  4756  4756 I art     : Explicit concurrent mark sweep GC freed 24417(1465KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 12MB/17MB, paused 1.366ms total 99.804ms
,08-29 13:12:42.546  1014  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 13:12:42.556  1963  1963 E SamsungIME: mOCRHelper is null
,08-29 13:12:42.556  1984  2157 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 13:12:42.566  1469  1469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 13:12:42.596  1014  1310 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-29 13:12:42.596  1014  1310 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.596  1494  1494 D MenuAppsGridFragment: onResume
,08-29 13:12:42.596  1494  1494 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 13:12:42.596  1494  1494 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-29 13:12:42.606  1014  1310 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:42.606  1014  1310 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-29 13:12:42.606  1014  1310 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-29 13:12:42.616  1455  1455 D PersonaManager: isKioskContainerExistOnDevice,
,08-29 13:12:42.636  1014  1123 V NetworkStats: removeUidsLocked() for UIDs [10171]
,08-29 13:12:42.636  1455  1455 D RegisteredServicesCache: empty dynamic service
,08-29 13:12:42.636  1014  1491 D ActivityManager: handle home activity for 0
08-29 13:12:42.636  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
08-29 13:12:42.636  1014  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-29 13:12:42.636  1014  1491 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,08-29 13:12:42.636  1014  1491 D KnoxTimeoutHandler: post home show event for user 0
,08-29 13:12:42.636  1014  1491 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-29 13:12:42.636  1014  1491 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-29 13:12:42.636  1014  1491 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-29 13:12:42.646  1494  1494 D Launcher.HomeView: onPause
,08-29 13:12:42.646  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-29 13:12:42.646  1494  1494 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-29 13:12:42.646  1014  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-29 13:12:42.656  1014  1123 V NetworkStats: performPollLocked() took 17ms
,08-29 13:12:42.656  1014  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:42.656  7404  7404 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-29 13:12:42.666  1014  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:42.666  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.676  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:42.676  7404  7404 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-29 13:12:42.676  1014  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:42.676  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: exit::IDLE
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-29 13:12:42.676  7404  7404 D InitializeManagerStateMachine: entry::SUCCESS
08-29 13:12:42.676  7404  7404 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-29 13:12:42.676   257   257 I SurfaceFlinger: id=15 createSurf (540x960),1 flag=4, Mauncher
,08-29 13:12:42.686  7404  7404 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-29 13:12:42.686  7404  7404 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-29 13:12:42.686  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 13:12:42.686  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:42.696  1014  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-29 13:12:42.696   277   994 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:12:42.696   277   994 D Netd    : getNetworkForDns: using netid 504 for uid 10011
,08-29 13:12:42.696  7404  7404 D InitializeManagerStateMachine: exit::SUCCESS
,08-29 13:12:42.696  7404  7404 D InitializeManagerStateMachine: entry::IDLE
,08-29 13:12:42.696  1014  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-29 13:12:42.706  2510  2532 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:42.706  1014  1094 D InputDispatcher: Focus entered window: 1494
,08-29 13:12:42.706  1014  1491 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-29 13:12:42.706  1494  1494 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-29 13:12:42.716  1014  1491 D SecContentProvider2: mCursor = null
08-29 13:12:42.716  1014  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-29 13:12:42.716  1014  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-29 13:12:42.716  4756  4756 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-29 13:12:42.716  1014  1014 I art     : Explicit concurrent mark sweep GC freed 67188(4MB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 24MB/37MB, paused 4.696ms total 251.918ms
,08-29 13:12:42.716  1014  1054 I art     : WaitForGcToComplete blocked for 119.775ms for cause Explicit
,08-29 13:12:42.736  1494  1494 V ActivityThread: updateVisibility : ActivityRecord{3e6de942 token=android.os.BinderProxy@1e3f560f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-29 13:12:42.736  1494  1494 D Launcher.HomeView: onStop
,08-29 13:12:42.736  1455  1455 D RegisteredComponentCache: Collect Tech packages for Knox
,08-29 13:12:42.736  1455  1455 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:12:42.746  4756  7424 I iu.UploadsManager: num queued entries: 0
,08-29 13:12:42.746  4756  7424 I iu.UploadsManager: num updated entries: 0
,08-29 13:12:42.746  4756  7424 I iu.SyncManager: NEXT; no task
,08-29 13:12:42.786  1014  1504 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-29 13:12:42.786  7384  7384 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-29 13:12:42.786  1014  7998 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-29 13:12:42.786  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,08-29 13:12:42.786  1014  1504 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6916 uid 10171
,08-29 13:12:42.796  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-29 13:12:42.796  1963  1963 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-29 13:12:42.796  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-29 13:12:42.796  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-29 13:12:42.796  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,08-29 13:12:42.806   287   287 E SMD     : DCD OFF,
08-29 13:12:42.806  7384  7384 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated,
,08-29 13:12:42.806  1014  1039 D EnterpriseDeviceManagerService: Package has changed for user 0,
08-29 13:12:42.806  1014  1039 W TextServicesManagerService: no available spell checker services found
,08-29 13:12:42.806  1014  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-29 13:12:42.816  7384  7384 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild,
,08-29 13:12:42.816  1014  1535 I ActivityManager: Killing 7778:com.samsung.android.sm/1000 (adj 15): empty #21,
08-29 13:12:42.816  7384  7384 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-29 13:12:42.816  1014  1535 I ActivityManager: Killing 7629:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,08-29 13:12:42.826  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,08-29 13:12:42.826  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-29 13:12:42.836  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 13:12:42 GMT+02:00 2016
,08-29 13:12:42.836  1014  1493 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-29 13:12:42.836  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.836  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:42.836  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:42.836  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 13:12:42.846  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:12:42.856  1014  1535 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,08-29 13:12:42.866  2953  2953 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-29 13:12:42.866  2953  2953 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-29 13:12:42.866  2953  2953 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-29 13:12:42.866  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 13:12:42.866  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-29 13:12:42.876  1014  1045 W ActivityManager: mDVFSHelper.release()
,08-29 13:12:42.876  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Aug 29 13:12:42 GMT+02:00 2016
,08-29 13:12:42.876  1014  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{268ae74b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:149285
,08-29 13:12:42.886  1014  1094 D PersonaManager: isKioskContainerExistOnDevice
,08-29 13:12:42.896  1014  1504 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-29 13:12:42.896  1014  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-29 13:12:42.896  1014  1504 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:42.896  1014  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:42.896  1014  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-29 13:12:42.896  2953  8000 I KLMS-2.5.123: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-29 13:12:42.896  2953  8000 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().START
,08-29 13:12:42.896  2953  8000 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().START 
,08-29 13:12:42.906  2953  2953 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-29 13:12:42.906  1014  1094 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,08-29 13:12:42.906  2953  8000 I KLMS-2.5.123: : NetworkChangeOperations(): uploadRequestLog().END 
,08-29 13:12:42.906  1014  1094 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-29 13:12:42.906  2953  8000 I KLMS-2.5.123: : StateImplV2(): networkChangeListener().END
08-29 13:12:42.906  1014  1094 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-29 13:12:42.916  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.916  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.916  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.916  1014  1094 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:42.926  8001  8001 E Zygote  : MountEmulatedStorage()
08-29 13:12:42.926  8001  8001 E Zygote  : v2
08-29 13:12:42.926  8001  8001 I libpersona: KNOX_SDCARD checking this for 10090
08-29 13:12:42.926  8001  8001 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:42.926  8001  8001 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:42.936  8001  8001 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-29 13:12:42.936  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:42.936  1014  1094 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8001 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,08-29 13:12:42.936  8001  8001 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:42.936  7326  7984 I SA      : [RC New] Execute method=[GET] start
,08-29 13:12:42.946  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-29 13:12:42.946  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:42.946  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:42.956  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.956  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.956  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:42.956  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-29 13:12:42.956  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 13:12:42.956  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-29 13:12:42.966  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 13:12:42.976  1014  1534 I TactileAssist: enable value -1
08-29 13:12:42.976  1014  1534 I TactileAssist: internal enable value -1
08-29 13:12:42.976  1014  1534 I TactileAssist: intensity value -1
08-29 13:12:42.976  1014  1534 I TactileAssist: saveAppList value true
,08-29 13:12:42.976  7326  7984 I SA      : [RC New] Security=[true]
,08-29 13:12:42.976  7326  7984 I System.out: Thread-1351(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
08-29 13:12:42.976  8016  8016 E Zygote  : MountEmulatedStorage()
08-29 13:12:42.976  8016  8016 E Zygote  : v2
08-29 13:12:42.976  8016  8016 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:42.976  8016  8016 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:42.976  7326  7984 I System.out: Thread-1351(ApacheHTTPLog):isSBSettingEnabled false
08-29 13:12:42.976  7326  7984 I System.out: Thread-1351(ApacheHTTPLog):isShipBuild true
08-29 13:12:42.976  7326  7984 I System.out: Thread-1351(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-29 13:12:42.976  7326  7984 I System.out: Thread-1351(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-29 13:12:42.976  8016  8016 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:42.976   277   994 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
08-29 13:12:42.976   277   994 D Netd    : getNetworkForDns: using netid 504 for uid 10036
,08-29 13:12:42.976  8016  8016 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-29 13:12:42.986  8016  8016 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:42.996  1014  1534 I TactileAssist: List of disabled apps :
,08-29 13:12:42.996  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:12:42.996  1014  1040 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=8016 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:42.996  1014  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,08-29 13:12:42.996  8001  8001 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:42.996  8001  8001 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:42.996  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.996  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.996  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:42.996  1014  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.006  8016  8016 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.006  1014  1054 I art     : Explicit concurrent mark sweep GC freed 17948(1442KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 16.388ms total 290.713ms
,08-29 13:12:43.006  8016  8016 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.016  7750  7766 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-29 13:12:43.016  8032  8032 E Zygote  : MountEmulatedStorage()
,08-29 13:12:43.016  8032  8032 E Zygote  : v2
08-29 13:12:43.016  8032  8032 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:43.016  8032  8032 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.016  8032  8032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.016  1014  1040 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=8032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:43.026  8032  8032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.026  8032  8032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:43.026  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-29 13:12:43.026  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-29 13:12:43.036  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-29 13:12:43.036  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-29 13:12:43.036  1014  1014 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicy: uID is 10171
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-29 13:12:43.036  1014  3371 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-29 13:12:43.036  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-29 13:12:43.036  1014  1014 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0,
08-29 13:12:43.036  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
08-29 13:12:43.036  1014  1014 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-29 13:12:43.036  1014  1014 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
08-29 13:12:43.036  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-29 13:12:43.046  1176  1176 I StatusBar: Icon Only
08-29 13:12:43.046  1176  1176 D PanelView: There is/are notification(s) ,
,08-29 13:12:43.046  8032  8032 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.046  8032  8032 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.056  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-29 13:12:43.066  1014  1159 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
,08-29 13:12:43.096  1014  1310 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,08-29 13:12:43.106  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.106  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.106  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.106  1014  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.116  8047  8047 E Zygote  : MountEmulatedStorage()
,08-29 13:12:43.116  8047  8047 E Zygote  : v2
08-29 13:12:43.116  8047  8047 I libpersona: KNOX_SDCARD checking this for 10048
08-29 13:12:43.116  8047  8047 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:43.116  8047  8047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.116  8047  8047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.116  8047  8047 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
08-29 13:12:43.116  8032  8032 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED,
08-29 13:12:43.116  1014  1310 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=8047 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,08-29 13:12:43.126  1014  1458 D SecContentProvider2: uri = -1 selection = getSealedState
08-29 13:12:43.126  1014  1458 D SecContentProvider2: mCursor = null
08-29 13:12:43.126  8032  8032 I PopupuiReceiver_KNOX: getSealedState : true
08-29 13:12:43.136  1014  4809 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
08-29 13:12:43.136  1014  4809 D SecContentProvider2: mCursor = null
,08-29 13:12:43.136  8001  8001 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-29 13:12:43.136  8001  8001 D elm:15121: ELMEngine.ELMEngine( context ).
08-29 13:12:43.136  8032  8032 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
08-29 13:12:43.136  1014  1027 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,08-29 13:12:43.136  1014  1027 D SecContentProvider2: mCursor = null
08-29 13:12:43.136  1014  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-29 13:12:43.136  8001  8001 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-29 13:12:43.136  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-29 13:12:43.146  8032  8032 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,08-29 13:12:43.146  8032  8032 D PopupuiReceiver: Action package removed
08-29 13:12:43.146  1014  1491 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-29 13:12:43.146  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.146  8016  8016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-29 13:12:43.146  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:43.146  1014  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:43.146  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-29 13:12:43.156  1014  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-29 13:12:43.156  8001  8001 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-29 13:12:43.156  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:12:43.156  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.156  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.156  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.156  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.156  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:43.156  2953  8000 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-29 13:12:43.166  8001  8001 D elm:15121: ElmAgentService : onCreate()
,08-29 13:12:43.166  8001  8062 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-29 13:12:43.166  8001  8062 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-29 13:12:43.166  8001  8062 D elm:15121: MDMBridge.getInstance()
08-29 13:12:43.166  8001  8062 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 13:12:43.166  2953  8000 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,08-29 13:12:43.166  8001  8062 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-29 13:12:43.166  8047  8047 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.166  8047  8047 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.166  8063  8063 E Zygote  : MountEmulatedStorage()
08-29 13:12:43.166  8063  8063 E Zygote  : v2
08-29 13:12:43.166  8063  8063 I libpersona: KNOX_SDCARD checking this for 10145
08-29 13:12:43.166  8063  8063 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.166  8063  8063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.176  8063  8063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.176  8063  8063 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:43.176  1014  1493 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=8063 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:43.176  1014  1094 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-29 13:12:43.176  1014  1094 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.186  1014  1094 W ActivityManager: userId = 0, bbcId = -10000,
08-29 13:12:43.186  1014  1094 I ActivityManager: Killing 7655:com.google.android.apps.maps/u0a105 (adj 15): empty #21
08-29 13:12:43.186  1014  1094 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:43.186  1014  1094 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-29 13:12:43.196  2953  2953 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-29 13:12:43.206  8001  8001 D elm:15121: ElmAgentService : onDestroy().
,08-29 13:12:43.206  8063  8063 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.206  8063  8063 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.206  7905  7905 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-29 13:12:43.206  7905  7905 I PCWCLIENTTRACE_PushUtil: sales region : global
08-29 13:12:43.206  7905  7905 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-29 13:12:43.206  7905  7905 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-29 13:12:43.206  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:12:43.206  1014  1054 D PackageManager: delete codoeFile: 
,08-29 13:12:43.206  1014  1493 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,08-29 13:12:43.206  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.206  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.206  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.206  1014  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.216  1014  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:12:43.216  1014  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:43.216  1014  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:43.216  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:43.216  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
08-29 13:12:43.216  1014  1054 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,08-29 13:12:43.226  8080  8080 E Zygote  : MountEmulatedStorage()
,08-29 13:12:43.226  8080  8080 E Zygote  : v2
08-29 13:12:43.226  8080  8080 I libpersona: KNOX_SDCARD checking this for 1000
08-29 13:12:43.226  8080  8080 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.226  8080  8080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.226  8080  8080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.226  8080  8080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 13:12:43.226  1014  1493 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=8080 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-29 13:12:43.236  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:12:43.236  1014  1054 D PackageManager: result of delete: 1{220386142}
,08-29 13:12:43.236  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:43.246  8047  8047 D Compatibility: onReceive() it will make start service
,08-29 13:12:43.246  7903  7903 D AndroidRuntime: Shutting down VM
,08-29 13:12:43.256  1014  3937 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
08-29 13:12:43.256  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:43.256  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-29 13:12:43.256  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.256  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.256  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.256  1014  3937 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.256  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-29 13:12:43.256  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-29 13:12:43.256  1014  1054 D PackageManager: userId{-1}
08-29 13:12:43.256  1014  1054 D PackageManager: andCode{true}
,08-29 13:12:43.256  8080  8080 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.256  8080  8080 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.266  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-29 13:12:43.266  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-29 13:12:43.266  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
08-29 13:12:43.266  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1},
08-29 13:12:43.266  8095  8095 I libpersona: KNOX_SDCARD checking this for 10029
08-29 13:12:43.266  8095  8095 E Zygote  : MountEmulatedStorage(),
08-29 13:12:43.266  8095  8095 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:43.266  8095  8095 E Zygote  : v2
08-29 13:12:43.266  8095  8095 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-29 13:12:43.266  1014  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-29 13:12:43.276  8095  8095 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.276  1014  3937 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8095 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-29 13:12:43.276  8095  8095 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:43.276  1014  3937 I ActivityManager: Killing 7164:com.samsung.android.securitylogagent/1000 (adj 15): empty #21
,08-29 13:12:43.286  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.286  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.286  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.286  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.286  1014  1054 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.296  8109  8109 E Zygote  : MountEmulatedStorage()
08-29 13:12:43.296  8109  8109 I libpersona: KNOX_SDCARD checking this for 10003
08-29 13:12:43.296  8109  8109 E Zygote  : v2
08-29 13:12:43.296  8109  8109 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.296  8109  8109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.306  8080  8080 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:43.306  8109  8109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:43.306  8109  8109 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-29 13:12:43.306  8095  8095 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:43.306  1014  1054 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8109 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-29 13:12:43.306  8095  8095 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.306  1014  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-29 13:12:43.306  1014  1493 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-29 13:12:43.306  1014  1493 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
08-29 13:12:43.306  1014  1493 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:43.306  1014  1493 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:43.306  1014  1493 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-29 13:12:43.306  1014  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-29 13:12:43.316  1014  3937 I ActivityManager: Killing 7540:com.samsung.android.app.FileShareClient/u0a64 (adj 15): empty #21
,08-29 13:12:43.326  8047  8120 D Compatibility: onHandleIntent()
08-29 13:12:43.326  1014  1458 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
08-29 13:12:43.326  8109  8109 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:43.326  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.326  8047  8120 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-29 13:12:43.326  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.326  8109  8109 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:43.326  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.326  1014  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.326  8047  8120 D Compatibility: found: 2
,08-29 13:12:43.326  8080  8080 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-29 13:12:43.336  8063  8063 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-29 13:12:43.336  8063  8063 D ThemeInfoUtil: isCurrentFestival = false
,08-29 13:12:43.336  8047  8120 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-29 13:12:43.336  8047  8120 D Compatibility: skipping ResolveInfo{1d1ebbdf com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-29 13:12:43.336  8047  8120 D Compatibility: considering ResolveInfo{30ce202c com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-29 13:12:43.336  8047  8120 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-29 13:12:43.336  8047  8120 D Compatibility: enabling receiver ResolveInfo{23994af5 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-29 13:12:43.346  8047  8120 D Compatibility: enabling receiver ResolveInfo{b99c08a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-29 13:12:43.346  1014  1535 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-29 13:12:43.346  1014  1535 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-29 13:12:43.346  8127  8127 E Zygote  : MountEmulatedStorage()
,08-29 13:12:43.346  8127  8127 E Zygote  : v2
08-29 13:12:43.346  8127  8127 I libpersona: KNOX_SDCARD checking this for 10052
08-29 13:12:43.346  8127  8127 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:43.346  8127  8127 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.346  1014  1458 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=8127 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
08-29 13:12:43.346  8127  8127 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.356  8127  8127 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:43.356  8047  8120 D Compatibility: enabling receiver ResolveInfo{3ddd36fb com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-29 13:12:43.366  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-29 13:12:43.366  8047  8120 D Compatibility: enabling receiver ResolveInfo{3f131318 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-29 13:12:43.366  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.366  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.366  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.366  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.366  8047  8120 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-29 13:12:43.386  8127  8127 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.386  8127  8127 D ActivityThread: Added TimaKeyStore provider,
,08-29 13:12:43.386  8143  8143 E Zygote  : MountEmulatedStorage(),
08-29 13:12:43.386  8143  8143 E Zygote  : v2
08-29 13:12:43.386  8143  8143 I libpersona: KNOX_SDCARD checking this for 10148
08-29 13:12:43.386  8143  8143 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.386  8143  8143 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:43.386  1014  1026 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=8143 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
08-29 13:12:43.396  1014  1026 I ActivityManager: Killing 7555:com.samsung.android.app.FileShareServer/u0a65 (adj 15): empty #21
,08-29 13:12:43.396  8143  8143 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:43.396  1014  1026 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-29 13:12:43.396  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.396  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.396  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.396  1014  1026 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.396  8143  8143 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-29 13:12:43.416  1494  1494 I Choreographer: Skipped 36 frames!  The application may be doing too much work on its main thread.
,08-29 13:12:43.416  1494  1494 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1e3f560f time:149825
,08-29 13:12:43.416  8157  8157 E Zygote  : MountEmulatedStorage()
08-29 13:12:43.416  8157  8157 I libpersona: KNOX_SDCARD checking this for 10087
08-29 13:12:43.416  8157  8157 E Zygote  : v2
08-29 13:12:43.416  8157  8157 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.416  8157  8157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.416  8157  8157 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:43.426  1014  1026 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=8157 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,08-29 13:12:43.426  1014  1026 I ActivityManager: Killing 7921:com.sec.android.cloudagent/u0a1 (adj 15): empty #21
,08-29 13:12:43.426  8157  8157 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-29 13:12:43.426  8143  8143 D TimaKeyStoreProvider: TimaSignature is unavailable
08-29 13:12:43.426  8143  8143 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.436  1014  1533 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,08-29 13:12:43.436  1014  1094 I ActivityManager: Killing 7930:com.sec.android.soagent/u0a31 (adj 15): empty #21
,08-29 13:12:43.436  1014  1094 I ActivityManager: Killing 7945:com.samsung.android.sconnect/u0a121 (adj 15): empty #21
,08-29 13:12:43.446   305   305 I art     : Explicit concurrent mark sweep GC freed 8707(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 761us total 23.149ms
,08-29 13:12:43.446  8157  8157 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.456  7903  7903 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-29 13:12:43.456  8157  8157 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.466   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 602us total 19.873ms
,08-29 13:12:43.476  8095  8174 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-29 13:12:43.476  1014  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-29 13:12:43.486  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.486  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.486  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.486  1014  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.486   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 620us total 18.174ms
08-29 13:12:43.486  8143  8143 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-29 13:12:43.506  1014  1533 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-29 13:12:43.506  8176  8176 E Zygote  : MountEmulatedStorage(),
08-29 13:12:43.506  8095  8174 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-29 13:12:43.506  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:43.506  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.506  8095  8174 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 13:12:43.506  8095  8174 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
08-29 13:12:43.506  8176  8176 E Zygote  : v2
08-29 13:12:43.506  8176  8176 I libpersona: KNOX_SDCARD checking this for 10032
08-29 13:12:43.506  8176  8176 I libpersona: KNOX_SDCARD not a persona
,08-29 13:12:43.506  8176  8176 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.506  1014  1504 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8176 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-29 13:12:43.506  1014  1504 I ActivityManager: Killing 7260:com.android.chrome/u0a77 (adj 15): empty #21
,08-29 13:12:43.516  8176  8176 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.516  8176  8176 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
08-29 13:12:43.516  1014  1493 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
,08-29 13:12:43.516  1014  1534 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:12:43.516  1014  1534 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.516  8095  8174 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-29 13:12:43.516  1014  1534 W ActivityManager: userId = 0, bbcId = -10000
,08-29 13:12:43.516  1014  1534 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:43.516  1014  1534 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-29 13:12:43.526  1014  1027 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-29 13:12:43.526  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.526  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.526  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.526  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.546  8095  8174 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:12:43.546  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:43.546  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:43.546  1014  1027 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=8193 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,08-29 13:12:43.556  8193  8193 E Zygote  : MountEmulatedStorage(),
08-29 13:12:43.556  8193  8193 I libpersona: KNOX_SDCARD checking this for 10152
08-29 13:12:43.556  8193  8193 E Zygote  : v2
08-29 13:12:43.556  8193  8193 I libpersona: KNOX_SDCARD not a persona,
,08-29 13:12:43.556  8176  8176 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.556  8176  8176 D ActivityThread: Added TimaKeyStore provider
08-29 13:12:43.556  8193  8193 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-29 13:12:43.556  8193  8193 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-29 13:12:43.566  8193  8193 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-29 13:12:43.566  8095  8174 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-29 13:12:43.566  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:43.576  8095  8174 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-29 13:12:43.576  1014  1094 I ActivityManager: Killing 7374:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,08-29 13:12:43.586  8193  8193 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-29 13:12:43.586  8193  8193 D ActivityThread: Added TimaKeyStore provider
,08-29 13:12:43.596  8095  8174 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-29 13:12:43.596  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-29 13:12:43.606  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-29 13:12:43.606  8095  8174 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-29 13:12:43.606  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-29 13:12:43.606  8095  8174 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 13:12:43.606  8095  8174 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 13:12:43.606  1014  1458 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-29 13:12:43.606  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.616  1014  1458 W ActivityManager: userId = 0, bbcId = -10000,
,08-29 13:12:43.616  1014  1458 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:43.616  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
08-29 13:12:43.626  8193  8193 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-29 13:12:43.626  8193  8193 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-29 13:12:43.626  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.626  8095  8174 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:12:43.626  8095  8174 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-29 13:12:43.626  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-29 13:12:43.626  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.636  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:43.636  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:43.636  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-29 13:12:43.636  8193  8193 I TapandpayWidget:Utils: Clear T&P info.
,08-29 13:12:43.646  8095  8174 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-29 13:12:43.646  8095  8174 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-29 13:12:43.646  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.646  8095  8174 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-29 13:12:43.646  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-29 13:12:43.646  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.646  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.646  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-29 13:12:43.646  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-29 13:12:43.656  8095  8174 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
08-29 13:12:43.656  8193  8193 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-29 13:12:43.656  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.656  8095  8174 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-29 13:12:43.656  8095  8174 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 13:12:43.666  8212  8212 E Zygote  : MountEmulatedStorage()
,08-29 13:12:43.676  8212  8212 E Zygote  : v2
08-29 13:12:43.676  8212  8212 I libpersona: KNOX_SDCARD checking this for 10055
,08-29 13:12:43.676  8212  8212 I libpersona: KNOX_SDCARD not a persona
08-29 13:12:43.676  8176  8211 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-29 13:12:43.676  8176  8211 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-29 13:12:43.676  1014  1491 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=8212 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,08-29 13:12:43.686  1014  1491 I ActivityManager: Killing 7494:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,08-29 13:12:43.686  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-29 13:12:43.686  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.686  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:43.686  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-29 13:12:43.686  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-29 13:12:43.696  8212  8212 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-29 13:12:43.696  8095  8174 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
08-29 13:12:43.696  8212  8212 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-29 13:12:43.696  8095  8174 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-29 13:12:43.696  8212  8212 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-29 13:12:43.696  8095  8174 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-29 13:12:43.696  8095  8174 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-29 13:12:43.706  8176  8211 D SPPClientService: PushLog.txt file is not deleted.
,08-29 13:12:43.706  8176  8211 D SPPClientService: PushLog.txt file is not deleted.
08-29 13:12:43.706  8176  8211 D SPPClientService: ============PushLog. stop!
,08-29 13:12:43.716  1984  1984 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-29 13:12:43.716  1984  1984 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,08-29 13:12:43.716  1984  1984 D AndroidRuntime: Shutting down VM
,08-29 13:12:43.716  1014  1458 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-29 13:12:43.716  1014  1458 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,08-29 13:12:43.716  1014  1458 W ActivityManager: userId = 0, bbcId = -10000
08-29 13:12:43.716  1014  1458 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-29 13:12:43.716  1014  1458 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore

```
