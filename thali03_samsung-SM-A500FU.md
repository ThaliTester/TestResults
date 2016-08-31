#### Test 83084099807e426_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
,08-31 16:50:39.582  4680  4680 D FactoryTest: Not factory mode
08-31 16:50:39.592  4680  4680 D FactoryTest: Not factory mode. isFactoryMode() returend false
--------- beginning of system
08-31 16:50:39.592  4680  4680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-31 16:50:39.592  4680  4680 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-31 16:50:39.592  4680  4680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
08-31 16:50:39.592  4680  4680 D MTPRx   : still no open session command from host, so toast
08-31 16:50:39.592  4680  4680 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:108367
08-31 16:50:39.592  1017  1468 E PersonaManagerService: inState():  stateMachine is null !!
08-31 16:50:39.592  1017  1468 I PersonaManagerService: PersonaId don't exist
08-31 16:50:39.592  1017  1468 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 16:50:39.602  1017  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:39.602  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:39.602  1017  1468 W ActivityManager: mDVFSHelper.acquire()
08-31 16:50:39.602  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:50:39.602  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
08-31 16:50:39.612  1017  1468 D FocusedStackFrame: Set to : 0
08-31 16:50:39.612  1017  1017 V ActivityManager: Display changed displayId=0
08-31 16:50:39.622  1017  1468 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:39.642  1017  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 16:50:39.642  1017  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:39.642  1017  1468 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:39.642  1017  1468 D InputDispatcher: Focus left window: 1469
08-31 16:50:39.642  4680  4680 E MTPRx   : started activity for popup
08-31 16:50:39.642  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:39.642  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:39.652  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-31 16:50:39.672  1017  1327 E Watchdog: !@Sync 3
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:50:39.672  4680  4680 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-31 16:50:39.692  4680  4680 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
08-31 16:50:39.692  1017  1468 D FocusedStackFrame: Set to : 0
08-31 16:50:39.692  1017  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-31 16:50:39.692  1017  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 16:50:39.692  1017  1468 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:39.692  1017  1468 D InputDispatcher: Focus entered window: 1469
08-31 16:50:39.692  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:39.692  1017  1029 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-31 16:50:39.692  1017  1029 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3a0b0063 attribute=android.view.inputmethod.EditorInfo@5f8460, token = android.os.BinderProxy@3383ad70
08-31 16:50:39.692  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:39.702  1804  1804 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
08-31 16:50:39.732  4680  4680 D SettingsReceiverActivity: dev.kiessupport is : TRUE
08-31 16:50:39.742  4680  4680 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-31 16:50:39.742  4680  4680 D PhoneWindow: *FMB* installDecor flags : 8388610
08-31 16:50:39.842  5475  5475 D AndroidRuntime: 
08-31 16:50:39.842  5475  5475 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:50:39.842  5475  5475 D AndroidRuntime: CheckJNI is OFF
08-31 16:50:39.842  5475  5475 D AndroidRuntime: readGMSProperty: start
08-31 16:50:39.842  5475  5475 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:50:39.842  5475  5475 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:50:39.842  5475  5475 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:50:39.842  5475  5475 D AndroidRuntime: readGMSProperty: end
08-31 16:50:39.842  5475  5475 D AndroidRuntime: addProductProperty: start
08-31 16:50:39.972  5475  5475 E AffinityControl: AffinityControl: registerfunction enter
08-31 16:50:39.992  5475  5475 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-31 16:50:40.002  1017  1692 E PersonaManagerService: inState():  stateMachine is null !!
08-31 16:50:40.002  1017  1692 I PersonaManagerService: PersonaId don't exist
08-31 16:50:40.002  1017  1692 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-31 16:50:40.002  1017  1692 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:40.012  1017  1692 W ActivityManager: mDVFSHelper.acquire()
08-31 16:50:40.022  1017  1692 D FocusedStackFrame: Set to : 0
08-31 16:50:40.022  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-31 16:50:40.022  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-31 16:50:40.022  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.022  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.022  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.022  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:50:40.032  5487  5487 E Zygote  : MountEmulatedStorage()
08-31 16:50:40.032  5487  5487 E Zygote  : v2
08-31 16:50:40.032  5487  5487 I libpersona: KNOX_SDCARD checking this for 10155
08-31 16:50:40.032  5487  5487 I libpersona: KNOX_SDCARD not a persona
08-31 16:50:40.042  5487  5487 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:50:40.042  1017  1692 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5487 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-31 16:50:40.042  1017  1692 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-31 16:50:40.042  1017  1692 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-31 16:50:40.042  1017  1692 D InputDispatcher: Focused application set to: xxxx
08-31 16:50:40.042  1017  1692 D InputDispatcher: Focus left window: 1469
08-31 16:50:40.042  5475  5475 D AndroidRuntime: Shutting down VM
08-31 16:50:40.042  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-31 16:50:40.042  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-31 16:50:40.042   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
08-31 16:50:40.042  5487  5487 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:50:40.052  5487  5487 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-31 16:50:40.062  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-31 16:50:40.062  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
08-31 16:50:40.072  5487  5487 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:50:40.072  5487  5487 D ActivityThread: Added TimaKeyStore provider
08-31 16:50:40.072  1017  2876 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-31 16:50:40.072  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-31 16:50:40.082  1017  2876 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:50:40.142   257  1039 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-31 16:50:40.142   257  1828 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-31 16:50:40.142  1469  1469 V ActivityThread: updateVisibility : ActivityRecord{34cb693 token=android.os.BinderProxy@22cef998 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-31 16:50:40.142  1469  1469 D Launcher: onTrimMemory. Level: 20
08-31 16:50:40.202  5487  5487 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-31 16:50:40.212  5487  5487 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8984-8986)
08-31 16:50:40.212  5487  5487 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:40.232  5487  5487 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29c71ee6}
08-31 16:50:40.242  5487  5487 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:50:40.242  5487  5487 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 16:50:40.242   330   330 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-31 16:50:40.242   330   330 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
08-31 16:50:40.252  5475  5475 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:50:40.272  5487  5487 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 16:50:40.272  5487  5487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:40.272  5487  5487 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:50:40.282  5487  5504 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,08-31 16:50:40.292  5487  5487 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-31 16:50:40.292  5487  5487 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-31 16:50:40.292  5487  5487 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-31 16:50:40.302  5487  5487 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:50:40.302  5487  5487 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:50:40.302  5487  5487 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:50:40.302  5487  5487 I Adreno-EGL: Local Branch: 
08-31 16:50:40.302  5487  5487 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:50:40.302  5487  5487 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:50:40.302  5487  5487 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:50:40.362  5487  5515 D BluetoothAdapter: 326345667: getState() :  mService = null. Returning STATE_OFF
,08-31 16:50:40.422  5487  5513 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-31 16:50:40.462  5487  5487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:40.482  5487  5487 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 16:50:40.492  5487  5487 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-31 16:50:40.492  5487  5487 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-31 16:50:40.492  5487  5487 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-31 16:50:40.502  5487  5487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:40.502  5487  5487 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:50:40.542  5487  5526 D OpenGLRenderer: Render dirty regions requested: true
,08-31 16:50:40.552  1017  1688 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-31 16:50:40.552  1017  1688 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-31 16:50:40.552  1017  1688 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-31 16:50:40.552  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-31 16:50:40.552  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,08-31 16:50:40.562  5487  5487 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-31 16:50:40.562  5487  5487 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-31 16:50:40.572   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-31 16:50:40.592  1017  1481 D InputDispatcher: Focus entered window: 5487
,08-31 16:50:40.592  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 16:50:40.592  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:50:40.602  5487  5487 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:50:40.602  5487  5526 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:50:40.602  5487  5526 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-31 16:50:40.602  5487  5526 D OpenGLRenderer: Enabling debug mode 0
,08-31 16:50:40.622  5487  5487 V ActivityThread: updateVisibility : ActivityRecord{3c5e396e token=android.os.BinderProxy@11e54d70 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-31 16:50:40.672  1017  1030 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-31 16:50:40.672  1179  1179 D PanelView: There is/are notification(s) 
,08-31 16:50:40.672  1017  5529 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:50:40.682  1804  1804 I SamsungIME: getCurrentCandidateView
,08-31 16:50:40.692  1017  1048 I ActivityManager: Displayed Component not be shown by security: +597ms (total +1s76ms)
,08-31 16:50:40.692  1017  1048 W ActivityManager: mDVFSHelper.release()
08-31 16:50:40.692  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{356b21de u0 com.test.thalitest/.MainActivity t128} time:109463
,08-31 16:50:40.692  5487  5487 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-31 16:50:40.692  5487  5487 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@11e54d70 time:109469
,08-31 16:50:40.702   257  1039 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
,08-31 16:50:40.702   257  1828 I SurfaceFlinger: id=11 Removed uhalitest (-2/9),
,08-31 16:50:40.752  1804  1804 D SamsungIME: Dismiss ExpandCandiate
,08-31 16:50:40.752  5487  5487 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5487
,08-31 16:50:40.872  5487  5487 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 16:50:40.882  1804  1804 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:40.922  1804  1804 I SamsungIME: getDebugLevel  : 0x4f4c
,08-31 16:50:40.932  1804  1804 I SamsungIME: KeybaordView init() : load resources
,08-31 16:50:40.962  1804  1804 I SamsungIME: getCurrentKeyboard
,08-31 16:50:40.962  1804  1804 I SamsungIME: getTextKeyboard
,08-31 16:50:40.972  1804  1804 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 16:50:40.982  5487  5530 D jxcore_app_log: JniHelper::setJavaVM(0xb7c41328), pthread_self() = -1206229304
,08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-31 16:50:40.982  5487  5530 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a01da1e added. We now have 1 listener(s)
,08-31 16:50:40.992  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-31 16:50:40.992  5487  5530 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-31 16:50:40.992  5487  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 16:50:40.992  5487  5530 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 16:50:41.012  5487  5530 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@37276715 added. We now have 1 listener(s)
,08-31 16:50:41.012  5487  5530 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 16:50:41.022  5487  5530 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-31 16:50:41.022  5487  5530 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:41.022  5487  5530 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:41.022  5487  5530 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 16:50:41.022  5487  5530 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-31 16:50:41.022  5487  5530 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 16:50:41.062  5487  5487 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 16:50:41.262   287   287 E SMD     : DCD OFF
,08-31 16:50:41.502  1804  5535 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-31 16:50:41.562  5487  5540 W jxcore-log: Initializing JXcore engine
08-31 16:50:41.562  5487  5540 W jxcore-log: JXcore engine is ready
,08-31 16:50:41.622  1909  1909 E audit   : type=1400 msg=audit(1472655041.622:203): avc:  denied  { ioctl } for  pid=5540 comm="Thread-949" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 16:50:41.622  1909  1909 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:50:41.622  1909  1909 E audit   : type=1300 msg=audit(1472655041.622:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e5c68f8 items=0 ppid=305 ppcomm=main pid=5540 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-949" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-31 16:50:41.622  1909  1909 E audit   : type=1320 msg=audit(1472655041.622:203): 
,08-31 16:50:41.632  5487  5540 W jxcore-log: Starting JXcore engine
,08-31 16:50:41.762  5487  5540 W jxcore-log: Platform android
08-31 16:50:41.762  5487  5540 W jxcore-log: 
08-31 16:50:41.762  5487  5540 W jxcore-log: Process ARCH arm
08-31 16:50:41.762  5487  5540 W jxcore-log: 
,08-31 16:50:41.962  5487  5540 I jxcore-log: JXcore Cordova bridge is ready!
08-31 16:50:41.962  5487  5540 I jxcore-log: 
,08-31 16:50:41.962  5487  5540 W jxcore-log: JXcore engine is started
,08-31 16:50:41.972  5487  5530 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 16:50:41.972  5487  5487 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 16:50:44.262   287   287 E SMD     : DCD OFF
,08-31 16:50:44.432  1017  2627 D SSRM:n  : SIOP:: AP = 320
,08-31 16:50:45.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:46.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:47.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:47.262   287   287 E SMD     : DCD OFF
,08-31 16:50:47.302  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:50:47.302  1017  1030 D BatteryService: level:56, scale:100, status:2, health:2, present:true, voltage: 3866, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-31 16:50:47.302  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 16:50:47.302  1017  1030 D BatteryService: stay LED for charging
08-31 16:50:47.302  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:47.302  1017  1017 I MotionRecognitionService: Plugged
,08-31 16:50:47.302  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:50:47.302  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:50:47.302  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:47.312  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-31 16:50:47.312  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 56
,08-31 16:50:47.332  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:47.332  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:47.332  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:47.362  1017  2642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-31 16:50:48.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:49.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:50.072  1017  1058 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-31 16:50:50.252   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-31 16:50:50.262   287   287 E SMD     : DCD OFF,
,08-31 16:50:51.232  1017  1096 V AlarmManager: waitForAlarm result :4,
,08-31 16:50:51.242  1017  1096 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-31 16:50:51.252  4699  4699 V GCMBroadcastReceiver: onReceive: com.google.android.gcm.intent.RETRY
,08-31 16:50:51.252  4699  4699 V GCMBroadcastReceiver: GCM IntentService class: com.dropbox.android.gcm.GcmService
,08-31 16:50:51.262  4699  4699 V GCMBaseIntentService: Acquiring wakelock
,08-31 16:50:51.262  1017  1029 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
08-31 16:50:51.262  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 16:50:51.262  1017  1029 W ActivityManager: userId = 0, bbcId = -10000,
08-31 16:50:51.262  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:50:51.262  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
08-31 16:50:51.262  4699  4699 V GCMBaseIntentService: Intent service name: GCMIntentService-DynamicSenderIds-8
,08-31 16:50:51.272  4699  5546 V GCMRegistrar: Unregistering app com.dropbox.android
,08-31 16:50:51.272  1017  1468 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:50:51.272  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:50:51.272  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:50:51.272  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.google.process.gapps
,08-31 16:50:51.282  4699  5546 V GCMBaseIntentService: Releasing wakelock
,08-31 16:50:51.282  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:50:51.292  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:50:51.292  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:50:51.292  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-31 16:50:51.362  3762  3762 D ConnectivityManager: CallingUid : 10012, CallingPid : 3762
,08-31 16:50:51.362  1017  1252 D ConnectivityService: listenForNetwork for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-31 16:50:51.412  3762  5550 W DriveInitializer: Background init thread started
,08-31 16:50:51.442  1017  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:50:51.442  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 16:50:51.442  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:51.442   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-31 16:50:51.442   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:50:51.442  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:50:51.442  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:50:51.442  3762  5550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-31 16:50:51.452  1928  4678 D GCM     : GcmService start Intent { act=com.google.android.c2dm.intent.UNREGISTER pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.c2dm.intent.UNREGISTER
,08-31 16:50:51.462  1017  1692 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 16:50:51.462  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 16:50:51.462  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:50:51.462  1017  1692 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:50:51.462  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:50:51.472  1928  4678 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:50:51.472   277   957 D EnterpriseController: uids 10012
08-31 16:50:51.472   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:50:51.472   277   957 D Netd    : getNetworkForDns: using netid 0 for uid 10012
,08-31 16:50:51.472  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:50:51.472  1017  1043 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:50:51.472  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.dropbox.android
,08-31 16:50:51.482  4699  4699 V GCMBroadcastReceiver: onReceive: com.google.android.c2dm.intent.REGISTRATION
,08-31 16:50:51.482  4699  4699 V GCMBroadcastReceiver: GCM IntentService class: com.dropbox.android.gcm.GcmService
08-31 16:50:51.482  4699  4699 V GCMBaseIntentService: Acquiring wakelock
,08-31 16:50:51.482  1017  1468 D ActivityManager: startService callerProcessName:com.dropbox.android, calleePkgName: com.dropbox.android
,08-31 16:50:51.482  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.gcm.GcmService; callingUser = 0; userId(target) = 0
08-31 16:50:51.482  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:50:51.482  1017  1468 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:50:51.482  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,08-31 16:50:51.482  4699  4699 V GCMBaseIntentService: Intent service name: GCMIntentService-DynamicSenderIds-9
,08-31 16:50:51.492  4699  5553 D GCMBaseIntentService: handleRegistration: registrationId = null, error = SERVICE_NOT_AVAILABLE, unregistered = null
,08-31 16:50:51.492  4699  5553 D GCMBaseIntentService: Registration error: SERVICE_NOT_AVAILABLE
,08-31 16:50:51.492  4699  5553 D GCMBaseIntentService: Scheduling registration retry, backoff = 46536 (48000)
,08-31 16:50:51.502  4699  5553 V GCMBaseIntentService: Releasing wakelock
,08-31 16:50:51.502  3762  5550 W DriveInitializer: Background init thread ended
,08-31 16:50:53.272   287   287 E SMD     : DCD OFF
,08-31 16:50:54.442  1017  2627 D SSRM:n  : SIOP:: AP = 330
,08-31 16:50:55.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:56.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:56.272   287   287 E SMD     : DCD OFF
,08-31 16:50:57.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...
,08-31 16:50:57.362  1017  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-31 16:50:57.362  1017  1030 D BatteryService: level:56, scale:100, status:2, health:2, present:true, voltage: 3865, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-31 16:50:57.362  1017  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 16:50:57.362  1017  1030 D BatteryService: stay LED for charging
08-31 16:50:57.362  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:50:57.362  1017  1017 I MotionRecognitionService: Plugged
08-31 16:50:57.362  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:50:57.372  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-31 16:50:57.372  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:50:57.372  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 16:50:57.372  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 56
,08-31 16:50:57.392  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:57.392  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:57.392  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:50:58.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:59.252   330   330 I ServiceManager: Waiting for service AtCmdFwd...,
,08-31 16:50:59.272   287   287 E SMD     : DCD OFF,
,08-31 16:50:59.392  1017  1050 I PowerManagerService: [PWL] Off : 75s ago,
,08-31 16:50:59.962  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-31 16:50:59.962  5487  5540 I jxcore-log: 
,08-31 16:50:59.962  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-31 16:50:59.962  5487  5540 I jxcore-log: 
,08-31 16:50:59.972  5487  5540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:50:59.972  5487  5540 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:50:59.972  5487  5540 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-31 16:50:59.972  5487  5540 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:50:59.972  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-31 16:50:59.972  5487  5540 I jxcore-log: 
,08-31 16:50:59.972  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-31 16:50:59.972  5487  5540 I jxcore-log: 
,08-31 16:50:59.992  1017  1096 V AlarmManager: waitForAlarm result :8,
,08-31 16:51:00.252   330   330 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-31 16:51:00.422  5487  5540 I jxcore-log: Running unit tests,
08-31 16:51:00.422  5487  5540 I jxcore-log: 
08-31 16:51:00.422  5487  5540 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-31 16:51:00.422  5487  5540 I jxcore-log: Failed to execute UT.
08-31 16:51:00.422  5487  5540 I jxcore-log: 
,08-31 16:51:00.422  5487  5540 I jxcore-log: Unit Test app is loaded,
08-31 16:51:00.422  5487  5540 I jxcore-log: 
,08-31 16:51:00.432  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-31 16:51:00.432  5487  5540 I jxcore-log: 
,08-31 16:51:00.432  1017  1140 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-31 16:51:00.432  1017  1140 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-31 16:51:00.432  1017  1140 D SecContentProvider2: mCursor = null
,08-31 16:51:00.442  5487  5487 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
,08-31 16:51:00.442  1017  1140 D WifiService: setWifiEnabled: true pid=5487, uid=10155
,08-31 16:51:00.442  1017  1140 W ActivityManager: Permission Denial: getCurrentUser() from pid=5487, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:51:00.442  1017  1140 W WifiService: Failed getting userId using ActivityManagerNative
08-31 16:51:00.442  1017  1140 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5487, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.442  1017  1140 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 16:51:00.442  1017  1140 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-31 16:51:00.442  1017  1140 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-31 16:51:00.442  1017  1140 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-31 16:51:00.442  1017  1140 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 16:51:00.442  1017  1140 D SettingsProvider: name = wifi_on
,08-31 16:51:00.452  1017  1491 I WifiService: disconnect: pid=5487, uid=10155
08-31 16:51:00.452  1017  1128 E WifiHW  : ##################### set firmware type 0 #####################
,08-31 16:51:00.452  5487  5540 D BluetoothAdapter: enable()
,08-31 16:51:00.452  1017  1689 W ActivityManager: Permission Denial: getCurrentUser() from pid=5487, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-31 16:51:00.492  1017  1689 W BluetoothManagerService: Failed getting userId using ActivityManagerNative,
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=5487, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-31 16:51:00.492  1017  1689 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-31 16:51:00.492  1017  1689 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.492  1017  1689 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.492  1017  1689 D SettingsProvider: name = bluetooth_on
,08-31 16:51:00.502  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-31 16:51:00.502  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.502  5487  5540 I jxcore-log: My device name is: samsung-SM-A500FU
08-31 16:51:00.502  5487  5540 I jxcore-log: 
,08-31 16:51:00.502  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth,
08-31 16:51:00.502  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-31 16:51:00.502  1017  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:00.502  5487  5540 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 16:51:00.502  5487  5540 I jxcore-log: 
08-31 16:51:00.502  1017  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.502  1017  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.502  1017  1047 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:00.522  5567  5567 E Zygote  : MountEmulatedStorage(),
08-31 16:51:00.522  5567  5567 E Zygote  : v2
08-31 16:51:00.522  5567  5567 I libpersona: KNOX_SDCARD checking this for 1002,
08-31 16:51:00.522  5567  5567 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:00.522  5567  5567 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-31 16:51:00.532  5567  5567 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:00.532  1017  1047 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=5567 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-31 16:51:00.532  5567  5567 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:00.572  5567  5567 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:00.572  5567  5567 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:00.592  5567  5567 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-31 16:51:00.592  5567  5567 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:00.632  5567  5567 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-31 16:51:00.682  5567  5567 D BtSettings.ProfileConfig: Adding GattService
,08-31 16:51:00.682  5567  5567 D BtSettings.ProfileConfig: Adding HeadsetService
,08-31 16:51:00.682  5567  5567 D BtSettings.ProfileConfig: Adding A2dpService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding HidService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding HealthService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding PanService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding SapService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding SapClientService
,08-31 16:51:00.692  5567  5567 D BtSettings.ProfileConfig: Adding HidDevService
,08-31 16:51:00.692  5567  5567 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-31 16:51:00.702  1017  1692 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-31 16:51:00.702  1017  1692 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.702  1017  1692 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.702  1017  1692 D SettingsProvider: selectionArgs: false
08-31 16:51:00.702  1017  1692 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.702  1017  1692 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.702  1017  1692 D SettingsProvider: ret = -1
,08-31 16:51:00.702  1017  1692 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.712  1017  1140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-31 16:51:00.712  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.712  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.712  1017  1140 D SettingsProvider: selectionArgs: false
08-31 16:51:00.712  1017  1140 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.712  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.712  1017  1140 D SettingsProvider: ret = -1
,08-31 16:51:00.712  1017  1140 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.712  1017  1689 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-31 16:51:00.712  1017  1689 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.712  1017  1689 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.712  1017  1689 D SettingsProvider: selectionArgs: false
08-31 16:51:00.712  1017  1689 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.712  1017  1689 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.712  1017  1689 D SettingsProvider: ret = -1
,08-31 16:51:00.722  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:00.722  1017  1689 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.722  1017  2876 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-31 16:51:00.722  1017  2876 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-31 16:51:00.722  1017  2876 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.722  1017  2876 D SettingsProvider: selectionArgs: false
08-31 16:51:00.722  1017  2876 D SettingsProvider: selectionArgs: 1002
,08-31 16:51:00.722  1017  2876 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 16:51:00.722  1017  2876 D SettingsProvider: ret = -1
,08-31 16:51:00.732  1017  2876 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.732  1017  1688 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-31 16:51:00.732  1017  1688 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.732  1017  1688 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.732  1017  1688 D SettingsProvider: selectionArgs: false
08-31 16:51:00.732  1017  1688 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.732  1017  1688 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.732  1017  1688 D SettingsProvider: ret = -1
,08-31 16:51:00.742  1017  1688 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
08-31 16:51:00.742  1017  1140 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-31 16:51:00.742  1017  1140 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.742  1017  1140 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.742  1017  1140 D SettingsProvider: selectionArgs: false
08-31 16:51:00.742  1017  1140 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.742  1017  1140 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.742  1017  1140 D SettingsProvider: ret = -1
08-31 16:51:00.752  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-31 16:51:00.752  1017  1140 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
08-31 16:51:00.762  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.762  1017  1468 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-31 16:51:00.762  1017  1468 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.762  1017  1468 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.762  1017  1468 D SettingsProvider: selectionArgs: false
08-31 16:51:00.762  1017  1468 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.762  1017  1468 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.762  1017  1468 D SettingsProvider: ret = -1
,08-31 16:51:00.762  1017  1468 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,08-31 16:51:00.762  1017  2876 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-31 16:51:00.762  1017  2876 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.762  1017  2876 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.762  1017  2876 D SettingsProvider: selectionArgs: false
08-31 16:51:00.762  1017  2876 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.762  1017  2876 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.762  1017  2876 D SettingsProvider: ret = -1
,08-31 16:51:00.772  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.772  1017  2876 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.772  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.782  1017  1477 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:51:00.782  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.782  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.782  1017  1477 D SettingsProvider: selectionArgs: false
,08-31 16:51:00.782  1017  1477 D SettingsProvider: selectionArgs: 1002
,08-31 16:51:00.782  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.782  1017  1477 D SettingsProvider: ret = -1
,08-31 16:51:00.782  1017  1477 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.782  1017  1029 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.782  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.782  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.782  1017  1029 D SettingsProvider: selectionArgs: false
08-31 16:51:00.782  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.782  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.782  1017  1029 D SettingsProvider: ret = -1
,08-31 16:51:00.792  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.792  1017  1029 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.792  1017  1481 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:00.792  1017  1481 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.792  1017  1481 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.792  1017  1481 D SettingsProvider: selectionArgs: false
08-31 16:51:00.792  1017  1481 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.792  1017  1481 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.792  1017  1481 D SettingsProvider: ret = -1
,08-31 16:51:00.802  1017  1481 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.802  1017  2875 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-31 16:51:00.802  1017  2875 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:00.802  1017  2875 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:00.802  1017  2875 D SettingsProvider: selectionArgs: false
08-31 16:51:00.802  1017  2875 D SettingsProvider: selectionArgs: 1002
08-31 16:51:00.802  1017  2875 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:00.802  1017  2875 D SettingsProvider: ret = -1
,08-31 16:51:00.802  1017  2875 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:00.802  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.812  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.822  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.822  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.832  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.832  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:00.842  5567  5567 D BluetoothAdapterState: make
,08-31 16:51:00.842  5567  5567 I bluedroid: init
,08-31 16:51:00.842  5567  5597 I BluetoothAdapterState: Entering OffState
,08-31 16:51:00.852  5567  5567 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-31 16:51:00.852  5567  5567 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-31 16:51:00.862  5567  5567 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-31 16:51:00.862  5567  5567 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-31 16:51:00.862  5567  5567 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-31 16:51:00.862  5567  5567 I bluedroid: get_profile_interface socket
,08-31 16:51:00.862  5567  5567 I bluedroid: get_profile_interface map_client
,08-31 16:51:00.862  5567  5567 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-31 16:51:00.872  5567  5600 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-31 16:51:00.872  5567  5567 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:00.872  1017  1252 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 16:51:00.872  1017  1252 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.872  1017  1252 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:00.872  1017  1252 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:00.872  1017  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:00.882  5567  5600 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 16:51:00.882  5567  5600 E BluetoothServiceJni: populateRssiValuesNative
,08-31 16:51:00.882  5567  5600 I bluedroid: getModelRssiValues
08-31 16:51:00.882  5567  5600 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:51:00.882  5567  5600 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
08-31 16:51:00.882  5567  5600 D BluetoothAdapterProperties: Name is: A5-1
,08-31 16:51:00.882  5567  5578 I bluedroid: config_hci_snoop_log
,08-31 16:51:00.882  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 16:51:00.882  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,08-31 16:51:00.892  1017  1047 D BluetoothManagerService: Ble is always on enable gatt
,08-31 16:51:00.892  1017  1047 I BluetoothManagerService: enableGattForLeMode, doBind called
08-31 16:51:00.892  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-31 16:51:00.892  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 16:51:00.892  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.892  5567  5567 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
08-31 16:51:00.892  1017  1047 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-31 16:51:00.892  1017  1047 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-31 16:51:00.902  1017  1047 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-31 16:51:00.902  5567  5597 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-31 16:51:00.902  5567  5597 D BluetoothAdapterProperties: Setting state to 11
,08-31 16:51:00.902  5567  5597 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-31 16:51:00.902  5567  5597 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-31 16:51:00.902  5567  5597 D BluetoothAdapterService: updateAdapterState state is 11
,08-31 16:51:00.902  5567  5597 D BluetoothAdapterService: Autoconnection is available 
,08-31 16:51:00.902  5567  5597 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-31 16:51:00.912  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:51:00.912  1017  1017 I InputMethodManagerService: [BT Setting State] State =11
,08-31 16:51:00.912  1017  1045 D Tethering: interfaceAdded wlan0
,08-31 16:51:00.922  5567  5597 D BluetoothSecureManager: getInstant: null
08-31 16:51:00.922  5567  5597 D BluetoothSecureManager: calling getMethod for getService
08-31 16:51:00.922  5567  5597 D BluetoothSecureManager: calling getService
,08-31 16:51:00.922  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 16:51:00.922  5567  5597 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@34ea746c
08-31 16:51:00.922  1017  1477 D BluetoothSecureManagerService: isSecureModeEnabled
08-31 16:51:00.922  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:00.922  1179  1179 D BluetoothTile:  getBluetoothState : 11
08-31 16:51:00.922  1017  1477 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-31 16:51:00.922  5567  5597 D BtConfig.SecureMode: isSecureModeOn:false
08-31 16:51:00.922  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-31 16:51:00.922  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-31 16:51:00.922  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-31 16:51:00.932  1804  1804 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-31 16:51:00.932  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-31 16:51:00.932  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-31 16:51:00.932  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService,
08-31 16:51:00.932  1179  1698 D BluetoothTile:  handleUpdatestate:false name:null
08-31 16:51:00.932  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-31 16:51:00.932  1179  1698 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-31 16:51:00.942  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-31 16:51:00.942  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-31 16:51:00.942  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:00.942  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 16:51:00.942  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 16:51:00.942  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:00.942  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:00.942  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:00.942  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:00.942  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:00.942  1017  1131 E Tethering: No numeric data
08-31 16:51:00.942  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 16:51:00.942  1017  2875 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-31 16:51:00.942  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-31 16:51:00.942  1017  1468 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-31 16:51:00.942  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-31 16:51:00.952  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-31 16:51:00.952  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:00.952  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-31 16:51:00.952  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-31 16:51:00.952  1017  1045 D Tethering: interfaceAdded p2p0
08-31 16:51:00.952  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-31 16:51:00.952  1017  1045 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-31 16:51:00.952  5567  5597 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-31 16:51:00.952  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-31 16:51:00.952  1017  1131 D Tethering: clearTetheredNotification()
08-31 16:51:00.952  1017  1131 D Tethering: InitialState.processMessage what=4
08-31 16:51:00.952  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-31 16:51:00.952   277   961 I WifiHW  : wifi_change_fw_path(): fwpath = sta
08-31 16:51:00.952   277   961 D SoftapController: Softap fwReload - Ok
,08-31 16:51:00.952  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:00.952  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:00.952  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:00.952  1017  1125 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:00.952  1017  1131 E Tethering: No numeric data
08-31 16:51:00.952  5567  5597 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:00.952  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:51:00.962  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 16:51:00.962   277   957 D EnterpriseController: uids 1000
08-31 16:51:00.962   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:00.962   277   957 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:00.962  1179  1179 D HotspotTile: updateTetherState():false, false
,08-31 16:51:00.962   277   957 D EnterpriseController: uids 1000
08-31 16:51:00.962   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:00.962   277   957 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:00.962  5567  5597 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:00.962  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-31 16:51:00.962  1017  1131 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-31 16:51:00.962  1017  1131 D Tethering: clearTetheredNotification()
,08-31 16:51:00.962  1017  1125 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:00.962   277   961 D CommandListener: Setting iface cfg
08-31 16:51:00.962   277   961 D CommandListener: Trying to bring down wlan0
08-31 16:51:00.962  5567  5597 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-31 16:51:00.962  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-31 16:51:00.962   277   961 D CommandListener: Clearing all IP addresses on wlan0
,08-31 16:51:00.962  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:00.962  5567  5597 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-31 16:51:00.962  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:00.962  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:00.972  1017  1125 V NetworkStats: performPollLocked() took 3ms
,08-31 16:51:00.972  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-31 16:51:00.972  1179  1179 D HotspotTile: updateTetherState():false, false
08-31 16:51:00.972  1283  1283 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:51:00.972  1017  1125 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:00.972  1017  1126 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:00.972  1017  1125 D NtpTrustedTime: forceRefresh Fail.
08-31 16:51:00.972  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
08-31 16:51:00.972  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:00.972  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 16:51:00.972  1017  1126 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:00.982  1017  1125 V NetworkStats: performPollLocked() took 5ms
,08-31 16:51:00.982  1017  1126 D NtpTrustedTime: forceRefresh() from cache miss
,08-31 16:51:00.982  1017  1126 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:00.982  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:00.982  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-31 16:51:00.982  5567  5597 D BluetoothBondStateMachine: make
,08-31 16:51:00.982  1017  1252 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-31 16:51:00.982  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.982  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.982  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:00.982  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:00.992  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-31 16:51:00.992  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-31 16:51:00.992  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-31 16:51:00.992  5567  5604 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-31 16:51:00.992  5606  5606 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.002  5606  5606 I libpersona: KNOX_SDCARD checking this for 10003
08-31 16:51:00.992  5606  5606 E Zygote  : v2
08-31 16:51:01.002  5606  5606 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.002  5606  5606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-31 16:51:01.002  5606  5606 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:01.002  5606  5606 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.012  1017  1252 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5606 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-31 16:51:01.012  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.012  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.012  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.012  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.012  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.012  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.012  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.012  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-31 16:51:01.012  1017  1481 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.012  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.012  5567  5567 D BtGatt.DebugUtils: handleDebugAction() action=null
08-31 16:51:01.012  5567  5567 D BtGatt.GattService: Received start request. Starting profile...
08-31 16:51:01.022  5567  5567 D BtGatt.GattService: start()
08-31 16:51:01.022  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.022  5567  5567 D BtGatt.GattService: start()
08-31 16:51:01.022  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.022  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:01.022  5567  5567 I bluedroid: get_profile_interface gatt
,08-31 16:51:01.022  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.022  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.022  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.022  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-31 16:51:01.022  5567  5567 D BtGatt.AdvertiseManager: advertise manager created
,08-31 16:51:01.022  1017  2875 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.022  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.022  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.022  1017  2875 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.022  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.022  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-31 16:51:01.022  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-31 16:51:01.022  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-31 16:51:01.032  1017  1692 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.032  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.032  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.032  1017  1692 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.032  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.032  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-31 16:51:01.032  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-31 16:51:01.032  5567  5567 D BtGatt.GattService: mStartError = false
08-31 16:51:01.032  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.042  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-31 16:51:01.042  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.042  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.042  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.042  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.042  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.042  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-31 16:51:01.042  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-31 16:51:01.042  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-31 16:51:01.042  5606  5606 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:01.042  5567  5567 D HeadsetService: Received start request. Starting profile...
08-31 16:51:01.042  5567  5567 D HeadsetService: start()
08-31 16:51:01.042  1017  1688 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.042  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.052  5606  5606 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.052  1017  1688 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.052  1017  1688 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.052  1017  1688 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.052  5567  5567 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-31 16:51:01.052  5567  5567 D HeadsetStateMachine: make
08-31 16:51:01.052  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:01.052  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-31 16:51:01.052  5567  5597 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-31 16:51:01.062  5567  5567 E HeadsetStateMachine: # of Max HF connection is 2
,08-31 16:51:01.062  1017  1030 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.062  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.062  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:01.062  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.062  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.072  1017  2875 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-31 16:51:01.072  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.072  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-31 16:51:01.072  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-31 16:51:01.072  5567  5597 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-31 16:51:01.072  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.072  1017  2875 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.072  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-31 16:51:01.072  1017  1029 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:01.072  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 16:51:01.072  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.072  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.072  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:01.072  1017  1689 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-31 16:51:01.072  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.072  1017  1689 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
08-31 16:51:01.082  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.082  1017  1689 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.082  1017  1689 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.082  1017  1689 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-31 16:51:01.082  1017  1128 E WifiHW  : supplicant_name : p2p_supplicant
08-31 16:51:01.082  5567  5597 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-31 16:51:01.082  5567  5567 I bluedroid: get_profile_interface handsfree
08-31 16:51:01.082  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.082  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-31 16:51:01.082  5567  5597 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-31 16:51:01.082  1017  1128 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,08-31 16:51:01.082  1017  1128 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory,
,08-31 16:51:01.092  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.092  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.092  5567  5597 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-31 16:51:01.092  5567  5597 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-31 16:51:01.092  5567  5597 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-31 16:51:01.092  5567  5597 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-31 16:51:01.092  5567  5597 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-31 16:51:01.102  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:01.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-31 16:51:01.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:01.102  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:01.102  5606  5606 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-31 16:51:01.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.102  1179  1698 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-31 16:51:01.102  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-31 16:51:01.102  1283  1283 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
08-31 16:51:01.102  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:01.102  1179  1179 D HotspotTile: onReceive : 2, 0
,08-31 16:51:01.132  5567  5567 I DualScoManager: Instantiating Dual Sco Manager
,08-31 16:51:01.132  5567  5567 I DualScoManager: Set HeadsetServiceHelper
,08-31 16:51:01.132  5567  5567 D BluetoothAtMessage: createCMTIContentObservers
,08-31 16:51:01.132  1017  1029 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-31 16:51:01.132  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:01.132  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:01.132  1017  1029 D SettingsProvider: selectionArgs: false
08-31 16:51:01.132  1017  1029 D SettingsProvider: selectionArgs: 1002
,08-31 16:51:01.132  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:01.132  1017  1029 D SettingsProvider: ret = -1
,08-31 16:51:01.142  5606  5606 D UserAnalysis.SecureDbManager: Key for secure DB is newly created,
,08-31 16:51:01.142  5606  5606 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
,08-31 16:51:01.142  5606  5606 D UserAnalysis: Create SecureDbHelper
,08-31 16:51:01.142  1017  1029 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002,
,08-31 16:51:01.142  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:01.152  5567  5623 D HeadsetStateMachine: Enter Disconnected: -2
,08-31 16:51:01.152  5606  5606 D IntelligenceServiceApplication: onCreate()
,08-31 16:51:01.152  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:01.152  5567  5567 D HeadsetService: mStartError = false
08-31 16:51:01.152  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.162  1017  1017 D BluetoothA2dp: Proxy object connected
,08-31 16:51:01.162  2696  2696 D BluetoothA2dp: Proxy object connected
,08-31 16:51:01.172  5624  5624 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
08-31 16:51:01.172  5624  5624 I wpa_supplicant: Successfully initialized wpa_supplicant
08-31 16:51:01.172  5624  5624 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-31 16:51:01.182  5606  5606 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-31 16:51:01.192  5567  5567 D A2dpService: Received start request. Starting profile...,
08-31 16:51:01.192  5567  5567 D A2dpService: start()
08-31 16:51:01.192  5567  5567 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-31 16:51:01.192  5567  5567 I bluedroid: get_profile_interface avrcp,
,08-31 16:51:01.192  5567  5623 D HeadsetStateMachine: Clear mHeadsetBrsf
08-31 16:51:01.192  5567  5623 D HeadsetStateMachine: map size, before remove : 0
08-31 16:51:01.192  5567  5623 D HeadsetStateMachine: map size, after remove: 0
08-31 16:51:01.202  5624  5624 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-31 16:51:01.202   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5624
08-31 16:51:01.202   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x0000010C
08-31 16:51:01.202  5624  5624 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-31 16:51:01.202  5624  5624 I wpa_supplicant: ssSupport state is = 1
08-31 16:51:01.202  5624  5624 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-31 16:51:01.202  5624  5624 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-31 16:51:01.202   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Credentials: uid 1010, gid 1010, pid 5624
08-31 16:51:01.202   370   370 I SecureStorage: [INFO]: SPID(0x00000001)Received function mask & code: 0x00000106
08-31 16:51:01.202  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-31 16:51:01.202  5606  5606 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-31 16:51:01.202  5567  5567 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-31 16:51:01.222  5606  5606 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
08-31 16:51:01.232  5567  5567 I Avrcp   :  Updating now playing list upon AVRCP Start
08-31 16:51:01.232  5567  5627 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-31 16:51:01.232  5567  5567 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-31 16:51:01.232  5567  5567 D A2dpStateMachine: make
08-31 16:51:01.242  5567  5567 I bluedroid: get_profile_interface a2dp
08-31 16:51:01.242  5567  5630 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-31 16:51:01.242  5567  5567 E bt-btif : warning : media task started media_task_refcnt 1 
,08-31 16:51:01.252  5567  5567 D A2dpService: mStartError = false
08-31 16:51:01.252  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:01.252  5567  5567 I BluetoothHidServiceJni: classInitNative: succeeds
08-31 16:51:01.252  5567  5629 D A2dpStateMachine: Enter Disconnected: -2
08-31 16:51:01.252  5567  5627 D BluetoothMediaBrowser: no now playing list
08-31 16:51:01.252  5567  5627 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-31 16:51:01.252  5567  5567 D HidService: Received start request. Starting profile...
08-31 16:51:01.252  5567  5567 D HidService: start()
08-31 16:51:01.252  5567  5567 I bluedroid: get_profile_interface hidhost
08-31 16:51:01.252  5567  5567 D HidService: setHidService(): set to: null
08-31 16:51:01.252  5567  5567 D HidService: mStartError = false
08-31 16:51:01.252  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.252  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-31 16:51:01.252  5567  5567 I BluetoothHealthServiceJni: classInitNative: succeeds
08-31 16:51:01.262  5567  5567 D HealthService: Received start request. Starting profile...
08-31 16:51:01.262  5567  5567 D HealthService: start()
08-31 16:51:01.262  5567  5567 I bluedroid: get_profile_interface health
08-31 16:51:01.262  5567  5567 D HealthService: mStartError = false
08-31 16:51:01.262  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.262  5567  5567 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-31 16:51:01.272  1017  1017 D BluetoothPan: BluetoothPAN Proxy object connected
08-31 16:51:01.272  5567  5567 D PanService: Received start request. Starting profile...
08-31 16:51:01.272  5567  5567 D PanService: start()
08-31 16:51:01.272  5567  5567 D BluetoothPanServiceJni: initializeNative(L110): pan
08-31 16:51:01.272  5567  5567 I bluedroid: get_profile_interface pan
08-31 16:51:01.272  5567  5567 D PanService: mStartError = false
08-31 16:51:01.272  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.272  5567  5567 D BluetoothMapService: Received start request. Starting profile...
08-31 16:51:01.272  5567  5567 D BluetoothMapService: start()
08-31 16:51:01.282  5567  5567 D BluetoothMapService: mStartError = false
08-31 16:51:01.282  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.282  5567  5567 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-31 16:51:01.302  5567  5567 D SapService: Received start request. Starting profile...
08-31 16:51:01.302  1423  1433 I Telecom : BluetoothPhoneService: queryPhoneState
08-31 16:51:01.302  5567  5567 D SapService: start()
08-31 16:51:01.302  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-31 16:51:01.302  5567  5567 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-31 16:51:01.302  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-31 16:51:01.302  5567  5567 I bluedroid: get_profile_interface sap
08-31 16:51:01.302  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 16:51:01.302  5567  5567 D SapService: mStartError = false
08-31 16:51:01.302  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-31 16:51:01.302  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
08-31 16:51:01.302  5567  5567 D HeadsetStateMachine: Proxy object connected
08-31 16:51:01.302  5567  5567 D HeadsetStateMachine: Try to query the phonestate on bind
,08-31 16:51:01.322  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:01.322  1423  1423 W BluetoothHeadset: Proxy not attached to service
08-31 16:51:01.322  1423  1433 I Telecom : BluetoothPhoneService: Result of Message : true
,08-31 16:51:01.322  5567  5567 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-31 16:51:01.322  5567  5567 D HeadsetPhoneState: sendDeviceDataStateChanged
08-31 16:51:01.322  5567  5567 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-31 16:51:01.322  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-31 16:51:01.322  5567  5623 D HeadsetStateMachine: Disconnected process message: 11
08-31 16:51:01.322  5567  5567 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:51:01.322  5567  5623 D HeadsetStateMachine: Disconnected process message: 18
08-31 16:51:01.322  5567  5567 D BluetoothA2dp: Proxy object connected
08-31 16:51:01.322  5567  5567 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-31 16:51:01.322  5567  5623 D HeadsetStateMachine: Disconnected process message: 10
,08-31 16:51:01.322  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-31 16:51:01.322  1017  1692 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-31 16:51:01.322  5567  5623 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=3
,08-31 16:51:01.322  5567  5623 D HeadsetStateMachine: Disconnected process message: 11
08-31 16:51:01.332  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.332  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.332  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.332  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.352  1017  1692 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=5634 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-31 16:51:01.352  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-31 16:51:01.352  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-31 16:51:01.352  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
08-31 16:51:01.352  1017  2875 I art     : Explicit concurrent mark sweep GC freed 40390(2MB) AllocSpace objects, 27(432KB) LOS objects, 33% free, 27MB/41MB, paused 3.274ms total 198.344ms
,08-31 16:51:01.352  5634  5634 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.352  5634  5634 I libpersona: KNOX_SDCARD checking this for 10107
08-31 16:51:01.352  5634  5634 E Zygote  : v2
08-31 16:51:01.352  5634  5634 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.352  5634  5634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:01.362  5634  5634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:01.362  5634  5634 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-31 16:51:01.362  1017  1477 D ActivityManager: getContentProviderImpl callerProcessName:com.android.bluetooth, calleePkgName: com.android.email,
,08-31 16:51:01.362  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.362  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.362  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.362  1017  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.392   305   305 I art     : Explicit concurrent mark sweep GC freed 8705(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 44.885ms
,08-31 16:51:01.392  5634  5634 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:01.402  5634  5634 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.412   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Secure Storage Daemon finished processing with result: 0
,08-31 16:51:01.422   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 608us total 26.375ms
,08-31 16:51:01.422  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)Processing data has been completed
,08-31 16:51:01.432   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 600us total 16.409ms,
,08-31 16:51:01.442  5649  5649 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:01.442  5649  5649 E Zygote  : v2,
08-31 16:51:01.442  5649  5649 I libpersona: KNOX_SDCARD checking this for 10145
08-31 16:51:01.442  5649  5649 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:01.452  5649  5649 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:01.452  5649  5649 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:01.452  5649  5649 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:01.462  1017  1477 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=5649 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
,08-31 16:51:01.462  1017  1030 I ActivityManager: Killing 4337:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,08-31 16:51:01.492  5649  5649 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:01.492  5649  5649 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:01.492  5624  5624 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-31 16:51:01.492  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 16:51:01.512  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 16:51:01.512   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5624
08-31 16:51:01.512   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 16:51:01.512  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 16:51:01.512  5624  5624 I wpa_supplicant: ssSupport state is = 1
,08-31 16:51:01.522  5649  5649 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
08-31 16:51:01.522  5649  5649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:01.522  5649  5649 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 16:51:01.522  5649  5649 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:01.522  5649  5649 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.,
,08-31 16:51:01.532  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.532  5624  5624 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.532  5624  5624 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.532  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.532  5624  5624 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.532  5624  5624 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.532  5624  5624 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:51:01.532  5624  5624 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:01.532  5624  5624 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-31 16:51:01.532  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.532  5624  5624 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-31 16:51:01.532  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.532  5624  5624 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.532  5624  5624 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:01.532  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-31 16:51:01.532  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:01.532  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
,08-31 16:51:01.582  5624  5624 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-31 16:51:01.582  1017  1252 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.602  1017  2876 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.652  1017  1491 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.662  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-31 16:51:01.662  5567  5567 E BluetoothAdapterService(700915430): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-31 16:51:01.672  1017  2876 I ActivityManager: Killing 4224:com.samsung.android.sm/1000 (adj 15): empty #31
,08-31 16:51:01.672  1017  1688 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.672  5567  5597 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-31 16:51:01.672  5567  5597 I bluedroid: enable
,08-31 16:51:01.672  5567  5597 I bt_hci_bdroid: init
,08-31 16:51:01.672  5567  5680 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-31 16:51:01.682  5567  5597 I bt_vendor: bt-vendor : init
08-31 16:51:01.682  5567  5597 I bt_vendor: bt-vendor : get_bt_soc_type
08-31 16:51:01.682  5567  5597 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-31 16:51:01.682  5567  5597 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-31 16:51:01.682  5567  5597 D bt_userial_mct: userial_init
08-31 16:51:01.682  5567  5597 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-31 16:51:01.682  5567  5597 I bt_vendor: Starting hciattach daemon
08-31 16:51:01.682  5567  5597 I bt_vendor: try to set false
,08-31 16:51:01.682  5567  5597 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-31 16:51:01.682  5567  5597 I bt_vendor: Starting hciattach daemon
08-31 16:51:01.682  5567  5597 I bt_vendor: try to set true
,08-31 16:51:01.682  5624  5624 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
08-31 16:51:01.682  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 16:51:01.702  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 16:51:01.702   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5624
08-31 16:51:01.702   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 16:51:01.702  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 16:51:01.702  5624  5624 I wpa_supplicant: ssSupport state is = 1
,08-31 16:51:01.702  5244  5258 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-31 16:51:01.712  5624  5624 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-31 16:51:01.712  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)Checking if this device supports Secure Storage
,08-31 16:51:01.712  5686  5686 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-31 16:51:01.722  5244  5258 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-31 16:51:01.722  5244  5258 D BadgeProvider: sendNotify, [notify] : null
08-31 16:51:01.722  5244  5258 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-31 16:51:01.722  5244  5258 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-31 16:51:01.722  5244  5258 D BadgeProvider: update, [UpdateCount] : 1
,08-31 16:51:01.732  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)This device supports Secure Storage
,08-31 16:51:01.732   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 5624,
08-31 16:51:01.732  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.732   370   370 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-31 16:51:01.732  5624  5624 I SecureStorage: [INFO]: SPID(0x00000002)SS Daemon is running
08-31 16:51:01.732  5624  5624 I wpa_supplicant: ssSupport state is = 1,
08-31 16:51:01.732  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:01.732  5624  5624 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:01.732  5624  5624 E wpa_supplicant: SIM READ ERROR
08-31 16:51:01.732  5624  5624 I wpa_supplicant: wpa_default_ap_write_once
08-31 16:51:01.732  5624  5624 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-31 16:51:01.732  5624  5624 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-31 16:51:01.732  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.742  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.732  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
08-31 16:51:01.742  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.742  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:01.742  1469  1469 D Launcher.Model: reloadBadges entered.,
,08-31 16:51:01.742  1017  2875 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:01.762  1017  1468 D RCPManagerService: exchangeData() failure , invalid userId,
,08-31 16:51:01.772  5695  5695 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-31 16:51:01.782  5696  5696 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-31 16:51:01.802  5624  5624 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-31 16:51:01.802  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-31 16:51:01.812  5698  5698 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 16:51:01.822  5700  5700 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-31 16:51:01.822  5701  5701 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-31 16:51:01.832  5702  5702 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-31 16:51:01.872  5624  5624 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
,08-31 16:51:01.872  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-31 16:51:01.872  5624  5624 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:01.882  1017  2875 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-31 16:51:01.882  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 16:51:01.882  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.882  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:01.882  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 16:51:01.892  1928  1928 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:01.892  1928  1928 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:01.922  1017  1045 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-31 16:51:01.922  1017  1045 D Tethering: interfaceLinkStateChanged p2p0, false
08-31 16:51:01.922  1017  1045 D Tethering: interfaceStatusChanged p2p0, false
,08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=387 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=379 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=328 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=328 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=327 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=325 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=322 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.k.c(PG:583)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.e.b(PG:170)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.952  1017  2875 I ActivityManager: Killing 4815:com.google.android.partnersetup/u0a15 (adj 15): empty #31
08-31 16:51:01.942  5634  5634 D StrictMode: StrictMode policy violation; ~duration=290 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.io.File.exists(File.java:363)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:01.942  5634  5634 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-31 16:51:01.952  1928  1928 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-31 16:51:01.962  1928  1928 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-31 16:51:01.972  1017  2876 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:01.972  1017  2876 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-31 16:51:01.972  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:01.972  1017  2876 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:01.972  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-31 16:51:01.972  3411  3411 I Hs20UtilService: Starting #2
08-31 16:51:01.972  3411  3444 I Hs20UtilService: Message received 5011
08-31 16:51:01.982  1017  1491 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-31 16:51:01.982  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.982  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.982  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:01.982  1017  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:01.992  5705  5705 E Zygote  : MountEmulatedStorage()
08-31 16:51:01.992  5705  5705 E Zygote  : v2
08-31 16:51:01.992  5705  5705 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:01.992  5705  5705 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:01.992  1017  1491 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=5705 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-31 16:51:02.002  5705  5705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:02.002  5705  5705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:02.002  1017  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-31 16:51:02.012  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.012  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.012  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:02.012  5705  5705 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.052  5634  5677 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.,
,08-31 16:51:02.052  5705  5705 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-31 16:51:02.052  5705  5705 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.062  5720  5720 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab 
,08-31 16:51:02.072  5722  5722 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-31 16:51:02.092  5567  5597 I bt_vendor: bluetooth satus is on
,08-31 16:51:02.092  5567  5682 D bt_userial_mct: userial_open(port:0)
08-31 16:51:02.092  5567  5682 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-31 16:51:02.092  5567  5682 I bt_vendor: Done intiailizing UART
,08-31 16:51:02.102  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-31 16:51:02.102  1017  1689 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.102  5567  5682 I bt_vendor: Done intiailizing UART
08-31 16:51:02.102  5567  5682 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-31 16:51:02.102  5567  5682 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-31 16:51:02.102  1017  1689 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.102  1017  1689 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:02.102  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-31 16:51:02.102  5624  5624 I wpa_supplicant: HOTSPOT20_ENABLE called
08-31 16:51:02.102  5624  5624 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-31 16:51:02.102  5624  5624 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-31 16:51:02.102  5624  5624 E wpa_supplicant: SIM READ ERROR
08-31 16:51:02.102  5624  5624 I wpa_supplicant: Blacklist: Clear (all) 
,08-31 16:51:02.102  1017  1689 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.102  5567  5726 D bt_userial_mct: Entering userial_read_thread()
,08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_HCI
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_AVDT
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_AVRC
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_A2D
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_BNEP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_BTM
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_GAP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_PAN
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_SAP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_SDP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_GATT
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_SMP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_BTIF
08-31 16:51:02.122  5567  5680 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-31 16:51:02.122  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
08-31 16:51:02.122  1017  1692 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-31 16:51:02.122  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.132  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.132  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 16:51:02.132  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.132  5705  5705 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:51:02.132  5705  5705 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:02.142  5624  5624 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-31 16:51:02.142  1017  1689 I ActivityManager: Killing 4914:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-31 16:51:02.152  5624  5624 I wpa_supplicant: Skip scan - bUseNetwork false
,08-31 16:51:02.152  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:51:02.152  1017  1128 D WifiConfigStore: Loading config and enabling all networks 
,08-31 16:51:02.152  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:02.152  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:02.152  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:02.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:02.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:02.162  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:02.162  1179  1179 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-31 16:51:02.162  1179  1179 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-31 16:51:02.162  1179  1698 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-31 16:51:02.162  1017  1128 E WifiConfigStore: Not a HS20
,08-31 16:51:02.162  1179  1179 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:02.162  1017  1128 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-31 16:51:02.162  1179  1179 D HotspotTile: onReceive : 3, 0
,08-31 16:51:02.162  1283  1283 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-31 16:51:02.172  5487  5487 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:02.172  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-31 16:51:02.172  5487  5487 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-31 16:51:02.172  5487  5487 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-31 16:51:02.172  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-31 16:51:02.172  1017  1688 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:02.172  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:02.172  1017  1128 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-31 16:51:02.172  5624  5624 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-31 16:51:02.172  5624  5624 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:51:02.172  5624  5624 I wpa_supplicant: reset timer : RESET_TIMER 0
08-31 16:51:02.172  5624  5624 I wpa_supplicant: P2P: Current p2p state = IDLE
08-31 16:51:02.172  5624  5624 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-31 16:51:02.172  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-31 16:51:02.172  5624  5624 I wpa_supplicant: First Scan Start
,08-31 16:51:02.172  5624  5624 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-31 16:51:02.172  1017  1688 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.172  1017  1688 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.172  1017  1688 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:02.182  3411  3411 I Hs20UtilService: Starting #3
,08-31 16:51:02.182  3411  3444 I Hs20UtilService: Message received 5011
,08-31 16:51:02.182  1017  1128 D WifiNative-wlan0: Setting external_sim to 1
,08-31 16:51:02.182  1017  1128 D WifiStateMachine: Setting OUI to DA-A1-19
08-31 16:51:02.182  1017  1128 I WifiNative-HAL: startHal
08-31 16:51:02.182  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9ca4788c
08-31 16:51:02.182  1017  1128 I WifiNative-HAL: Could not start hal
,08-31 16:51:02.182  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:51:02.182  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:02.182  5705  5705 D SecurityLogAgent: StateMachine : Current State = 1
08-31 16:51:02.182  5705  5705 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:02.182  1017  1128 E WifiNative-wlan0: do suspend true
,08-31 16:51:02.192  1017  1128 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-31 16:51:02.192  1017  1127 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-31 16:51:02.192  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.192  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.192  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 16:51:02.192  1017  1017 D WifiScanningService: SCAN_AVAILABLE : 3
,08-31 16:51:02.192  1017  1017 D RttService: SCAN_AVAILABLE : 3
,08-31 16:51:02.192  1017  1151 D WifiScanningService: DefaultState got{ when=-2ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:02.192  1017  1151 I WifiNative-HAL: startHal
08-31 16:51:02.192  1017  1151 E wifi    : getStaticLongField sWifiHalHandle 0x9d9f19bc
,08-31 16:51:02.192  1017  1151 I WifiNative-HAL: Could not start hal
,08-31 16:51:02.192  1017  1152 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:02.192   277   961 D CommandListener: Setting iface cfg
08-31 16:51:02.192   277   961 D CommandListener: Trying to bring up p2p0
08-31 16:51:02.192  1017  1151 E WifiScanningService: could not start HAL
,08-31 16:51:02.192  5624  5624 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 16:51:02.192  1017  1127 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-31 16:51:02.202  5624  5624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-31 16:51:02.202  1017  1127 D WifiP2pService: P2pEnablingState
,08-31 16:51:02.202  1017  1127 D WifiP2pService: P2pEnablingState{ what=147457 }
08-31 16:51:02.202  1017  1127 D WifiP2pService: P2p socket connection successful
,08-31 16:51:02.202  5624  5624 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-31 16:51:02.202  1017  1127 D WifiP2pService: P2pEnabledState
,08-31 16:51:02.202  1017  1127 D WifiP2pService: sending p2p connection changed broadcast: IDLE
08-31 16:51:02.202  1017  1128 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-31 16:51:02.202  1017  1128 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-31 16:51:02.202  1017  1128 E WifiNative-wlan0: invaild command id : 215
,08-31 16:51:02.202  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.202  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:02.212  1017  1017 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-31 16:51:02.212  1017  1048 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-31 16:51:02.212  1017  1127 D WifiP2pService: create mNetworkAgent
08-31 16:51:02.212  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.212  1017  1048 D WifiDisplayController: disconnect
08-31 16:51:02.212  1017  1048 D WifiDisplayController: updateConnection
08-31 16:51:02.212  1017  1048 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-31 16:51:02.212  1017  1048 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:02.212  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:02.212  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:02.212  5567  5680 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-31 16:51:02.222  5567  5680 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ff06e9 
08-31 16:51:02.222  5567  5680 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ff06e9 
,08-31 16:51:02.222  1017  1127 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-31 16:51:02.222  5567  5600 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-31 16:51:02.232  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-31 16:51:02.232  1017  1130 E ConnectivityService: updateNetworkInfo()
08-31 16:51:02.232  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from null to UNKNOWN, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:02.232  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{501}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} } for legacy network type 13
,08-31 16:51:02.232  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress
08-31 16:51:02.232  1017  1127 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
,08-31 16:51:02.232  5567  5600 E bt-btif :                : sec
,08-31 16:51:02.232  1179  1179 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-31 16:51:02.232  1017  1252 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:02.232  1179  1179 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0,
,08-31 16:51:02.232  5567  5600 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-31 16:51:02.232  5567  5600 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-31 16:51:02.232  1017  1048 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: UNKNOWN/IDLE, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-31 16:51:02.232  5567  5600 E BluetoothServiceJni: populateRssiValuesNative
08-31 16:51:02.232  5567  5600 I bluedroid: getModelRssiValues
08-31 16:51:02.232  5567  5600 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-31 16:51:02.232  5567  5600 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-31 16:51:02.242  5567  5600 D BluetoothAdapterProperties: Name is: A5-1
08-31 16:51:02.242  1017  1127 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-31 16:51:02.242  1283  1283 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-31 16:51:02.242  1017  1048 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  primary type: 10-0050F204-5
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  secondary type: null
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  wps: 0
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  grpcapab: 0
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  devcapab: 0
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  status: 3
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  wfdInfo: null
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  groupownerAddress: null
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  GOdeviceName: null
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  interfaceAddress: 
08-31 16:51:02.242  1017  1048 D WifiDisplayController:  SConnectInfo : null
,08-31 16:51:02.242  1283  1283 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:02.242  1017  1017 D SettingsProvider: name = bluetooth_name
,08-31 16:51:02.242  5567  5600 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:02.242  5567  5600 D BluetoothAdapterProperties: Scan Mode:20
08-31 16:51:02.242  5567  5600 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-31 16:51:02.242  5567  5600 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-31 16:51:02.242  5567  5600 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-31 16:51:02.242  5567  5600 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-31 16:51:02.242  5567  5600 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-31 16:51:02.242  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:02.242  5567  5600 E bt-btif : btif_sock_init: !vhci_init
08-31 16:51:02.242  5567  5726 E bt_mct  : hci lib postload completed
08-31 16:51:02.242  5567  5600 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-31 16:51:02.252  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:02.252  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-31 16:51:02.252  1283  1283 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-31 16:51:02.252  1283  2912 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 16:51:02.252  5567  5600 D IOP_DB_BT: db_open: db_open : handle 3028676624l, read 13894 bytes onto local cache
08-31 16:51:02.252  5567  5600 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-31 16:51:02.252  5567  5600 D IOP_DB_BT: db_query: result 1
08-31 16:51:02.252  5567  5600 I         : iop_db_open: iop_db_open status 0
,08-31 16:51:02.252  5567  5600 D bte_conf: Device ID record 1 : primary
,08-31 16:51:02.252  5567  5600 D bte_conf:   vendorId            = 0075
08-31 16:51:02.252  5567  5600 D bte_conf:   vendorIdSource      = 0001
08-31 16:51:02.252  5567  5600 D bte_conf:   product             = 0100
08-31 16:51:02.252  5567  5600 D bte_conf:   version             = 0200
08-31 16:51:02.252  5567  5600 D bte_conf:   clientExecutableURL = 
08-31 16:51:02.252  5567  5600 D bte_conf:   serviceDescription  = 
08-31 16:51:02.252  5567  5600 D bte_conf:   documentationURL    = 
08-31 16:51:02.252  5567  5600 D bte_conf: bte_load_did_conf no section named DID2.
08-31 16:51:02.252  5567  5600 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-31 16:51:02.252  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:02.252  1017  1252 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-31 16:51:02.252  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.252  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.252  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.252  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.272  5736  5736 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:02.272  5736  5736 I libpersona: KNOX_SDCARD checking this for 10068
08-31 16:51:02.272  5736  5736 E Zygote  : v2
08-31 16:51:02.272  5736  5736 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:02.272  5736  5736 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:02.272  1017  1252 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=5736 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:02.272   287   287 E SMD     : DCD OFF
08-31 16:51:02.272  5567  5597 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-31 16:51:02.272  5567  5597 D BluetoothAdapterProperties: ScanMode =  20
08-31 16:51:02.272  5567  5597 D BluetoothAdapterProperties: State =  11
08-31 16:51:02.272  5736  5736 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:02.272  1017  2875 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-31 16:51:02.272  5567  5597 D BluetoothAdapterProperties: Setting state to 12
08-31 16:51:02.272  1017  1127 D WifiP2pService: sending p2p persistent groups changed broadcast
08-31 16:51:02.272  5567  5597 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12,
08-31 16:51:02.272  1017  1127 D WifiP2pService: InactiveState
08-31 16:51:02.272  5624  5624 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-31 16:51:02.272  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.272  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 16:51:02.282  5567  5600 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-31 16:51:02.282  5567  5600 D BluetoothAdapterProperties: Scan Mode:21
,08-31 16:51:02.282  5567  5600 D BluetoothAdapterProperties: Discoverable Timeout:120
08-31 16:51:02.282  5736  5736 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:02.282  1017  1127 D WifiP2pService: InactiveState{ what=143376 }
08-31 16:51:02.282  1017  1127 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-31 16:51:02.282  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:02.282  1017  1029 D SettingsProvider: name = bluetooth_a2dp_sink_mode
08-31 16:51:02.282  1017  1029 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:02.282  1017  1029 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:02.282  1017  1029 D SettingsProvider: selectionArgs: false
08-31 16:51:02.282  1017  1029 D SettingsProvider: selectionArgs: 1002
08-31 16:51:02.282  1017  1029 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:02.282  1017  1029 D SettingsProvider: ret = -1
,08-31 16:51:02.292  1017  1029 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=1002
,08-31 16:51:02.292  5567  5597 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
08-31 16:51:02.292  5567  5597 D BluetoothAdapterService: updateAdapterState state is 12
08-31 16:51:02.292  1017  1692 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.292  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.292  5487  5487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-31 16:51:02.292  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.292  1017  1692 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.292  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.302  5487  5487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-31 16:51:02.302  5567  5625 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:02.312  1179  1195 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.312  5567  5597 D BluetoothAdapterService: Autoconnection is available 
08-31 16:51:02.312  1179  1195 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.312  5567  5597 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-31 16:51:02.312  5567  5597 D BluetoothAdapterService: starting service from this receiver
08-31 16:51:02.312  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:02.312  1017  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.312  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.312  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-31 16:51:02.312  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.312  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-31 16:51:02.312  5567  5597 I BluetoothAdapterState: Entering On State from state = 11
,08-31 16:51:02.312  5487  5487 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-31 16:51:02.312  1928  2092 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.312  1928  2092 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.312  5567  5625 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.312  5567  5625 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.322  1017  1047 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  1017  1047 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.322  1423  1431 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  1423  1431 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.322  5487  5500 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  5487  5500 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.322  2696  2751 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  2696  2751 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-31 16:51:02.322  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-31 16:51:02.322  5567  5567 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-31 16:51:02.322  5634  5647 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  5634  5647 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.322  1017  1047 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:02.322  5487  5487 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-31 16:51:02.322  1445  1657 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.322  1445  1657 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-31 16:51:02.322  1436  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
08-31 16:51:02.332  1436  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-31 16:51:02.332  2696  2708 D BluetoothA2dp: onBluetoothStateChange: up=true
08-31 16:51:02.332  5736  5736 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.332  1017  1047 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-31 16:51:02.332  5736  5736 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:02.332  1017  1047 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-31 16:51:02.332  5567  5567 I BluetoothPbapService: Handler(): got msg=1
,08-31 16:51:02.342  1017  1017 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:02.342  1017  1017 I InputMethodManagerService: [BT Setting State] State =12
,08-31 16:51:02.342  1017  1017 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-31 16:51:02.342  1017  1689 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:51:02.342  1423  1423 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@47332ff, true
,08-31 16:51:02.342  1423  1423 D BluetoothHeadset: registerMessageListener
08-31 16:51:02.342  5567  5753 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-31 16:51:02.352  1179  1179 D BluetoothTile:  onBluetoothStateChange:
,08-31 16:51:02.352  1179  1179 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-31 16:51:02.352  1179  1179 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-31 16:51:02.352  1179  1179 D BluetoothTile:  getBluetoothState : 12
,08-31 16:51:02.352  1804  1804 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-31 16:51:02.352  1179  1698 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:02.362  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 16:51:02.362  1017  2876 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:02.362  1017  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:02.362  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.362  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.362  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.362  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.362  1017  1477 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-31 16:51:02.362  5567  5583 D HeadsetService: registerMessageListener
,08-31 16:51:02.362  5567  5583 D HeadsetService: registerMessageListener
,08-31 16:51:02.362  5567  5623 D HeadsetStateMachine: Disconnected process message: 70
08-31 16:51:02.362  5567  5623 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@3e165793
08-31 16:51:02.362  1179  1179 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-31 16:51:02.372  1423  1423 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-31 16:51:02.372  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-31 16:51:02.372  5567  5755 D BluetoothMapMasInstance: set MAP SDP message type : 1
08-31 16:51:02.372  1179  1698 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:02.372  5567  5753 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:51:02.372  5567  5753 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.372  1179  1698 D BluetoothTile:  handleUpdatestate:false name:null
,08-31 16:51:02.372  5567  5753 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-31 16:51:02.372  5567  5753 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.372  5567  5753 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.372  5567  5753 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@ce443d0
08-31 16:51:02.372  5567  5753 D BluetoothSocket: channel: 19
08-31 16:51:02.372  5567  5753 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-31 16:51:02.372  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-31 16:51:02.372  1423  1423 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,08-31 16:51:02.382  1423  1423 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-31 16:51:02.382  5567  5755 D BluetoothSocket: bindListen(): myUserId = 0
08-31 16:51:02.382  5567  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.382  5567  5755 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-31 16:51:02.382  5567  5755 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.382  5567  5755 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.382  5567  5755 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@cba6fc9
,08-31 16:51:02.382  5567  5623 D HeadsetStateMachine: Disconnected process message: 9
,08-31 16:51:02.382  5567  5755 D BluetoothSocket: channel: 5
08-31 16:51:02.382  5567  5623 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-31 16:51:02.382  5736  5736 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-31 16:51:02.392   282   686 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.392   282   686 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.392   282   686 V voice   : voice_set_parameters: exit with code(-2)
08-31 16:51:02.392   282   686 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-31 16:51:02.392   282   686 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-31 16:51:02.392   282   686 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-31 16:51:02.392   282   686 V audio_hw_primary: adev_set_parameters: exit
08-31 16:51:02.392  5567  5623 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-31 16:51:02.412  5736  5736 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.412  5736  5736 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-31 16:51:02.442  5736  5736 D FileShare-Client: Outbound.stopDelayTimer - 
,08-31 16:51:02.442  1017  2876 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
08-31 16:51:02.442  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.452  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:02.452  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.452  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:02.462  5760  5760 E Zygote  : MountEmulatedStorage(),
08-31 16:51:02.462  1017  2876 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=5760 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:02.462  5760  5760 E Zygote  : v2
08-31 16:51:02.462  5760  5760 I libpersona: KNOX_SDCARD checking this for 10069,
,08-31 16:51:02.462  5760  5760 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:02.462  5760  5760 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:02.462  5760  5760 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:02.462  1017  2876 I ActivityManager: Killing 5123:com.sec.pcw.device/1000 (adj 15): empty #31
,08-31 16:51:02.472  5760  5760 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:02.482  5760  5760 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:02.482  5760  5760 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:02.502  5760  5760 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-31 16:51:02.512  1017  1692 I ActivityManager: Killing 4461:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31,
,08-31 16:51:02.522  1283  1283 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-31 16:51:02.522  1017  1477 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-31 16:51:02.522  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.522  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.522  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.522  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-31 16:51:02.552  1283  1283 D LocalBluetoothProfileManager: Adding local A2DP profile
,08-31 16:51:02.552  1283  1283 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.552  1017  1477 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-31 16:51:02.552  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.562  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.562  1017  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.562  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.562  1283  1283 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-31 16:51:02.562  1283  1283 E BluetoothHeadset: BTStateChangeCB is registed
,08-31 16:51:02.562  1283  1283 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-31 16:51:02.562  1017  1029 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-31 16:51:02.562  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-31 16:51:02.562  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.562  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.562  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.562  1283  1283 E BluetoothHeadset: BluetoothHeadset service is binded
,08-31 16:51:02.572  1283  1283 D BluetoothMap: Create BluetoothMap proxy object
,08-31 16:51:02.572  1017  1481 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-31 16:51:02.572  1017  1481 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.572  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.572  1017  1481 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.572  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.572  1017  1692 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-31 16:51:02.572  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.572  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.582  1017  1692 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.582  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.582  1283  1283 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap.<init>:179 com.android.settings.bluetooth.SapProfile.<init>:129 
,08-31 16:51:02.582  1017  1689 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-31 16:51:02.582  1017  1689 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.592  1017  1689 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.592  1017  1689 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.592  1017  1689 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.592  1283  1283 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-31 16:51:02.592  1017  1688 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-31 16:51:02.592  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.592  1017  1688 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.592  1017  1688 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.592  1017  1688 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.602  1017  2876 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-31 16:51:02.602  1017  2876 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.602  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.602  1017  2876 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.602  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.602  1283  1283 D LocalBluetoothProfileManager: PANU : true
,08-31 16:51:02.612  1283  1283 W LocalBluetoothProfileManager: Warning: SAP profile was previously added.
08-31 16:51:02.612  1283  1283 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-31 16:51:02.612  1283  1283 D DockEventReceiver: finishStartingService: stopping service
,08-31 16:51:02.612  1283  1283 D BluetoothNotiBroadcastReceiver: onReceive
,08-31 16:51:02.612  1283  1283 D BluetoothA2dp: Proxy object connected
08-31 16:51:02.612  1283  1283 D A2dpProfile: Bluetooth service connected
,08-31 16:51:02.612  1179  1179 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-31 16:51:02.612  1179  1179 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-31 16:51:02.622  1283  1283 D HeadsetProfile: Bluetooth service connected
,08-31 16:51:02.622  5567  5567 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@29c71ee6
,08-31 16:51:02.622  5567  5567 D BtConfig.SecureMode: isSecureModeOn:false
,08-31 16:51:02.632  1017  1689 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-31 16:51:02.632  1017  1689 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.632  1283  1283 D BluetoothMap: Proxy object connected
08-31 16:51:02.632  1017  1689 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.632  1283  1283 D MapProfile: Bluetooth service connected
08-31 16:51:02.632  1283  1283 D BluetoothMap: getConnectedDevices()
,08-31 16:51:02.632  1017  1689 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:02.632  1017  1689 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-31 16:51:02.632  1283  1283 D BluetoothPbap: Proxy object connected
08-31 16:51:02.632  1283  1283 D PbapServerProfile: Bluetooth service connected
08-31 16:51:02.632  1283  1283 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-31 16:51:02.632  1283  1283 D SapProfile: Bluetooth service connected
08-31 16:51:02.632  1283  1283 D Bluetoothsap: getConnectedDevices()
,08-31 16:51:02.632  1283  1283 D BluetoothInputDevice: Proxy object connected
,08-31 16:51:02.632  1283  1283 D HidProfile: Bluetooth service connected
,08-31 16:51:02.642  1283  1283 D BluetoothPan: BluetoothPAN Proxy object connected
,08-31 16:51:02.642  1283  1283 D PanProfile: Bluetooth service connected
,08-31 16:51:02.642  1928  1928 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-31 16:51:02.642  1017  1029 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:02.642  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:02.652  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.652  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:02.652  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.662  1928  5777 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-31 16:51:02.662  1017  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.672  1017  1688 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-31 16:51:02.672  1928  1928 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-31 16:51:02.672  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:02.672  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:02.672  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.692  5567  5781 D BluetoothSocket: bindListen(): myUserId = 0
,08-31 16:51:02.692  5567  5781 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-31 16:51:02.692  5567  5781 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-31 16:51:02.692  5567  5781 D BluetoothSocket: bindListen(), new LocalSocket 
08-31 16:51:02.692  5567  5781 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-31 16:51:02.692  5567  5781 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3b2f260b
,08-31 16:51:02.692  5567  5781 D BluetoothSocket: channel: 12
08-31 16:51:02.692  5567  5781 I BtOppRfcommListener: Accept thread started.
,08-31 16:51:02.692  1017  1252 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:02.702  1017  1252 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:02.702  1017  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:02.702  1017  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:02.702  1928  5777 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-31 16:51:03.392  5624  5624 I wpa_supplicant: nl80211: Received scan results (23 BSSes),
08-31 16:51:03.392  5624  5624 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-31 16:51:03.392  5624  5624 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-31 16:51:03.392  5624  5624 I wpa_supplicant: Trying to associate with  'G700'
08-31 16:51:03.392  5624  5624 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-31 16:51:03.392  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.392  1017  5725 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
08-31 16:51:03.392  1017  1128 I WifiNative-HAL: startHal
,08-31 16:51:03.392  1017  1128 E wifi    : getStaticLongField sWifiHalHandle 0x9ca478ac
08-31 16:51:03.392  1017  1128 I WifiNative-HAL: Could not start hal
,08-31 16:51:03.402  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
,08-31 16:51:03.402  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:03.482   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb75bd7c8
08-31 16:51:03.482   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
08-31 16:51:03.482   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
08-31 16:51:03.482   271   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1218717560)
,08-31 16:51:03.532   271   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504,
08-31 16:51:03.532   271   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-31 16:51:03.532   271   318 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1218717560) wakelock released: 1, error no: 0
,08-31 16:51:03.532   271   318 I rmt_storage: 
,08-31 16:51:03.532   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb75bd7c8
,08-31 16:51:03.562  5624  5624 E wpa_supplicant: Cmd 35605 not handled
08-31 16:51:03.562  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.562  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.562  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.562  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.562  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.562  5624  5624 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-31 16:51:03.562  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
08-31 16:51:03.562  5624  5624 I wpa_supplicant: Associated with F4.99.3E
08-31 16:51:03.562  5624  5624 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e,
08-31 16:51:03.562  5624  5624 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-31 16:51:03.562  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-31 16:51:03.562  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, false
08-31 16:51:03.562  1017  1045 D Tethering: interfaceStatusChanged wlan0, false
08-31 16:51:03.562  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.562  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:51:03.562  1017  1131 E Tethering: No numeric data
08-31 16:51:03.562  1017  1131 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-31 16:51:03.562  1179  1179 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-31 16:51:03.562  1017  1131 D Tethering: clearTetheredNotification()
08-31 16:51:03.562  1179  1179 D HotspotTile: updateTetherState():false, false
08-31 16:51:03.562  1017  1125 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:03.562   277   957 D EnterpriseController: uids 1000
08-31 16:51:03.562   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:03.562   277   957 D Netd    : getNetworkForDns: using netid 0 for uid 1000
08-31 16:51:03.562  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-31 16:51:03.562  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:03.572   277   957 D EnterpriseController: uids 1000
08-31 16:51:03.572   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:03.572   277   957 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-31 16:51:03.572  1017  1125 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.572  1017  1125 V NetworkStats: performPollLocked(flags=0x1)
,08-31 16:51:03.572  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:03.572  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 16:51:03.572  5624  5624 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-31 16:51:03.572  5624  5624 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-31 16:51:03.572  5624  5624 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE,
,08-31 16:51:03.572  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
08-31 16:51:03.572  1017  1125 V NetworkStats: performPollLocked() took 3ms
,08-31 16:51:03.572  5624  5624 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-31 16:51:03.572  1017  1045 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
08-31 16:51:03.572  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.572  5624  5624 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,08-31 16:51:03.572  1017  1128 D SecContentProvider2: mCursor = null
08-31 16:51:03.572  5624  5624 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-31 16:51:03.572  5624  5624 I wpa_supplicant: Blacklist: Clear (temp) 
08-31 16:51:03.572  1017  1045 D Tethering: interfaceLinkStateChanged wlan0, true
,08-31 16:51:03.572  1017  1045 D Tethering: interfaceStatusChanged wlan0, true
08-31 16:51:03.572  5624  5624 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
08-31 16:51:03.572  1017  1126 D NtpTrustedTime: forceRefresh() from cache miss
08-31 16:51:03.572  1017  1126 D NtpTrustedTime: forceRefresh Fail.
,08-31 16:51:03.582  1017  1128 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-31 16:51:03.582  1017  1128 E WifiConfigStore: setLastSelectedConfiguration -1
,08-31 16:51:03.592  1017  1130 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-31 16:51:03.592  1017  1128 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-31 16:51:03.592  1017  1130 E ConnectivityService: updateNetworkInfo()
08-31 16:51:03.592  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-31 16:51:03.592  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:03.592  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:03.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.592  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.592  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:51:03.602  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:03.602  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:03.602  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:03.602  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:03.602  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:03.602  3411  3411 I Hs20UtilService: Starting #4
,08-31 16:51:03.602  3411  3444 I Hs20UtilService: Message received 5007
,08-31 16:51:03.612  1017  1128 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-31 16:51:03.612  1283  1283 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:03.612  1283  1283 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:03.612  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-31 16:51:03.612  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,08-31 16:51:03.622  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false,
,08-31 16:51:03.622  1283  1283 I NearbySettings: MountReceiver.onReceive - Set preference state off,
08-31 16:51:03.622  1283  2912 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-31 16:51:03.622   277   961 D CommandListener: Setting iface cfg
08-31 16:51:03.622  1017  1128 E WifiStateMachine: Start Dhcp Watchdog 1
08-31 16:51:03.632  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.632  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:03.642  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:03.642  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:03.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:03.642  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:03.642  1017  1128 E WifiNative-wlan0: do suspend false
,08-31 16:51:03.642  1017  1127 D WifiP2pService: InactiveState{ what=143375 },
08-31 16:51:03.642  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:51:03.642  1017  1128 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-31 16:51:03.642  1017  1128 D SecContentProvider2: mCursor = null
,08-31 16:51:03.862  5788  5788 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-31 16:51:03.862  5788  5788 I dhcpcd  : version 5.5.6 starting,
08-31 16:51:03.862  5788  5788 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-31 16:51:03.912  5788  5788 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
08-31 16:51:03.912  5788  5788 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-31 16:51:03.912  5788  5788 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-31 16:51:03.912  5788  5788 I dhcpcd  : bssid match,
,08-31 16:51:03.922  5788  5788 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
,08-31 16:51:03.972  5788  5788 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-31 16:51:04.022  5788  5788 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-31 16:51:04.252  1017  1128 E WifiNative-wlan0: do suspend true,
,08-31 16:51:04.282  1017  1127 D WifiP2pService: InactiveState{ what=143375 },
08-31 16:51:04.282  1017  1127 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-31 16:51:04.282  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 16:51:04.282  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:04.282  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
08-31 16:51:04.282  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.282  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.282  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.292  1017  1128 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-31 16:51:04.292  1017  1128 E WifiStateMachine: VerifyingLinkState enter
,08-31 16:51:04.292  1017  1128 D WifiNative-wlan0: callSECApiInt - ID [210]
,08-31 16:51:04.292  1017  1130 E ConnectivityService: updateNetworkInfo()
,08-31 16:51:04.292  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,08-31 16:51:04.302  1017  1130 D ConnectivityService: Adding iface wlan0 to network 502
,08-31 16:51:04.302  1017  1145 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-31 16:51:04.302  1017  1145 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:51:04.302  1017  1145 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.302  1017  1145 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-31 16:51:04.302  1017  1145 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:51:04.312  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-31 16:51:04.312  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-31 16:51:04.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.312  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.312  1017  1491 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.312  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.322  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:04.322  1017  1491 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:04.322  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.322  3411  3411 I Hs20UtilService: Starting #5
,08-31 16:51:04.322  1017  1128 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-31 16:51:04.322  3411  3444 I Hs20UtilService: Message received 5007
,08-31 16:51:04.322  1283  1283 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.322  1283  1283 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.332  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-31 16:51:04.332  1017  1128 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-31 16:51:04.332  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-31 16:51:04.332  1017  1130 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 502
,08-31 16:51:04.342  1017  1130 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 502
,08-31 16:51:04.342  1017  1130 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 502,
,08-31 16:51:04.342  1017  1130 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-31 16:51:04.342  1017  1130 D ConnectivityService: Setting Dns servers for network 502 to [/192.168.1.1]
08-31 16:51:04.342  1179  1179 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x0/(null) mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.342  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-31 16:51:04.342  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.342  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.342  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.342  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.342  1017  1130 D ConnectivityService: LTETest block dns file not exists
,08-31 16:51:04.342  1017  1017 I WifiTrafficPoller: evaluateTrafficStatsPolling,
08-31 16:51:04.342  1017  1017 I WifiTrafficPoller: mBoosterFLAG : 0
,08-31 16:51:04.342  1017  1017 I WifiTrafficPoller: current booster mode : FullMode
,08-31 16:51:04.342  1017  1017 D WifiNative-wlan0: callSECApiVoid - ID [212]
,08-31 16:51:04.352  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.352  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 16:51:04.352  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.362  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.362  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.362  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.362  1017  1130 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.362  1017  1130 E ConnectivityService: updateNetworkInfo()
08-31 16:51:04.362  1017  1130 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-31 16:51:04.362  1017  1130 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 502]
08-31 16:51:04.362  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.362  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-31 16:51:04.362  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
,08-31 16:51:04.362  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-31 16:51:04.362  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,08-31 16:51:04.362  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.372  1017  1130 D ConnectivityService:    accepting network in place of null
,08-31 16:51:04.372  1017  1130 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,4525824,524288,1048576,4525824
,08-31 16:51:04.372  1017  1127 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-31 16:51:04.372  1445  1445 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-31 16:51:04.372  1445  1445 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-31 16:51:04.382  1017  1128 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-31 16:51:04.382  1017  5785 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 16:51:04.382  1017  5785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:51:04.382  1017  5785 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:04.382  1017  5785 I System.out: (HTTPLog)-Thread-175-373707727: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:04.382  1017  5785 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:04.382  1017  2875 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-31 16:51:04.382  1017  1130 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-31 16:51:04.382  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.382  1017  1130 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=true
08-31 16:51:04.382   277   957 D EnterpriseController: uids 1000
08-31 16:51:04.382   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:04.382   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,08-31 16:51:04.382  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-31 16:51:04.392  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:04.392  1017  2875 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:04.392  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.392  3411  3411 I Hs20UtilService: Starting #6
,08-31 16:51:04.392  1017  1130 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-31 16:51:04.392  1017  1017 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-31 16:51:04.392  1017  1131 D Tethering: MasterInitialState.processMessage what=3
,08-31 16:51:04.392  3411  3444 I Hs20UtilService: Message received 5007
,08-31 16:51:04.392  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.392  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:04.392  1017  1125 V NetworkStats: updateIfacesLocked()
08-31 16:51:04.392  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-31 16:51:04.392  1017  1125 V NetworkStats: performPollLocked(flags=0x1),
08-31 16:51:04.392  1017  1126 D NtpTrustedTime: forceRefresh() from cache miss,
08-31 16:51:04.392  1017  1047 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-31 16:51:04.392   277   957 D EnterpriseController: uids 1000
,08-31 16:51:04.392   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
,08-31 16:51:04.392   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 1000
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-31 16:51:04.402  1017  1125 V NetworkStats: performPollLocked() took 11ms
,08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-31 16:51:04.402  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-31 16:51:04.402  1179  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:04.402  3762  5549 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-31 16:51:04.402  1283  1283 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.402  1283  1283 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-31 16:51:04.402  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.402  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.412  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-31 16:51:04.412  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
08-31 16:51:04.412  1283  1283 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-31 16:51:04.412  1283  1283 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.422  1017  1468 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-31 16:51:04.422  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-31 16:51:04.422  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:04.422  1017  1468 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:04.422  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-31 16:51:04.422  3411  3411 I Hs20UtilService: Starting #7
,08-31 16:51:04.422  1283  1283 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-31 16:51:04.422  1283  1283 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-31 16:51:04.422  3411  3444 I Hs20UtilService: Message received 5007
,08-31 16:51:04.432  1017  1029 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-31 16:51:04.442  1017  1252 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,08-31 16:51:04.442  1017  1252 D SecContentProvider2: mCursor = null
,08-31 16:51:04.442  1017  2875 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-31 16:51:04.442  1017  2875 D SecContentProvider2: mCursor = null
,08-31 16:51:04.442  1017  1688 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,08-31 16:51:04.442  1017  1688 D SecContentProvider2: mCursor = null
,08-31 16:51:04.452  1017  1468 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 16:51:04.452  1017  1468 D SecContentProvider2: mCursor = null
,08-31 16:51:04.452  1017  1481 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-31 16:51:04.452  1017  1481 D SecContentProvider2: mCursor = null
,08-31 16:51:04.452  1017  1689 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-31 16:51:04.452  1017  1689 D SecContentProvider2: mCursor = null
,08-31 16:51:04.462  1017  2627 D SSRM:n  : SIOP:: AP = 340
,08-31 16:51:04.482   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-31 16:51:04.492  1017  1252 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-31 16:51:04.502  1179  1179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:51:04.542  5487  5540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 16:51:04.542  5487  5540 I jxcore-log: 
,08-31 16:51:04.692  1017  5785 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:04.692  1017  1126 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1472655064467 mCachedNtpElapsedRealtime : 133464 mCachedNtpCertainty : 15
,08-31 16:51:04.692  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:04.692  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:04.692  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:04.692  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:04.692  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:04.692  1017  1126 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-31 16:51:04.702  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:04.762  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 31 Aug 2016 14:51:04 GMT], X-Android-Received-Millis=[1472655064771], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472655064738]}
,08-31 16:51:04.762  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-31 16:51:04.762  1017  5785 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-31 16:51:04.762  1017  1130 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.762  1017  1130 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.762  1017  1130 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 502] was already satisfying request 1. No change.
,08-31 16:51:04.762  1017  1130 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:04.762  1179  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.772  3762  5549 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-31 16:51:04.772  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: EthernetConnected: false
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: updateDataNetType()
08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-31 16:51:04.772  1179  1179 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-31 16:51:04.772  1179  1179 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-31 16:51:04.782  1179  1179 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-31 16:51:04.782  1179  1179 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-31 16:51:04.782  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.782  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.782  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-31 16:51:04.782  1179  1179 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-31 16:51:04.892  1017  1130 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-31 16:51:04.902  1017  1389 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:04.902  1017  1389 D AlarmManagerService: Setting time of day to sec=1472655064
08-31 16:51:04.902  1017  1389 D AlarmManagerService: Trying to open a file
,08-31 16:51:04.902  1017  1389 D AlarmManagerService: File Open Success
08-31 16:51:04.902  1017  1389 D AlarmManagerService: File Close Success
08-31 16:51:04.902  1017  1389 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,08-31 16:51:04.674  1017  1389 W AlarmManagerService: Unable to set rtc to 1472655064: Invalid argument
08-31 16:51:04.674  1017  1096 V AlarmManager: waitForAlarm result :65536
,08-31 16:51:04.674  2969  2969 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-31 16:51:04.674  2969  2969 I DBG_DM  : [com.wssyncmldm.llllIIIllIlIIIIllllI(230/onReceive)] ----------- XEVENT_DM_INIT WIFI ok
,08-31 16:51:04.674  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-31 16:51:04.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:04.683  2969  3011 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
,08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 16:51:04.683  5487  5487 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 16:51:04.683  5487  5487 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 16:51:04.693  5825  5825 E Zygote  : MountEmulatedStorage()
08-31 16:51:04.693  5825  5825 E Zygote  : v2
08-31 16:51:04.693  5825  5825 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:04.693  5825  5825 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:04.693  5825  5825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:04.693  1017  1043 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=5825 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-31 16:51:04.693  5825  5825 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:04.693  5825  5825 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:04.703  1017  1096 V AlarmManager: No more alarm at this time.nowELAPSED=133714 batch.start=167296
,08-31 16:51:04.713  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1472655064727
,08-31 16:51:04.723  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-31 16:51:04.723  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
,08-31 16:51:04.723  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-31 16:51:04.723  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,08-31 16:51:04.723  2969  3011 I DBG_DM  : [IlIlllIlllllIlIllllI(403/llIIllllIIlllIIIIlll)] Check completed.
,08-31 16:51:04.723  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,08-31 16:51:04.733  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
,08-31 16:51:04.733  5825  5825 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:04.733  5825  5825 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:04.733  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:04.733  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,08-31 16:51:04.743  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-31 16:51:04.743  2969  3011 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-31 16:51:04.743  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
08-31 16:51:04.743  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.743  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:04.753  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:04.753  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-31 16:51:04.763  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:04.763  1017  1689 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-31 16:51:04.763  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
08-31 16:51:04.763  1017  1689 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:04.763  1017  1689 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:04.763  1017  1689 D SettingsProvider: selectionArgs: false
08-31 16:51:04.763  1017  1689 D SettingsProvider: selectionArgs: 10054
08-31 16:51:04.763  1017  1689 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:04.763  1017  1689 D SettingsProvider: ret = -1
,08-31 16:51:04.763  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.763  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.763  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.763  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.763  1017  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:04.763   281   281 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1472655064 after conversion: 1472655064
08-31 16:51:04.763   281   281 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1472655064 after conversion: 1472655064
,08-31 16:51:04.773  1017  1689 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,08-31 16:51:04.783  5844  5844 E Zygote  : MountEmulatedStorage(),
08-31 16:51:04.783  5844  5844 E Zygote  : v2
08-31 16:51:04.783  5844  5844 I libpersona: KNOX_SDCARD checking this for 10044
08-31 16:51:04.783  5844  5844 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:04.783  5844  5844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-31 16:51:04.783  1179  1179 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,08-31 16:51:04.783  5844  5844 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:04.783  5844  5844 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:04.783  1017  1042 I ActivityManager: Start proc com.sec.android.gallery3d for service com.sec.android.gallery3d/.remote.picasa.PicasaService: pid=5844 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-31 16:51:04.793  1928  1928 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-31 16:51:04.793  1179  1179 D KeyguardEffectViewController: isPreloadedWallpaper=true
,08-31 16:51:04.793  1179  1179 I GeometricMosaic_Keyguard: update
,08-31 16:51:04.793  1179  1179 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,08-31 16:51:04.803  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:04.803  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.metadata.ContactMetadataSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.813  5844  5844 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:04.813  5844  5844 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:04.833  1017  1252 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:04.833  1017  1252 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.843  1017  1252 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:04.843  1017  1252 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:04.843  1017  1252 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 16:51:04.843  5844  5844 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-31 16:51:04.853  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:04.853  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.873  1179  1179 I KeyguardEffectViewUtil: set current wallpaper info
,08-31 16:51:04.873  1017  1477 D SettingsProvider: name = keyguard_current_wallpaper_type
08-31 16:51:04.873  1017  1477 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:04.873  1017  1477 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:04.873  1017  1477 D SettingsProvider: selectionArgs: false
08-31 16:51:04.873  1017  1477 D SettingsProvider: selectionArgs: 10054
08-31 16:51:04.873  1017  1477 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:04.873  1017  1477 D SettingsProvider: ret = -1
,08-31 16:51:04.873  1017  1252 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-31 16:51:04.873  1017  1252 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:04.873  1017  1252 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-31 16:51:04.873  1017  1252 D SettingsProvider: selectionArgs: false
08-31 16:51:04.873  1017  1252 D SettingsProvider: selectionArgs: 10054
08-31 16:51:04.873  1017  1252 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-31 16:51:04.873  1017  1252 D SettingsProvider: ret = -1
,08-31 16:51:04.873  1017  1689 D SettingsProvider: name = keyguard_current_wallpaper_res_id
,08-31 16:51:04.873  1017  1689 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-31 16:51:04.873  5825  5825 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-31 16:51:04.873  5825  5825 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-31 16:51:04.873  5825  5825 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-31 16:51:04.873  1017  1689 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-31 16:51:04.873  1017  1689 D SettingsProvider: selectionArgs: false
08-31 16:51:04.873  1017  1689 D SettingsProvider: selectionArgs: 10054
,08-31 16:51:04.873  1017  1689 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-31 16:51:04.873  1017  1689 D SettingsProvider: ret = -1
,08-31 16:51:04.923  2969  3011 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,08-31 16:51:04.933  2969  3011 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,08-31 16:51:04.943  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
08-31 16:51:04.943  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,08-31 16:51:04.973  2969  3011 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,08-31 16:51:04.983  1179  1617 D TEST    : run!!!,
,08-31 16:51:04.993  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:05.013  1179  1179 D KeyguardEffectViewController: isPreloadedWallpaper=true,
,08-31 16:51:05.013  1017  1042 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-31 16:51:05.013  1179  1617 I GeometricMosaic_Renderer: setBackgroundBitmap
,08-31 16:51:05.033   287   287 E SMD     : DCD OFF
,08-31 16:51:05.053  2969  3011 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-31 16:51:05.063  2969  3011 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 1
,08-31 16:51:05.063  2969  3011 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,08-31 16:51:05.073  2969  3011 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,08-31 16:51:05.073  2969  3012 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
08-31 16:51:05.073  2969  3011 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,08-31 16:51:05.073  2969  3011 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,08-31 16:51:05.083  2969  3012 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,08-31 16:51:05.083  2969  3011 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,08-31 16:51:05.083  2969  3011 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,08-31 16:51:05.093  2969  3012 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:985416429
,08-31 16:51:05.093  5487  5540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 16:51:05.093  5487  5540 I jxcore-log: 
,08-31 16:51:05.093  2969  3012 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,08-31 16:51:05.103  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,08-31 16:51:05.113  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,08-31 16:51:05.123  1017  2876 I art     : Explicit concurrent mark sweep GC freed 62576(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.797ms total 191.935ms
,08-31 16:51:05.123  3762  5865 E ActivityThread: Failed to find provider info for com.android.contacts.metadata
,08-31 16:51:05.133  1017  1042 E GpsLocationProvider: No APN found to select.
,08-31 16:51:05.133  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,08-31 16:51:05.133  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 1016996214
,08-31 16:51:05.143  5487  5540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 16:51:05.143  5487  5540 I jxcore-log: 
,08-31 16:51:05.143  2969  2969 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,08-31 16:51:05.143  5844  5844 D NearbySource: Nearby Source Create!
,08-31 16:51:05.143  5844  5844 D NearbyContext: Nearby Context Create!
,08-31 16:51:05.153  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:05.153  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.163  5825  5825 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-31 16:51:05.163  5825  5825 I PCWCLIENTTRACE_PushUtil: sales region : global
08-31 16:51:05.163  5825  5825 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-31 16:51:05.163  5825  5825 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:05.163  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.163  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.163  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.173  1017  1468 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
08-31 16:51:05.173  2969  2969 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,08-31 16:51:05.173  1017  1468 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-31 16:51:05.173  2969  2969 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,08-31 16:51:05.173  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-31 16:51:05.173  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.173  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.173  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.173  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.183  2969  2969 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,08-31 16:51:05.183  2969  2969 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
08-31 16:51:05.183  2969  2969 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
08-31 16:51:05.183  2969  2969 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@200b4f01
,08-31 16:51:05.193  2969  3012 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,08-31 16:51:05.193  5871  5871 E Zygote  : MountEmulatedStorage(),
,08-31 16:51:05.193  5871  5871 E Zygote  : v2
,08-31 16:51:05.193  5871  5871 I libpersona: KNOX_SDCARD checking this for 10009
08-31 16:51:05.193  5871  5871 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.193  5871  5871 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
08-31 16:51:05.193  1017  1043 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=5871 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
08-31 16:51:05.193   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-31 16:51:05.193  5871  5871 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:05.193   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
08-31 16:51:05.203  5871  5871 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-31 16:51:05.203  5844  5844 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-31 16:51:05.203  5844  5844 D SLinkSource: Samsung link source created
08-31 16:51:05.203  1720  1720 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-31 16:51:05.213  1017  1468 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
08-31 16:51:05.213  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.213  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.213  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.213  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.223  2969  3012 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-31 16:51:05.233  5881  5881 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.233  5881  5881 I libpersona: KNOX_SDCARD checking this for 10111
08-31 16:51:05.233  5881  5881 E Zygote  : v2
08-31 16:51:05.233  5881  5881 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.233  1017  1468 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=5881 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.233  5881  5881 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:05.243  1017  1491 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator,
08-31 16:51:05.243  1017  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.243  5881  5881 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:05.243  1017  2875 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:05.243  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.253  5881  5881 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.253  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.253  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.253  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:05.253  5871  5871 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:05.253  5871  5871 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.263  1720  1720 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,08-31 16:51:05.263  1720  1720 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,08-31 16:51:05.263  1720  1720 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,08-31 16:51:05.263  1720  1720 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:05.263  1017  1689 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:05.263  1017  1042 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 24426, reason: UserStart, SyncResult: databaseError: true stats []
,08-31 16:51:05.283  1017  1689 D RCPManagerService: exchangeData() failure , invalid userId
,08-31 16:51:05.283  1017  1042 D SyncManager: not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 164396, reason: UserStart
,08-31 16:51:05.283  5881  5881 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.283  5881  5881 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.283  2969  3012 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,08-31 16:51:05.303  2969  3012 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,08-31 16:51:05.303  1720  1720 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-31 16:51:05.313  2969  3012 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,08-31 16:51:05.313  1720  1720 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-31 16:51:05.313  1309  1320 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,08-31 16:51:05.323  1017  1688 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:05.323  1017  1477 D SettingsProvider: name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,08-31 16:51:05.323  5844  5897 D ContactProvider: getAllContactInfoList Start
,08-31 16:51:05.333  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-31 16:51:05.333  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.333  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.333  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.333  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.333  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-31 16:51:05.343  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:05.343  5705  5705 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:51:05.343  5904  5904 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.343  5904  5904 E Zygote  : v2
,08-31 16:51:05.353  5904  5904 I libpersona: KNOX_SDCARD checking this for 10081
08-31 16:51:05.353  5904  5904 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.353  5705  5705 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-31 16:51:05.353  5904  5904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:05.353  1017  1030 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=5904 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.353  2969  3012 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-31 16:51:05.353  5904  5904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:05.363  5904  5904 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.363  1720  1720 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-31 16:51:05.363  1017  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-31 16:51:05.363  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,08-31 16:51:05.363  1017  1477 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:05.373  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.373  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.373  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.373  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.383  3762  5893 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-31 16:51:05.383  3762  5893 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-31 16:51:05.383  1017  1030 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=5919 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:05.383  5919  5919 E Zygote  : MountEmulatedStorage(),
08-31 16:51:05.383  5919  5919 E Zygote  : v2
08-31 16:51:05.393  5919  5919 I libpersona: KNOX_SDCARD checking this for 10159
08-31 16:51:05.393  5919  5919 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:05.393  5919  5919 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:05.393  5919  5919 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:05.393  5919  5919 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.403  5904  5904 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.403  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
08-31 16:51:05.403  5904  5904 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.433  5919  5919 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.433  5919  5919 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.453  1017  1689 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 16:51:05.453  1017  1689 D SecContentProvider2: mCursor = null
,08-31 16:51:05.473  1017  2875 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-31 16:51:05.473  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.483  1017  1252 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-31 16:51:05.483  1017  1252 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-31 16:51:05.493  1928  1928 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:05.493  1017  1017 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,08-31 16:51:05.493  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,08-31 16:51:05.493  1179  2248 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:05.533  1017  2875 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-31 16:51:05.533  1017  2875 D SecContentProvider2: mCursor = null
,08-31 16:51:05.533  5844  5897 D ContactProvider: getAllContactInfoList End
,08-31 16:51:05.533  5844  5897 I syncContacts: thread: 973, sync time = 263
,08-31 16:51:05.543  2969  3012 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,08-31 16:51:05.553  1017  1029 I ActivityManager: Killing 5141:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-31 16:51:05.553  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,08-31 16:51:05.553  5871  5871 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 16:51:05.563  1017  1252 D SecContentProvider2: uri = 15 selection = getToastGravity
,08-31 16:51:05.563  1017  1252 D SecContentProvider2: mCursor = null
,08-31 16:51:05.563  5871  5871 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,08-31 16:51:05.563  5871  5871 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,08-31 16:51:05.583  1017  1491 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-31 16:51:05.583  1017  1491 D SecContentProvider2: mCursor = null
,08-31 16:51:05.583  5871  5871 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,08-31 16:51:05.593  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-31 16:51:05.593  1017  1030 D SecContentProvider2: mCursor = null
,08-31 16:51:05.593  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.sec.android.gallery3d, action: android.content.SyncAdapter
08-31 16:51:05.593  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.gallery3d/com.sec.android.gallery3d.remote.picasa.PicasaService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.593  3445  3445 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Aug 31 16:51:05 GMT+02:00 2016
,08-31 16:51:05.603  1017  2875 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-31 16:51:05.603  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.613  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.613  1017  2875 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:05.613  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:05.613  1017  1689 I ActivityManager: Killing 4839:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-31 16:51:05.613  3445  3445 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:05.623  2969  3012 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,08-31 16:51:05.623  1017  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-31 16:51:05.633  5881  5881 I MusicStore: Database version: 108
,08-31 16:51:05.633  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.633  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:05.633  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.633  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:05.643  1179  1179 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,08-31 16:51:05.643  3445  3445 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 16:51:05.653  1017  1688 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,08-31 16:51:05.653  1017  1688 D SecContentProvider2: mCursor = null
08-31 16:51:05.653  5945  5945 E Zygote  : MountEmulatedStorage()
08-31 16:51:05.653  5945  5945 I libpersona: KNOX_SDCARD checking this for 10034
08-31 16:51:05.653  5945  5945 E Zygote  : v2
08-31 16:51:05.653  5945  5945 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:05.653  1179  1179 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,08-31 16:51:05.653  5945  5945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:05.653  3445  3445 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:51:05.663  5945  5945 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:05.663  5945  5945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:05.663  1017  1477 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState,
08-31 16:51:05.663  1017  1477 D SecContentProvider2: mCursor = null
,08-31 16:51:05.663  3762  5864 E Auth.Api.Credentials: [CredentialSyncAdapter] Unknown sync event.
08-31 16:51:05.663  3445  3445 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:51:05.673  1179  1179 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
08-31 16:51:05.673  1017  1029 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=5945 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-31 16:51:05.673  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:51:05.673  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:05.673  1179  1179 D PanelView: There is/are notification(s) 
08-31 16:51:05.673  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 16:51:05.673  1179  1179 D PersonaManager: isKioskContainerExistOnDevice
08-31 16:51:05.673  1179  1179 D PanelView: There is/are notification(s) 
08-31 16:51:05.673  1179  1179 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-31 16:51:05.683   305   305 I art     : Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 23.705ms
,08-31 16:51:05.683  1017  2875 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-31 16:51:05.683  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.683  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:05.683  1017  2875 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:05.683  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,08-31 16:51:05.693  2969  3012 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,08-31 16:51:05.693  2969  3012 I DBG_DM  : [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,08-31 16:51:05.693  5945  5945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:05.693  5945  5945 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:05.703   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 16.966ms
,08-31 16:51:05.723   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 711us total 17.143ms
,08-31 16:51:05.723  1017  1689 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:05.723  1017  1689 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.723  1017  1689 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.723  1017  1689 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.723  1017  1689 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:05.743  3762  5964 I iu.SyncManager: SYNC; picasa accounts
,08-31 16:51:05.743  1179  1179 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-31 16:51:05.753  3762  3762 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,08-31 16:51:05.753   277   957 D EnterpriseController: uids 10012
08-31 16:51:05.753   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:05.753   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 16:51:05.753  3762  3762 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-31 16:51:05.763  3762  5964 I iu.UploadsManager: num queued entries: 0
,08-31 16:51:05.763  3762  5964 I iu.UploadsManager: num updated entries: 0
,08-31 16:51:05.763  3762  5964 I iu.SyncManager: NEXT; no task
,08-31 16:51:05.773  1017  1688 I ActivityManager: Killing 5156:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-31 16:51:05.803  3445  5942 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-31 16:51:05.803  3445  5942 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,08-31 16:51:05.813  1017  2876 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 16:51:05.813  1017  2876 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 16:51:05.813  3445  5942 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,08-31 16:51:05.813  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:05.813  1017  2876 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.813  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:05.813  2936  5968 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:05.823  3445  5942 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,08-31 16:51:05.823  3445  5942 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,08-31 16:51:05.833  2936  5968 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-31 16:51:05.833  2936  5968 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-31 16:51:05.833  2936  5968 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(259/xdmNotInitSetResume)] DM Not Init
,08-31 16:51:05.833  2936  5968 I DBG_POLICYDM: [com.policydm.XDMService(300/xdmInitializing)] ----------- XEVENT_DM_INIT WIFI ok
,08-31 16:51:05.833  2936  3024 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(33/xuiAdpGetUiMode)] nDmUiMode : 0
,08-31 16:51:05.843  2936  3024 I DBG_POLICYDM: [com.policydm.agent.XDMTask(200/xdmAgentTaskHandler)] XEVENT_DM_INIT
,08-31 16:51:05.853  2936  3024 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:05.853  3445  5942 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,08-31 16:51:05.863  3445  5942 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-31 16:51:05.863  3445  3445 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 16:51:05.873  5301  5301 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-31 16:51:05.883  2936  3024 I DBG_POLICYDM: [com.policydm.XDMService(661/xdmGetNotibarState)] get NotibarState : 7
,08-31 16:51:05.883  2936  3024 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,08-31 16:51:05.893  2936  3024 I DBG_POLICYDM: [com.policydm.XDMService(653/xdmSetNotibarState)] set NotibarState : 7
,08-31 16:51:05.893  3868  3868 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-31 16:51:05.903  5356  5356 I SA      : [DM] init START
,08-31 16:51:05.923  5356  5356 I SA      : [DM] This device is not a Vodafone
,08-31 16:51:05.933  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-31 16:51:05.933  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.933  1017  1140 W ActivityManager: userId = 0, bbcId = -10000,
08-31 16:51:05.933  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:05.933  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75),
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75),
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75),
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-31 16:51:05.933  5356  5356 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-31 16:51:05.943  5356  5356 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-31 16:51:05.943  5356  5356 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-31 16:51:05.943  5356  5356 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-31 16:51:05.943  1928  5965 I qtaguid : Tagging socket 50 with tag 1000040700000000{268436487,0} for uid -1, pid: 1928, getuid(): 10012
,08-31 16:51:05.943  5356  5356 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-31 16:51:05.943  5356  5356 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-31 16:51:05.953  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(234/xdbGetCryptionkey)] try read dbString
08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,08-31 16:51:05.953  5356  5356 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-31 16:51:05.963  5356  5356 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-31 16:51:05.963  5881  5881 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-31 16:51:05.963  5881  5881 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 16:51:05.963  5356  5356 I SA      : [SCU] isHaveSA() - false
08-31 16:51:05.963  5356  5356 I SA      : support phone number id : false
,08-31 16:51:05.963  5356  5356 I SA      : [DM] Supports Ref Jpn : true
,08-31 16:51:05.963  5356  5356 I SA      : [DM] init END
08-31 16:51:05.973  5356  5356 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-31 16:51:05.973  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(442/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,08-31 16:51:05.973  5356  5356 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,08-31 16:51:05.983  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
,08-31 16:51:05.983  5356  5356 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-31 16:51:05.983  5356  5356 I SA      : [SLFUCHKMGR] constructor called
,08-31 16:51:05.983  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,08-31 16:51:05.993  5356  5356 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:51:05.993  5356  5356 I SA      : [OR] == isSIMCardReady false ==
,08-31 16:51:06.003  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(574/xdbGetFUMOInitiatedType)] Initiated Type: 0,
,08-31 16:51:06.003  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(78/xpollingCheckVersionInfo)] 
,08-31 16:51:06.003  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(277/xpollingCheckTimer)] 
,08-31 16:51:06.013  2936  3025 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(216/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,08-31 16:51:06.013  5356  5356 I SA      : [SCU] == networkStateCheck == true
,08-31 16:51:06.013  5356  5356 I SA      : [DM] getCountryCodeFromCSC : PL
,08-31 16:51:06.013  5356  5356 I SA      : isChinaCountryCode : false
,08-31 16:51:06.023  2936  3025 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:06.023  5356  5356 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-31 16:51:06.023  5356  5356 I SA      : [OR] == networkStateCheck true ==
,08-31 16:51:06.033  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(291/xpollingCheckTimer)] savedpollingtime : 2016/09/01/05:27:44
,08-31 16:51:06.043  1017  1140 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-31 16:51:06.043  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.043  5844  5974 D PicasaService: start picasa sync
,08-31 16:51:06.043  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.043  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.043  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:06.043  5356  5356 I SA      : [OR] GetMyCountryZoneTask
,08-31 16:51:06.043  5356  5356 I SA      : [OR] onReceive END
,08-31 16:51:06.053  5844  5974 D PicasaService: end picasa sync
,08-31 16:51:06.053  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.053  1017  1692 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-31 16:51:06.053  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.053  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.053  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.053  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.063  5881  5881 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:51:06.073  5983  5983 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.073  5983  5983 E Zygote  : v2
08-31 16:51:06.073  5983  5983 I libpersona: KNOX_SDCARD checking this for 10104
08-31 16:51:06.073  5983  5983 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:06.073  5983  5983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:06.073  5983  5983 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:06.073  1017  1692 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=5983 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-31 16:51:06.073  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(292/xpollingCheckTimer)] currentTime : 2016/08/31/16:51:06
08-31 16:51:06.083  5983  5983 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.093  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:06.093  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(296/xpollingCheckTimer)] Restart Timer..
08-31 16:51:06.093  2936  3024 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 0
,08-31 16:51:06.113  2936  3024 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(318/xPollingReportReStartAlarm)] 
,08-31 16:51:06.143  2936  3025 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(306/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,08-31 16:51:06.143  2936  3025 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(307/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,08-31 16:51:06.143  2936  3025 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(308/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,08-31 16:51:06.143  2936  3025 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(348/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,08-31 16:51:06.143  2936  3025 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(175/xnotiPushAdpClearSessionStatus)] 
,08-31 16:51:06.163  5881  5881 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:51:06.163  5881  5881 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@15f0c1da: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 16:51:06.163  5881  5881 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-31 16:51:06.163  5881  5881 D AndroidMusic: GMSCore installation verified
,08-31 16:51:06.173  2936  3025 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,08-31 16:51:06.173  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(453/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,08-31 16:51:06.173  5356  5981 I SA      : [SRS] prepareGetMyCountryZone
,08-31 16:51:06.183  5983  5983 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.183  5983  5983 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.193  1017  1130 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-31 16:51:06.193  5356  5981 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,08-31 16:51:06.193  5356  5981 I SA      : [SSP] query invoked
,08-31 16:51:06.193  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:06.193  1017  1130 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 502]
,08-31 16:51:06.193  3762  5549 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:06.203  1179  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:06.203  1179  1681 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-31 16:51:06.203  3762  5549 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-31 16:51:06.203  1017  1029 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-31 16:51:06.203  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.203  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(552/xdbSetFUMOInitiatedType)] Initiated Type: 0
,08-31 16:51:06.213  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.213  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:06.213  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,08-31 16:51:06.253  2936  3024 I DBG_POLICYDM: [com.policydm.XDMService(668/xdmStartAlarm)] Alarm ID: 1
,08-31 16:51:06.263  1017  1688 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 16:51:06.263  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-31 16:51:06.263  1017  1688 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.263  1017  1688 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.263  1017  1688 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:06.273  5356  5981 I SA      : [TPMU] GetMccFromDB : null
08-31 16:51:06.273  5356  5981 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 16:51:06.273  5356  5981 I SA      : [LBE] isSupportCheckDomainRegion : false
08-31 16:51:06.273  5356  5981 I SA      : [TPM] isNoProxy(default) : true
,08-31 16:51:06.273  5983  5983 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-31 16:51:06.273  1017  2875 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,08-31 16:51:06.273  1017  2875 D SecContentProvider2: mCursor = null
,08-31 16:51:06.293  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDB(1781/xdbSetBackUpServerUrl)] 
,08-31 16:51:06.293  5881  5881 I ConfigStore: Config Database version: 1
,08-31 16:51:06.303  2936  3024 I DBG_POLICYDM: [com.policydm.agent.XDMTask(225/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,08-31 16:51:06.333  1017  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:06.333  1017  1491 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.333  1017  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.333  1017  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:06.343  1017  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter,
,08-31 16:51:06.343  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.metadata.sync.syncadapter.SyncAdapterService; callingUser = 0; userId(target) = 0,
,08-31 16:51:06.403  5356  5981 E File    : fail readDirectory() errno=2
,08-31 16:51:06.423  1017  2875 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:06.423  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.423  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.423  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:06.453   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 16:51:06.453   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:06.453  5881  5881 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 16:51:06.483   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 16:51:06.483   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:06.493  1017  1481 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:06.493  1017  1481 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.493  1017  1481 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.493  1017  1481 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:06.493  5881  5881 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
08-31 16:51:06.493  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.493  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.493  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:06.493  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:06.503   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-31 16:51:06.503   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:06.503  5881  5881 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-31 16:51:06.513  6007  6007 E Zygote  : MountEmulatedStorage()
08-31 16:51:06.513  6007  6007 E Zygote  : v2
08-31 16:51:06.513  6007  6007 I libpersona: KNOX_SDCARD checking this for 10012
08-31 16:51:06.513  6007  6007 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:06.513  6007  6007 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:06.513  6007  6007 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:06.513  6007  6007 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:06.533  1017  1481 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6007 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,08-31 16:51:06.533  1017  1477 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-31 16:51:06.533  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.543  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.543  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.543  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:06.553  6007  6007 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:06.553  6007  6007 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:06.553  1017  1030 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
08-31 16:51:06.553  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.553  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.553  1017  1030 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
08-31 16:51:06.553  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,08-31 16:51:06.583  6007  6007 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-31 16:51:06.583  6007  6007 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-31 16:51:06.583  5301  5301 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-31 16:51:06.583  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,08-31 16:51:06.613  5301  5301 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: exit::IDLE
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-31 16:51:06.623  1017  1468 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-31 16:51:06.623  5301  5301 D InitializeManagerStateMachine: entry::SUCCESS
08-31 16:51:06.623  5301  5301 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-31 16:51:06.623  1017  1468 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-31 16:51:06.623  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.623  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.623  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:06.633  5301  5301 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,08-31 16:51:06.643  6007  6007 I MultiDex: VM with version 2.1.0 has multidex support
,08-31 16:51:06.643  6007  6007 I MultiDex: install
08-31 16:51:06.643  6007  6007 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-31 16:51:06.643  5301  5301 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-31 16:51:06.643  5301  5301 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-31 16:51:06.643  2936  3025 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,08-31 16:51:06.653  5301  5301 D InitializeManagerStateMachine: exit::SUCCESS
08-31 16:51:06.653  5301  5301 D InitializeManagerStateMachine: entry::IDLE
,08-31 16:51:06.663  1017  1252 I ActivityManager: Killing 4879:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-31 16:51:06.673  1017  1688 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:06.683  6007  6007 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-31 16:51:06.693  1017  1029 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:06.703  1017  1689 I AudioService: getStreamVolume 3 index 0
,08-31 16:51:06.713  5881  5881 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-31 16:51:06.713  5881  5881 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-31 16:51:06.743  5881  5881 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 16:51:06.773  6007  6007 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-31 16:51:06.773  6007  6007 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e165793: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-31 16:51:06.773  6007  6007 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-31 16:51:06.793  6007  6007 D ChimeraCfgMgr: Reading stored module config
,08-31 16:51:06.883  6007  6007 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 16:51:06.893  6007  6007 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-31 16:51:06.893  6007  6032 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-31 16:51:06.903  5983  6036 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-31 16:51:06.903  5983  6036 I Babel   : MmsConfig.loadMmsSettings
,08-31 16:51:06.923  1017  2875 I art     : Explicit concurrent mark sweep GC freed 33563(1618KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/41MB, paused 2.939ms total 173.842ms
,08-31 16:51:06.923  5983  6036 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-31 16:51:06.923  5983  6036 I Babel   : MmsConfig.loadFromDatabase
,08-31 16:51:06.943  5983  6036 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-31 16:51:06.943  5983  6036 I Babel   : MmsConfig.loadFromResources
,08-31 16:51:06.943  5983  6036 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-31 16:51:06.943  5983  6036 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-31 16:51:06.953  1639  1715 I art     : Explicit concurrent mark sweep GC freed 1747(63KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 766us total 30.241ms
,08-31 16:51:06.963  1017  1688 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 16:51:06.963  1017  1688 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
08-31 16:51:06.963  1017  1688 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.963  1017  1688 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.963  1017  1688 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:06.973  1017  2875 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 16:51:06.973  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.973  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:06.973  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.973  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:06.973  1017  2876 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-31 16:51:06.973  1017  2876 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-31 16:51:06.973  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:06.973  1017  2876 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:06.973  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:07.003  1017  2875 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-31 16:51:07.013  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-31 16:51:07.013  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.013  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.013  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.013  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.013  5881  5881 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-31 16:51:07.033  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.043  1017  1017 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-31 16:51:07.043  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.043  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.043  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.043  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.053   282   703 D WVCdm   : Instantiating CDM.
,08-31 16:51:07.063  6044  6044 E Zygote  : MountEmulatedStorage()
,08-31 16:51:07.063  6044  6044 I libpersona: KNOX_SDCARD checking this for 10002
08-31 16:51:07.063  6044  6044 E Zygote  : v2
08-31 16:51:07.063  6044  6044 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:07.063  6044  6044 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:07.063   282   686 I WVCdm   : CdmEngine::OpenSession
08-31 16:51:07.063  6044  6044 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:07.063   282   686 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-31 16:51:07.063  6044  6044 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:07.073  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6044 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:07.073  1017  1477 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.073  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.083  5983  5983 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-31 16:51:07.083  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.083  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.083   282   686 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-31 16:51:07.103  6044  6044 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:07.103  6044  6044 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:07.113  1017  1468 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.113  1017  1468 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.113  1017  1468 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.113  1017  1468 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.113   282   686 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-31 16:51:07.113   282   686 D DrmWidevineDash: Service_Initialize: starts!
08-31 16:51:07.113   282   686 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-31 16:51:07.113   282   686 D QSEECOMAPI: : App is not loaded in QSEE
08-31 16:51:07.113   282   686 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-31 16:51:07.113   282   686 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-31 16:51:07.113   282   686 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-31 16:51:07.113   282   686 D QSEECOMAPI: : App is not loaded in QSEE
08-31 16:51:07.113   282   686 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-31 16:51:07.113   282   686 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-31 16:51:07.113   282   686 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-31 16:51:07.113   282   686 D QSEECOMAPI: : App is not loaded in QSEE
,08-31 16:51:07.123  1017  1150 D WifiWatchdogStateMachine.CaptivePortalHandler: Do not check CP during LCD off.
,08-31 16:51:07.123  1017  2642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-31 16:51:07.153  1017  1140 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-31 16:51:07.153  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.153  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.153  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.153  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.173  5881  5881 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-31 16:51:07.173  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-31 16:51:07.173  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-31 16:51:07.183  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:07.183  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.183  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-31 16:51:07.183  1017  1140 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-31 16:51:07.183  1017  1140 D BatteryService: level:56, scale:100, status:2, health:2, present:true, voltage: 3801, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-31 16:51:07.183  1017  1140 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-31 16:51:07.183  1017  1140 D BatteryService: stay LED for charging,
08-31 16:51:07.183  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-31 16:51:07.183   282   686 D QSEECOMAPI: : Loaded image: APP id = 10
,08-31 16:51:07.183   282   686 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-31 16:51:07.193  1017  1017 I MotionRecognitionService: Plugged
,08-31 16:51:07.193  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,08-31 16:51:07.203  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-31 16:51:07.203  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-31 16:51:07.203  1407  1407 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-31 16:51:07.203  1407  1407 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 56
,08-31 16:51:07.213  5567  5567 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-31 16:51:07.213   282   686 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-31 16:51:07.213   282   686 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-31 16:51:07.213   282   686 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1689000
08-31 16:51:07.213   282   686 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1689000
08-31 16:51:07.213   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.213  5567  5623 D HeadsetStateMachine: Disconnected process message: 10
,08-31 16:51:07.223  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
08-31 16:51:07.223  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:51:07.223  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:56 status:2 health:2
,08-31 16:51:07.233   430   440 D DrmLibTime: got the req here! ret=0
08-31 16:51:07.233   430   440 D DrmLibTime: command id, time_cmd_id = 770
08-31 16:51:07.233   430   440 D DrmLibTime: time_getutcsec starts!
08-31 16:51:07.233   430   440 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-31 16:51:07.233   430   440 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-31 16:51:07.233   430   440 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-31 16:51:07.233   430   440 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-31 16:51:07.233  5983  5983 I Babel_StickerModule: App launched.
,08-31 16:51:07.243   430   440 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-31 16:51:07.243   430   440 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-31 16:51:07.243   430   440 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-31 16:51:07.243   430   440 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-31 16:51:07.243   332   425 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-31 16:51:07.243   332  6062 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
08-31 16:51:07.243   332  6062 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-31 16:51:07.243   332  6062 D QC-time-services: offset is: 0 for base: 0
,08-31 16:51:07.243   430   440 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-31 16:51:07.243   430   440 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-31 16:51:07.243   430   440 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472655067
08-31 16:51:07.243   430   440 D DrmLibTime: time_getutcsec returns 0, sec = 1472655067; nsec = 0,
08-31 16:51:07.243   430   440 D DrmLibTime: time_getutcsec finished! 
08-31 16:51:07.243   332   425 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-31 16:51:07.243   430   440 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-31 16:51:07.243   430   440 D DrmLibTime: before calling ioctl to read the next time_cmd
08-31 16:51:07.243   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
08-31 16:51:07.243  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-31 16:51:07.243  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.243  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.243  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.243  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.263   282   686 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-31 16:51:07.263   282   686 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-31 16:51:07.263   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 16:51:07.263   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.263   282   686 D DrmWidevineDash: hlos api version =  9
08-31 16:51:07.263   282   686 D DrmWidevineDash: tz api version =  9
08-31 16:51:07.263   282   686 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-31 16:51:07.263   282   686 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-31 16:51:07.263   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.273  6063  6063 E Zygote  : MountEmulatedStorage()
08-31 16:51:07.273  6063  6063 E Zygote  : v2
08-31 16:51:07.273  6063  6063 I libpersona: KNOX_SDCARD checking this for 10113
08-31 16:51:07.273  6063  6063 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:07.273  6063  6063 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:07.283  6063  6063 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:07.283  1017  1481 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6063 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:07.283  6063  6063 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:07.303   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-31 16:51:07.303   282   686 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb18dd960
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-31 16:51:07.303   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.303   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-31 16:51:07.303   282   686 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb756b268, dataLength=8
08-31 16:51:07.303   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.313   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.313   282   686 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-31 16:51:07.313  6007  6013 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-31 16:51:07.313  6063  6063 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:07.313  6007  6013 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-31 16:51:07.313  6007  6013 I System.out: (HTTPLog)-Static: isShipBuild true
08-31 16:51:07.313  6007  6013 I System.out: (HTTPLog)-Thread-999-814006164: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-31 16:51:07.313  6007  6013 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:07.313  6063  6063 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:07.313  1928  1928 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=f4584310-bca8-451a-9768-66d2cd243964
,08-31 16:51:07.313   282   686 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7511f00, wrapped_rsa_key_length=1280
08-31 16:51:07.313   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.323   277   957 D EnterpriseController: uids 10012,
08-31 16:51:07.323   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:07.323   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-31 16:51:07.323   282   686 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.323   282   686 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-31 16:51:07.323   282   686 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-31 16:51:07.323   282   703 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
08-31 16:51:07.323   282   703 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-31 16:51:07.323   282   703 I WVCdm   : CdmEngine::GenerateKeyRequest
08-31 16:51:07.323   282   703 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7514ac0, idLength=0xb17dd730
08-31 16:51:07.323   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.353  5983  5997 W art     : Suspending all threads took: 84.746ms
,08-31 16:51:07.373  6007  6013 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:07.373  1017  1140 I ActivityManager: Killing 5206:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-31 16:51:07.373  6007  6013 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6007, getuid(): 10012
,08-31 16:51:07.373  1017  2875 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-31 16:51:07.383  1017  2875 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 16:51:07.383  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 16:51:07.383  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.383  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb17dd746, maximum = 0xb17dd747
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
,08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: hlos api version =  9
08-31 16:51:07.383   282   703 D DrmWidevineDash: tz api version =  9
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb17dd7b4
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
,08-31 16:51:07.383   282   703 D WVCdm   : PrepareKeyRequest: nonce=4265882092
08-31 16:51:07.383   282   703 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb75274e8
08-31 16:51:07.383   282   703 D DrmWidevineDash: message_length=1599, signature=0xb7539558, signature_length=0xb17dd714
08-31 16:51:07.383   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.393  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-31 16:51:07.393  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.393  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.393  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:07.393  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:07.403  1928  1928 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.,
08-31 16:51:07.403  1928  1928 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-31 16:51:07.413  6084  6084 E Zygote  : MountEmulatedStorage(),
08-31 16:51:07.413  6084  6084 E Zygote  : v2
08-31 16:51:07.413  6084  6084 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:07.413  6084  6084 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:07.413  6084  6084 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:07.413  6084  6084 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:07.413  6084  6084 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:07.413  1017  1481 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6084 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-31 16:51:07.453  6084  6084 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:07.453  6084  6084 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:07.473  1017  2876 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:07.483  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.483  1017  2876 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:07.483  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:07.533   282   686 W QCamera2Factory: getCameraInfo: E, camera_id = 0
08-31 16:51:07.533   282   686 W QCamera2Factory: getCameraInfo: X
,08-31 16:51:07.553   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-31 16:51:07.553   282   282 W QCamera2Factory: getCameraInfo: X
,08-31 16:51:07.573  1017  1140 I ActivityManager: Killing 5244:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,08-31 16:51:07.573  1017  1140 I ActivityManager: Killing 5104:com.android.mms/u0a46 (adj 15): empty #32
,08-31 16:51:07.583   282   703 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.583   282   703 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-31 16:51:07.593   282   282 I WVCdm   : CdmEngine::CloseSession
08-31 16:51:07.593   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-31 16:51:07.593   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.593   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.593   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-31 16:51:07.593   282   282 I WVCdm   : L3 Terminate.
08-31 16:51:07.593   282   282 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-31 16:51:07.593   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-31 16:51:07.593  6084  6084 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-31 16:51:07.603   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-31 16:51:07.603   282   282 D DrmWidevineDash: Service_Uninitialize: starts!
08-31 16:51:07.603   282   282 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-31 16:51:07.603   282   282 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,08-31 16:51:07.603   282   282 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-31 16:51:07.603   282   282 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-31 16:51:07.613  1017  1029 D CountryDetector: No listener is left
,08-31 16:51:07.613  5983  5983 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-31 16:51:07.613  5983  5983 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.623  5983  5983 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.623  5983  5983 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-31 16:51:07.623  5983  5983 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-31 16:51:07.633  5983  5983 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-31 16:51:07.633  5983  5983 W AudioCapabilities: Unsupported mime audio/x-ima
,08-31 16:51:07.633  5983  5983 W AudioCapabilities: Unsupported mime audio/qcelp
,08-31 16:51:07.633  5983  5983 W AudioCapabilities: Unsupported mime audio/evrc
,08-31 16:51:07.643  5983  5983 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.643  5983  5983 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.653  5983  5983 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-31 16:51:07.653  5983  5983 W VideoCapabilities: Unsupported mime video/wvc1
,08-31 16:51:07.663  5983  5983 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-31 16:51:07.663  5983  5983 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-31 16:51:07.663  5983  5983 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-31 16:51:07.673  5983  5983 W VideoCapabilities: Unsupported mime video/mp43
,08-31 16:51:07.673  5983  5983 W VideoCapabilities: Unsupported mime video/sorenson
,08-31 16:51:07.673  5983  5983 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-31 16:51:07.713  5983  5983 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-31 16:51:07.733   257   452 I SurfaceFlinger: id=13 Removed Uoast (8/9)
,08-31 16:51:07.733   257  1039 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,08-31 16:51:07.743  1017  1030 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 136751
,08-31 16:51:07.743  1017  1030 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
08-31 16:51:07.743  1017  1030 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3487)
,08-31 16:51:07.763  2969  6102 D OpenGLRenderer: Render dirty regions requested: true
,08-31 16:51:07.773  6007  6013 I qtaguid : Untagging socket 30
,08-31 16:51:07.783   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-31 16:51:07.813  1017  2876 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,08-31 16:51:07.823  2969  2969 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-31 16:51:07.823  2969  6102 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:07.823  2969  6102 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:07.823  2969  6102 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:07.823  2969  6102 I Adreno-EGL: Local Branch: 
08-31 16:51:07.823  2969  6102 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:07.823  2969  6102 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:07.823  2969  6102 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:07.823  2969  6102 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 16:51:07.833  5788  5788 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-31 16:51:07.843  2969  6102 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-31 16:51:07.843  2969  6102 D OpenGLRenderer: Enabling debug mode 0
,08-31 16:51:07.853  1017  1029 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-31 16:51:07.853  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-31 16:51:07.853  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:07.853  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:07.853  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-31 16:51:07.873  6084  6084 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-31 16:51:07.903  1017  1468 I ActivityManager: Killing 5259:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-31 16:51:07.913  5487  5540 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 16:51:07.913  5487  5540 I jxcore-log: 
,08-31 16:51:07.943  6084  6084 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-31 16:51:07.953  6084  6084 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:07.953  6084  6084 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-31 16:51:07.953  6084  6084 I DIAGMON_AGENT: ./extraInfo: "NG700"
,08-31 16:51:07.953  6084  6084 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-31 16:51:08.013   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:08.013   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.013  6063  6107 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:08.033   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:08.033   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.033  5567  5598 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-31 16:51:08.043   287   287 E SMD     : DCD OFF,
,08-31 16:51:08.043  6063  6107 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files,
,08-31 16:51:08.043  1928  2104 I art     : Explicit concurrent mark sweep GC freed 54794(3MB) AllocSpace objects, 5(80KB) LOS objects, 40% free, 13MB/23MB, paused 1.489ms total 209.404ms
,08-31 16:51:08.073   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-31 16:51:08.073   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.073  6063  6110 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-31 16:51:08.103   256   540 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-31 16:51:08.103   256   540 W Vold    : Returning OperationFailed - no handler for errno 0
,08-31 16:51:08.103  6063  6110 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-31 16:51:08.153  1017  1481 I ActivityManager: Killing 5280:com.wsomacp/u0a25 (adj 15): empty #31
,08-31 16:51:08.183  1928  2089 W GCoreFlp: No location to return for getLastLocation()
,08-31 16:51:08.223  1017  1692 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.223  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.223  1017  1692 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.223  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.233  1017  2875 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.233  1017  2875 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:08.233  1017  2875 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.233  1017  2875 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.243  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.243  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.243  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.243  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.273  1928  2094 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:08.273  6116  6116 I dex2oat : ----------------------------------------------------
08-31 16:51:08.273  6116  6116 I dex2oat : <SS>: S T A R T I N G . . .
08-31 16:51:08.273  6116  6116 I dex2oat : <SS>: Zip is absent. Canceled.
,08-31 16:51:08.273  6116  6116 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-31 16:51:08.283  3762  5982 D UdcContextInitService: registered all accounts: true
,08-31 16:51:08.293  1928  2104 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-31 16:51:08.323  1017  1140 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-31 16:51:08.323  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.323  1017  1140 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-31 16:51:08.333  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.343  6063  6063 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-31 16:51:08.353  5487  5540 I jxcore-log: ERROR runTests: 
08-31 16:51:08.353  5487  5540 I jxcore-log: 
,08-31 16:51:08.353  5487  5540 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.353  5487  5540 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 16:51:08.353  5487  5540 I jxcore-log: WARN testUtils: logCallback not set!
08-31 16:51:08.353  5487  5540 I jxcore-log: 
,08-31 16:51:08.363  6063  6063 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7369-7371)
08-31 16:51:08.363  6063  6063 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-31 16:51:08.363  6116  6116 I dex2oat : dex2oat took 86.126ms (threads: 4)
,08-31 16:51:08.373  5487  5540 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _functionName: 'loadFile',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _lineNumber: '26',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _columnNumber: '11',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 16:51:08.373  5487  5540 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _functionName: '',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _lineNumber: '38',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _columnNumber: '7',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 16:51:08.373  5487  5540 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _functionName: '',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _lineNumber: '35',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _columnNumber: '3',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 16:51:08.373  5487  5540 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _lineNumber: '621',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _columnNumber: '8',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 16:51:08.373  5487  5540 I jxcore-log:   { _fileName: 'module.js',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _lineNumber: '651',
08-31 16:51:08.373  5487  5540 I jxcore-log:     _columnNumber: '1',
08-31 16:51:08.373  5487  5540 I jxcore-log:    
08-31 16:51:08.373  5487  5540 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 16:51:08.373  5487  5540 I jxcore-log: 
,08-31 16:51:08.373  5487  5540 E jxcore-log: Error: 
08-31 16:51:08.373  5487  5540 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 16:51:08.373  5487  5540 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 16:51:08.373  5487  5540 E jxcore-log: 
08-31 16:51:08.373  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-31 16:51:08.373  5487  5540 I jxcore-log: 
08-31 16:51:08.373  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-31 16:51:08.373  5487  5540 I jxcore-log: 
08-31 16:51:08.383  5487  5540 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 16:51:08.383  5487  5540 I jxcore-log: 
08-31 16:51:08.383  6063  6063 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b41dd39}
,08-31 16:51:08.383  6063  6063 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 16:51:08.383  6063  6063 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-31 16:51:08.383  6007  6013 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-31 16:51:08.383  6007  6013 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.383  6007  6013 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.383  6007  6013 I Adreno-EGL: Local Branch: 
08-31 16:51:08.383  6007  6013 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.383  6007  6013 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.383  6007  6013 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.413  6063  6063 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-31 16:51:08.413  6063  6063 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-31 16:51:08.413  6063  6063 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-31 16:51:08.443  6063  6063 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty(),
08-31 16:51:08.443  6063  6063 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-31 16:51:08.443  6063  6063 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-31 16:51:08.443  6063  6063 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-31 16:51:08.443  6063  6063 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.443  6063  6063 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.443  6063  6063 I Adreno-EGL: Local Branch: 
08-31 16:51:08.443  6063  6063 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.443  6063  6063 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.443  6063  6063 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.473  6007  6013 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-31 16:51:08.473  6007  6013 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.473  6007  6013 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.473  6007  6013 I Adreno-EGL: Local Branch: 
08-31 16:51:08.473  6007  6013 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.473  6007  6013 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.473  6007  6013 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.513  6063  6148 W AudioManagerAndroid: Requires BLUETOOTH permission,
,08-31 16:51:08.533  6007  6013 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-31 16:51:08.533  6007  6013 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-31 16:51:08.533  6007  6013 I Adreno-EGL: Build Date: 04/06/15 Mon
08-31 16:51:08.533  6007  6013 I Adreno-EGL: Local Branch: 
08-31 16:51:08.533  6007  6013 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-31 16:51:08.533  6007  6013 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-31 16:51:08.533  6007  6013 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-31 16:51:08.533  6063  6063 I NSApplication: Starting up...,
,08-31 16:51:08.553  1017  1689 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-31 16:51:08.563  1017  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.563  1017  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.563  1017  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:08.563  1017  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:08.583  1017  1689 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6153 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:08.583  1017  1689 I ActivityManager: Killing 5325:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,08-31 16:51:08.593  6153  6153 E Zygote  : MountEmulatedStorage()
08-31 16:51:08.593  6153  6153 I libpersona: KNOX_SDCARD checking this for 10120
08-31 16:51:08.593  6153  6153 E Zygote  : v2
08-31 16:51:08.593  6153  6153 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:08.593  6153  6153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:08.593  6153  6153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:08.593  6153  6153 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-31 16:51:08.613  6153  6153 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:08.613  6153  6153 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:08.643  1017  1481 I ActivityManager: Killing 4796:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-31 16:51:08.653  6153  6153 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:08.663  6139  6139 D AndroidRuntime: 
08-31 16:51:08.663  6139  6139 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-31 16:51:08.673  6139  6139 D AndroidRuntime: CheckJNI is OFF
08-31 16:51:08.673  6139  6139 D AndroidRuntime: readGMSProperty: start
08-31 16:51:08.673  6139  6139 D AndroidRuntime: readGMSProperty: already setted!!
08-31 16:51:08.673  6139  6139 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-31 16:51:08.673  6139  6139 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-31 16:51:08.673  6139  6139 D AndroidRuntime: readGMSProperty: end
08-31 16:51:08.673  6139  6139 D AndroidRuntime: addProductProperty: start
,08-31 16:51:08.713  5356  5981 I SA      : [RC New] Execute method=[GET] start
,08-31 16:51:08.753  5356  5981 I SA      : [RC New] Security=[true]
,08-31 16:51:08.753  5356  5981 I System.out: Thread-910(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
08-31 16:51:08.753  5356  5981 I System.out: Thread-910(ApacheHTTPLog):isSBSettingEnabled false
,08-31 16:51:08.753  5356  5981 I System.out: Thread-910(ApacheHTTPLog):isShipBuild true
08-31 16:51:08.753  5356  5981 I System.out: Thread-910(ApacheHTTPLog):SMARTBONDING_ENABLED is false
08-31 16:51:08.753  5356  5981 I System.out: Thread-910(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false,
08-31 16:51:08.753   277   957 D EnterpriseController: uids 10041
08-31 16:51:08.753   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:08.753   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,08-31 16:51:08.803  1017  1477 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 16:51:08.803  1017  1477 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-31 16:51:08.803  1017  1477 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:08.803  1017  1477 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:08.803  1017  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:08.843  6139  6139 E AffinityControl: AffinityControl: registerfunction enter,
,08-31 16:51:08.863  6139  6139 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 16:51:08.883  1017  1140 D PackageManager: START PACKAGE DELETE: observer{842418679}
08-31 16:51:08.883  1017  1140 D PackageManager: pkg{<packageName>}
08-31 16:51:08.883  1017  1140 D PackageManager: user{0}
08-31 16:51:08.883  1017  1140 D PackageManager: caller{2000}
08-31 16:51:08.883  1017  1140 D PackageManager: flags{2}
,08-31 16:51:08.883  1017  1140 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
,08-31 16:51:08.883  1017  1140 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-31 16:51:08.883  1017  1140 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-31 16:51:08.883  1017  1140 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 16:51:08.883  1017  1140 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-31 16:51:08.893  1017  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-31 16:51:08.893  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-31 16:51:08.893  1017  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-31 16:51:08.893  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
08-31 16:51:08.893  1017  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-31 16:51:08.893  1017  1058 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-31 16:51:08.903  1017  2876 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-31 16:51:08.903  1017  2876 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,08-31 16:51:08.903  1017  2876 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:08.903  1017  2876 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,08-31 16:51:08.903  1017  2876 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,08-31 16:51:08.913  1017  1043 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-31 16:51:08.913  1017  1043 I ActivityManager: Killing 5487:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-31 16:51:08.913  1017  1043 I ActivityManager:   Force finishing activity ActivityRecord{356b21de u0 com.test.thalitest/.MainActivity t128}
08-31 16:51:08.923  1017  1043 D InputDispatcher: Focus left window: 5487
,08-31 16:51:08.923   257   449 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,08-31 16:51:08.933   257  1828 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,08-31 16:51:08.933  1017  1043 D InputDispatcher: Focused application released
,08-31 16:51:08.933  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-31 16:51:08.933  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-31 16:51:09.043  1017  1058 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-31 16:51:09.063  1017  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-31 16:51:09.083  3672  3672 I art     : Explicit concurrent mark sweep GC freed 2789(174KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 1.347ms total 38.162ms
,08-31 16:51:09.113  1017  1099 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-31 16:51:09.113  1804  1804 E SamsungIME: mOCRHelper is null
,08-31 16:51:09.123  1928  2094 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-31 16:51:09.133  3762  3762 I art     : Explicit concurrent mark sweep GC freed 24740(1630KB) AllocSpace objects, 17(272KB) LOS objects, 25% free, 15MB/20MB, paused 1.773ms total 89.825ms
,08-31 16:51:09.173  1436  1436 D PersonaManager: isKioskContainerExistOnDevice,
,08-31 16:51:09.193  1436  1436 D RegisteredServicesCache: empty dynamic service
,08-31 16:51:09.193  1017  1125 V NetworkStats: removeUidsLocked() for UIDs [10155]
,08-31 16:51:09.193  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-31 16:51:09.193  1017  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-31 16:51:09.193  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-31 16:51:09.193  1017  1030 D SecContentProvider2: mCursor = null
,08-31 16:51:09.203  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-31 16:51:09.203  1017  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-31 16:51:09.213  1017  1030 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-31 16:51:09.213  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.213  1436  1436 D RegisteredComponentCache: Collect Tech packages for Knox
08-31 16:51:09.213  1017  1125 V NetworkStats: performPollLocked() took 18ms
,08-31 16:51:09.213  1017  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.213  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.213  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-31 16:51:09.213  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-31 16:51:09.213  1436  1436 D PersonaManager: isKioskContainerExistOnDevice
,08-31 16:51:09.223  1928  6003 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:09.223   277   957 D EnterpriseController: uids 10012
08-31 16:51:09.223   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-31 16:51:09.223   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-31 16:51:09.253  1017  1017 D RCPManagerService: PackageReceiver onReceive()
08-31 16:51:09.253  1017  1017 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-31 16:51:09.253  1017  1017 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-31 16:51:09.253  1017  1017 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-31 16:51:09.253  1017  1017 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-31 16:51:09.253  1017  1017 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-31 16:51:09.253  1017  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
08-31 16:51:09.253  1017  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-31 16:51:09.253  1017  1042 W TextServicesManagerService: no available spell checker services found
,08-31 16:51:09.263  1928  6003 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-31 16:51:09.263  1928  6003 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1928, getuid(): 10012
,08-31 16:51:09.263  1017  1017 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-31 16:51:09.263  1017  1017 I OTPFW   : ProvisionData::getAllEntries Enter
,08-31 16:51:09.263  1017  1017 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-31 16:51:09.263  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-31 16:51:09.273  1017  1017 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-31 16:51:09.273  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 16:51:09.273  1017  1017 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-31 16:51:09.273  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicy: uID is 10155
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicy: Removed Packageuid is0
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-31 16:51:09.283  1017  1017 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-31 16:51:09.283  1017  1017 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-31 16:51:09.283  1017  2627 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-31 16:51:09.283  1017  1162 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,08-31 16:51:09.283  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.293  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.333  1928  6003 I qtaguid : Tagging socket 64 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1928, getuid(): 10012
,08-31 16:51:09.333  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.333  1017  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-31 16:51:09.343  1017  1468 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-31 16:51:09.353  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.353  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.353  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.353  1017  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.363  6190  6190 E Zygote  : MountEmulatedStorage(),
08-31 16:51:09.363  6190  6190 E Zygote  : v2,
08-31 16:51:09.363  6190  6190 I libpersona: KNOX_SDCARD checking this for 10125
08-31 16:51:09.363  6190  6190 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.363  6190  6190 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-31 16:51:09.363  1017  1468 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6190 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a,
08-31 16:51:09.373  6190  6190 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:09.373  6190  6190 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:09.373  1017  1468 I ActivityManager: Killing 5191:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31,
,08-31 16:51:09.383  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-31 16:51:09.393  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.393  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.393  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.403  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:51:09.403  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:09.403  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:09.403  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,08-31 16:51:09.413  6190  6190 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.413  6190  6190 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:09.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:09.413  2936  3024 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-31 16:51:09.413  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:09.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-31 16:51:09.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-31 16:51:09.423  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-31 16:51:09.423  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-31 16:51:09.423  1017  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-31 16:51:09.423  1017  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-31 16:51:09.433  1017  1327 E Watchdog: !@Sync 4
,08-31 16:51:09.433  6190  6190 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:09.433  6190  6190 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-31 16:51:09.433  6190  6190 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-31 16:51:09.433  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-31 16:51:09.433  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-31 16:51:09.433  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-31 16:51:09.433  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-31 16:51:09.443  2936  3024 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-31 16:51:09.443  2936  3024 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-31 16:51:09.453  5356  5981 I SA      : [RC New] [v2liruge] api execute + 702
,08-31 16:51:09.453  5356  5981 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,08-31 16:51:09.453  2936  3024 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-31 16:51:09.463  1017  1058 I art     : Explicit concurrent mark sweep GC freed 43084(3MB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 28MB/42MB, paused 5.486ms total 295.081ms
,08-31 16:51:09.473  2936  3024 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-31 16:51:09.473  5356  5981 I System.out: AsyncTask #1 calls detatch()
,08-31 16:51:09.473  1017  1058 D PackageManager: delete codoeFile: 
,08-31 16:51:09.483  1017  1058 I AASA_removePackage: UID=10155 Target=com.test.thalitest,
08-31 16:51:09.483  1017  1058 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,08-31 16:51:09.493  6190  6190 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-31 16:51:09.493  6190  6190 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-31 16:51:09.503  1017  1058 D PackageManager: result of delete: 1{842418679}
,08-31 16:51:09.503  6190  6190 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-31 16:51:09.503  1017  2876 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-31 16:51:09.503  1017  2876 I ActivityManager: Killing 5172:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-31 16:51:09.513  1017  1017 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=23
08-31 16:51:09.513  1017  1017 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,08-31 16:51:09.513  6139  6139 D AndroidRuntime: Shutting down VM
08-31 16:51:09.513  5356  5981 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,08-31 16:51:09.513  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-31 16:51:09.513  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.513  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.523  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.523  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.523  5356  5981 I SA      : [OCP] update openData : PL
,08-31 16:51:09.533  5356  5981 I SA      : [TPMU] getNetworkMcc : ,
,08-31 16:51:09.533  6205  6205 I libpersona: KNOX_SDCARD checking this for 10062
08-31 16:51:09.533  6205  6205 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.533  6205  6205 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.533  6205  6205 E Zygote  : v2
,08-31 16:51:09.533  1017  1043 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6205 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:09.533  5356  5981 I SA      : [SCU] saveMccToPreferece Start
08-31 16:51:09.533  5356  5981 I SA      : [SCU] RegionMCC : 260
08-31 16:51:09.533  6205  6205 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:09.533  5356  5981 I SA      : [SSP] query invoked
,08-31 16:51:09.533  6205  6205 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:09.533  6205  6205 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-31 16:51:09.533  1017  1043 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
08-31 16:51:09.533  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.533  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-31 16:51:09.543  5356  5981 I SA      : [TPMU] GetMccFromDB : null
08-31 16:51:09.533  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.543  5356  5981 I SA      : [SCU] getMccFromPreferece mcc = 260
08-31 16:51:09.533  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.543  5356  5981 I SA      : [SCU] saveMccToPreferece End
,08-31 16:51:09.543  5356  5981 I SA      : [RC New] executeRequest [v2liruge] end. 826
08-31 16:51:09.543  5356  5981 I SA      : [RC New] Execute end
08-31 16:51:09.543  5356  5356 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-31 16:51:09.543  5356  5356 I SA      : [OR] GetMyCountryZoneTask Success
,08-31 16:51:09.553  6218  6218 E Zygote  : MountEmulatedStorage()
,08-31 16:51:09.553  6218  6218 I libpersona: KNOX_SDCARD checking this for 10135
08-31 16:51:09.553  6218  6218 E Zygote  : v2
08-31 16:51:09.553  6218  6218 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.553  6218  6218 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:09.553  1017  1043 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6218 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-31 16:51:09.563  6218  6218 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:09.563  6218  6218 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.563  6205  6205 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.563  6205  6205 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.563  5871  5871 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,08-31 16:51:09.573  6218  6218 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.573  6218  6218 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.583  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-31 16:51:09.583  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-31 16:51:09.583  1309  1309 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:51:09.593  1309  1309 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:51:09.593  1309  1309 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-31 16:51:09.593  1309  1309 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-31 16:51:09.593  1309  1309 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-31 16:51:09.593  1309  1309 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 150916856558 ] [ 3 ] 
,08-31 16:51:09.593  1309  1309 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-31 16:51:09.593  1309  1309 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-31 16:51:09.593  1309  1309 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-31 16:51:09.593  1309  1309 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
08-31 16:51:09.603  5871  5871 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-31 16:51:09.603  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-31 16:51:09.603  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-31 16:51:09.603  6218  6218 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-31 16:51:09.603  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-31 16:51:09.603  6218  6218 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-31 16:51:09.603  1309  1309 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
08-31 16:51:09.603  6218  6218 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:09.613  1309  1309 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-31 16:51:09.613  3445  3445 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Wed Aug 31 16:51:09 GMT+02:00 2016
,08-31 16:51:09.613  1017  1030 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,08-31 16:51:09.613  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.613  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-31 16:51:09.623  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-31 16:51:09.623  1309  1309 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-31 16:51:09.623  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-31 16:51:09.633  3445  3445 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-31 16:51:09.633  5356  5356 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,08-31 16:51:09.643  3445  3445 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-31 16:51:09.643  1309  1309 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
08-31 16:51:09.643  1309  1309 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-31 16:51:09.653  3445  3445 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-31 16:51:09.653  6205  6205 I ExternalOEMControlProvider: onCreate
,08-31 16:51:09.653  3445  3445 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-31 16:51:09.653  3445  6236 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,08-31 16:51:09.663  1017  2876 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,08-31 16:51:09.663  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.663  3445  6236 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
08-31 16:51:09.663  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.663  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.663  1017  2876 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.663  3445  6236 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Wed Aug 31 16:51:09 GMT+02:00 2016
,08-31 16:51:09.673  6241  6241 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.673  6241  6241 E Zygote  : v2
08-31 16:51:09.673  6241  6241 I libpersona: KNOX_SDCARD checking this for 1000
08-31 16:51:09.673  6241  6241 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.673  6241  6241 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:09.683  1017  2876 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=6241 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
08-31 16:51:09.683  6241  6241 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-31 16:51:09.683  6241  6241 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.683  1017  1692 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-31 16:51:09.683  1017  1692 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.683  1017  1692 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.683  1017  1692 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:09.683  1017  1692 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 16:51:09.683  1309  1326 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-31 16:51:09.693  3445  6236 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,08-31 16:51:09.693  6205  6239 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-31 16:51:09.693  1017  1692 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,08-31 16:51:09.693  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.693  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.693  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.693  1017  1692 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.703  3445  3445 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-31 16:51:09.713  6241  6241 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.713  6241  6241 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.713  6258  6258 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.713  6258  6258 E Zygote  : v2
08-31 16:51:09.713  6258  6258 I libpersona: KNOX_SDCARD checking this for 10046
08-31 16:51:09.713  6258  6258 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.713  6258  6258 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:09.713  1017  1692 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=6258 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,08-31 16:51:09.713  1017  1140 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-31 16:51:09.713  1017  1140 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-31 16:51:09.713  6258  6258 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-31 16:51:09.713  6258  6258 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.723  1017  1140 W ActivityManager: userId = 0, bbcId = -10000
08-31 16:51:09.723  1017  1140 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-31 16:51:09.723  1017  1140 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-31 16:51:09.723  6139  6139 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-31 16:51:09.743  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-31 16:51:09.743  5705  5705 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-31 16:51:09.743  5705  5705 D SecurityLogAgent: StateMachine : Current State = 1
,08-31 16:51:09.743   305   305 I art     : Explicit concurrent mark sweep GC freed 8735(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 671us total 27.034ms
,08-31 16:51:09.743  1017  1252 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-31 16:51:09.743  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.743  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.743  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.743  1017  1252 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.753  6258  6258 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.753  1017  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-31 16:51:09.753  1017  1058 D PackageManager: userId{-1}
08-31 16:51:09.753  1017  1058 D PackageManager: andCode{true}
08-31 16:51:09.753  6258  6258 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:09.753  6241  6241 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:09.763   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 695us total 17.368ms
,08-31 16:51:09.783   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 604us total 18.383ms
,08-31 16:51:09.793  6275  6275 E Zygote  : MountEmulatedStorage()
,08-31 16:51:09.793  6275  6275 E Zygote  : v2
,08-31 16:51:09.793  6275  6275 I libpersona: KNOX_SDCARD checking this for 10042
08-31 16:51:09.793  6275  6275 I libpersona: KNOX_SDCARD not a persona,
08-31 16:51:09.793  1017  1252 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6275 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-31 16:51:09.793  6275  6275 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:09.793  6275  6275 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-31 16:51:09.793  1017  6186 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
08-31 16:51:09.793  6275  6275 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.793  1017  6186 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.793  1017  6186 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.793  1017  6186 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.793  1017  6186 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.823  6287  6287 E Zygote  : MountEmulatedStorage()
08-31 16:51:09.823  6287  6287 E Zygote  : v2
08-31 16:51:09.823  6287  6287 I libpersona: KNOX_SDCARD checking this for 10157
08-31 16:51:09.823  6287  6287 I libpersona: KNOX_SDCARD not a persona
08-31 16:51:09.823  6287  6287 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-31 16:51:09.823  6275  6275 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.823  6275  6275 D ActivityThread: Added TimaKeyStore provider
08-31 16:51:09.823  1017  6186 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=6287 uid=10157 gids={50157, 9997} abi=armeabi-v7a
08-31 16:51:09.823  6287  6287 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-31 16:51:09.823  1017  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-31 16:51:09.823  6287  6287 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.853  1928  2104 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-31 16:51:09.853  1928  2104 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
08-31 16:51:09.853  1017  2875 I ActivityManager: Killing 5390:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
08-31 16:51:09.853  1928  2104 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-31 16:51:08.564+0200, stopTime=2016-08-31 16:51:09.865+0200, duration=1301ms
,08-31 16:51:09.863  1720  1720 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-31 16:51:09.863  6258  6258 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-31 16:51:09.863  1720  1720 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
08-31 16:51:09.863  1017  1481 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
08-31 16:51:09.863  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.863  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.863  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-31 16:51:09.863  1017  1481 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-31 16:51:09.873  6275  6275 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-31 16:51:09.873  6287  6287 D TimaKeyStoreProvider: TimaSignature is unavailable
08-31 16:51:09.873  6287  6287 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.883  6312  6312 E Zygote  : MountEmulatedStorage()
,08-31 16:51:09.883  6312  6312 E Zygote  : v2
08-31 16:51:09.883  6312  6312 I libpersona: KNOX_SDCARD checking this for 10085
08-31 16:51:09.883  6312  6312 I libpersona: KNOX_SDCARD not a persona
,08-31 16:51:09.883  6312  6312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-31 16:51:09.893  1017  1481 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6312 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-31 16:51:09.893  6312  6312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-31 16:51:09.893  6312  6312 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-31 16:51:09.903  1928  1928 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/playlog.db" with flag (131138) and mode_t (0) due to error (30)
,08-31 16:51:09.903  1928  6307 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-31 16:51:09.923  6287  6287 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-31 16:51:09.923  6312  6312 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-31 16:51:09.923  6312  6312 D ActivityThread: Added TimaKeyStore provider
,08-31 16:51:09.923  1928  1928 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1508)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:11519)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at hkd.a(:com.google.android.gms:298)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at hkf.a(:com.google.android.gms:11628)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at com.google.android.gms.clearcut.receiver.WallClockChangedChimeraReceiver.onReceive(:com.google.android.gms:27)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at com.google.android.chimera.container.BroadcastReceiverProxy.onReceive(:com.google.android.gms:119)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-31 16:51:09.923  1928  1928 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-31 16:51:09.933   277   957 D EnterpriseController: uids 10012,
08-31 16:51:09.933   277   957 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
08-31 16:51:09.933   277   957 D Netd    : getNetworkForDns: using netid 502 for uid 10012
```
