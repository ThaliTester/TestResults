#### Test 82337235c858ce8_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-23 15:43:19.159   288   288 E SMD     : DCD OFF
,08-23 15:43:19.989  6277  6277 D AndroidRuntime: 
08-23 15:43:19.989  6277  6277 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 15:43:19.989  6277  6277 D AndroidRuntime: CheckJNI is OFF
08-23 15:43:19.989  6277  6277 D AndroidRuntime: readGMSProperty: start
08-23 15:43:19.989  6277  6277 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:19.989  6277  6277 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:19.989  6277  6277 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:19.989  6277  6277 D AndroidRuntime: readGMSProperty: end
08-23 15:43:19.989  6277  6277 D AndroidRuntime: addProductProperty: start
08-23 15:43:20.119  6277  6277 E AffinityControl: AffinityControl: registerfunction enter
08-23 15:43:20.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
08-23 15:43:20.139  6277  6277 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 15:43:20.149  1016  2929 E PersonaManagerService: inState():  stateMachine is null !!
08-23 15:43:20.149  1016  2929 I PersonaManagerService: PersonaId don't exist
08-23 15:43:20.149  1016  2929 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 15:43:20.159  1016  2929 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-23 15:43:20.169  1016  2929 W ActivityManager: mDVFSHelper.acquire()
08-23 15:43:20.179  1016  1046 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 15:43:20.179  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.179  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.179  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.179  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:20.179  1016  1046 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 15:43:20.189  6288  6288 E Zygote  : MountEmulatedStorage()
08-23 15:43:20.189  6288  6288 E Zygote  : v2
08-23 15:43:20.189  6288  6288 I libpersona: KNOX_SDCARD checking this for 10155
08-23 15:43:20.189  6288  6288 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:20.189  1016  2929 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-23 15:43:20.189  1016  2929 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6288 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 15:43:20.189  1016  2929 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:20.189  1016  2929 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:20.189  1016  2929 D InputDispatcher: Focus left window: 3247
08-23 15:43:20.199  6277  6277 D AndroidRuntime: Shutting down VM
08-23 15:43:20.199  6288  6288 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-23 15:43:20.199  6288  6288 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:20.199  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:20.199  1016  1046 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 15:43:20.199   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
08-23 15:43:20.199  6288  6288 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 15:43:20.209  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:20.209  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 15:43:20.219  6288  6288 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:20.219  6288  6288 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:20.219  1016  1016 V ActivityManager: Display changed displayId=0
08-23 15:43:20.229  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 15:43:20.249  1016  3209 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:20.279   258   446 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
08-23 15:43:20.279   258   802 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
08-23 15:43:20.289  3247  3247 V ActivityThread: updateVisibility : ActivityRecord{22ca068c token=android.os.BinderProxy@156618d3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
08-23 15:43:20.359  6288  6288 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-23 15:43:20.379  6288  6288 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4240-4242)
08-23 15:43:20.379  6288  6288 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:43:20.399  6277  6277 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:20.409  6288  6288 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1534d608}
,08-23 15:43:20.409  6288  6288 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 15:43:20.409  6288  6288 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 15:43:20.429  5479  5479 D FactoryTest: Not factory mode
,08-23 15:43:20.429  5479  5479 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-23 15:43:20.429  5479  5479 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,08-23 15:43:20.429  5479  5479 D MTPRx   : still no open session command from host, so toast
,08-23 15:43:20.429  5479  5479 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,08-23 15:43:20.429  5479  5479 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-23 15:43:20.429  5479  5479 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114295
,08-23 15:43:20.429  1016  3213 E PersonaManagerService: inState():  stateMachine is null !!
,08-23 15:43:20.429  1016  3213 I PersonaManagerService: PersonaId don't exist
08-23 15:43:20.429  1016  3213 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-23 15:43:20.429  1016  3213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:20.439  1016  3213 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:20.439  1016  3213 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:20.439  1016  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-23 15:43:20.439  1016  3213 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:20.439  1016  3213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:20.439  1016  3213 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-23 15:43:20.439  1016  3213 D InputDispatcher: Focused application set to: xxxx
,08-23 15:43:20.439  6288  6288 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-23 15:43:20.449  6288  6288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:43:20.449  5479  5479 E MTPRx   : started activity for popup
,08-23 15:43:20.449  6288  6288 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 15:43:20.469  6288  6288 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-23 15:43:20.469  6288  6288 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-23 15:43:20.469  6288  6288 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-23 15:43:20.469  6288  6288 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:20.469  6288  6288 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:20.469  6288  6288 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:20.469  6288  6288 I Adreno-EGL: Local Branch: 
08-23 15:43:20.469  6288  6288 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:20.469  6288  6288 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:20.469  6288  6288 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:20.579  6288  6314 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-23 15:43:20.619  6288  6288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:43:20.639  6288  6288 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 15:43:20.649  6288  6288 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 15:43:20.649  6288  6288 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 15:43:20.649  6288  6288 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 15:43:20.659  6288  6288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:43:20.659  6288  6288 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 15:43:20.709  6288  6327 D OpenGLRenderer: Render dirty regions requested: true
,08-23 15:43:20.709  1016  1475 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:20.709  1016  1475 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:20.709  1016  1475 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:20.709  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:20.709  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:20.719  1016  3213 D PersonaManager: isKioskContainerExistOnDevice,
,08-23 15:43:20.739  6288  6288 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 15:43:20.739  6288  6288 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 15:43:20.749   258   258 I SurfaceFlinger: id=14 createSurf (720x1280),1 flag=404, NainActivit
,08-23 15:43:20.759  6288  6288 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 15:43:20.759  6288  6327 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 15:43:20.759  5479  5479 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 15:43:20.759  6288  6327 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
08-23 15:43:20.759  6288  6327 D OpenGLRenderer: Enabling debug mode 0
,08-23 15:43:20.799  6288  6288 V ActivityThread: updateVisibility : ActivityRecord{11fa113 token=android.os.BinderProxy@30c5314d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 15:43:20.809  5479  5479 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-23 15:43:20.809  1016  1547 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-23 15:43:20.809  1016  1547 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 15:43:20.809  1016  1547 D InputDispatcher: Focused application set to: xxxx
08-23 15:43:20.809  1016  1547 D InputDispatcher: Focus entered window: 6288
,08-23 15:43:20.819  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 15:43:20.819  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:20.839  1016  1046 I ActivityManager: Displayed Component not be shown by security: +582ms (total +661ms)
,08-23 15:43:20.839  1016  1046 W ActivityManager: mDVFSHelper.release()
,08-23 15:43:20.839  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{c6f552 u0 com.test.thalitest/.MainActivity t128} time:114704
,08-23 15:43:20.839   258   802 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,08-23 15:43:20.849  1016  1547 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 15:43:20.849  1176  1176 D PanelView: There is/are notification(s) 
,08-23 15:43:20.849  6288  6288 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30c5314d time:114717
,08-23 15:43:20.849  1016  6332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:20.859  6288  6288 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 15:43:20.859  1780  1780 I SamsungIME: getCurrentCandidateView
,08-23 15:43:20.869  5479  5479 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-23 15:43:20.889  5479  5479 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-23 15:43:20.889  5479  5479 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-23 15:43:20.899  1016  1475 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:20.909  1016  2930 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:20.909  1016  2930 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:20.909  1016  2930 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:20.909  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 15:43:20.909  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 15:43:20.929  6288  6288 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6288
,08-23 15:43:20.929  6288  6288 V ActivityThread: updateVisibility : ActivityRecord{11fa113 token=android.os.BinderProxy@30c5314d {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 15:43:20.929  6288  6288 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30c5314d time:114795
,08-23 15:43:20.929  1016  2929 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:20.959  1780  1780 D SamsungIME: Dismiss ExpandCandiate
,08-23 15:43:21.079  6288  6288 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 15:43:21.089  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:21.129  1780  1780 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 15:43:21.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:21.139  1780  1780 I SamsungIME: KeybaordView init() : load resources
,08-23 15:43:21.169  1780  1780 I SamsungIME: getCurrentKeyboard
08-23 15:43:21.169  1780  1780 I SamsungIME: getTextKeyboard
,08-23 15:43:21.169  6288  6331 D jxcore_app_log: JniHelper::setJavaVM(0xb7e1f328), pthread_self() = -1204258872
,08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 15:43:21.179  1780  1780 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 15:43:21.179  6288  6331 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@782f503 added. We now have 1 listener(s)
,08-23 15:43:21.189  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-23 15:43:21.189  6288  6331 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-23 15:43:21.189  6288  6331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-23 15:43:21.189  6288  6331 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 15:43:21.199  6288  6331 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50096fe added. We now have 1 listener(s)
,08-23 15:43:21.199  6288  6331 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 15:43:21.199  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 15:43:21.199  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 15:43:21.199  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 15:43:21.199  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 15:43:21.199  6288  6331 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 15:43:21.209  6288  6331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 15:43:21.209  6288  6331 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-23 15:43:21.219  6288  6331 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:21.219  6288  6331 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 15:43:21.219  6288  6331 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 15:43:21.219  6288  6331 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 15:43:21.219  6288  6331 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 15:43:21.219  6288  6288 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:21.229  6288  6288 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 15:43:21.259  6288  6288 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 15:43:21.719  1780  6338 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 15:43:21.789  6288  6342 W jxcore-log: Initializing JXcore engine
08-23 15:43:21.789  6288  6342 W jxcore-log: JXcore engine is ready
,08-23 15:43:21.839  1892  1892 E audit   : type=1400 msg=audit(1471959801.839:205): avc:  denied  { ioctl } for  pid=6342 comm="Thread-1079" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 15:43:21.839  1892  1892 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:21.839  1892  1892 E audit   : type=1300 msg=audit(1471959801.839:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9eec28f8 items=0 ppid=304 ppcomm=main pid=6342 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1079" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 15:43:21.839  1892  1892 E audit   : type=1320 msg=audit(1471959801.839:205): 
,08-23 15:43:21.849  6288  6342 W jxcore-log: Starting JXcore engine
,08-23 15:43:21.959  6288  6342 W jxcore-log: Platform android,
08-23 15:43:21.959  6288  6342 W jxcore-log: 
08-23 15:43:21.959  6288  6342 W jxcore-log: Process ARCH arm
08-23 15:43:21.959  6288  6342 W jxcore-log: 
,08-23 15:43:22.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:22.149   288   288 E SMD     : DCD OFF
,08-23 15:43:22.159  6288  6342 I jxcore-log: JXcore Cordova bridge is ready!
08-23 15:43:22.159  6288  6342 I jxcore-log: 
,08-23 15:43:22.159  6288  6342 W jxcore-log: JXcore engine is started
,08-23 15:43:22.169  6288  6331 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 15:43:22.169  6288  6288 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 15:43:22.189  1016  1217 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:22.189  1016  1217 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4180, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-23 15:43:22.189  1016  1217 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 15:43:22.189  1016  1217 D BatteryService: stay LED for charging
,08-23 15:43:22.189  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:22.189  1016  1016 I MotionRecognitionService: Plugged
,08-23 15:43:22.189  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 15:43:22.189  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 15:43:22.199  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 15:43:22.199  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-23 15:43:22.199  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-23 15:43:22.209  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:22.209  2649  2763 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:22.219  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:22.219  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:22.219  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:22.549  1016  2761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-23 15:43:23.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:23.899  1016  1041 W ActivityManager: mDVFSHelper.release(),
,08-23 15:43:24.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:24.269  1016  2735 D SSRM:n  : SIOP:: AP = 310
,08-23 15:43:25.139   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-23 15:43:25.149   288   288 E SMD     : DCD OFF,
,08-23 15:43:26.139  1016  1094 V AlarmManager: waitForAlarm result :4
,08-23 15:43:26.149  1016  1094 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.159  1909  1909 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-23 15:43:26.189  1016  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:26.189  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.189  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.199  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.199  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.259  3835  3835 D ConnectivityManager: CallingUid : 10012, CallingPid : 3835
,08-23 15:43:26.269  1016  1475 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-23 15:43:26.269  3835  6347 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-23 15:43:26.269  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
08-23 15:43:26.269  1016  1128 D ConnectivityService: apparently satisfied.  currentScore=60
08-23 15:43:26.269  1016  1128 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-23 15:43:26.329  3835  6348 W DriveInitializer: Background init thread started
,08-23 15:43:26.359   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-23 15:43:26.359   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 15:43:26.359  3835  6348 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-23 15:43:26.409  1016  2930 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:26.409  1016  2930 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.409  1016  2930 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.409  1016  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.409  1016  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.449  1016  1382 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-23 15:43:26.449  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.449  1016  1547 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 15:43:26.449  1016  1547 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.459  1016  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.459  1016  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.459  1016  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.459  3835  6348 W DriveInitializer: Background init thread ended
,08-23 15:43:26.479  3835  6356 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
08-23 15:43:26.479  3835  6356 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-23 15:43:26.499  1909  1909 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:26.549  1016  1041 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.549  1016  1041 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:26.549  1016  1041 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.599  1016  1475 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:26.599  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.599  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.609  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.609  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.639  1016  1217 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:26.639  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-23 15:43:26.639  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:26.639  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.639  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.689  1016  1094 V AlarmManager: waitForAlarm result :4
,08-23 15:43:26.689  1016  1382 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:26.699  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.699  1016  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.699  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.749  1016  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:26.759  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.759  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.759  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.789  1016  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:26.799  1016  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:26.799  1016  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:26.799  1016  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:26.799  1016  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:26.799  1016  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:26.799  1016  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:26.799  1016  1138 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:26.809  6361  6361 E Zygote  : MountEmulatedStorage()
,08-23 15:43:26.809  6361  6361 E Zygote  : v2
,08-23 15:43:26.809  6361  6361 I libpersona: KNOX_SDCARD checking this for 10012
08-23 15:43:26.809  6361  6361 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:26.809  1016  1138 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6361 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
08-23 15:43:26.819  6361  6361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:26.819  6361  6361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-23 15:43:26.819  6361  6361 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:26.839  6361  6361 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:26.839  6361  6361 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:26.859  6361  6361 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-23 15:43:26.859  6361  6361 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-23 15:43:26.899  6361  6361 I MultiDex: VM with version 2.1.0 has multidex support
08-23 15:43:26.899  6361  6361 I MultiDex: install
08-23 15:43:26.899  6361  6361 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-23 15:43:26.929  6361  6361 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-23 15:43:26.989  6361  6361 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-23 15:43:26.989  6361  6361 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a395a2d: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-23 15:43:26.989  6361  6361 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-23 15:43:27.009  1016  3210 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.009  6361  6361 D ChimeraCfgMgr: Reading stored module config
08-23 15:43:27.009  1016  1138 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.019  1016  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.019  1016  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.019  1016  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.029  1016  1475 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.029  1016  1475 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.029  1016  1475 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.029  1016  1475 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.099  6361  6375 I art     : Background sticky concurrent mark sweep GC freed 21716(1113KB) AllocSpace objects, 3(133KB) LOS objects, 6% free, 10MB/11MB, paused 9.025ms total 62.516ms
,08-23 15:43:27.109  6361  6379 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-23 15:43:27.119  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 15:43:27.129  6361  6361 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-23 15:43:27.159  1909  2112 I art     : Explicit concurrent mark sweep GC freed 59209(3MB) AllocSpace objects, 16(640KB) LOS objects, 39% free, 14MB/23MB, paused 1.515ms total 98.513ms
,08-23 15:43:27.169  1909  1909 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=cce5e218-d202-4213-8188-0c55f0dcf3d6
,08-23 15:43:27.179  1016  1138 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-23 15:43:27.179  1016  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 15:43:27.179  1016  1138 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.179  1016  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.179  1016  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.189  1909  1909 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:27.189  1909  1909 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-23 15:43:27.199  1016  1382 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.199  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.199  1016  1382 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:27.199  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.249   283   698 D WVCdm   : Instantiating CDM.
,08-23 15:43:27.259   283   723 I WVCdm   : CdmEngine::OpenSession,
08-23 15:43:27.259   283   723 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-23 15:43:27.289   283   723 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-23 15:43:27.309   283   723 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
08-23 15:43:27.309   283   723 D DrmWidevineDash: Service_Initialize: starts!
08-23 15:43:27.309   283   723 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-23 15:43:27.309   283   723 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 15:43:27.309   283   723 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-23 15:43:27.309   283   723 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 15:43:27.309   283   723 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 15:43:27.309   283   723 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 15:43:27.309   283   723 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-23 15:43:27.309   283   723 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-23 15:43:27.309   283   723 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-23 15:43:27.309   283   723 D QSEECOMAPI: : App is not loaded in QSEE
,08-23 15:43:27.329   283   723 D QSEECOMAPI: : Loaded image: APP id = 11
,08-23 15:43:27.329   283   723 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-23 15:43:27.339   283   723 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
,08-23 15:43:27.339   283   723 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-23 15:43:27.339   283   723 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb172c000
08-23 15:43:27.339   283   723 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb172c000
08-23 15:43:27.339   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.339   425   436 D DrmLibTime: got the req here! ret=0
08-23 15:43:27.339   425   436 D DrmLibTime: command id, time_cmd_id = 770
08-23 15:43:27.339   425   436 D DrmLibTime: time_getutcsec starts!
08-23 15:43:27.339   425   436 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-23 15:43:27.339   425   436 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-23 15:43:27.339   425   436 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-23 15:43:27.339   425   436 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-23 15:43:27.349   425   436 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-23 15:43:27.349   425   436 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-23 15:43:27.349   425   436 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,08-23 15:43:27.349   425   436 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
,08-23 15:43:27.349   318   427 D QC-time-services: Daemon: Connection accepted:time_genoff
08-23 15:43:27.349   318  6386 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0,
08-23 15:43:27.349   318  6386 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2,
08-23 15:43:27.349   318  6386 D QC-time-services: offset is: 0 for base: 0
08-23 15:43:27.349   425   436 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-23 15:43:27.349   425   436 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,08-23 15:43:27.349   425   436 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1471959807
08-23 15:43:27.349   425   436 D DrmLibTime: time_getutcsec returns 0, sec = 1471959807; nsec = 0
08-23 15:43:27.349   425   436 D DrmLibTime: time_getutcsec finished! 
08-23 15:43:27.349   425   436 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-23 15:43:27.349   425   436 D DrmLibTime: before calling ioctl to read the next time_cmd
08-23 15:43:27.349   318   427 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-23 15:43:27.349   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 15:43:27.359   283   723 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-23 15:43:27.359   283   723 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 15:43:27.359   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 15:43:27.359   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 15:43:27.359   283   723 D DrmWidevineDash: hlos api version =  9
08-23 15:43:27.359   283   723 D DrmWidevineDash: tz api version =  9
,08-23 15:43:27.369   283   723 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 15:43:27.369   283   723 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-23 15:43:27.369   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-23 15:43:27.389   283   723 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb170b960
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb811bd28, dataLength=8
08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb80aaf48, wrapped_rsa_key_length=1280
08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.389   283   723 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 15:43:27.389   283   723 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-23 15:43:27.389   283   723 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-23 15:43:27.389   283   698 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-23 15:43:27.389   283   698 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-23 15:43:27.389   283   698 I WVCdm   : CdmEngine::GenerateKeyRequest
08-23 15:43:27.389   283   698 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb80c79f0, idLength=0xb1932730
08-23 15:43:27.389   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.399  1647  4325 I art     : Explicit concurrent mark sweep GC freed 1436(49KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 728us total 28.492ms
,08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1932746, maximum = 0xb1932747
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: hlos api version =  9
08-23 15:43:27.409   283   698 D DrmWidevineDash: tz api version =  9
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb19327b4
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-23 15:43:27.409   283   698 D WVCdm   : PrepareKeyRequest: nonce=1789539187
08-23 15:43:27.409   283   698 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb80c66d0
,08-23 15:43:27.409   283   698 D DrmWidevineDash: message_length=1599, signature=0xb811a238, signature_length=0xb1932714
08-23 15:43:27.409   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.419  6361  6372 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
08-23 15:43:27.419  6361  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 15:43:27.419  6361  6372 I System.out: (HTTPLog)-Static: isShipBuild true
08-23 15:43:27.419  6361  6372 I System.out: (HTTPLog)-Thread-1060-229020294: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-23 15:43:27.419  6361  6372 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:27.419   278   982 D EnterpriseController: uids 10012
08-23 15:43:27.419   278   982 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 15:43:27.419   278   982 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 15:43:27.419  6361  6372 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:27.419  6361  6372 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6361, getuid(): 10012
,08-23 15:43:27.469  1909  2097 W GCoreFlp: No location to return for getLastLocation()
,08-23 15:43:27.499  1016  1028 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.499  1016  1028 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.499  1016  1028 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.499  1016  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.499  1016  2930 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.499  1016  2930 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.499  1016  2930 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.499  1016  2930 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.509  1909  2109 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:27.509  1016  1547 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.519  1016  1547 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.519  1016  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.519  1016  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.529  1909  2115 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-23 15:43:27.549  3835  6357 D UdcContextInitService: registered all accounts: true
,08-23 15:43:27.569   283   698 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.569   283   698 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-23 15:43:27.579   283   283 I WVCdm   : CdmEngine::CloseSession
,08-23 15:43:27.579   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
08-23 15:43:27.579   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-23 15:43:27.579   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.579   283   283 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-23 15:43:27.579   283   283 I WVCdm   : L3 Terminate.
08-23 15:43:27.579   283   283 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-23 15:43:27.579   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-23 15:43:27.579   283   283 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-23 15:43:27.579   283   283 D DrmWidevineDash: Service_Uninitialize: starts!
08-23 15:43:27.579   283   283 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-23 15:43:27.579   283   283 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
08-23 15:43:27.579   283   283 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-23 15:43:27.579   283   283 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-23 15:43:27.669  1016  3213 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-23 15:43:27.669  1016  3213 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-23 15:43:27.669  1016  3213 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.669  1016  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.669  1016  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.709  1016  1138 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 15:43:27.709  1016  1138 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-23 15:43:27.709  1016  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.709  1016  1138 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-23 15:43:27.709  1016  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.739  6361  6372 I qtaguid : Untagging socket 30
,08-23 15:43:27.939  1016  1029 I art     : Explicit concurrent mark sweep GC freed 34527(1823KB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 27MB/41MB, paused 2.618ms total 150.223ms
08-23 15:43:27.939  1016  1029 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.939  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:27.939  1016  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.939  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:27.979  1016  3213 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:27.979  1016  3213 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:27.979  1016  3213 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:27.979  1016  3213 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.029  1016  3210 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.029  1016  3210 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.029  1016  3210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.029  1016  3210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.029  1909  6394 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 15:43:28.029  1909  6392 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-23 15:43:28.029  1016  3209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.029  1016  3209 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.029  1016  3209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.029  1016  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.059  1016  1547 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.059  1016  1547 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.059  1016  1547 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.059  1016  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 15:43:28.059  1909  6394 E CommitToConfigurationOperation: Malformed snapshot token (size): 
08-23 15:43:28.059  1909  6392 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-23 15:43:28.059  1016  1217 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 15:43:28.059  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:28.059  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.069  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.089  1016  3209 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 15:43:28.089  1016  3209 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.089  1016  3209 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.089  1016  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.089  1909  6394 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-23 15:43:28.089  1909  6392 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
08-23 15:43:28.089  1909  6392 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-23 15:43:28.109  1909  6392 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 15:43:28.149   288   288 E SMD     : DCD OFF
,08-23 15:43:28.169  1016  1382 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:28.209  1016  3210 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-23 15:43:28.209  1016  3210 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-23 15:43:28.209  1016  3210 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:28.209  1016  3210 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:28.209  1016  3210 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 15:43:28.219  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.219   278   982 D EnterpriseController: uids 10012
08-23 15:43:28.219   278   982 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 15:43:28.219   278   982 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 15:43:28.219  1909  6392 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:28.219  1909  6392 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:28.269  1909  6392 I qtaguid : Tagging socket 80 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:28.369  6397  6397 I dex2oat : ----------------------------------------------------
08-23 15:43:28.369  6397  6397 I dex2oat : <SS>: S T A R T I N G . . .
08-23 15:43:28.369  6397  6397 I dex2oat : <SS>: Zip is absent. Canceled.
,08-23 15:43:28.369  6397  6397 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-23 15:43:28.409  6397  6397 I dex2oat : dex2oat took 33.140ms (threads: 4)
,08-23 15:43:28.419  6361  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:28.419  6361  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:28.419  6361  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:28.419  6361  6372 I Adreno-EGL: Local Branch: 
08-23 15:43:28.419  6361  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:28.419  6361  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:28.419  6361  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:28.499  6361  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:28.499  6361  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:28.499  6361  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:28.499  6361  6372 I Adreno-EGL: Local Branch: 
08-23 15:43:28.499  6361  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:28.499  6361  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:28.499  6361  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:28.559  1016  1345 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:28.569  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.569  1909  6392 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:28.709  1016  1502 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:28.719  6361  6372 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 15:43:28.719  6361  6372 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 15:43:28.719  6361  6372 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 15:43:28.719  6361  6372 I Adreno-EGL: Local Branch: 
08-23 15:43:28.719  6361  6372 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 15:43:28.719  6361  6372 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 15:43:28.719  6361  6372 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 15:43:28.749  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.759   278   982 D EnterpriseController: uids 10012
08-23 15:43:28.759   278   982 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 15:43:28.759   278   982 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-23 15:43:28.759  1909  6392 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:28.759  1909  6392 I qtaguid : Tagging socket 74 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:28.779  1909  6392 I qtaguid : Tagging socket 83 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:28.789  1909  6359 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.789  1909  6359 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:28.789  1909  6359 I qtaguid : Tagging socket 84 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:28.819  1909  6359 I qtaguid : Tagging socket 87 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:28.969  1909  2115 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-23 15:43:28.969  1909  2115 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-23 15:43:28.979  1909  2115 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-23 15:43:27.626+0200, stopTime=2016-08-23 15:43:28.993+0200, duration=1367ms
,08-23 15:43:28.979  1909  6406 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:28.989  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-23 15:43:28.989   278   982 D EnterpriseController: uids 10012
08-23 15:43:28.989   278   982 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-23 15:43:28.989   278   982 D Netd    : getNetworkForDns: using netid 502 for uid 10012
08-23 15:43:28.989  1909  6392 I qtaguid : Tagging socket 77 with tag fffffca200000000{4294966434,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:28.989  1909  6406 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-23 15:43:28.989  1909  6406 I qtaguid : Tagging socket 90 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:29.019  1909  6406 I qtaguid : Tagging socket 91 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:29.039  1016  3210 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 15:43:29.149  1016  2930 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:29.159  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:29.159  1909  6392 I qtaguid : Tagging socket 77 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:29.229  1909  6406 I qtaguid : Untagging socket 90
,08-23 15:43:29.239  1909  2115 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-23 15:43:29.299  1016  1502 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:29.309  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:29.309  1909  6392 I qtaguid : Tagging socket 77 with tag 1106583100000000{285628465,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:29.439  1016  1138 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:29.449  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:29.449  1909  6392 I qtaguid : Tagging socket 77 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:29.589  1016  3209 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-23 15:43:29.609  1909  6392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:29.609  1909  6392 I qtaguid : Tagging socket 77 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1909, getuid(): 10012
,08-23 15:43:30.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:30.229  1016  1056 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-23 15:43:31.099  1909  6408 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-23 15:43:31.099  1909  6408 I qtaguid : Tagging socket 90 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1909, getuid(): 10012
,08-23 15:43:31.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:31.149   288   288 E SMD     : DCD OFF
,08-23 15:43:31.329  1909  6408 I qtaguid : Untagging socket 90
,08-23 15:43:31.339  1909  2115 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-23 15:43:31.349  1016  1475 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-23 15:43:32.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:32.249  1016  1345 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
08-23 15:43:32.249  1016  1345 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4182, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 15:43:32.249  1016  1345 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-23 15:43:32.249  1016  1345 D BatteryService: stay LED for charging
,08-23 15:43:32.249  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:32.259  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 15:43:32.259  1016  1016 I MotionRecognitionService: Plugged
08-23 15:43:32.259  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
08-23 15:43:32.259  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-23 15:43:32.259  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:32.259  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
,08-23 15:43:32.269  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 15:43:32.269  2649  2763 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:32.279  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:32.279  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:32.279  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:33.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:33.779  1016  1502 I ActivityManager: Killing 5399:com.google.android.talk/u0a104 (adj 15): empty #31
,08-23 15:43:33.999  1016  1048 I PowerManagerService: [PWL] Off : 50s ago
,08-23 15:43:34.139   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:34.149   288   288 E SMD     : DCD OFF
,08-23 15:43:34.289  1016  2735 D SSRM:n  : SIOP:: AP = 330
,08-23 15:43:35.139   316   316 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-23 15:43:36.389  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-23 15:43:36.389  6288  6342 I jxcore-log: 
,08-23 15:43:37.159   288   288 E SMD     : DCD OFF
,08-23 15:43:38.579  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-23 15:43:38.579  6288  6342 I jxcore-log: 
,08-23 15:43:38.609  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js,
08-23 15:43:38.609  6288  6342 I jxcore-log: 
,08-23 15:43:38.629  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js,
08-23 15:43:38.629  6288  6342 I jxcore-log: 
,08-23 15:43:38.659  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js,
08-23 15:43:38.659  6288  6342 I jxcore-log: 
,08-23 15:43:38.669  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js,
08-23 15:43:38.669  6288  6342 I jxcore-log: 
,08-23 15:43:40.159   288   288 E SMD     : DCD OFF,
,08-23 15:43:42.299  1016  1547 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 15:43:42.299  1016  1547 D BatteryService: level:93, scale:100, status:2, health:2, present:true, voltage: 4200, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-23 15:43:42.299  1016  1547 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-23 15:43:42.309  1016  1547 D BatteryService: stay LED for charging
08-23 15:43:42.309  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 15:43:42.309  1016  1016 I MotionRecognitionService: Plugged
08-23 15:43:42.309  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
08-23 15:43:42.309  1415  1415 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 15:43:42.309  1415  1415 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 93
08-23 15:43:42.309  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-23 15:43:42.309  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 15:43:42.329  2649  2649 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-23 15:43:42.329  2649  2763 D HeadsetStateMachine: Disconnected process message: 10
,08-23 15:43:42.339  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:42.339  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
08-23 15:43:42.339  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:93 status:2 health:2
,08-23 15:43:42.349  6288  6342 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-23 15:43:42.349  6288  6342 I jxcore-log: 
,08-23 15:43:42.349  6288  6342 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-23 15:43:42.349  6288  6342 I jxcore-log: 
,08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 15:43:42.359  6288  6342 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-23 15:43:42.359  6288  6342 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-23 15:43:42.359  6288  6342 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-23 15:43:42.359  6288  6342 I jxcore-log: 
,08-23 15:43:42.359  6288  6342 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-23 15:43:42.359  6288  6342 I jxcore-log: 
,08-23 15:43:42.549  1016  2761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:43.159   288   288 E SMD     : DCD OFF,
,08-23 15:43:44.309  1016  2735 D SSRM:n  : SIOP:: AP = 330
,08-23 15:43:44.579  1016  1324 E Watchdog: !@Sync 4
,08-23 15:43:45.149   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:46.149   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,08-23 15:43:46.159   288   288 E SMD     : DCD OFF,
,08-23 15:43:47.029  6288  6342 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-23 15:43:47.029  6288  6342 I jxcore-log: 
,08-23 15:43:47.149   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:47.189  6288  6342 I jxcore-log: ERROR runTests: ,
08-23 15:43:47.189  6288  6342 I jxcore-log: 
,08-23 15:43:47.189  6288  6342 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie',
08-23 15:43:47.189  6288  6342 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-23 15:43:47.189  6288  6342 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-23 15:43:47.189  6288  6342 I jxcore-log: 
,08-23 15:43:47.199  6288  6288 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\nError: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js: Error: Cannot find module 'thali/NextGeneration/thaliMoblie'\n    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7\n    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 15:43:47.199  6288  6288 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 15:43:47.199  1016  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:47.199  1016  1345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
08-23 15:43:47.199  1016  1345 D InputDispatcher: Focused application set to: xxxx
,08-23 15:43:47.209  1016  1345 I ActivityManager: Killing 5111:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-23 15:43:47.209  6288  6288 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 15:43:47.209  6288  6288 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 15:43:47.209  6288  6288 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 15:43:47.209  6288  6288 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 15:43:47.209  6288  6288 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 15:43:47.209  6288  6288 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 15:43:47.209  6288  6288 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@782f503 removed from the list
08-23 15:43:47.209  6288  6288 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 15:43:47.209  6288  6288 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@50096fe removed from the list
08-23 15:43:47.209  6288  6288 D io.jxcore.node.ConnectivityMonitor: stop
08-23 15:43:47.209  6288  6288 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 15:43:47.209  6288  6288 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 15:43:47.239   258   802 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
,08-23 15:43:47.239   258   448 I SurfaceFlinger: id=14 Removed NainActivit (-2/8)
,08-23 15:43:47.239  1016  2734 D InputDispatcher: Focus left window: 6288
,08-23 15:43:47.249  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:47.249  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:47.259  6288  6288 E ViewRootImpl: sendUserActionEvent() mView == null
,08-23 15:43:47.259  1016  3210 W ActivityManager: mDVFSHelper.acquire()
,08-23 15:43:47.289  3247  3247 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,08-23 15:43:47.309  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 4
,08-23 15:43:47.319  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-23 15:43:47.339  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-23 15:43:47.339  3247  3247 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 4
,08-23 15:43:47.349  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,08-23 15:43:47.349  3247  3247 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,08-23 15:43:47.359  3247  3247 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,08-23 15:43:47.359  1016  1041 W ProcessCpuTracker: Skipping unknown process pid 6420
,08-23 15:43:47.369  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,08-23 15:43:47.379  1016  1217 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,08-23 15:43:47.379  1016  1217 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,08-23 15:43:47.379  1016  1016 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,08-23 15:43:47.389  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,08-23 15:43:47.389  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 4
,08-23 15:43:47.389  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:47.389  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:47.389  1176  1176 D PanelView: There is/are notification(s) 
08-23 15:43:47.389  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-23 15:43:47.399  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:47.399  1176  1176 D PanelView: There is/are notification(s) 
08-23 15:43:47.399  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,08-23 15:43:47.399  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,08-23 15:43:47.409  3247  3247 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,08-23 15:43:47.409  3247  3247 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,08-23 15:43:47.409  3247  3247 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
08-23 15:43:47.409  3247  3247 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
08-23 15:43:47.409  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 15:43:47.409  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 15:43:47.409  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 15:43:47.409  3247  3247 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
08-23 15:43:47.409  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 15:43:47.409  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 15:43:47.419   258   258 I SurfaceFlinger: id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,08-23 15:43:47.419  1016  1044 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-23 15:43:47.419  1016  3212 D InputDispatcher: Focus entered window: 3247
,08-23 15:43:47.419  1016  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 15:43:47.419  1016  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 15:43:47.419  3247  3247 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 15:43:47.429  3247  3247 V ActivityThread: updateVisibility : ActivityRecord{22ca068c token=android.os.BinderProxy@156618d3 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,08-23 15:43:47.439  1016  3210 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 15:43:47.439  6288  6288 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-23 15:43:47.439  1176  1176 D PanelView: There is/are notification(s) 
,08-23 15:43:47.449  1780  1780 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 15:43:47.449  1016  6424 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 15:43:47.459  3247  3247 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@156618d3 time:141322
,08-23 15:43:47.469  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,08-23 15:43:47.479  6418  6418 D AndroidRuntime: 
08-23 15:43:47.479  6418  6418 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 15:43:47.479  1016  1046 W ActivityManager: mDVFSHelper.release()
08-23 15:43:47.479  1016  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39641d66 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:141343
,08-23 15:43:47.479  6418  6418 D AndroidRuntime: CheckJNI is OFF
,08-23 15:43:47.479  6418  6418 D AndroidRuntime: readGMSProperty: start
08-23 15:43:47.479  6418  6418 D AndroidRuntime: readGMSProperty: already setted!!
08-23 15:43:47.479  6418  6418 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 15:43:47.479  6418  6418 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 15:43:47.479  6418  6418 D AndroidRuntime: readGMSProperty: end
08-23 15:43:47.479  6418  6418 D AndroidRuntime: addProductProperty: start
,08-23 15:43:47.609  6418  6418 E AffinityControl: AffinityControl: registerfunction enter,
,08-23 15:43:47.629  6418  6418 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-23 15:43:47.649  1016  1547 D PackageManager: START PACKAGE DELETE: observer{735077024},
08-23 15:43:47.649  1016  1547 D PackageManager: pkg{<packageName>}
08-23 15:43:47.649  1016  1547 D PackageManager: user{0}
08-23 15:43:47.649  1016  1547 D PackageManager: caller{2000}
08-23 15:43:47.649  1016  1547 D PackageManager: flags{2}
08-23 15:43:47.649  1016  1547 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 15:43:47.649  1016  1547 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 15:43:47.649  1016  1547 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 15:43:47.649  1016  1547 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 15:43:47.649  1016  1547 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 15:43:47.649  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 15:43:47.649  1016  1056 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 15:43:47.649  1016  1056 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 15:43:47.649  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 15:43:47.649  1016  1056 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
08-23 15:43:47.649  1016  1056 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,08-23 15:43:47.659  1016  1041 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-23 15:43:47.659  1016  1041 I ActivityManager: Killing 6288:com.test.thalitest/u0a155 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-23 15:43:47.659  1016  1041 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:47.799  1016  1056 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,08-23 15:43:47.829  1016  1056 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 15:43:47.839  5846  5846 I art     : Explicit concurrent mark sweep GC freed 663(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 789us total 28.779ms
08-23 15:43:47.839  5732  5732 I art     : Explicit concurrent mark sweep GC freed 1964(113KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 819us total 29.470ms
,08-23 15:43:47.849  5521  5521 I art     : Explicit concurrent mark sweep GC freed 389(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 877us total 46.400ms
,08-23 15:43:47.879  1780  1780 E SamsungIME: mOCRHelper is null
,08-23 15:43:47.879  1909  2109 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 15:43:47.899  3657  3657 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 15:43:47 GMT+02:00 2016
,08-23 15:43:47.909  1016  1097 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 15:43:47.909  3835  3835 I art     : Explicit concurrent mark sweep GC freed 23251(1410KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 15MB/21MB, paused 1.884ms total 106.211ms
,08-23 15:43:47.929  1016  1123 V NetworkStats: removeUidsLocked() for UIDs [10155]
,08-23 15:43:47.939  1016  1123 V NetworkStats: performPollLocked(flags=0x3)
,08-23 15:43:47.939  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
08-23 15:43:47.939  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:47.939  1016  1502 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 15:43:47.939  1016  1502 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 15:43:47.939  1016  1502 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:47.939  1016  1502 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:47.939  1016  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 15:43:47.949  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 15:43:47.949  1016  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 15:43:47.949  1438  1438 D RegisteredServicesCache: empty dynamic service
,08-23 15:43:47.949  1016  1040 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 15:43:47.949  1016  1040 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-23 15:43:47.949  1016  1040 W TextServicesManagerService: no available spell checker services found
,08-23 15:43:47.949  1016  1123 V NetworkStats: performPollLocked() took 18ms
08-23 15:43:47.949  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:47.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:47.959  1016  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 15:43:47.959  3657  3657 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-23 15:43:47.959  1016  2930 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,08-23 15:43:47.959  1016  2930 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 15:43:47.969  1016  2930 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-23 15:43:47.969  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.969  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.969  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.969  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:47.989  6436  6436 E Zygote  : MountEmulatedStorage()
08-23 15:43:47.989  6436  6436 E Zygote  : v2
08-23 15:43:47.989  6436  6436 I libpersona: KNOX_SDCARD checking this for 10094
08-23 15:43:47.989  6436  6436 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:47.989  6436  6436 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:47.999  6436  6436 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-23 15:43:47.999  6436  6436 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 15:43:47.999  1016  2930 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6436 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-23 15:43:47.999  3657  3657 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-23 15:43:48.009  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 15:43:48.009  3657  3657 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 15:43:48.009  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.009  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.009  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.009  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.019  1016  1382 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 15:43:48.019  1016  1382 D SecContentProvider2: mCursor = null
,08-23 15:43:48.029  6449  6449 E Zygote  : MountEmulatedStorage(),
08-23 15:43:48.029  6449  6449 E Zygote  : v2
08-23 15:43:48.029  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.029  6449  6449 I libpersona: KNOX_SDCARD checking this for 10044
08-23 15:43:48.029  6449  6449 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.029  6449  6449 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.029  6449  6449 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-23 15:43:48.029  6449  6449 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-23 15:43:48.029  1016  1041 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6449 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-23 15:43:48.039  1016  1041 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,08-23 15:43:48.039  6436  6436 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.039  6436  6436 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.039  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.039  3657  3657 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-23 15:43:48.039  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.039  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.039  1016  1041 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.049  6461  6461 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.049  6461  6461 E Zygote  : v2
08-23 15:43:48.049  6461  6461 I libpersona: KNOX_SDCARD checking this for 10149
08-23 15:43:48.049  6461  6461 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.059  6461  6461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.059  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.059  6461  6461 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:48.059  1016  1041 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6461 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 15:43:48.059  6449  6449 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.059  6449  6449 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.059  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.059  6461  6461 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.069  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
08-23 15:43:48.069  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 15:43:48.069  1016  1016 I art     : Explicit concurrent mark sweep GC freed 39428(3MB) AllocSpace objects, 15(240KB) LOS objects, 33% free, 27MB/41MB, paused 4.665ms total 247.200ms
,08-23 15:43:48.069  1016  1056 I art     : WaitForGcToComplete blocked for 148.137ms for cause Explicit
,08-23 15:43:48.079  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 15:43:48.079  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-23 15:43:48.089  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-23 15:43:48.099  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,08-23 15:43:48.099  6461  6461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.099  6461  6461 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.119  6449  6449 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-23 15:43:48.129  6449  6449 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 15:43:48.139  5846  6459 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched),
,08-23 15:43:48.149   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,08-23 15:43:48.159  5846  5846 I art     : Explicit concurrent mark sweep GC freed 621(35KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 748us total 42.248ms
,08-23 15:43:48.169  6436  6436 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 15:43:48.179  6005  6016 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-23 15:43:48.179  6005  6016 D BadgeProvider: sendNotify, [notify] : null
08-23 15:43:48.179  6005  6016 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-23 15:43:48.179  6005  6016 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-23 15:43:48.179  6005  6016 D BadgeProvider: update, [UpdateCount] : 1
,08-23 15:43:48.179  6436  6436 D elm:15183: ELMEngine.ELMEngine( context ).
,08-23 15:43:48.179  6436  6436 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-23 15:43:48.209  6461  6461 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-23 15:43:48.209  6461  6461 D ThemeInfoUtil: isCurrentFestival = false
,08-23 15:43:48.219  1016  1138 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 15:43:48.219  1016  1138 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.219  1016  1138 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:48.219  1016  1138 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 15:43:48.219  1016  1138 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,08-23 15:43:48.229  1016  1547 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-23 15:43:48.229  1016  1547 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.229  6436  6436 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 15:43:48.229  1016  1547 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.229  1016  1547 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.229  1016  1547 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-23 15:43:48.239  6436  6436 D elm:15183: ElmAgentService : onCreate()
,08-23 15:43:48.239  6436  6482 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-23 15:43:48.239  6436  6482 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-23 15:43:48.239  6436  6482 D elm:15183: MDMBridge.getInstance()
08-23 15:43:48.239  6436  6482 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:48.239  3310  3310 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-23 15:43:48.239  6436  6482 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 15:43:48.239  3310  3310 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 15:43:48.239  3310  3310 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-23 15:43:48.239  3310  3310 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-23 15:43:48.239  3310  3310 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 15:43:48.239  3310  3310 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 15:43:48.239  3310  3310 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 15:43:48.239  3310  3310 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 15:43:48.239  3310  3310 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-23 15:43:48.249  5948  5948 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
08-23 15:43:48.249  5948  5948 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
08-23 15:43:48.249  5948  5948 I TapandpayWidget:Utils: Clear T&P info.
08-23 15:43:48.249  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
08-23 15:43:48.269  5162  5162 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
08-23 15:43:48.269  5948  5948 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
08-23 15:43:48.279  1016  3212 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-23 15:43:48.279  1016  3212 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-23 15:43:48.279  1016  3212 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.279  1016  3212 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.279  1016  3212 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-23 15:43:48.289  3657  6435 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
08-23 15:43:48.289  1016  1040 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
08-23 15:43:48.289  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
08-23 15:43:48.289  3657  6435 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
08-23 15:43:48.289  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.289  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.289  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.289  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.309  6488  6488 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.309  6488  6488 E Zygote  : v2
08-23 15:43:48.309  6488  6488 I libpersona: KNOX_SDCARD checking this for 10160
08-23 15:43:48.309  6488  6488 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.309  1016  1029 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6488 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
08-23 15:43:48.309  6488  6488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.309  6488  6488 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:48.309  6488  6488 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.319  6436  6436 D elm:15183: ElmAgentService : onDestroy().
08-23 15:43:48.319  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.319  3657  3657 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-23 15:43:48.339  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.339  6488  6488 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.339  6488  6488 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.349  5598  5598 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-23 15:43:48.359  1016  1138 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,08-23 15:43:48.369  1016  1138 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-23 15:43:48.379  1016  1056 I art     : Explicit concurrent mark sweep GC freed 9438(469KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/41MB, paused 7.004ms total 307.733ms
,08-23 15:43:48.389  6449  6449 D NearbySource: Nearby Source Create!
,08-23 15:43:48.389  6449  6449 D NearbyContext: Nearby Context Create!
,08-23 15:43:48.389  6488  6488 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-23 15:43:48.399  1016  2930 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-23 15:43:48.399  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.399  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.399  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.399  1016  2930 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.409  6488  6488 D [0]UMC:UMCContentProvider: @onCreate
,08-23 15:43:48.419  6503  6503 E Zygote  : MountEmulatedStorage()
,08-23 15:43:48.419  6503  6503 E Zygote  : v2
08-23 15:43:48.419  6503  6503 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:48.419  6503  6503 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.419  6503  6503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-23 15:43:48.419  1016  2930 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6503 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-23 15:43:48.419  6503  6503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-23 15:43:48.419  6503  6503 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.429  1016  2930 I ActivityManager: Killing 5542:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-23 15:43:48.439   257   522 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 15:43:48.439   257   522 W Vold    : Returning OperationFailed - no handler for errno 0
08-23 15:43:48.439  1016  1056 D PackageManager: delete codoeFile: 
,08-23 15:43:48.439  6449  6449 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 15:43:48.449  6449  6449 D SLinkSource: Samsung link source created
,08-23 15:43:48.449  1016  1056 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-23 15:43:48.449  1016  1056 I AASA_removePackage: UID=10155 Target=com.test.thalitest
,08-23 15:43:48.449  6503  6503 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.449  6503  6503 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.449  6488  6488 D [0]UMC:Core: onCreate(): 
08-23 15:43:48.449  6488  6488 D [0]UMC:Core: @isManagedProfileUser
08-23 15:43:48.449  6488  6488 D [0]UMC:Core: userId: 0
,08-23 15:43:48.459  6488  6488 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
,08-23 15:43:48.459  6488  6488 D [0]UMC:Core: userInfo.isManagedProfile() : false
,08-23 15:43:48.459  1016  1056 D PackageManager: result of delete: 1{735077024}
,08-23 15:43:48.459  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.469  6418  6418 D AndroidRuntime: Shutting down VM
,08-23 15:43:48.469  1016  1040 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 15:43:48.469  1016  1040 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:48.469  1016  1040 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 15:43:48.479  1016  1956 V SAMP_SPCM_test: CSC File load.. 
,08-23 15:43:48.499  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.499  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,08-23 15:43:48.499  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 15:43:48.499  1016  1056 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 15:43:48.499  1016  1056 D PackageManager: userId{-1}
08-23 15:43:48.499  1016  1056 D PackageManager: andCode{true}
,08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-23 15:43:48.499  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
,08-23 15:43:48.499  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.499  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
08-23 15:43:48.499  6488  6488 D [0]UMC:DeviceInfo: USA==US==
08-23 15:43:48.499  1016  1016 D OTPFW   : OtpDbHelper::getInstance New instance created
08-23 15:43:48.509  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-23 15:43:48.509  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
08-23 15:43:48.509  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
08-23 15:43:48.509  1016  1016 D OTPFW   : DBIntegrity::getInstance - New instance created
08-23 15:43:48.519  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
08-23 15:43:48.519  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
08-23 15:43:48.519  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
08-23 15:43:48.519  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 15:43:48.519  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicy: uID is 10155
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:48.519  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 15:43:48.529  1016  1502 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 15:43:48.529  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-23 15:43:48.529  6503  6503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 15:43:48.539  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-23 15:43:48.549  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-23 15:43:48.549  1016  1956 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
08-23 15:43:48.549  1016  1056 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-23 15:43:48.549  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.559  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.559  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:48.559  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.559  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.559  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:48.569  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 15:43:48.569  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-23 15:43:48.569  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicy: uID is 10155
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 15:43:48.569  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
08-23 15:43:48.569  1016  2735 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-23 15:43:48.569  1016  1040 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 15:43:48.569  1016  3209 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
08-23 15:43:48.569  1016  3209 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
08-23 15:43:48.579  1016  3209 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.579  1016  3209 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.579  1016  3209 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
08-23 15:43:48.579  6488  6488 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US
08-23 15:43:48.589  6488  6488 D [0]UMC:AdminManager: init - start
08-23 15:43:48.589  1016  1016 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
08-23 15:43:48.599  1016  2929 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
08-23 15:43:48.599  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.599  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.599  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.599  1016  2929 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.599  1016  1138 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-23 15:43:48.599  5881  5881 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-23 15:43:48.599  5881  5881 I PCWCLIENTTRACE_PushUtil: sales region : global
08-23 15:43:48.599  6449  6449 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
08-23 15:43:48.609  5881  5881 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-23 15:43:48.609  5881  5881 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.609  6522  6522 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.609  6522  6522 E Zygote  : v2
08-23 15:43:48.609  6522  6522 I libpersona: KNOX_SDCARD checking this for 1000
08-23 15:43:48.609  6522  6522 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-23 15:43:48.609  6522  6522 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.609  6488  6488 D [0]UMC:AdminManager: loadAdmins
08-23 15:43:48.609  6522  6522 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-23 15:43:48.619  6522  6522 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 15:43:48.619  1016  2929 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6522 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-23 15:43:48.619  1016  1956 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
08-23 15:43:48.619  6449  6518 D ContactProvider: getAllContactInfoList Start
,08-23 15:43:48.629  6488  6488 D [0]UMC:AdminManager: init - end
,08-23 15:43:48.639  6488  6488 D GSLBManager: migrateStoredUrlFromOldPref
,08-23 15:43:48.649  1016  1040 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-23 15:43:48.649  1016  1040 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-23 15:43:48.649  6522  6522 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.649  6522  6522 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.649  1016  1028 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-23 15:43:48.649  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.649  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.649  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.649  1016  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.659  6488  6488 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
08-23 15:43:48.659  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
08-23 15:43:48.659  6488  6488 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
08-23 15:43:48.659  6488  6488 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
08-23 15:43:48.659  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
08-23 15:43:48.659  6488  6488 D [0]UMC:UMCAdmin: isContainer : 0
,08-23 15:43:48.669  6538  6538 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.669  6538  6538 E Zygote  : v2
08-23 15:43:48.669  6538  6538 I libpersona: KNOX_SDCARD checking this for 10035
08-23 15:43:48.669  6538  6538 I libpersona: KNOX_SDCARD not a persona
,08-23 15:43:48.669  1016  1028 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6538 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 15:43:48.669  6538  6538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.669  6538  6538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:48.669  6538  6538 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.679  6418  6418 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 15:43:48.689  5863  5863 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-23 15:43:48.689  1016  3212 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,08-23 15:43:48.689  6488  6488 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
,08-23 15:43:48.689  6488  6488 D [0]UMC:UMCAdmin: isContainer : 0
,08-23 15:43:48.699  5846  5846 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-23 15:43:48.699  1016  1016 I ActivityManager: Killing 5631:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,08-23 15:43:48.699  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
08-23 15:43:48.699  1016  1160 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
08-23 15:43:48.699  1016  1029 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-23 15:43:48.699  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.699  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.699  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.699  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,08-23 15:43:48.709  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,08-23 15:43:48.719  6538  6538 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 15:43:48.719  6538  6538 D ActivityThread: Added TimaKeyStore provider
,08-23 15:43:48.719  1016  1138 I TactileAssist: enable value -1
08-23 15:43:48.719  1016  1138 I TactileAssist: internal enable value -1
08-23 15:43:48.719  1016  1138 I TactileAssist: intensity value -1
08-23 15:43:48.719  1016  1138 I TactileAssist: saveAppList value true
08-23 15:43:48.719  6005  6016 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-23 15:43:48.719  6005  6016 D BadgeProvider: sendNotify, [notify] : null
08-23 15:43:48.719  6005  6016 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-23 15:43:48.719  6005  6016 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-23 15:43:48.719  6005  6016 D BadgeProvider: update, [UpdateCount] : 1
,08-23 15:43:48.719  1016  1138 I TactileAssist: List of disabled apps :
08-23 15:43:48.719  5863  6553 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.719  5863  6553 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,08-23 15:43:48.729  1016  1345 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
08-23 15:43:48.729  1016  1345 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.729  1016  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:48.729  1016  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 15:43:48.729  1016  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,08-23 15:43:48.729  1477  1477 D Launcher.Model: reloadBadges entered.
,08-23 15:43:48.729  6488  6488 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
,08-23 15:43:48.739  6488  6488 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
,08-23 15:43:48.739  6488  6488 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
08-23 15:43:48.739  6488  6488 D [0]UMC:CoreReceiver: Intent Replacing : false
,08-23 15:43:48.739  1477  1477 D Launcher.Model: reloadBadges entered.
,08-23 15:43:48.749  1016  3210 I ActivityManager: Killing 5914:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-23 15:43:48.749  6488  6488 D [0]UMC:CoreReceiver: bulk enrolled package: null
08-23 15:43:48.749  6488  6488 V [0]UMC:ProfileStorage: Enter loadList
08-23 15:43:48.759  6488  6488 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
08-23 15:43:48.759  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,08-23 15:43:48.759  6488  6488 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,08-23 15:43:48.759  6488  6488 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
08-23 15:43:48.759  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
08-23 15:43:48.759  6488  6488 D [0]UMC:UMCAdmin: isContainer : 0
,08-23 15:43:48.759  1016  1217 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,08-23 15:43:48.759  6488  6488 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
08-23 15:43:48.759  6488  6488 D [0]UMC:UMCAdmin: isContainer : 0
,08-23 15:43:48.759  6488  6488 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,08-23 15:43:48.769  6488  6488 D [0]UMC:GuardService: @GuardService oncreate()
08-23 15:43:48.769  6488  6488 D [0]UMC:GuardService: @GuardService onStartCommand()
08-23 15:43:48.769  6064  6064 D Compatibility: onReceive() it will make start service
,08-23 15:43:48.769  6522  6559 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,08-23 15:43:48.769  1016  1475 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-23 15:43:48.769  6522  6559 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,08-23 15:43:48.779  1016  1475 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor}
08-23 15:43:48.779  1016  1475 W BroadcastQueue: android.os.TransactionTooLargeException
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
08-23 15:43:48.779  1016  1475 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
08-23 15:43:48.779  1016  1475 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-23 15:43:48.779  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.779  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.779  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.779  1016  1475 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.799  6560  6560 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.799  6560  6560 E Zygote  : v2
08-23 15:43:48.799  6560  6560 I libpersona: KNOX_SDCARD checking this for 10120
08-23 15:43:48.799  6560  6560 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.799  6560  6560 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.799  6560  6560 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-23 15:43:48.799  1016  1475 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=6560 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-23 15:43:48.799  6560  6560 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.809  1016  1382 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-23 15:43:48.809  1016  1382 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,08-23 15:43:48.809  1016  1382 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.809  1016  1382 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.809  1016  1382 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,08-23 15:43:48.809  1016  1345 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
08-23 15:43:48.809  1016  1345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.819  1016  1345 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.819  1016  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.819  1016  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,08-23 15:43:48.819  5653  5653 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(304): Wear auto uninstall disabled for package com.test.thalitest
,08-23 15:43:48.819  1016  2734 W ActivityManager: Spurious death for ProcessRecord{1b933713 6560:com.google.android.apps.plus/u0a120}, curProc for 5631: null
,08-23 15:43:48.819  6449  6518 D ContactProvider: getAllContactInfoList End
08-23 15:43:48.819  1016  1217 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 15:43:48.819  6522  6522 D AcmsService: Enter Oncreate
08-23 15:43:48.819  1016  1217 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.829  6449  6518 I syncContacts: thread: 1073, sync time = 322
,08-23 15:43:48.829  1016  1217 W ActivityManager: userId = 0, bbcId = -10000
,08-23 15:43:48.829  1016  1217 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:48.829  6522  6522 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:48.829  6522  6522 D AcmsService: creating AcmsCore
08-23 15:43:48.829  6522  6522 D AcmsCore: AcmsCore.getAcmsCore() - Enter
08-23 15:43:48.829  6522  6522 D AcmsCore: AcmsCore
08-23 15:43:48.829  1016  1217 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 15:43:48.829  1016  1040 W libprocessgroup: failed to kill pid 5914: No such process
,08-23 15:43:48.829  6064  6571 D Compatibility: onHandleIntent()
08-23 15:43:48.829  1016  1502 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
08-23 15:43:48.829  6064  6571 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-23 15:43:48.829  1016  1502 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,08-23 15:43:48.829  1016  1502 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.829  1016  1502 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 15:43:48.829  1016  1502 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
08-23 15:43:48.829  6560  6560 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 15:43:48.829  6064  6571 D Compatibility: found: 2
08-23 15:43:48.829  6064  6571 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-23 15:43:48.829  6064  6571 D Compatibility: skipping ResolveInfo{34755b87 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-23 15:43:48.829  6064  6571 D Compatibility: considering ResolveInfo{29454ab4 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-23 15:43:48.829  6064  6571 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
08-23 15:43:48.839  6560  6560 D ActivityThread: Added TimaKeyStore provider
08-23 15:43:48.839  6064  6571 D Compatibility: enabling receiver ResolveInfo{2a7bd6dd com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 15:43:48.839  1016  1040 W libprocessgroup: failed to open /acct/uid_10120/pid_5631/cgroup.procs: No such file or directory
,08-23 15:43:48.839  6522  6522 D AcmsCore: init
08-23 15:43:48.839  6522  6522 D AcmsCore: Looper handler is not null
08-23 15:43:48.839  6522  6522 D AcmsCore: Post to AcmsCoreHandler
08-23 15:43:48.839  6522  6522 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 15:43:48.839  6522  6522 D AcmsServiceMonitor: Incrementing - Counter value: 1
08-23 15:43:48.839  6522  6522 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,08-23 15:43:48.839  1016  1029 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-23 15:43:48.839  1016  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
08-23 15:43:48.839  6064  6571 D Compatibility: enabling receiver ResolveInfo{1e200252 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
08-23 15:43:48.839  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
08-23 15:43:48.839  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 15:43:48.839  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
08-23 15:43:48.839  6522  6574 D AcmsCertificateMngr: AcmsCertificateMngr
,08-23 15:43:48.839  6522  6522 D AcmsService: onStartCommand
08-23 15:43:48.839  6522  6522 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
08-23 15:43:48.839  6522  6522 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
08-23 15:43:48.839  6522  6522 D AcmsServiceMonitor: Incrementing - Counter value: 2
08-23 15:43:48.839  6522  6522 D AcmsService: Incremented Counter Value : onStartCommand
,08-23 15:43:48.839  6522  6574 D AcmsRevocationMngr: AcmsRevocationMngr
,08-23 15:43:48.849  6064  6571 D Compatibility: enabling receiver ResolveInfo{31c22923 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-23 15:43:48.859  5521  6577 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-23 15:43:48.859  6064  6571 D Compatibility: enabling receiver ResolveInfo{c465e20 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-23 15:43:48.859  6538  6578 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-23 15:43:48.859  6538  6578 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 15:43:48.869  1016  1345 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
08-23 15:43:48.869  1016  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.869  1016  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.869  1016  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 15:43:48.869  1016  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 15:43:48.869  6538  6538 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,08-23 15:43:48.879  6064  6571 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-23 15:43:48.879  6580  6580 E Zygote  : MountEmulatedStorage()
08-23 15:43:48.879  6538  6578 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:48.879  1016  1345 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6580 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
08-23 15:43:48.879  6538  6578 D SPPClientService: PushLog.txt file is not deleted.
08-23 15:43:48.879  6560  6560 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 15:43:48.879  6538  6578 D SPPClientService: ============PushLog. stop!
08-23 15:43:48.879  6580  6580 E Zygote  : v2
,08-23 15:43:48.879  6580  6580 I libpersona: KNOX_SDCARD checking this for 10003
08-23 15:43:48.879  6580  6580 I libpersona: KNOX_SDCARD not a persona
08-23 15:43:48.879  6580  6580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-23 15:43:48.889  6580  6580 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-23 15:43:48.889  6580  6580 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 15:43:48.889  1016  2930 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0

```
