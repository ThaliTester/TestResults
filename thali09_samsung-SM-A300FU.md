#### Test 7214543196063dc_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
07-05 14:04:21.971   287   287 E SMD     : DCD OFF
,07-05 14:04:22.821  6566  6566 D AndroidRuntime: 
07-05 14:04:22.821  6566  6566 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:04:22.821  6566  6566 D AndroidRuntime: CheckJNI is OFF
07-05 14:04:22.821  6566  6566 D AndroidRuntime: readGMSProperty: start
07-05 14:04:22.821  6566  6566 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:22.821  6566  6566 D AndroidRuntime: propertySet: couldn't set property (it is from app)
07-05 14:04:22.821  6566  6566 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:04:22.821  6566  6566 D AndroidRuntime: readGMSProperty: end
07-05 14:04:22.821  6566  6566 D AndroidRuntime: addProductProperty: start
07-05 14:04:22.941  6566  6566 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:04:22.941   316   316 I ServiceManager: Waiting for service AtCmdFwd...
07-05 14:04:22.961  6566  6566 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:04:22.981  1016  1537 E PersonaManagerService: inState():  stateMachine is null !!
07-05 14:04:22.981  1016  1537 I PersonaManagerService: PersonaId don't exist
07-05 14:04:22.981  1016  1537 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 14:04:22.981  1016  1537 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
07-05 14:04:23.001  1016  1537 W ActivityManager: mDVFSHelper.acquire()
07-05 14:04:23.001  1016  1537 D FocusedStackFrame: Set to : 0
07-05 14:04:23.011  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:23.011  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:23.011  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:23.011  1016  1537 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:23.011  1016  1047 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 14:04:23.011  1016  1047 D PhoneWindow: *FMB* installDecor flags : -2122120936
07-05 14:04:23.021  6577  6577 E Zygote  : MountEmulatedStorage()
07-05 14:04:23.021  6577  6577 E Zygote  : v2
07-05 14:04:23.021  6577  6577 I libpersona: KNOX_SDCARD checking this for 10170
07-05 14:04:23.021  6577  6577 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:23.031  6577  6577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:23.031  1016  1537 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6577 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 14:04:23.031  1016  1537 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 14:04:23.031  1016  1537 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:23.031  1016  1537 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:23.031  1016  1537 D InputDispatcher: Focus left window: 1481
07-05 14:04:23.031  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 14:04:23.031  1016  1047 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 14:04:23.031  6577  6577 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:23.031   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
07-05 14:04:23.041  6566  6566 D AndroidRuntime: Shutting down VM
07-05 14:04:23.041  6577  6577 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 14:04:23.041  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:23.051  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:23.061  6577  6577 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:23.061  6577  6577 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:23.061  1016  1211 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 14:04:23.061  1016  1016 V ActivityManager: Display changed displayId=0
07-05 14:04:23.081  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:04:23.101  1016  1211 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:04:23.111  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
07-05 14:04:23.131   257   456 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
07-05 14:04:23.131   257   454 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
07-05 14:04:23.141  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{15349438 token=android.os.BinderProxy@3d4674cf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 14:04:23.141  1481  1481 D Launcher: onTrimMemory. Level: 20
07-05 14:04:23.211  6577  6577 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 14:04:23.231  6577  6577 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 4121-4130)
07-05 14:04:23.231  6577  6577 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:23.241  6566  6566 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
07-05 14:04:23.251  5695  5695 D FactoryTest: Not factory mode
07-05 14:04:23.251  5695  5695 D FactoryTest: Not factory mode. isFactoryMode() returend false
07-05 14:04:23.251  5695  5695 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
07-05 14:04:23.251  5695  5695 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
07-05 14:04:23.251  5695  5695 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
07-05 14:04:23.251  5695  5695 D MTPRx   : still no open session command from host, so toast
07-05 14:04:23.261  6577  6577 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22266a9f}
07-05 14:04:23.261  6577  6577 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:04:23.261  6577  6577 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:04:23.271  5695  5695 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114170
07-05 14:04:23.271  1016  1480 E PersonaManagerService: inState():  stateMachine is null !!
07-05 14:04:23.271  1016  1480 I PersonaManagerService: PersonaId don't exist
07-05 14:04:23.271  1016  1480 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 14:04:23.271  1016  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
07-05 14:04:23.271  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:23.271  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:23.271  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
07-05 14:04:23.281  1016  1480 W ActivityManager: mDVFSHelper.acquire()
07-05 14:04:23.291  1016  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:23.291  1016  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
07-05 14:04:23.291  1016  1480 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:23.291  5695  5695 E MTPRx   : started activity for popup
07-05 14:04:23.311  6577  6577 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:04:23.311  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:23.311  6577  6577 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:04:23.331  6577  6577 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-05 14:04:23.331  6577  6577 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 14:04:23.331  6577  6577 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-05 14:04:23.341  6577  6577 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
07-05 14:04:23.341  6577  6577 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
07-05 14:04:23.341  6577  6577 I Adreno-EGL: Build Date: 04/06/15 Mon
07-05 14:04:23.341  6577  6577 I Adreno-EGL: Local Branch: 
07-05 14:04:23.341  6577  6577 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
07-05 14:04:23.341  6577  6577 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
07-05 14:04:23.341  6577  6577 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
07-05 14:04:23.541  6577  6603 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-05 14:04:23.581  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:23.601  6577  6577 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:04:23.601  1016  1042 W ActivityManager: Activity pause timeout for ActivityRecord{211b643e u0 com.test.thalitest/.MainActivity t43}
07-05 14:04:23.611  6577  6577 D PhoneWindow: *FMB* installDecor mIsFloating : false
07-05 14:04:23.611  6577  6577 D PhoneWindow: *FMB* installDecor flags : -2139027200
07-05 14:04:23.611  1016  1042 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:04:23.621  6577  6577 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 14:04:23.631  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:23.631  6577  6577 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:04:23.651  5695  5695 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
07-05 14:04:23.661  5695  5695 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
07-05 14:04:23.691  1016  3705 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
07-05 14:04:23.691  1016  3705 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:23.691  1016  3705 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:23.711  6577  6617 D OpenGLRenderer: Render dirty regions requested: true
07-05 14:04:23.711  1016  1029 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:23.711  1016  1029 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:04:23.711  1016  1029 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:04:23.711  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:04:23.711  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:23.731  6577  6577 V ActivityThread: updateVisibility : ActivityRecord{240bdfc6 token=android.os.BinderProxy@13088608 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:04:23.731  6577  6577 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
07-05 14:04:23.731  6577  6577 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
07-05 14:04:23.741   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
07-05 14:04:23.761  1016  1479 D InputDispatcher: Focus entered window: 6577
07-05 14:04:23.761  5695  5695 D SettingsReceiverActivity: dev.kiessupport is : TRUE
07-05 14:04:23.761  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:23.761  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:23.761  6577  6577 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
07-05 14:04:23.761  6577  6617 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:04:23.771  5695  5695 D PhoneWindow: *FMB* installDecor mIsFloating : true
07-05 14:04:23.771  5695  5695 D PhoneWindow: *FMB* installDecor flags : 8388610
07-05 14:04:23.771  6577  6617 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
07-05 14:04:23.771  6577  6617 D OpenGLRenderer: Enabling debug mode 0
07-05 14:04:23.791  1016  4039 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:04:23.791  1016  6619 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 14:04:23.791  1175  1175 I StatusBar: Icon Only
07-05 14:04:23.801  1175  1175 D PanelView: There is/are notification(s) 
07-05 14:04:23.811  1016  1047 W ActivityManager: mDVFSHelper.release()
07-05 14:04:23.811  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{211b643e u0 com.test.thalitest/.MainActivity t43} time:114711
07-05 14:04:23.811  6577  6577 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-05 14:04:23.811  1876  1876 I SamsungIME: getCurrentCandidateView
07-05 14:04:23.811  1016  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:23.811  1016  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:04:23.811  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:04:23.811  1016  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:04:23.811  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:23.821   257   456 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
07-05 14:04:23.821   257   454 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
07-05 14:04:23.831  1016  1028 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:04:23.841  6577  6577 V ActivityThread: updateVisibility : ActivityRecord{240bdfc6 token=android.os.BinderProxy@13088608 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:04:23.841  6577  6577 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13088608 time:114743
07-05 14:04:23.841  6577  6577 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13088608 time:114743
07-05 14:04:23.911  1876  1876 D SamsungIME: Dismiss ExpandCandiate
07-05 14:04:23.941   316   316 I ServiceManager: Waiting for service AtCmdFwd...
07-05 14:04:23.961  6577  6577 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6577
,07-05 14:04:24.071  6577  6577 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:04:24.131  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:04:24.181  1876  1876 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:04:24.191  1876  1876 I SamsungIME: KeybaordView init() : load resources
,07-05 14:04:24.231  1876  1876 I SamsungIME: getCurrentKeyboard
07-05 14:04:24.231  1876  1876 I SamsungIME: getTextKeyboard
,07-05 14:04:24.231  6577  6622 D jxcore_app_log: JniHelper::setJavaVM(0xb869a2f0), pthread_self() = -1195423720
,07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 14:04:24.241  6577  6622 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3371c676 added. We now have 1 listener(s)
,07-05 14:04:24.251  1876  1876 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 14:04:24.251  6577  6622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,07-05 14:04:24.251  6577  6622 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,07-05 14:04:24.251  6577  6622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-05 14:04:24.251  6577  6622 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:04:24.251  6577  6622 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd2214d added. We now have 1 listener(s)
,07-05 14:04:24.251  6577  6622 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:04:24.271  6577  6622 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-05 14:04:24.271  6577  6622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-05 14:04:24.271  6577  6622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-05 14:04:24.271  6577  6622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-05 14:04:24.271  6577  6622 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-05 14:04:24.281  6577  6622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:04:24.281  6577  6622 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:24.291  6577  6622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:04:24.291  6577  6622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:04:24.291  6577  6622 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-05 14:04:24.291  6577  6622 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:04:24.291  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:24.301  6577  6577 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:04:24.321  6577  6577 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:04:24.871  6577  6627 W jxcore-log: Initializing JXcore engine
07-05 14:04:24.871  6577  6627 W jxcore-log: JXcore engine is ready
,07-05 14:04:24.931  2031  2031 E audit   : type=1400 msg=audit(1467720264.931:205): avc:  denied  { ioctl } for  pid=6627 comm="Thread-1203" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-05 14:04:24.931  2031  2031 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:24.931  2031  2031 E audit   : type=1300 msg=audit(1467720264.931:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9f7008f8 items=0 ppid=308 ppcomm=main pid=6627 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1203" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-05 14:04:24.931  2031  2031 E audit   : type=1320 msg=audit(1467720264.931:205): 
,07-05 14:04:24.941  6577  6627 W jxcore-log: Starting JXcore engine
,07-05 14:04:24.941   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:24.961   287   287 E SMD     : DCD OFF,
,07-05 14:04:25.041  6577  6627 W jxcore-log: Platform android
07-05 14:04:25.041  6577  6627 W jxcore-log: 
07-05 14:04:25.041  6577  6627 W jxcore-log: Process ARCH arm
07-05 14:04:25.041  6577  6627 W jxcore-log: 
,07-05 14:04:25.251  6577  6627 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:04:25.251  6577  6627 I jxcore-log: 
07-05 14:04:25.251  6577  6627 W jxcore-log: JXcore engine is started
,07-05 14:04:25.251  6577  6622 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:04:25.251  6577  6577 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:04:25.261  6577  6627 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
07-05 14:04:25.261  6577  6627 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-05 14:04:25.271  6577  6577 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
,07-05 14:04:25.271  1016  1437 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:04:25.271  1016  1437 D FocusedStackFrame: Set to : 0
07-05 14:04:25.271  1016  1437 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
07-05 14:04:25.271  1016  1437 D InputDispatcher: Focused application set to: xxxx
07-05 14:04:25.271  1016  1437 D InputDispatcher: Focus left window: 6577
07-05 14:04:25.271  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:25.271  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:25.281  6577  6577 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-05 14:04:25.281  1016  1437 I ActivityManager: Killing 6238:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
07-05 14:04:25.291  6577  6577 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-05 14:04:25.291  6577  6577 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-05 14:04:25.291  6577  6577 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-05 14:04:25.291  6577  6577 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-05 14:04:25.291  6577  6577 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-05 14:04:25.291  6577  6577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-05 14:04:25.291  6577  6577 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3371c676 removed from the list
07-05 14:04:25.291  6577  6577 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-05 14:04:25.291  6577  6577 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3bd2214d removed from the list
07-05 14:04:25.291  6577  6577 D io.jxcore.node.ConnectivityMonitor: stop
07-05 14:04:25.291  6577  6577 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-05 14:04:25.291  6577  6577 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-05 14:04:25.301   257   454 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,07-05 14:04:25.301   257  1038 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,07-05 14:04:25.311  1016  1465 W ActivityManager: mDVFSHelper.acquire()
,07-05 14:04:25.311  1016  1465 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,07-05 14:04:25.321  1016  4039 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:25.321  1016  4039 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
07-05 14:04:25.321  1016  4039 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,07-05 14:04:25.331  1016  4039 D BatteryService: stay LED for fully charged
07-05 14:04:25.331  1016  1016 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:25.331  1016  1016 I MotionRecognitionService: Plugged,
07-05 14:04:25.331  1016  1016 I MotionRecognitionService: mGripSensorEnabled= false
,07-05 14:04:25.331  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:25.331  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:04:25.331  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
07-05 14:04:25.331  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
07-05 14:04:25.341  1481  1481 D Launcher: onRestart, Launcher: 999363003
,07-05 14:04:25.351  3336  3336 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:04:25.351  3336  3430 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:25.351  1481  1481 D Launcher: onStart, Launcher: 999363003
,07-05 14:04:25.351  1481  1481 D Launcher.HomeView: onStart
,07-05 14:04:25.351  1481  1481 D Launcher: onResume, Launcher: 999363003
07-05 14:04:25.351  1016  1536 D SettingsProvider: name = kids_home_mode
07-05 14:04:25.351  1016  1536 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-05 14:04:25.351  1016  1536 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-05 14:04:25.351  1016  1536 D SettingsProvider: selectionArgs: false
07-05 14:04:25.351  1016  1536 D SettingsProvider: selectionArgs: 10006
07-05 14:04:25.351  1016  1536 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-05 14:04:25.351  1016  1536 D SettingsProvider: ret = -1
,07-05 14:04:25.351  1481  1481 D Launcher.HomeView: onResume
,07-05 14:04:25.361  1175  1175 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED,
07-05 14:04:25.361  1175  1175 D SViewCoverView: level :100 plugged : 2
07-05 14:04:25.361  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:25.361  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:04:25.361  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2,
,07-05 14:04:25.371  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,07-05 14:04:25.371  1481  1481 D MenuAppsGridFragment: onResume
,07-05 14:04:25.371  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.371  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.371  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,07-05 14:04:25.371  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 14:04:25.371  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,07-05 14:04:25.371  1016  1480 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,07-05 14:04:25.381  1016  1480 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,07-05 14:04:25.381  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:25.381  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,07-05 14:04:25.381  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,07-05 14:04:25.381  1016  1480 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,07-05 14:04:25.381  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.381  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.381  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.381  1016  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.401  1016  1480 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=6634 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,07-05 14:04:25.401  1016  1255 D ActivityManager: handle home activity for 0,
07-05 14:04:25.401  6634  6634 I libpersona: KNOX_SDCARD checking this for 10039,
,07-05 14:04:25.401  1016  1255 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
07-05 14:04:25.401  6634  6634 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:25.401  1016  1255 D KnoxTimeoutHandler: post home show event for user 0,
07-05 14:04:25.401  1016  1016 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:04:25.401  6634  6634 E Zygote  : MountEmulatedStorage()
07-05 14:04:25.401  6634  6634 E Zygote  : v2,
07-05 14:04:25.401  1016  1255 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:25.401  1016  1255 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:04:25.401  1016  1255 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false,
07-05 14:04:25.401  1016  1016 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
07-05 14:04:25.401  1016  1016 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
07-05 14:04:25.401  1016  1016 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:25.401  1481  1481 D Launcher.HomeView: onPause,
07-05 14:04:25.401  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
07-05 14:04:25.401  6634  6634 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:25.401  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.401  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.401  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
07-05 14:04:25.411  6634  6634 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:25.411  6634  6634 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:25.411  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
07-05 14:04:25.411  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:25.411  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.411  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
07-05 14:04:25.411  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.411  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.411  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.411  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.431  6644  6644 E Zygote  : MountEmulatedStorage(),
,07-05 14:04:25.431  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.431  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=6644 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
07-05 14:04:25.431  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.431  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
07-05 14:04:25.431  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
07-05 14:04:25.441  6634  6634 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:25.441  6644  6644 E Zygote  : v2
07-05 14:04:25.441  6644  6644 I libpersona: KNOX_SDCARD checking this for 10089
07-05 14:04:25.441  6644  6644 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:25.441  6634  6634 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:25.441  6644  6644 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:25.441  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.441  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.441  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.441  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.441  6644  6644 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:25.441  6644  6644 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,07-05 14:04:25.451  6659  6659 E Zygote  : MountEmulatedStorage()
,07-05 14:04:25.451  6659  6659 E Zygote  : v2
07-05 14:04:25.451  6659  6659 I libpersona: KNOX_SDCARD checking this for 10139
,07-05 14:04:25.451  6659  6659 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:25.451  6659  6659 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:25.461  1016  1042 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6659 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,07-05 14:04:25.461  6659  6659 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:25.461  6659  6659 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:25.471  6644  6644 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:25.471  6644  6644 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:25.481   257   257 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,07-05 14:04:25.481  6659  6659 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:25.481  6659  6659 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:25.481  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 14:04:25.491  1016  3705 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.491  1016  3705 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
07-05 14:04:25.491  1016  3705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.491  1016  3705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,07-05 14:04:25.491  1016  1045 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-05 14:04:25.491  1016  1029 D InputDispatcher: Focus entered window: 1481
07-05 14:04:25.491  1016  1042 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.491  1016  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.491  1016  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,07-05 14:04:25.491  1016  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:04:25.491  1016  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:25.491  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-05 14:04:25.501  6634  6634 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-05 14:04:25.501  2600  2600 D Recents_RecreateReceiver: onReceive by home
07-05 14:04:25.501  6644  6644 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:04:25.501  6644  6644 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,07-05 14:04:25.511  1016  1029 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.511  1016  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.511  1016  1029 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
07-05 14:04:25.511  1016  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,07-05 14:04:25.511  1481  1481 D Launcher.HomeView: onStop
07-05 14:04:25.511  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.511  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.511  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.511  1016  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.511  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{15349438 token=android.os.BinderProxy@3d4674cf {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-05 14:04:25.511  1016  1479 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-05 14:04:25.521  1016  6680 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:25.521  6577  6577 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-05 14:04:25.531  1876  1876 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,07-05 14:04:25.531  1175  1175 I StatusBar: Icon Only
,07-05 14:04:25.531  6682  6682 E Zygote  : MountEmulatedStorage()
07-05 14:04:25.531  6682  6682 I libpersona: KNOX_SDCARD checking this for 10084
07-05 14:04:25.531  6682  6682 E Zygote  : v2
07-05 14:04:25.531  6682  6682 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:25.531  6682  6682 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:25.531  1175  1175 D PanelView: There is/are notification(s) 
,07-05 14:04:25.541  6682  6682 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:25.541  6682  6682 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
07-05 14:04:25.541  1016  1029 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=6682 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,07-05 14:04:25.561  6659  6659 V TaskCloserActivity: TaskCloserActivity enter()
,07-05 14:04:25.561  6630  6630 D AndroidRuntime: 
07-05 14:04:25.561  6630  6630 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-05 14:04:25.571  6630  6630 D AndroidRuntime: CheckJNI is OFF
,07-05 14:04:25.571  6630  6630 D AndroidRuntime: readGMSProperty: start
07-05 14:04:25.571  6630  6630 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:04:25.571  6630  6630 D AndroidRuntime: propertySet: couldn't set property (it is from app)
,07-05 14:04:25.571  6630  6630 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
07-05 14:04:25.571  6630  6630 D AndroidRuntime: readGMSProperty: end
07-05 14:04:25.571  6630  6630 D AndroidRuntime: addProductProperty: start,
,07-05 14:04:25.571  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3d4674cf time:116477
,07-05 14:04:25.571  6659  6659 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,07-05 14:04:25.581  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.581  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.581  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
07-05 14:04:25.581  1016  1537 I ActivityManager: Killing 6257:com.sec.spp.push/u0a32 (adj 15): empty #21
,07-05 14:04:25.581  6682  6682 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:25.581  6682  6682 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:25.601  1016  3705 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:25.601  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
07-05 14:04:25.601  1016  3705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:25.601  1016  3705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
07-05 14:04:25.601  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.601  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.601  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:25.601  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:25.611  6682  6682 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:25.621  6700  6700 E Zygote  : MountEmulatedStorage()
07-05 14:04:25.621  6700  6700 E Zygote  : v2
,07-05 14:04:25.621  6700  6700 I libpersona: KNOX_SDCARD checking this for 10135
07-05 14:04:25.621  6700  6700 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:25.621  6700  6700 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:25.621  6700  6700 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,07-05 14:04:25.631  1016  3705 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6700 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,07-05 14:04:25.631  6700  6700 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:25.631  1016  3705 I ActivityManager: Killing 6272:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,07-05 14:04:25.631  1016  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c20a955 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:116538
07-05 14:04:25.631  1016  1016 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
07-05 14:04:25.631  1016  1047 W ActivityManager: mDVFSHelper.release()
,07-05 14:04:25.651  1016  1511 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:25.651  6700  6700 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:25.651  6700  6700 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:25.661  1016  1211 I ActivityManager: Killing 6288:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,07-05 14:04:25.671  6700  6700 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
07-05 14:04:25.671  6700  6700 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:25.671  6700  6700 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
07-05 14:04:25.671  6700  6700 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
07-05 14:04:25.671  6700  6700 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-05 14:04:25.701  6630  6630 E AffinityControl: AffinityControl: registerfunction enter
,07-05 14:04:25.711  1016  1437 I ActivityManager: Killing 6330:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,07-05 14:04:25.731  6630  6630 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-05 14:04:25.741  6634  6634 D NearbySource: Nearby Source Create!
,07-05 14:04:25.751  6634  6634 D NearbyContext: Nearby Context Create!
,07-05 14:04:25.751  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:04:25.751  1016  1029 D PackageManager: START PACKAGE DELETE: observer{892903528}
07-05 14:04:25.751  1016  1029 D PackageManager: pkg{<packageName>}
07-05 14:04:25.751  1016  1029 D PackageManager: user{0}
07-05 14:04:25.751  1016  1029 D PackageManager: caller{2000}
07-05 14:04:25.751  1016  1029 D PackageManager: flags{2}
07-05 14:04:25.751  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:04:25.751  1016  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:04:25.751  1016  1029 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 14:04:25.751  1016  1057 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
07-05 14:04:25.751  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
07-05 14:04:25.751  1016  1029 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:04:25.751  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:04:25.751  1016  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:04:25.751  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:04:25.751  1016  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true,
,07-05 14:04:25.761  1016  1042 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,07-05 14:04:25.761  1016  1042 I ActivityManager: Killing 6577:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,07-05 14:04:25.781   256   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
07-05 14:04:25.781   256   519 W Vold    : Returning OperationFailed - no handler for errno 0
,07-05 14:04:25.781  6634  6634 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
07-05 14:04:25.791  6634  6634 D SLinkSource: Samsung link source created
,07-05 14:04:25.851  1016  1057 W PackageSettings: Skipping PackageSetting{30f822fe com.example.hello/10168} due to missing metadata
,07-05 14:04:25.901  1016  1057 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,07-05 14:04:25.941   316   316 I ServiceManager: Waiting for service AtCmdFwd...,
,07-05 14:04:25.971  1016  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,07-05 14:04:25.971  2734  2734 I art     : Explicit concurrent mark sweep GC freed 23427(1279KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 955us total 50.926ms
,07-05 14:04:25.981  1016  4039 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-05 14:04:25.981  6441  6441 I art     : Explicit concurrent mark sweep GC freed 597(34KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 1.019ms total 55.515ms
,07-05 14:04:25.991  1016  1098 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:04:26.001  1876  1876 E SamsungIME: mOCRHelper is null
,07-05 14:04:26.011  2045  2194 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:26.011  4694  4694 I art     : Explicit concurrent mark sweep GC freed 1505(83KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 12MB/16MB, paused 1.109ms total 91.426ms
,07-05 14:04:26.041  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:26.051  1016  1122 V NetworkStats: removeUidsLocked() for UIDs [10170]
,07-05 14:04:26.051  1016  1122 V NetworkStats: performPollLocked(flags=0x3)
07-05 14:04:26.051  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:26.051  1016  1041 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-05 14:04:26.051  1016  1041 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 14:04:26.051  1016  1041 W TextServicesManagerService: no available spell checker services found
,07-05 14:04:26.051  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
07-05 14:04:26.051  1016  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,07-05 14:04:26.061  1441  1441 D RegisteredServicesCache: empty dynamic service
07-05 14:04:26.061  1016  1122 V NetworkStats: performPollLocked() took 8ms
07-05 14:04:26.061  1016  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:26.071  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.071  1016  1479 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-05 14:04:26.081  6634  6724 D ContactProvider: getAllContactInfoList Start
,07-05 14:04:26.081  1441  1441 D RegisteredComponentCache: Collect Tech packages for Knox
,07-05 14:04:26.081  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.081  1441  1441 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:04:26.091  6634  6634 D GalleryCacheReady: Receive : home resume
,07-05 14:04:26.101  1016  1437 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:26.101  1016  1437 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
07-05 14:04:26.101  1016  1437 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,07-05 14:04:26.101  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:26.101  1016  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,07-05 14:04:26.111  6171  6171 D Mms/UIEventReceiver: ui event
,07-05 14:04:26.111  1016  1255 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,07-05 14:04:26.111  1016  1255 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.111  1016  1255 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.111  1016  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,07-05 14:04:26.121  6659  6659 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,07-05 14:04:26.121  1016  1016 I art     : Explicit concurrent mark sweep GC freed 45426(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 24MB/36MB, paused 4.337ms total 191.213ms
,07-05 14:04:26.121  1016  1057 I art     : WaitForGcToComplete blocked for 89.786ms for cause Explicit
,07-05 14:04:26.141  2682  2682 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Jul 05 14:04:26 GMT+02:00 2016
,07-05 14:04:26.151  1016  1480 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,07-05 14:04:26.161  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.161  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.161  1016  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.161  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,07-05 14:04:26.171  1016  4039 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 14:04:26.171  1016  4039 D SecContentProvider2: mCursor = null
,07-05 14:04:26.171  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.171  2682  2682 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
07-05 14:04:26.171  1016  3706 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
07-05 14:04:26.171  1016  3706 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
07-05 14:04:26.171  1016  3706 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-05 14:04:26.181  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.181  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.181  2682  2682 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
07-05 14:04:26.181  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.181  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.181  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.181  2682  2682 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-05 14:04:26.191  1016  1016 D RCPManagerService: PackageReceiver onReceive()
,07-05 14:04:26.191  1016  1016 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-05 14:04:26.191  6727  6727 E Zygote  : MountEmulatedStorage(),
07-05 14:04:26.191  6727  6727 E Zygote  : v2
07-05 14:04:26.191  6727  6727 I libpersona: KNOX_SDCARD checking this for 10090
07-05 14:04:26.191  6727  6727 I libpersona: KNOX_SDCARD not a persona,
07-05 14:04:26.191  6727  6727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.191  1016  1016 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-05 14:04:26.191  1016  1016 I OTPFW   : PackageRemovalReceiver::onReceive Enter
07-05 14:04:26.191  1016  1016 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,07-05 14:04:26.201  6727  6727 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:26.201  1016  1016 I OTPFW   : ProvisionData::getAllEntries Enter
,07-05 14:04:26.201  6727  6727 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:26.201  1016  3706 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6727 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,07-05 14:04:26.201  1016  1016 E OTPFW   : ProvisionData::getAllEntries Table is empty
,07-05 14:04:26.201  2682  2682 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
07-05 14:04:26.211  6171  6171 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-05 14:04:26.211  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
07-05 14:04:26.211  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.221  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.221  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.221  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.221  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
07-05 14:04:26.231  6742  6742 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.231  6742  6742 E Zygote  : v2
07-05 14:04:26.231  6742  6742 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:26.231  6742  6742 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:26.231  6742  6742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:26.231  6742  6742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:26.241  6727  6727 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:26.241  1016  1042 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6742 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 14:04:26.241  1016  1042 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
07-05 14:04:26.241  6727  6727 D ActivityThread: Added TimaKeyStore provider,
,07-05 14:04:26.241  6742  6742 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,07-05 14:04:26.251  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.251  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.251  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.251  1016  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.261   308   308 I art     : Explicit concurrent mark sweep GC freed 8686(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 609us total 24.771ms
,07-05 14:04:26.271  6742  6742 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:26.281  6742  6742 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.281  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,07-05 14:04:26.281   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 18.898ms
,07-05 14:04:26.281  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,07-05 14:04:26.281  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,07-05 14:04:26.301   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 596us total 16.562ms
07-05 14:04:26.301  1016  1041 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,07-05 14:04:26.301  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.311  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.311  6757  6757 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.311  6757  6757 E Zygote  : v2
07-05 14:04:26.311  6757  6757 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:26.311  6757  6757 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:26.311  6757  6757 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,07-05 14:04:26.321  1016  1042 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6757 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
07-05 14:04:26.321  1016  1537 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-05 14:04:26.321  1016  1537 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.321  6757  6757 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.321  1016  1537 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.321  1016  1537 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.321  1016  1537 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
07-05 14:04:26.321  6757  6757 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:26.341  6171  6765 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,07-05 14:04:26.341  6171  6765 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,07-05 14:04:26.351  6757  6757 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:26.361  6757  6757 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.361  1016  1057 I art     : Explicit concurrent mark sweep GC freed 10452(655KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.558ms total 232.342ms
,07-05 14:04:26.361  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,07-05 14:04:26.371  2682  6726 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-05 14:04:26.371  1016  1465 I TactileAssist: enable value -1
,07-05 14:04:26.371  2682  6726 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
07-05 14:04:26.371  1016  1465 I TactileAssist: internal enable value -1
07-05 14:04:26.371  1016  1465 I TactileAssist: intensity value -1
07-05 14:04:26.371  1016  1465 I TactileAssist: saveAppList value true
,07-05 14:04:26.381  1016  1465 I TactileAssist: List of disabled apps :
,07-05 14:04:26.381  6727  6727 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-05 14:04:26.391  6727  6727 D elm:15121: ELMEngine.ELMEngine( context ).
,07-05 14:04:26.391  6727  6727 D elm:15121: MDMBridge.setEnterpriseBridge()
,07-05 14:04:26.391  1016  1057 D PackageManager: delete codoeFile: 
,07-05 14:04:26.391  1016  1057 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
07-05 14:04:26.391  1016  1057 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,07-05 14:04:26.401  1016  1057 D PackageManager: result of delete: 1{892903528}
,07-05 14:04:26.401  6634  6724 D ContactProvider: getAllContactInfoList End
,07-05 14:04:26.401  6634  6724 I syncContacts: thread: 1188, sync time = 491
,07-05 14:04:26.411  2682  2682 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,07-05 14:04:26.411  6630  6630 D AndroidRuntime: Shutting down VM
,07-05 14:04:26.411  1016  1511 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 14:04:26.411  1016  1511 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.411  1016  1511 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.411  1016  1511 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.411  1016  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,07-05 14:04:26.421  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.421  6727  6727 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-05 14:04:26.431  6424  6424 D Compatibility: onReceive() it will make start service
,07-05 14:04:26.431  1016  3706 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,07-05 14:04:26.431  1016  3706 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,07-05 14:04:26.431  6727  6727 D elm:15121: ElmAgentService : onCreate()
,07-05 14:04:26.431  6727  6773 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-05 14:04:26.431  6727  6773 D elm:15121: MainReceiver.listeningToPackageRemoved()
07-05 14:04:26.431  6727  6773 D elm:15121: MDMBridge.getInstance()
07-05 14:04:26.431  6727  6773 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 14:04:26.441  6727  6773 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,07-05 14:04:26.441  1016  1041 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:04:26.441  1016  1041 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:26.441  1016  1041 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:26.441  1016  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 14:04:26.441  1016  1057 D PackageManager: userId{-1}
07-05 14:04:26.441  1016  1057 D PackageManager: andCode{true}
,07-05 14:04:26.441  1016  3706 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.441  1016  3706 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.441  1016  3706 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,07-05 14:04:26.441  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.451  6757  6757 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,07-05 14:04:26.451  1016  1016 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-05 14:04:26.451  1016  1016 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-05 14:04:26.451  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-05 14:04:26.451  1016  1537 D SecContentProvider2: uri = -1 selection = getSealedState
07-05 14:04:26.451  1016  1537 D SecContentProvider2: mCursor = null
,07-05 14:04:26.451  6757  6757 I PopupuiReceiver_KNOX: getSealedState : true
,07-05 14:04:26.451  1016  1511 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
07-05 14:04:26.451  1016  1511 D SecContentProvider2: mCursor = null
,07-05 14:04:26.461  1016  1057 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
07-05 14:04:26.461  6757  6757 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,07-05 14:04:26.461  1016  1511 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
,07-05 14:04:26.461  1016  1511 D SecContentProvider2: mCursor = null
07-05 14:04:26.461  6742  6742 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,07-05 14:04:26.461  6757  6757 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
07-05 14:04:26.461  6757  6757 D PopupuiReceiver: Action package removed
,07-05 14:04:26.461  2864  2864 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-05 14:04:26.461  1016  1016 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicy: uID is 10170
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:04:26.461  1016  3463 D SSRM:bc : MSG_TYPE_APP_REMOVED::
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-05 14:04:26.461  1016  1211 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
07-05 14:04:26.461  1016  1211 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-05 14:04:26.461  1016  1016 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-05 14:04:26.471  1016  1211 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.471  1016  1211 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.471  1016  1211 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
07-05 14:04:26.471  2864  2864 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-05 14:04:26.471  1016  1016 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
07-05 14:04:26.471  2864  2864 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
,07-05 14:04:26.471  2864  2864 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
,07-05 14:04:26.471  2864  2864 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
07-05 14:04:26.471  2864  2864 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
07-05 14:04:26.471  2864  2864 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
07-05 14:04:26.471  2864  2864 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:26.471  2864  2864 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:26.471  2864  2864 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:26.471  2864  2864 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:26.471  2864  2864 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:26.471  2864  2864 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:26.471  2864  2864 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:26.471  6424  6775 D Compatibility: onHandleIntent()
,07-05 14:04:26.471  6424  6775 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,07-05 14:04:26.481  6424  6775 D Compatibility: found: 2
07-05 14:04:26.481  6424  6775 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
07-05 14:04:26.481  6424  6775 D Compatibility: skipping ResolveInfo{121d4e4a com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
07-05 14:04:26.481  6424  6775 D Compatibility: considering ResolveInfo{3b9111bb com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
07-05 14:04:26.481  6424  6775 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,07-05 14:04:26.481  6424  6775 D Compatibility: enabling receiver ResolveInfo{1cdb6d8 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-05 14:04:26.481  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.491  1016  1159 D TaskPersister: removeObsoleteFile: deleting file=43_task.xml
,07-05 14:04:26.491  6424  6775 D Compatibility: enabling receiver ResolveInfo{355cda31 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 14:04:26.491  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.491  6727  6727 D elm:15121: ElmAgentService : onDestroy().
,07-05 14:04:26.491  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:26.491  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:26.501  1016  1536 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:26.501  6424  6775 D Compatibility: enabling receiver ResolveInfo{35ea0516 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,07-05 14:04:26.501  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.501  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.501  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.501  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-05 14:04:26.501  1016  1041 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,07-05 14:04:26.511  6424  6775 D Compatibility: enabling receiver ResolveInfo{7350e97 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,07-05 14:04:26.511  6778  6778 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.511  6778  6778 E Zygote  : v2
07-05 14:04:26.521  6778  6778 I libpersona: KNOX_SDCARD checking this for 10145
07-05 14:04:26.521  6778  6778 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.521  6778  6778 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:26.521  6424  6775 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,07-05 14:04:26.521  6778  6778 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.521  1016  1536 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6778 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
07-05 14:04:26.521  6778  6778 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:26.521  1016  1041 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-05 14:04:26.521  1016  1041 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-05 14:04:26.531  1016  3705 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
07-05 14:04:26.531  1016  3705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
07-05 14:04:26.531  1016  3705 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.531  1016  3705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.531  1016  3705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,07-05 14:04:26.531  1016  1016 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,07-05 14:04:26.531  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.531  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.531  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.531  1016  1016 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.541  6441  6788 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-05 14:04:26.551  6794  6794 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.551  6794  6794 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:26.551  6794  6794 E Zygote  : v2
07-05 14:04:26.551  6794  6794 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.551  6794  6794 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.551  6778  6778 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:26.551  6778  6778 D ActivityThread: Added TimaKeyStore provider,
07-05 14:04:26.551  1016  1016 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6794 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 14:04:26.561  6794  6794 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.561  1016  1255 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-05 14:04:26.561  6794  6794 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:26.561  1016  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.561  1016  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.561  1016  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.561  1016  1255 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.581  6806  6806 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.581  1016  1255 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6806 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 14:04:26.581  6806  6806 E Zygote  : v2
07-05 14:04:26.581  6806  6806 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:26.581  6806  6806 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.581  6806  6806 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.581  6806  6806 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.581  6794  6794 D TimaKeyStoreProvider: TimaSignature is unavailable,
07-05 14:04:26.581  6806  6806 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:26.581  6794  6794 D ActivityThread: Added TimaKeyStore provider
07-05 14:04:26.591  1016  3706 I ActivityManager: Killing 6305:com.osp.app.signin/u0a36 (adj 15): empty #21
07-05 14:04:26.591  1016  3706 I ActivityManager: Killing 5975:com.android.vending/u0a26 (adj 15): empty #21
,07-05 14:04:26.601  1016  3706 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,07-05 14:04:26.601  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.601  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.601  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.601  1016  3706 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.621  6630  6630 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
,07-05 14:04:26.621  6824  6824 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.621  6824  6824 I libpersona: KNOX_SDCARD checking this for 10055
07-05 14:04:26.621  6824  6824 E Zygote  : v2
07-05 14:04:26.621  6824  6824 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.621  6824  6824 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.621  6824  6824 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
07-05 14:04:26.631  6824  6824 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:04:26.631  1016  3706 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6824 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,07-05 14:04:26.641  1016  1511 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,07-05 14:04:26.641  1016  1511 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.641  1016  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.641  1016  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,07-05 14:04:26.641  6806  6806 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:26.641  6806  6806 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.651  6794  6794 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
07-05 14:04:26.651  6794  6794 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
07-05 14:04:26.651  6794  6794 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,07-05 14:04:26.651  1016  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:26.651  1016  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.651  1016  1480 W ActivityManager: userId = 0, bbcId = -10000
,07-05 14:04:26.651  1016  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.651  1016  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
07-05 14:04:26.651  6824  6824 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:26.661  6824  6824 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.671  6806  6806 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:26.671  6794  6794 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 14:04:26.671  6794  6794 I PCWCLIENTTRACE_PushUtil: sales region : global
,07-05 14:04:26.671  6794  6794 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 14:04:26.671  6794  6794 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 14:04:26.671  1016  1511 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:26.671  1016  1511 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.671  1016  1511 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.671  1016  1511 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.671  1016  1511 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 14:04:26.671  6778  6778 D ThemeInfoUtil: getCurrentFestivalName is [null]
07-05 14:04:26.671  6778  6778 D ThemeInfoUtil: isCurrentFestival = false
,07-05 14:04:26.681  1016  1255 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.681  1016  1255 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.681  1016  1255 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.681  1016  1255 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 14:04:26.681  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,07-05 14:04:26.681  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.681  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.681  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.681  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.691  6806  6806 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,07-05 14:04:26.691  1016  3706 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,07-05 14:04:26.691  1016  3706 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,07-05 14:04:26.701  6840  6840 E Zygote  : MountEmulatedStorage()
,07-05 14:04:26.701  6840  6840 E Zygote  : v2
07-05 14:04:26.701  6840  6840 I libpersona: KNOX_SDCARD checking this for 10029
07-05 14:04:26.701  6840  6840 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.701  6840  6840 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.701  1016  3705 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6840 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,07-05 14:04:26.701  6824  6824 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,07-05 14:04:26.701  6840  6840 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.701  6840  6840 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:26.711  1016  3705 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,07-05 14:04:26.711  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.711  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.711  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.711  1016  3705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:26.731  6854  6854 E Zygote  : MountEmulatedStorage(),
07-05 14:04:26.731  6854  6854 E Zygote  : v2
07-05 14:04:26.731  6854  6854 I libpersona: KNOX_SDCARD checking this for 10148
07-05 14:04:26.731  6854  6854 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:26.731  6854  6854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,07-05 14:04:26.741  6824  6824 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
07-05 14:04:26.741  6854  6854 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,07-05 14:04:26.741  6824  6824 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
07-05 14:04:26.741  6824  6824 D UserAnalysis: Create SecureDbHelper
,07-05 14:04:26.741  6840  6840 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:04:26.741  1016  3705 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6854 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a
07-05 14:04:26.741  6840  6840 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.741  1016  3705 I ActivityManager: Killing 6370:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,07-05 14:04:26.741  6854  6854 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:26.761  1016  1465 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:26.761  1016  1465 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,07-05 14:04:26.761  1016  1465 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.761  1016  1465 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
07-05 14:04:26.761  1016  1465 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,07-05 14:04:26.761  6854  6854 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:26.761  6854  6854 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:26.781  6824  6824 D IntelligenceServiceApplication: onCreate()
,07-05 14:04:26.781  6824  6824 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
07-05 14:04:26.781  6824  6824 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.intelligenceservice/databases/privacy" with flag (131138) and mode_t (0) due to error (30)
,07-05 14:04:26.791  6824  6824 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.intelligenceservice/databases/privacy'.
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:26.791  6824  6824 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: Couldn't open privacy for writing (will try read-only):
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at ,android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.useranalysis.privacy.PrivacyManager.isUserConsented(PrivacyManager.java:69)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at com.samsung.android.intelligenceservice.IntelligenceServiceApplication$1.run(IntelligenceServiceApplication.java:46)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.os.Handler.handleCallback(Handler.java:739)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:26.791  6824  6824 E SQLiteOpenHelper: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:26.791  6473  6473 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
07-05 14:04:26.791  6824  6824 W SQLiteOpenHelper: Opened privacy in read-only mode
07-05 14:04:26.791  6473  6473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
07-05 14:04:26.801  6824  6824 D IntelligenceServiceApplication: no applications having user consent for prediction
07-05 14:04:26.801  1016  1479 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
07-05 14:04:26.801  1016  1479 W ActivityManager: userId = 0, bbcId = -10000
07-05 14:04:26.801  1016  1479 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
07-05 14:04:26.801  1016  1479 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
07-05 14:04:26.801  1016  1479 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
07-05 14:04:26.801  1016  1536 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
07-05 14:04:26.801  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.801  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.801  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.801  1016  1536 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:26.811  6473  6473 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
07-05 14:04:26.811  6473  6871 I FilterInstaller: FilterPackageService : ACTION_REMOVED
07-05 14:04:26.811  6473  6871 D FilterUnInstaller: before removeFromFS
07-05 14:04:26.821  6441  6788 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-05 14:04:26.821  6872  6872 E Zygote  : MountEmulatedStorage()
07-05 14:04:26.821  6872  6872 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:26.821  6872  6872 E Zygote  : v2
07-05 14:04:26.821  6872  6872 I libpersona: KNOX_SDCARD not a persona
07-05 14:04:26.821  6441  6788 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-05 14:04:26.821  6872  6872 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
07-05 14:04:26.821  6854  6854 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db" with flag (131138) and mode_t (0) due to error (30)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.provider.shootingmodeprovider/databases/shootingmodemanager.db'.
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.initializeSQLiteStatements(ShootingModeProvider.java:277)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider.onCreate(ShootingModeProvider.java:240)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1729)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1698)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5702)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237),
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:26.821  6854  6854 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:26.821  6854  6854 D AndroidRuntime: Shutting down VM
07-05 14:04:26.821  1016  1536 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6872 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 14:04:26.821  6854  6854 E AndroidRuntime: FATAL EXCEPTION: main
07-05 14:04:26.821  6854  6854 E AndroidRuntime: Process: com.samsung.android.provider.shootingmodeprovider, PID: 6854
07-05 14:04:26.821  6854  6854 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.shootingmodeprovider.ShootingModeProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5705)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5297)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5237)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-05 14:04:26.821  6854  6854 E AndroidRuntime: 	
```
