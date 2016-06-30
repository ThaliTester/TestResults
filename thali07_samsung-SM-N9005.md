#### Test 7578926851a8f91_thali07_samsung-SM-N9005 Logs


```
--------- beginning of main,
06-30 12:51:16.015  6988  6988 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
--------- beginning of system
06-30 12:51:16.025   767   924 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
06-30 12:51:16.025   767   924 D ActivityManager: com.sec.android.widgetapp.SPlannerAppWidget, Starting
06-30 12:51:16.035   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.035   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.035   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.035   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.095  7062  7062 E Zygote  : MountEmulatedStorage()
06-30 12:51:16.115   767   924 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7062 uid=10171 gids={50171, 9997} abi=armeabi-v7a
06-30 12:51:16.115   767  3234 I ActivityManager: Killing 6402:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
06-30 12:51:16.145  7062  7062 E Zygote  : v2
06-30 12:51:16.145  7062  7062 I libpersona: KNOX_SDCARD checking this for 10171
06-30 12:51:16.145  7062  7062 I libpersona: KNOX_SDCARD not a persona
06-30 12:51:16.165  7062  7062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:16.165  7062  7062 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:51:16.165  7062  7062 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
06-30 12:51:16.175   331   331 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 317us total 56.031ms
06-30 12:51:16.185   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 9.588ms
06-30 12:51:16.195   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 269us total 9.809ms
06-30 12:51:16.215  7062  7062 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:51:16.215  7062  7062 D ActivityThread: Added TimaKeyStore provider
06-30 12:51:16.235  7062  7062 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
06-30 12:51:16.235  7062  7062 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:51:16.235  7062  7062 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
06-30 12:51:16.265   767  1351 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
06-30 12:51:16.265   767  1351 D ActivityManager: caller:android.app.ApplicationThreadProxy@123f9747, r.packageName :com.android.calendar
06-30 12:51:16.275   767   782 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
06-30 12:51:16.275   767   782 D ActivityManager: caller:android.app.ApplicationThreadProxy@19dfd89d, r.packageName :com.android.calendar
06-30 12:51:16.285   767  1351 I ActivityManager: Killing 6420:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
06-30 12:51:16.455  7068  7068 D AndroidRuntime: 
06-30 12:51:16.455  7068  7068 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 12:51:16.455  7068  7068 D AndroidRuntime: CheckJNI is OFF
06-30 12:51:16.455  7068  7068 D AndroidRuntime: readGMSProperty: start
06-30 12:51:16.455  7068  7068 D AndroidRuntime: readGMSProperty: already setted!!
06-30 12:51:16.455  7068  7068 D AndroidRuntime: readGMSProperty: end
06-30 12:51:16.455  7068  7068 D AndroidRuntime: addProductProperty: start
06-30 12:51:16.645  7068  7068 E AffinityControl: AffinityControl: registerfunction enter
06-30 12:51:16.665  7068  7068 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:51:16.685   767  1439 E PersonaManagerService: inState():  stateMachine is null !!
06-30 12:51:16.685   767  1439 I PersonaManagerService: PersonaId don't exist
06-30 12:51:16.685   767  1439 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 12:51:16.685   767  1439 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 12:51:16.685   767  1439 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:51:16.685   767  1439 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 12:51:16.695   767  1439 W ActivityManager: mDVFSHelper.acquire()
06-30 12:51:16.695   767  1439 D FocusedStackFrame: Set to : 0
06-30 12:51:16.695   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.695   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.695   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.695   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:16.785  7111  7111 E Zygote  : MountEmulatedStorage()
06-30 12:51:16.785   767  1439 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7111 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:51:16.785  7111  7111 E Zygote  : v2
06-30 12:51:16.785  7111  7111 I libpersona: KNOX_SDCARD checking this for 10079
06-30 12:51:16.785  7111  7111 I libpersona: KNOX_SDCARD not a persona
06-30 12:51:16.805  7111  7111 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:16.805  7111  7111 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:51:16.805  7111  7111 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 12:51:16.805   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 12:51:16.805   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:51:16.805   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
06-30 12:51:16.805   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:51:16.805  7068  7068 D AndroidRuntime: Shutting down VM
06-30 12:51:16.835  7111  7111 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:51:16.835  7111  7111 D ActivityThread: Added TimaKeyStore provider
06-30 12:51:16.835   767  1222 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
06-30 12:51:16.835   767  1222 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
06-30 12:51:16.835   767  1222 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-30 12:51:16.835   767  1222 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
06-30 12:51:16.835   767  1222 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
06-30 12:51:16.835   767   767 V ActivityManager: Display changed displayId=0
06-30 12:51:16.865  1432  1432 D SurfaceWidgetView: destroyHardwareResources():1014931735
06-30 12:51:16.875   767  3075 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 12:51:16.875  7111  7111 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
06-30 12:51:16.925   266  1492 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
06-30 12:51:16.925   266   416 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
06-30 12:51:16.945  1735  1745 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
06-30 12:51:16.945  1432  1432 V ActivityThread: updateVisibility : ActivityRecord{bfb58d8 token=android.os.BinderProxy@3b50ded6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 12:51:16.945  1432  1432 D Launcher: onTrimMemory. Level: 20
06-30 12:51:16.975  7111  7111 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 12:51:16.975  7111  7111 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
06-30 12:51:16.985  7111  7111 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5996-5998)
06-30 12:51:16.985  7111  7111 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:17.005  7111  7111 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c56fdbe}
06-30 12:51:17.015  7111  7111 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:17.015  7111  7111 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:51:17.045  7111  7111 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 12:51:17.045  7111  7111 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:17.045  7111  7111 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 12:51:17.065  7111  7111 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 12:51:17.065  7111  7111 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 12:51:17.065  7111  7111 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
06-30 12:51:17.075  7111  7111 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 12:51:17.075  7111  7111 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 12:51:17.075  7111  7111 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 12:51:17.075  7111  7111 I Adreno-EGL: Local Branch: mybranch5813579
06-30 12:51:17.075  7111  7111 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 12:51:17.075  7111  7111 I Adreno-EGL: Local Patches: NONE
06-30 12:51:17.075  7111  7111 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
06-30 12:51:17.315  7111  7147 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
06-30 12:51:17.365  7111  7111 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:17.365   767   924 W ActivityManager: Activity pause timeout for ActivityRecord{265460e3 u0 com.test.thalitest/.MainActivity t41}
06-30 12:51:17.375  7111  7111 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:51:17.395  7111  7111 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 12:51:17.405  7111  7111 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:17.405  7111  7111 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:17.495   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 12:51:17.505  7111  7111 D Activity: performCreate Call secproduct feature valuefalse
06-30 12:51:17.505  7111  7111 D Activity: performCreate Call debug elastic valuetrue
06-30 12:51:17.535  7111  7164 D OpenGLRenderer: Render dirty regions requested: true
06-30 12:51:17.545   767  1466 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 12:51:17.545   767  1466 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 12:51:17.545   767  1466 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 12:51:17.545   767   767 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 12:51:17.545   767   767 D PersonaManagerService: getPersonasForUser(): returning null!
06-30 12:51:17.585  7111  7111 V ActivityThread: updateVisibility : ActivityRecord{2e36ab88 token=android.os.BinderProxy@7bf277a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 12:51:17.605   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
06-30 12:51:17.615   767  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 12:51:17.625   767  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 12:51:17.645   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 12:51:17.645   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:51:17.645   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
06-30 12:51:17.645   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 12:51:17.645  7111  7164 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:51:17.675  7111  7164 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cffd58 ,&mEglDisplay = 1 , &mEglConfig = 8 
06-30 12:51:17.685  7111  7164 D OpenGLRenderer: Enabling debug mode 0
06-30 12:51:17.785   767  3149 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 12:51:17.805   767  7167 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 12:51:17.825   767  1055 W ActivityManager: mDVFSHelper.release()
06-30 12:51:17.825   767  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{265460e3 u0 com.test.thalitest/.MainActivity t41} time:96831
06-30 12:51:17.845  1691  1691 I SamsungIME: getCurrentCandidateView
06-30 12:51:17.855  7111  7111 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 12:51:17.865  7111  7111 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7bf277a time:96877
06-30 12:51:17.905  1691  1691 D SamsungIME: Dismiss ExpandCandiate
06-30 12:51:17.955  7111  7111 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7111
06-30 12:51:17.995  1691  1691 I SamsungIME: getDebugLevel  : 0x4f4c
06-30 12:51:18.085  1691  1691 I SamsungIME: getDebugLevel  : 0x4f4c
06-30 12:51:18.115  1691  1691 I SamsungIME: KeybaordView init() : load resources
06-30 12:51:18.145  1691  1691 I SamsungIME: getCurrentKeyboard
06-30 12:51:18.155  1691  1691 I SamsungIME: getTextKeyboard
06-30 12:51:18.165  7111  7111 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:51:18.175  1691  1691 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
06-30 12:51:18.295   298   298 E SMD     : DCD ON
06-30 12:51:18.365  7111  7174 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1356875904
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:51:18.375  7111  7174 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15b006b8 added. We now have 1 listener(s)
06-30 12:51:18.385  7111  7174 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
06-30 12:51:18.385  7111  7174 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
06-30 12:51:18.385  7111  7174 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:51:18.395  7111  7174 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:51:18.395  7111  7174 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@94007f7 added. We now have 1 listener(s)
06-30 12:51:18.395  7111  7174 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:51:18.415  7111  7174 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
06-30 12:51:18.425  7111  7174 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 12:51:18.425  7111  7174 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 12:51:18.425  7111  7174 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:51:18.425  7111  7174 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
06-30 12:51:18.435   767  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:51:18.435  7111  7174 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
06-30 12:51:18.435  7111  7174 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:51:18.435  7111  7174 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:51:18.435  7111  7174 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:51:18.435   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 12:51:18.445  7111  7111 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
06-30 12:51:18.445   767   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 12:51:18.455  7111  7111 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:51:18.515  7111  7111 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:51:18.605  1691  7180 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-30 12:51:19.265   767  1114 V AlarmManager: waitForAlarm result :4
06-30 12:51:19.265   767   924 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
06-30 12:51:19.265   767   924 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
06-30 12:51:19.265   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:19.265   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:19.265   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:19.265   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:19.305  7200  7200 E Zygote  : MountEmulatedStorage()
06-30 12:51:19.305  7200  7200 E Zygote  : v2
06-30 12:51:19.305  7200  7200 I libpersona: KNOX_SDCARD checking this for 10201
06-30 12:51:19.305  7200  7200 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:19.305   767   924 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7200 uid=10201 gids={50201, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,06-30 12:51:19.325  7111  7188 W jxcore-log: Initializing JXcore engine
06-30 12:51:19.325  7111  7188 W jxcore-log: JXcore engine is ready
,06-30 12:51:19.345  7200  7200 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:19.345  7200  7200 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:51:19.345  7200  7200 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:51:19.345   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
06-30 12:51:19.345   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:51:19.345   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:51:19.345   767   782 D BatteryService: stay LED for fully charged
06-30 12:51:19.345   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:51:19.345  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:51:19.345  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:51:19.345   767   767 I MotionRecognitionService: Plugged
06-30 12:51:19.355   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:51:19.355  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:51:19.355  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:51:19.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:19.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:19.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:19.355  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:51:19.395  1773  1773 E auditd  : In denial and Property audit_ondenial is set to 1 
,06-30 12:51:19.395  1773  1773 E audit   : type=1400 msg=audit(1467283879.395:203): avc:  denied  { ioctl } for  pid=7188 comm="Thread-1189" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3089 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 12:51:19.395  1773  1773 E audit   :  SEPF_SM-N9005_5.0-1_0032
06-30 12:51:19.395  1773  1773 E audit   : 
06-30 12:51:19.395   767  1030 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
06-30 12:51:19.395  7200  7200 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 12:51:19.395   767  1030 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
06-30 12:51:19.395  1773  1773 E audit   : type=1300 msg=audit(1467283879.395:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a3008d8 items=0 ppid=331 ppcomm=main pid=7188 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1189" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 12:51:19.395  1773  1773 E audit   : type=1320 msg=audit(1467283879.395:203): 
,06-30 12:51:19.395  7200  7200 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:19.395   767  1030 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,06-30 12:51:19.405  7200  7200 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,06-30 12:51:19.405  7200  7200 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,06-30 12:51:19.415  7111  7188 W jxcore-log: Starting JXcore engine
,06-30 12:51:19.425  7200  7200 D UMC:Core: onCreate(): 
,06-30 12:51:19.485  7200  7200 D USER_AGENT: UMC/1.1.40 (SM-N9005) SAFE-5.3 KNOX-2.3
,06-30 12:51:19.495  7111  7188 W jxcore-log: Platform android
06-30 12:51:19.495  7111  7188 W jxcore-log: 
06-30 12:51:19.495  7111  7188 W jxcore-log: Process ARCH arm
06-30 12:51:19.495  7111  7188 W jxcore-log: 
,06-30 12:51:19.575  7200  7200 D [SAMSUNG SMARCART NATIVE]: initialize...
,06-30 12:51:19.575  7200  7200 D [SAMSUNG SMARCART NATIVE]: DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,06-30 12:51:19.585  7200  7200 I CSTORAGE: ================================================
,06-30 12:51:19.585  7200  7200 I CSTORAGE:  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
06-30 12:51:19.585  7200  7200 I CSTORAGE: ================================================
,06-30 12:51:19.585  7200  7200 I TZ_CCM_C_GetFunctionList: : TZ_CCM_C_GetFunctionList was called
06-30 12:51:19.585  7200  7200 D [SAMSUNG SMARCART NATIVE]: FINISHED: initialize rv:0
,06-30 12:51:19.595   767  3075 D SSRM:n  : SIOP:: AP = 370, PST = 407, CUR = 300
,06-30 12:51:19.645  7200  7200 D UMC:SecurityUtils: Loaded server certificates: 0
,06-30 12:51:19.645  7200  7200 D UMC:SecurityUtils: Loaded server certificates: 0
,06-30 12:51:19.645  7200  7200 D UMC:SecurityUtils: timaVersion on the device: 3.0
,06-30 12:51:19.645  7200  7200 D UMC:CloudMDMSecurity: New Flow
,06-30 12:51:19.645   767   782 D TimaService: TIMA3: in ccmRegisterForDefaultCertificate
06-30 12:51:19.645   767   782 D TimaService: TIMA: in getTimaVersion
06-30 12:51:19.645   767   782 I         : CCM JNI: In ccm_register_for_default_cert
06-30 12:51:19.645   767   782 I         : CCM JNI: In ccm_create_slot
,06-30 12:51:19.645   767   782 I TZ_CCM_C_Initialize: : DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
06-30 12:51:19.645   767   782 I TZ_CCM_C_Initialize: : pInitArgs 0xb3deb814 has not called C_Init before.
06-30 12:51:19.645   767   782 I TZ_CCM_C_Initialize: : &ctx = 0x9feb2c1c
06-30 12:51:19.645   767   782 I TLC_TZ_CCM: : creating new ccm context...
06-30 12:51:19.645   767   782 I TLC_TZ_CCM: : initializing ccm context...
06-30 12:51:19.645   767   782 I TLC_TZ_CCM: : root = /firmware/image, root_strlen = 15
06-30 12:51:19.645   767   782 I TLC_TZ_CCM: : process = tz_ccm, process_strlen = 6
06-30 12:51:19.645   767   782 I TZ: client_server_communication: input max_sendmsg_size = 19420
06-30 12:51:19.645   767   782 I TZ: client_server_communication: input max_recvmsg_size = 19420
06-30 12:51:19.645   767   782 I TZ: client_server_communication: root = /firmware/image, root_len = 15
06-30 12:51:19.645   767   782 I TZ: client_server_communication: process = tz_ccm, process_strlen = 6
06-30 12:51:19.645   767   782 I TZ: client_server_communication: aligned max_sendmsg_size = 19456
06-30 12:51:19.645   767   782 I TZ: client_server_communication: aligned max_recvmsg_size = 19456
06-30 12:51:19.645   767   782 I TZ: client_server_communication: Client_Server_Open was called
06-30 12:51:19.645   767   782 I TZ: client_server_communication: IClientServer::IClientServer()
,06-30 12:51:19.655   767   782 I TZ: client_server_communication: BpClientServer::BpClientServer()
06-30 12:51:19.655   767   782 I TZ: client_server_communication: IClientServer::~IClientServer()
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: BnCCM::onTransact(0) 16
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: OPENSWCONN
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: creating new ccm context...
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: initializing ccm context...
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: root = /firmware/image, root_strlen = 15
06-30 12:51:19.655  1101  1105 I TZ_CCM_SERVER: process = tz_ccm, process_strlen = 6
06-30 12:51:19.655  1101  1105 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
06-30 12:51:19.655  1101  1105 I TZ: qc_tlc_communication: process = tz_ccm, process_strlen = 6
06-30 12:51:19.655  1101  1105 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 19456 = 0x4c00
06-30 12:51:19.655  1101  1105 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 19456 = 0x4c00
06-30 12:51:19.655  1101  1105 I TZ: qc_tlc_communication: max_message_size = 38912 = 0x9800
06-30 12:51:19.655  1101  1105 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x9800
06-30 12:51:19.655  1101  1105 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:51:19.665  1101  1105 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 12:51:19.665  1101  1105 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,06-30 12:51:19.665   767   782 I TZ: client_server_communication: OpenSWConn(CCM) is successful
06-30 12:51:19.665   767   782 I TZ: client_server_communication: Client_Server_Open succeeded, serverName = CCM
06-30 12:51:19.665   767   782 I TZ_CCM_C_Initialize: : ctx = 0x9af426d0, comm = 0x9bd014a8, sendmsg = 0x9afe6000, recvmsg = 0x9afeac00
06-30 12:51:19.665   767   782 I TZ_init: : TZ_init: sending initialization request...
06-30 12:51:19.665   767   782 I TZ: client_server_communication: Cmd id = 2, len = 19456
06-30 12:51:19.665   767   782 I TZ: client_server_communication: Calling Communicate()
,06-30 12:51:19.665  1101  1101 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
06-30 12:51:19.665  1101  1101 I TZ_CCM_SERVER: COMM
,06-30 12:51:19.665   767   782 I TZ_init: : TZ_init: successful initialization
,06-30 12:51:19.665   767   782 I TLC_TZ_COMMON: key_db_init: : Exercising TZ_DB_INIT in TLC
06-30 12:51:19.665   767   782 I TZ: client_server_communication: Cmd id = 17, len = 19456
06-30 12:51:19.665   767   782 I TZ: client_server_communication: Calling Communicate()
,06-30 12:51:19.665  1101  1105 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
06-30 12:51:19.665  1101  1105 I TZ_CCM_SERVER: COMM
,06-30 12:51:19.675   767   782 I TZ_COMMON: tlc_key_db_util: : DB Operation suceeded
06-30 12:51:19.675   767   782 I TLC_TZ_CCM: register for default cert: : Exercising TZ_CCM_register_default_TLC
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Cmd id = 25, len = 19456
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Calling Communicate()
06-30 12:51:19.675  1101  1101 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
06-30 12:51:19.675  1101  1101 I TZ_CCM_SERVER: COMM
06-30 12:51:19.675   767   782 I TLC_TZ_CCM: register for default cert: : TZ_CCM_register_default_TLC_END: DB file size to update is 0
06-30 12:51:19.675   767   782 I TLC_TZ_CCM: register for default cert: : TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
06-30 12:51:19.675   767   782 I TZ_CCM_C_Finalize: : DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Cmd id = 41, len = 19456
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Calling Communicate()
06-30 12:51:19.675  1101  1105 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
06-30 12:51:19.675  1101  1105 I TZ_CCM_SERVER: COMM
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Client_Server_Close was called
06-30 12:51:19.675  1101  1101 I TZ_CCM_SERVER: BnCCM::onTransact(1) 16
06-30 12:51:19.675  1101  1101 I TZ_CCM_SERVER: CLOSESWCONN
06-30 12:51:19.675  1101  1101 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-30 12:51:19.675  1101  1101 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
06-30 12:51:19.675   767   782 I TZ: client_server_communication: Client_Server_Close succeeded
06-30 12:51:19.675  7200  7200 D UMC:CloudMDMSecurity: ccmRegisterForDefaultCertificate: 0
06-30 12:51:19.675  7200  7200 D UMC:CloudMDMSecurity: TIMA service call for password change success!!
,06-30 12:51:19.685  7200  7200 D UMC:AdminManager: init - start
,06-30 12:51:19.715  7200  7200 D UMC:AdminManager: loadAdmins
,06-30 12:51:19.715  7111  7188 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:51:19.715  7111  7188 I jxcore-log: 
,06-30 12:51:19.715  7111  7188 W jxcore-log: JXcore engine is started
06-30 12:51:19.725  7200  7200 D UMC:AdminManager: startPolicyHandlers
,06-30 12:51:19.725  7200  7200 I UMC:TestPolicyHandler: Setup is called in testpolicyhandler
,06-30 12:51:19.725  7200  7200 D UMC:AdminManager: init - end
06-30 12:51:19.725  7111  7174 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:51:19.725  7200  7200 V UMC:AlarmHandler: Enter loadList
06-30 12:51:19.725  7111  7111 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 12:51:19.745  7200  7200 D GSLBManager: migrateStoredUrlFromOldPref
,06-30 12:51:19.745  7200  7200 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,06-30 12:51:19.745  7200  7200 D UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,06-30 12:51:19.745  7200  7200 E UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
06-30 12:51:19.745  7200  7200 D UMC:UMCAdmin: deactivateUMCAdmin : -1
,06-30 12:51:19.745  7200  7200 D UMC:UMCAdmin: isContainer : 0
,06-30 12:51:19.745   767  3319 W LicenseLogService: log() failed
,06-30 12:51:19.755   767  1470 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,06-30 12:51:19.755  7200  7200 E UMC:UMCAdmin: No active admin owned by uid 10201
06-30 12:51:19.755  7200  7200 D UMC:UMCAdmin: isContainer : 0
,06-30 12:51:19.755  7200  7200 D UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,06-30 12:51:19.755  7200  7200 V UMC:AlarmHandler: onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,06-30 12:51:19.755   767  1466 I ActivityManager: Killing 5956:sstream.app/u0a25 (adj 15): emptyCount ##41
,06-30 12:51:19.755  7200  7200 D QuickStartReceiver: Msg Id : 2
06-30 12:51:19.755  7200  7200 D QuickStartReceiver: model : SM-N9005
,06-30 12:51:19.755  7200  7200 D QuickStartReceiver: id : 100
,06-30 12:51:19.765   767   767 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,06-30 12:51:19.765   767   767 I BackgroundCompactionService: onStart. jobID=801
,06-30 12:51:19.765   767   767 I BackgroundCompactionService: onStart done. jobID=801
,06-30 12:51:19.775  7011  7011 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,06-30 12:51:19.775  7011  7011 D SecurityLogAgent:  SeDenialReceiver : File path = null
,06-30 12:51:19.775   767  7231 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
,06-30 12:51:19.795   767  7231 I BackgroundCompactionService: compact_memory command done
,06-30 12:51:21.295   298   298 E SMD     : DCD ON
,06-30 12:51:24.305   298   298 E SMD     : DCD ON
,06-30 12:51:26.715   767  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,06-30 12:51:27.305   298   298 E SMD     : DCD ON
,06-30 12:51:29.465   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:51:29.485   767  1222 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:29.515   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:51:29.515   767  3290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:51:29.515   767  3290 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:51:29.515   767  3290 D BatteryService: stay LED for fully charged
06-30 12:51:29.515   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:51:29.525   767   767 I MotionRecognitionService: Plugged
06-30 12:51:29.525   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:51:29.525  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:51:29.525  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:51:29.525  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 12:51:29.525  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:29.525  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:29.525  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 12:51:29.525  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:29.525  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:51:29.605   767  1059 I PowerManagerService: [PWL] Off : 30s ago
06-30 12:51:29.605   767  1059 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
06-30 12:51:29.605   767  1059 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
06-30 12:51:29.605   767  1059 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.notifications.GunsService' (uid=10015, pid=1787, ws=null) (elapsedTime=52648)
,06-30 12:51:29.635   767  3075 D SSRM:n  : SIOP:: AP = 390, PST = 405, CUR = 300
,06-30 12:51:29.635  7111  7188 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 12:51:29.635  7111  7188 I jxcore-log: 
,06-30 12:51:29.635  7111  7188 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 12:51:29.635  7111  7188 I jxcore-log: 
,06-30 12:51:29.635   767  1467 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
06-30 12:51:29.635  7111  7188 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,06-30 12:51:29.645  7111  7188 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,06-30 12:51:29.645  7111  7188 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 12:51:29.645  7111  7188 I jxcore-log: 
,06-30 12:51:29.645  7111  7188 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 12:51:29.645  7111  7188 I jxcore-log: 
,06-30 12:51:29.755   767  1063 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,06-30 12:51:29.755   767   767 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,06-30 12:51:29.765   767  1055 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,06-30 12:51:29.765   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,06-30 12:51:29.765   767  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 12:51:29.775  3671  3671 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.sec.enterprise.knox.cloudmdm.smdms, uid = -1
,06-30 12:51:29.775  1420  1420 D RegisteredServicesCache: empty dynamic service
,06-30 12:51:29.775  1432  1432 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,06-30 12:51:29.775   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,06-30 12:51:29.785  1432  1432 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:29.785  1432  1432 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 12:51:29.785   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,06-30 12:51:29.785   767   782 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
06-30 12:51:29.785   767   782 D ActivityManager: sstream.app, Starting
,06-30 12:51:29.785   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:29.785   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:29.785   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:29.785  1432  1432 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
06-30 12:51:29.785   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:29.805  1432  1432 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 12:51:29.805   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,06-30 12:51:29.805   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,06-30 12:51:29.815   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,06-30 12:51:29.815   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,06-30 12:51:29.825   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,06-30 12:51:29.825   767   782 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=7262 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,06-30 12:51:29.825  7262  7262 E Zygote  : MountEmulatedStorage()
,06-30 12:51:29.825  7262  7262 E Zygote  : v2
06-30 12:51:29.825  7262  7262 I libpersona: KNOX_SDCARD checking this for 10025
06-30 12:51:29.825  7262  7262 I libpersona: KNOX_SDCARD not a persona
06-30 12:51:29.835   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,06-30 12:51:29.835  1432  1432 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:29.835  1432  1432 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 12:51:29.835   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,06-30 12:51:29.835   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,06-30 12:51:29.845   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 12:51:29.845   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,06-30 12:51:29.855  7262  7262 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:29.855  7262  7262 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:51:29.855  1432  1432 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,06-30 12:51:29.855  1432  1432 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:29.855   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 12:51:29.855  1432  1432 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,06-30 12:51:29.855  7262  7262 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:51:29.855   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,06-30 12:51:29.855   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,06-30 12:51:29.865   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,06-30 12:51:29.865   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,06-30 12:51:29.865   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,06-30 12:51:29.865   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,06-30 12:51:29.875   767  3290 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,06-30 12:51:29.875   767  3290 D SecContentProvider2: mCursor = null
,06-30 12:51:29.875   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,06-30 12:51:29.885   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,06-30 12:51:29.885   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,06-30 12:51:29.885   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.895   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,06-30 12:51:29.895   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,06-30 12:51:29.895   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.895   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,06-30 12:51:29.905  7262  7262 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:29.905  7262  7262 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:29.915   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,06-30 12:51:29.915   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,06-30 12:51:29.915  7262  7262 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,06-30 12:51:29.925   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,06-30 12:51:29.925  7262  7262 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:29.925   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.925   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,06-30 12:51:29.925   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.925   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,06-30 12:51:29.935   767   767 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,06-30 12:51:29.935   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.935   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.935   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.935   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,06-30 12:51:29.935   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.945   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,06-30 12:51:29.945   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.945   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.945   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,06-30 12:51:29.945   767   918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:51:29.945   767   918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:51:29.955   767   918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:29.955   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.955   767   918 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,06-30 12:51:29.955   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,06-30 12:51:29.965   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,06-30 12:51:29.965  7262  7262 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,06-30 12:51:29.965  7262  7262 D MVFD_interface: <<<  caMVFace_FaceInit
,06-30 12:51:29.965   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.965   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,06-30 12:51:29.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 12:51:29.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 12:51:29.975   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,06-30 12:51:29.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.975   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,06-30 12:51:29.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 12:51:29.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 12:51:29.985   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,06-30 12:51:29.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:29.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 12:51:29.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 12:51:30.005   265   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
06-30 12:51:30.005   265   541 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:51:30.005  7262  7262 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,06-30 12:51:30.015   265   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
06-30 12:51:30.015   265   541 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:51:30.015  7262  7262 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,06-30 12:51:30.035   767  1337 E Watchdog: !@Sync 3
,06-30 12:51:30.065  7262  7262 D HockeyApp: Current handler class = sstream.app.util.Log$1
,06-30 12:51:30.085  7111  7188 I jxcore-log: Unit Test app is loaded
06-30 12:51:30.085  7111  7188 I jxcore-log: 
,06-30 12:51:30.095  7111  7188 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
06-30 12:51:30.095  7111  7188 I jxcore-log: 
,06-30 12:51:30.095  7111  7111 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,06-30 12:51:30.095  7111  7188 I jxcore-log: My device name is: samsung-SM-N9005
06-30 12:51:30.095  7111  7188 I jxcore-log: 
,06-30 12:51:30.155  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,06-30 12:51:30.165  7262  7298 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,06-30 12:51:30.175  7262  7298 D ApplicationCompatibleReceiver: com.sec.chaton Already existed in setting table , SKIP!!!
,06-30 12:51:30.175  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
,06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:51:30.195  7262  7298 D ApplicationCompatibleReceiver: com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
,06-30 12:51:30.195  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:51:30.195  7262  7298 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,06-30 12:51:30.205  7262  7298 D ApplicationCompatibleReceiver: com.sec.pcw Already existed in setting table , SKIP!!!
,06-30 12:51:30.205  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,06-30 12:51:30.205  7262  7298 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:51:30.205  7262  7298 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 12:51:30.205  7262  7298 D ApplicationCompatibleReceiver: com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
,06-30 12:51:30.205  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:30.215  7262  7298 E SQLiteLog: (1299) abort at 20 in [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,?,?,?,?,?
,06-30 12:51:30.215  7262  7298 E SQLiteDatabase: Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131625003 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: android.database.sqlite.SQLiteConstraintException: NOT NULL constraint failed: config.stream_id (code 1299)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
06-30 12:51:30.215  7262  7298 E SQLiteDatabase: 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
,06-30 12:51:30.215  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
06-30 12:51:30.215  7262  7298 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 12:51:30.225  7262  7298 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
06-30 12:51:30.225  7262  7298 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 12:51:30.225  7262  7298 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
06-30 12:51:30.225  7262  7298 D ApplicationCompatibleReceiver: com.sec.android.gallery3d Already existed in setting table , SKIP!!!
06-30 12:51:30.225  7262  7298 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
06-30 12:51:30.235  7262  7298 D ApplicationCompatibleReceiver: com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
06-30 12:51:30.235  7262  7298 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
06-30 12:51:30.235  7262  7298 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
06-30 12:51:30.235  7262  7298 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
06-30 12:51:30.245  7262  7298 D ApplicationCompatibleReceiver: com.samsung.android.snote Already existed in setting table , SKIP!!!
,06-30 12:51:30.295   767  1470 I ActivityManager: Killing 6437:com.sec.pcw.device/1000 (adj 15): emptyCount ##41
,06-30 12:51:30.305   298   298 E SMD     : DCD ON
,06-30 12:51:30.325   767  1629 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,06-30 12:51:30.325   767  1629 D ActivityManager: caller:android.app.ApplicationThreadProxy@32704df2, r.packageName :com.google.android.googlequicksearchbox
,06-30 12:51:30.335   767   784 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
06-30 12:51:30.335   767   784 D ActivityManager: com.samsung.android.app.FileShareServer, Starting
,06-30 12:51:30.335  1503  7302 I UpdateIcingCorporaServi: Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
06-30 12:51:30.335   767   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.335   767   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.335   767   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.335   767   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:30.355  7262  7291 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:51:30.355  7262  7291 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:51:30.355  7262  7291 I System.out: (HTTPLog)-Thread-1185-257689092: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:51:30.355  7262  7291 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:30.355  7262  7289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:30.375  7262  7290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:30.375  7305  7305 E Zygote  : MountEmulatedStorage()
06-30 12:51:30.375  7305  7305 E Zygote  : v2
06-30 12:51:30.375  7305  7305 I libpersona: KNOX_SDCARD checking this for 10088
06-30 12:51:30.375  7305  7305 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:30.385   767   784 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7305 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:51:30.405  1503  7302 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 66 ms] updated apps [took 66 ms] 
,06-30 12:51:30.415  7305  7305 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:30.415  7305  7305 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:51:30.415  7305  7305 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:51:30.425  7262  7291 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:51:30.425  7262  7291 I qtaguid : Tagging socket 50 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7262, getuid(): 10025
,06-30 12:51:30.435  7262  7290 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:51:30.435  7262  7290 I qtaguid : Tagging socket 53 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7262, getuid(): 10025
,06-30 12:51:30.435  7262  7289 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
06-30 12:51:30.435  7262  7289 I qtaguid : Tagging socket 52 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 7262, getuid(): 10025
,06-30 12:51:30.435  7305  7305 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:30.435  7305  7305 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:30.455  7305  7305 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,06-30 12:51:30.455   767  1648 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,06-30 12:51:30.455   767  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@9f3a2c0, r.packageName :com.samsung.android.app.galaxyfinder
,06-30 12:51:30.465  7305  7305 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,06-30 12:51:30.465   767  1222 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,06-30 12:51:30.465   767  1222 D ActivityManager: com.sec.knox.bridge, Starting
,06-30 12:51:30.465   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.465   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.465   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.465   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:30.505  7322  7322 E Zygote  : MountEmulatedStorage()
06-30 12:51:30.505  7322  7322 E Zygote  : v2
06-30 12:51:30.505  7322  7322 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:51:30.505  7322  7322 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:30.515   767  1222 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7322 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 12:51:30.515   767  1222 I ActivityManager: Killing 4864:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,06-30 12:51:30.555  7322  7322 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:30.555  7322  7322 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:51:30.555  7322  7322 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:51:30.575  7322  7322 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:30.575  7322  7322 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:30.585  7322  7322 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,06-30 12:51:30.585  7322  7322 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:30.615   767  1351 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
06-30 12:51:30.615   767  1351 D ActivityManager: com.sec.knox.knoxsetupwizardclient, Starting
,06-30 12:51:30.615   767  1351 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.615   767  1351 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.615   767  1351 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.615   767  1351 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:30.655  7337  7337 E Zygote  : MountEmulatedStorage()
,06-30 12:51:30.655  7337  7337 E Zygote  : v2
06-30 12:51:30.655  7337  7337 I libpersona: KNOX_SDCARD checking this for 1000
06-30 12:51:30.655  7337  7337 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:30.655   767  1351 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7337 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 12:51:30.665   767  1351 I ActivityManager: Killing 6472:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,06-30 12:51:30.705  7337  7337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:30.705  7337  7337 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 12:51:30.705  7337  7337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 12:51:30.735  7337  7337 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:30.745  7337  7337 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:30.755  7337  7337 D ResourcesManager: creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,06-30 12:51:30.775  7337  7337 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,06-30 12:51:30.775   767  1629 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 12:51:30.775   767  1629 D ActivityManager: caller:android.app.ApplicationThreadProxy@18d2fbf9, r.packageName :com.google.android.apps.plus
,06-30 12:51:30.785   767  1648 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,06-30 12:51:30.785   767  1648 D ActivityManager: caller:android.app.ApplicationThreadProxy@138b399f, r.packageName :com.google.android.apps.plus
,06-30 12:51:30.795   767  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:30.795   767  1466 D ActivityManager: caller:android.app.ApplicationThreadProxy@d3e5eb5, r.packageName :com.google.android.gms
,06-30 12:51:30.805   767  1467 D ActivityManager: startProcessLocked calleePkgName: flipboard.app, hostingType: broadcast
06-30 12:51:30.805   767  1467 D ActivityManager: flipboard.app, Starting
,06-30 12:51:30.805   767  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.805   767  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.805   767  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:30.805   767  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:30.815  2520  7355 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,06-30 12:51:30.845  7356  7356 E Zygote  : MountEmulatedStorage()
06-30 12:51:30.845  7356  7356 E Zygote  : v2
06-30 12:51:30.845  7356  7356 I libpersona: KNOX_SDCARD checking this for 10125
06-30 12:51:30.845  7356  7356 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:30.855   767  1467 I ActivityManager: Start proc flipboard.app for broadcast flipboard.app/flipboard.sstream.SstreamBroadcastReceiver: pid=7356 uid=10125 gids={50125, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,06-30 12:51:30.855   767  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:30.855   767  1470 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ff3d0bb, r.packageName :com.google.android.gms
,06-30 12:51:30.915  7356  7356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:30.915  7356  7356 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:51:30.915  7356  7356 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 12:51:30.915   767  3234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:51:30.915   767  3234 D ActivityManager: caller:android.app.ApplicationThreadProxy@26c33131, r.packageName :com.google.android.gms
,06-30 12:51:30.915   767  1365 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:30.915   767  1365 D ActivityManager: caller:android.app.ApplicationThreadProxy@2884bd97, r.packageName :com.google.android.gms
,06-30 12:51:30.915   767  1351 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:30.915   767  1351 D ActivityManager: caller:android.app.ApplicationThreadProxy@33e8af6d, r.packageName :com.google.android.gms
,06-30 12:51:30.925   767  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:30.925   767  1470 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ad417a2, r.packageName :com.google.android.gms
,06-30 12:51:30.925  2520  7355 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,06-30 12:51:30.925   767  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:51:30.925   767  1439 D ActivityManager: caller:android.app.ApplicationThreadProxy@23953bf0, r.packageName :com.google.android.gms
06-30 12:51:30.925   767  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 12:51:30.925   767  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@bee, r.packageName :com.google.android.gms
,06-30 12:51:30.945  7356  7356 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:30.945  7356  7356 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:30.965  7356  7356 D ResourcesManager: creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,06-30 12:51:30.985  7262  7290 I qtaguid : Untagging socket 53
,06-30 12:51:30.985  7356  7356 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:51:30.985  7356  7356 I MultiDex: install
06-30 12:51:30.985  7356  7356 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:51:30.985  7262  7291 I qtaguid : Untagging socket 50
,06-30 12:51:30.995  7262  7289 I qtaguid : Untagging socket 52
,06-30 12:51:31.055   767  1467 I art     : Explicit concurrent mark sweep GC freed 44415(2MB) AllocSpace objects, 11(176KB) LOS objects, 30% free, 37MB/53MB, paused 1.379ms total 98.268ms
,06-30 12:51:31.065   767  1142 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:31.065   767  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@27e4f8fa, r.packageName :com.google.android.gms
,06-30 12:51:31.075   767  3290 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:31.075   767  3290 D ActivityManager: caller:android.app.ApplicationThreadProxy@30c09908, r.packageName :com.google.android.gms
,06-30 12:51:31.085   767  1439 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:31.085   767  1439 D ActivityManager: caller:android.app.ApplicationThreadProxy@15f9aac6, r.packageName :com.google.android.gms
,06-30 12:51:31.115   767  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:31.115   767  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ab5f823, r.packageName :com.google.android.gms
,06-30 12:51:31.125  2520  7376 W IcingInternalCorpora: getNumBytesRead when not calculated.
,06-30 12:51:31.135   767  1365 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:31.135   767  1365 D ActivityManager: caller:android.app.ApplicationThreadProxy@1be9ead9, r.packageName :com.google.android.gms
,06-30 12:51:31.145   767  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:31.155   265   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
06-30 12:51:31.155   265   541 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:51:31.155  7356  7356 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,06-30 12:51:31.175   265   541 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/flipboard.app/files/cache/
06-30 12:51:31.175   265   541 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 12:51:31.175  7356  7383 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/flipboard.app/files/cache
,06-30 12:51:31.225  7356  7356 I System.out: Reading bundled version for config.json
,06-30 12:51:31.345  7356  7356 I System.out: Reading bundled version for services.json
,06-30 12:51:31.365  7356  7356 I System.out: Reading bundled version for dynamicStrings.json
,06-30 12:51:31.385  7356  7356 I System.out: Parsed section Cover Stories, private: false
,06-30 12:51:31.415   767  1142 I ActivityManager: Killing 6552:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
06-30 12:51:31.415   767  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:31.535   338   338 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:51:31.535   338   338 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:51:32.135  2520  3618 I Icing   : Indexing F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9 from com.google.android.gms
,06-30 12:51:32.155  2520  3618 I Icing   : Indexing done F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9
,06-30 12:51:33.305   298   298 E SMD     : DCD ON
,06-30 12:51:33.985  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 12:51:33.985  7111  7188 I jxcore-log: 
,06-30 12:51:34.375  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 12:51:34.375  7111  7188 I jxcore-log: 
,06-30 12:51:34.405  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 12:51:34.405  7111  7188 I jxcore-log: 
,06-30 12:51:34.405  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 12:51:34.405  7111  7188 I jxcore-log: 
,06-30 12:51:34.425  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 12:51:34.425  7111  7188 I jxcore-log: 
,06-30 12:51:34.425  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 12:51:34.425  7111  7188 I jxcore-log: 
,06-30 12:51:36.305   298   298 E SMD     : DCD ON
,06-30 12:51:36.355  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 12:51:36.355  7111  7188 I jxcore-log: 
,06-30 12:51:36.365  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 12:51:36.365  7111  7188 I jxcore-log: 
,06-30 12:51:36.375  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 12:51:36.375  7111  7188 I jxcore-log: 
,06-30 12:51:36.525  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 12:51:36.525  7111  7188 I jxcore-log: 
,06-30 12:51:36.535   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:36.615  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 12:51:36.615  7111  7188 I jxcore-log: 
,06-30 12:51:36.665  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 12:51:36.665  7111  7188 I jxcore-log: 
,06-30 12:51:36.675  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 12:51:36.675  7111  7188 I jxcore-log: 
,06-30 12:51:36.855  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 12:51:36.855  7111  7188 I jxcore-log: 
,06-30 12:51:36.875  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 12:51:36.875  7111  7188 I jxcore-log: 
,06-30 12:51:36.885  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 12:51:36.885  7111  7188 I jxcore-log: 
,06-30 12:51:36.885  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 12:51:36.885  7111  7188 I jxcore-log: 
,06-30 12:51:36.905  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 12:51:36.905  7111  7188 I jxcore-log: 
,06-30 12:51:36.925  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 12:51:36.925  7111  7188 I jxcore-log: 
,06-30 12:51:37.005  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 12:51:37.005  7111  7188 I jxcore-log: 
,06-30 12:51:37.015  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 12:51:37.015  7111  7188 I jxcore-log: 
,06-30 12:51:37.035  7111  7188 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 12:51:37.035  7111  7188 I jxcore-log: 
,06-30 12:51:37.045  7111  7188 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,06-30 12:51:37.055  7111  7188 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 12:51:37.055  7111  7188 I jxcore-log: 
,06-30 12:51:37.505   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:51:37.535   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:37.975   767  1365 I ActivityManager: Killing 6567:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,06-30 12:51:38.535   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:39.305   298   298 E SMD     : DCD ON
,06-30 12:51:39.535   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:39.675   767  3075 D SSRM:n  : SIOP:: AP = 380, PST = 402, CUR = 300
,06-30 12:51:40.535   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:40.805  6192  6192 D FactoryTest: Not factory mode
,06-30 12:51:40.815  6192  6192 D FactoryTest: Not factory mode. isFactoryMode() returend false
,06-30 12:51:40.815  6192  6192 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,06-30 12:51:40.825  6192  6192 D MTPRx   : still no open session command from host, so toast
,06-30 12:51:40.825  6192  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,06-30 12:51:40.835  6192  6192 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,06-30 12:51:40.835  6192  6192 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:119845
,06-30 12:51:40.835   767  1648 E PersonaManagerService: inState():  stateMachine is null !!
,06-30 12:51:40.845   767  1648 I PersonaManagerService: PersonaId don't exist
,06-30 12:51:40.845   767  1648 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,06-30 12:51:40.855   767  1648 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,06-30 12:51:40.855   767  1648 I ActivityManager: START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,06-30 12:51:40.855   767  1648 W ActivityManager: mDVFSHelper.acquire()
,06-30 12:51:40.885   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-30 12:51:40.895   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 12:51:40.895   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
06-30 12:51:40.895   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:51:40.895   767  3075 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:40.905  6192  6192 E MTPRx   : started activity for popup
,06-30 12:51:40.925  6192  6192 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 12:51:40.935  6192  6192 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,06-30 12:51:40.985  6192  6192 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,06-30 12:51:40.995   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,06-30 12:51:40.995   767  1222 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 12:51:40.995   767  1222 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@30000f02 attribute=null, token = android.os.BinderProxy@ff3bd28
,06-30 12:51:40.995   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 12:51:40.995   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,06-30 12:51:40.995   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,06-30 12:51:40.995   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:51:41.015   767  1114 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,06-30 12:51:41.015   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:41.045  6192  6192 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,06-30 12:51:41.055  1787  1787 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,06-30 12:51:41.055   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:51:41.055   767  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4322, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:51:41.055   767  1142 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:51:41.055   767  1142 D BatteryService: stay LED for fully charged
,06-30 12:51:41.055   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:51:41.055   767   767 I MotionRecognitionService: Plugged
,06-30 12:51:41.055   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:51:41.065  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:51:41.065  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:51:41.075  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:51:41.075  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 12:51:41.075  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:51:41.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:41.075  6192  6192 D Activity: performCreate Call secproduct feature valuefalse
06-30 12:51:41.075  6192  6192 D Activity: performCreate Call debug elastic valuetrue
06-30 12:51:41.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:51:41.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:41.085  7111  7111 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
06-30 12:51:41.085  7111  7111 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
06-30 12:51:41.085  7111  7111 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
06-30 12:51:41.085  7111  7111 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,06-30 12:51:41.085   767  3149 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 12:51:41.085   767  3149 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 12:51:41.085   767  3149 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 12:51:41.085   767   767 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 12:51:41.085   767   767 D PersonaManagerService: getPersonasForUser(): returning null!
,06-30 12:51:41.095   767  1142 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:41.095   767  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@828ba6f, r.packageName :com.google.android.gms
,06-30 12:51:41.105  7111  7111 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
06-30 12:51:41.105  7111  7111 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,06-30 12:51:41.105  7111  7111 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@ccd25e9 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@85a27b7, 16908290=android.view.AbsSavedState$1@85a27b7}, android:focusedViewId=100}]}]
,06-30 12:51:41.115  7111  7111 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
06-30 12:51:41.115  7111  7111 V ActivityThread: updateVisibility : ActivityRecord{2e36ab88 token=android.os.BinderProxy@7bf277a {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 12:51:41.115  7111  7111 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
06-30 12:51:41.115  7111  7111 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,06-30 12:51:41.115  7111  7111 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@7bf277a time:120122
,06-30 12:51:41.165   767  1222 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:41.215   767  1629 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:41.225   767  1629 D ActivityManager: caller:android.app.ApplicationThreadProxy@4f55405, r.packageName :com.google.android.gms
,06-30 12:51:41.275   767  1648 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-30 12:51:41.275   767  1648 D ActivityManager: com.google.android.gms, Starting
,06-30 12:51:41.285   767  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:41.285   767  1222 D ActivityManager: caller:android.app.ApplicationThreadProxy@7978867, r.packageName :com.google.android.gms
,06-30 12:51:41.315  2520  7461 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
06-30 12:51:41.315  2520  7461 D SchedPeriodicTask: Scheduled AdAttestation task.
,06-30 12:51:41.345  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:41.375   767  3319 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:41.425   767  3075 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:41.495   767  3234 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:41.535   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:51:41.615   767  3234 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:41.625   767  3234 D ActivityManager: caller:android.app.ApplicationThreadProxy@383efebd, r.packageName :com.google.android.gms
,06-30 12:51:41.755   767  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:41.755   767  1222 D ActivityManager: caller:android.app.ApplicationThreadProxy@388a4403, r.packageName :com.google.android.gms
,06-30 12:51:41.845   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.005   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:42.005   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:42.005   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:51:42.015   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:51:42.065  7477  7477 E Zygote  : MountEmulatedStorage()
06-30 12:51:42.065  7477  7477 E Zygote  : v2
06-30 12:51:42.065  7477  7477 I libpersona: KNOX_SDCARD checking this for 10015
06-30 12:51:42.065  7477  7477 I libpersona: KNOX_SDCARD not a persona
,06-30 12:51:42.075  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 12:51:42.075  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:51:42.075  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,06-30 12:51:42.075   767  3319 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7477 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,06-30 12:51:42.125  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:51:42.125  7477  7477 D ActivityThread: Added TimaKeyStore provider
,06-30 12:51:42.155  7477  7477 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,06-30 12:51:42.155  7477  7477 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,06-30 12:51:42.155  7477  7477 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:51:42.205  7477  7477 I MultiDex: VM with version 2.1.0 has multidex support
06-30 12:51:42.205  7477  7477 I MultiDex: install
06-30 12:51:42.205  7477  7477 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:51:42.295  7477  7477 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,06-30 12:51:42.305   298   298 E SMD     : DCD ON
,06-30 12:51:42.355   767  1439 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,06-30 12:51:42.375  7477  7477 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,06-30 12:51:42.375  7477  7477 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@107feada: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,06-30 12:51:42.375  7477  7477 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,06-30 12:51:42.405  1787  1787 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=6e6123b6-86cc-4ea4-aa0c-306d5595af4e
,06-30 12:51:42.415   767  1439 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:51:42.415  7477  7477 D ChimeraCfgMgr: Reading stored module config
,06-30 12:51:42.435  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:42.435  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:51:42.505  7477  7501 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,06-30 12:51:42.515  7477  7477 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,06-30 12:51:42.515  7477  7477 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,06-30 12:51:42.565  1787  6020 I art     : Explicit concurrent mark sweep GC freed 65930(3MB) AllocSpace objects, 7(112KB) LOS objects, 39% free, 23MB/38MB, paused 771us total 71.461ms
,06-30 12:51:42.645   310   310 D WVCdm   : Instantiating CDM.
,06-30 12:51:42.645   310   693 I WVCdm   : CdmEngine::OpenSession
06-30 12:51:42.645   310   693 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,06-30 12:51:42.655  1787  2221 W GCoreFlp: No location to return for getLastLocation()
,06-30 12:51:42.665   310   693 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,06-30 12:51:42.685   310   693 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
06-30 12:51:42.685   310   693 D DrmWidevineDash: Service_Initialize: starts!
06-30 12:51:42.685   310   693 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,06-30 12:51:42.685   310   693 D QSEECOMAPI: : App is not loaded in QSEE
06-30 12:51:42.685   310   693 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
06-30 12:51:42.685   310   693 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 12:51:42.685   310   693 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 12:51:42.685   310   693 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:51:42.685   310   693 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
06-30 12:51:42.685   310   693 E QSEECOMAPI: : Error::Loading image failed with ret = -1
06-30 12:51:42.685   310   693 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
06-30 12:51:42.685   310   693 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:51:42.705   310   693 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 12:51:42.705   767  3149 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e12a7d3, r.packageName :com.google.android.gms
06-30 12:51:42.705   310   693 D DrmWidevineDash: Service_Initialize: ends! returns 0
06-30 12:51:42.705   310   693 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1732000
06-30 12:51:42.705   310   693 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1732000
,06-30 12:51:42.705  7477  7485 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:51:42.705  7477  7485 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:51:42.705  7477  7485 I System.out: (HTTPLog)-Thread-1194-298413612: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:51:42.705  7477  7485 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:42.705   767  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d45ef10, r.packageName :com.google.android.gms
,06-30 12:51:42.715   767   782 D ActivityManager: caller:android.app.ApplicationThreadProxy@bfdda09, r.packageName :com.google.android.gms
,06-30 12:51:42.715  7477  7485 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:51:42.715  7477  7485 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} uid -1, pid: 7477, getuid(): 10015
,06-30 12:51:42.725  2520  7468 D UdcContextInitService: registered all accounts: true
,06-30 12:51:42.735  1787  2236 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 12:51:42.735   310   693 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
06-30 12:51:42.735   310   693 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 12:51:42.735   310   693 D DrmWidevineDash: hlos api version =  9
06-30 12:51:42.735   310   693 D DrmWidevineDash: tz api version =  8
06-30 12:51:42.735   310   693 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 12:51:42.735   310   693 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
06-30 12:51:42.745   310   693 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1eff940
,06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb3172690, dataLength=8
,06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,06-30 12:51:42.745   310   693 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb1d6c000, wrapped_rsa_key_length=1280
,06-30 12:51:42.755   310   693 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
06-30 12:51:42.755   310   693 I WVCdm   : CdmEngine::QueryKeyControlInfo
,06-30 12:51:42.755  1787  2294 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,06-30 12:51:42.755   310  1363 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
06-30 12:51:42.755   310  1363 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
06-30 12:51:42.755   310  1363 I WVCdm   : CdmEngine::GenerateKeyRequest
06-30 12:51:42.755   310  1363 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb26b2740, idLength=0xb1aff710
,06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
,06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,06-30 12:51:42.765   310  1363 D DrmWidevineDash: hlos api version =  9
06-30 12:51:42.765   310  1363 D DrmWidevineDash: tz api version =  8
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
06-30 12:51:42.765   310  1363 D WVCdm   : PrepareKeyRequest: nonce=3368326128
06-30 12:51:42.765   310  1363 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb19edd00
06-30 12:51:42.765   310  1363 D DrmWidevineDash: message_length=1587, signature=0xb0115680, signature_length=2981099252
,06-30 12:51:42.815   767  3290 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.825   767  3149 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.855   767  3290 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:51:42.855   767  3290 D ActivityManager: caller:android.app.ApplicationThreadProxy@ba10dc5, r.packageName :com.google.android.gms
,06-30 12:51:42.895   767  1365 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:51:42.895   310  1363 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,06-30 12:51:42.905   310   310 I WVCdm   : CdmEngine::CloseSession
06-30 12:51:42.905   310   310 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,06-30 12:51:42.905   310   310 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
06-30 12:51:42.905   310   310 I WVCdm   : L3 Terminate.
06-30 12:51:42.905   310   310 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,06-30 12:51:42.905   310   310 D DrmWidevineDash: Service_Uninitialize: starts!
06-30 12:51:42.905   310   310 D QSEECOMAPI: : QSEECom_dealloc_memory 
06-30 12:51:42.905   310   310 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 3
06-30 12:51:42.905   310   310 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,06-30 12:51:42.905   310   310 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,06-30 12:51:42.965   767  1439 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.975   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.985  7477  7485 I qtaguid : Untagging socket 30
,06-30 12:51:42.985   767  3290 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:42.985   767  1222 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.015   767  1466 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:51:43.025  1787  2294 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:43.025  1787  2294 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:51:43.025  1787  2294 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:43.045   767   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@29a52bc3, r.packageName :com.google.android.gms
,06-30 12:51:43.085   767  1470 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c545779, r.packageName :com.google.android.gms
,06-30 12:51:43.095  1787  7515 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 12:51:43.095  1787  7510 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-30 12:51:43.095   767  1365 D ActivityManager: caller:android.app.ApplicationThreadProxy@3264cbe, r.packageName :com.google.android.gms
,06-30 12:51:43.095  1787  2294 I qtaguid : Tagging socket 71 with tag 1000040100000000{268436481,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:43.115   767  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ba4c11f, r.packageName :com.google.android.gms
,06-30 12:51:43.115  1787  7515 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 12:51:43.115  1787  7510 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,06-30 12:51:43.115   767  1351 D ActivityManager: caller:android.app.ApplicationThreadProxy@34f7dc6c, r.packageName :com.google.android.gms
,06-30 12:51:43.145   767  1470 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a39f235, r.packageName :com.google.android.gms
,06-30 12:51:43.145  1787  7515 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,06-30 12:51:43.145  1787  7510 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
06-30 12:51:43.145  1787  7510 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,06-30 12:51:43.165  1787  7510 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,06-30 12:51:43.205   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:51:43.215   767  1629 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:43.215   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.215   767  3319 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.255   767  1470 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.275  1787  7510 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:43.275  1787  7510 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
06-30 12:51:43.275  1787  7510 I qtaguid : Tagging socket 74 with tag 11065c0800000000{285629448,0} uid -1, pid: 1787, getuid(): 10015
,06-30 12:51:43.315  1787  7510 I qtaguid : Tagging socket 77 with tag 11065c0800000000{285629448,0} uid -1, pid: 1787, getuid(): 10015
,06-30 12:51:43.585   767  1365 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.585   767   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.585   767  3234 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.595   767  1629 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:43.595   767  1351 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.595   767  1365 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.605  1787  7510 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:43.605  1787  7510 I qtaguid : Tagging socket 74 with tag 11065b5800000000{285629272,0} uid -1, pid: 1787, getuid(): 10015
,06-30 12:51:43.685  7519  7519 I dex2oat : ----------------------------------------------------
06-30 12:51:43.685  7519  7519 I dex2oat : <SS>: S T A R T I N G . . .
06-30 12:51:43.685  7519  7519 I dex2oat : <SS>: Zip is absent. Canceled.
06-30 12:51:43.685  7519  7519 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,06-30 12:51:43.735   767  1629 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.745   767  1142 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.755   767  1439 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.755   767   782 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:43.765   767   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.775  7519  7519 I dex2oat : dex2oat took 90.558ms (threads: 4)
,06-30 12:51:43.785   767  3149 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.795   767  1222 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.795  1787  7510 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:51:43.795  1787  7510 I qtaguid : Tagging socket 74 with tag fffffca200000000{4294966434,0} uid -1, pid: 1787, getuid(): 10015
,06-30 12:51:43.825  7477  7485 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 12:51:43.825  7477  7485 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 12:51:43.825  7477  7485 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 12:51:43.825  7477  7485 I Adreno-EGL: Local Branch: mybranch5813579
06-30 12:51:43.825  7477  7485 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 12:51:43.825  7477  7485 I Adreno-EGL: Local Patches: NONE
06-30 12:51:43.825  7477  7485 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 12:51:43.855   767   924 W ActivityManager: mDVFSHelper.release()
,06-30 12:51:43.955   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.955  7477  7485 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 12:51:43.955  7477  7485 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 12:51:43.955  7477  7485 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 12:51:43.955  7477  7485 I Adreno-EGL: Local Branch: mybranch5813579
06-30 12:51:43.955  7477  7485 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 12:51:43.955  7477  7485 I Adreno-EGL: Local Patches: NONE
06-30 12:51:43.955  7477  7485 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 12:51:43.955   767  3319 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.965   767  3149 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.965   767  1222 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,06-30 12:51:43.975   767  1142 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.975   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:43.975  1787  7510 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:43.975  1787  7510 I qtaguid : Tagging socket 74 with tag 11065fff00000000{285630463,0} uid -1, pid: 1787, getuid(): 10015
,06-30 12:51:44.015  7477  7485 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
06-30 12:51:44.015  7477  7485 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
06-30 12:51:44.015  7477  7485 I Adreno-EGL: Build Date: 11/19/14 Wed
06-30 12:51:44.015  7477  7485 I Adreno-EGL: Local Branch: mybranch5813579
06-30 12:51:44.015  7477  7485 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
06-30 12:51:44.015  7477  7485 I Adreno-EGL: Local Patches: NONE
06-30 12:51:44.015  7477  7485 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,06-30 12:51:44.105   767  1629 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:44.115   767  1142 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:44.125   767   782 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:44.145  1787  7474 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:44.145  1787  7474 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
06-30 12:51:44.145  1787  7474 I qtaguid : Tagging socket 79 with tag 1000040100000000{268436481,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:44.185  1787  7474 I qtaguid : Tagging socket 70 with tag 1000040100000000{268436481,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:44.185   767  3149 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:44.375  1787  2294 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-06-30 12:51:42.831+0200, stopTime=2016-06-30 12:51:44.381+0200, duration=1550ms
,06-30 12:51:44.375  1787  5923 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:51:44.375  1787  5923 I qtaguid : Tagging socket 53 with tag 1000310500000000{268448005,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:44.405   767  3149 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:44.445   767   784 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,06-30 12:51:44.455  2520  3618 V UdcCtxListenerSrv: handle intent
,06-30 12:51:44.535  1787  5923 I qtaguid : Untagging socket 53
,06-30 12:51:44.545  1787  2294 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,06-30 12:51:45.305   298   298 E SMD     : DCD ON
,06-30 12:51:46.475   767  1365 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:51:46.515  1787  5924 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:51:46.515  1787  5924 I qtaguid : Tagging socket 53 with tag 1000310200000000{268448002,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:51:46.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:46.735  1787  5924 I qtaguid : Untagging socket 53
,06-30 12:51:46.745  1787  2294 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,06-30 12:51:46.775   767  1222 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,06-30 12:51:46.785  2520  3618 V UdcCtxListenerSrv: handle intent
,06-30 12:51:47.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:48.305   298   298 E SMD     : DCD ON
,06-30 12:51:48.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:49.165   767   782 I ActivityManager: Killing 5612:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,06-30 12:51:49.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:49.605   767  1059 I PowerManagerService: [PWL] Off : 50s ago
,06-30 12:51:49.725   767  3075 D SSRM:n  : SIOP:: AP = 360, PST = 394, CUR = 300
,06-30 12:51:50.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:51:51.105   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:51:51.115   767  3319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:51:51.115   767  3319 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:51:51.115   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:51:51.125  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:51:51.125  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:51:51.125   767   767 I MotionRecognitionService: Plugged
,06-30 12:51:51.135   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:51:51.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:51:51.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:51.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:51.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:51:51.145   767  3319 D BatteryService: stay LED for fully charged
,06-30 12:51:51.145  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:51:51.145  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:51:51.305   298   298 E SMD     : DCD ON
,06-30 12:51:51.545   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:51:54.305   298   298 E SMD     : DCD ON
,06-30 12:51:57.305   298   298 E SMD     : DCD ON
,06-30 12:51:57.505   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:51:59.775   767  3075 D SSRM:n  : SIOP:: AP = 340, PST = 385, CUR = 300
,06-30 12:51:59.995   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 12:52:00.035   767  1337 E Watchdog: !@Sync 4
,06-30 12:52:00.315   298   298 E SMD     : DCD ON
,06-30 12:52:01.155   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:01.165   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:52:01.165   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:52:01.165   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:01.175  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:01.175  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:01.185   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:01.185   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:01.185   767   782 D BatteryService: stay LED for fully charged
,06-30 12:52:01.185  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:01.185  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:01.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:01.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:01.195  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:01.195  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:01.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:02.545   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:02.865   767  1820 V SAMP_SPCM_test: CSC File load.. 
,06-30 12:52:02.915   767  1820 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,06-30 12:52:02.925   767  1820 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,06-30 12:52:02.925   767  1820 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,06-30 12:52:02.945   767  1820 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,06-30 12:52:02.975   767  1820 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,06-30 12:52:02.995   767  1820 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,06-30 12:52:03.315   298   298 E SMD     : DCD ON
,06-30 12:52:03.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:04.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:05.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:06.315   298   298 E SMD     : DCD ON
,06-30 12:52:06.555   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:52:09.315   298   298 E SMD     : DCD ON
,06-30 12:52:09.825   767  3075 D SSRM:n  : SIOP:: AP = 340, PST = 376, CUR = 300
,06-30 12:52:11.225   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:11.225   767  1629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:52:11.225   767  1629 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:52:11.225   767  1629 D BatteryService: stay LED for fully charged
,06-30 12:52:11.225   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:11.225  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:11.225  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:52:11.225   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:11.225   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:11.235  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:11.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:11.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:11.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:11.235  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:11.245  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:12.315   298   298 E SMD     : DCD ON
,06-30 12:52:14.605   767  1059 I PowerManagerService: [PWL] Off : 75s ago
,06-30 12:52:15.315   298   298 E SMD     : DCD ON
,06-30 12:52:17.515   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:18.315   298   298 E SMD     : DCD ON
,06-30 12:52:19.875   767  3075 D SSRM:n  : SIOP:: AP = 330, PST = 367, CUR = 300
,06-30 12:52:21.285   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:21.285   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:52:21.285   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:52:21.285   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:21.295  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:21.295   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:21.295  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:21.305   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:21.305  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:21.305  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:21.305  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:21.315   767  1470 D BatteryService: stay LED for fully charged
,06-30 12:52:21.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:21.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:21.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:21.315   298   298 E SMD     : DCD ON
,06-30 12:52:21.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:22.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:23.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:24.315   298   298 E SMD     : DCD ON
,06-30 12:52:24.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:25.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:26.555   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:52:27.315   298   298 E SMD     : DCD ON
,06-30 12:52:29.915   767  3075 D SSRM:n  : SIOP:: AP = 330, PST = 360, CUR = 300
,06-30 12:52:30.035   767  1337 E Watchdog: !@Sync 5
,06-30 12:52:30.325   298   298 E SMD     : DCD ON
,06-30 12:52:30.375  1787  2913 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,06-30 12:52:31.345   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:31.345   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:52:31.345   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:52:31.345   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:31.355   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:31.355  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:31.355  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:31.365   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:31.365   767   782 D BatteryService: stay LED for fully charged
,06-30 12:52:31.365  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:31.365  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:31.365  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:31.375  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:31.375  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:31.375  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:33.325   298   298 E SMD     : DCD ON
,06-30 12:52:36.325   298   298 E SMD     : DCD ON
,06-30 12:52:37.515   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:39.325   298   298 E SMD     : DCD ON
,06-30 12:52:39.965   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 352, CUR = 300
,06-30 12:52:41.405   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:41.405   767  3319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:52:41.405   767  3319 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:52:41.415   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:41.415  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:41.425  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:41.425   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:41.425   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:41.425   767  3319 D BatteryService: stay LED for fully charged
,06-30 12:52:41.435  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:41.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:41.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:41.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:41.445  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:41.445  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:42.325   298   298 E SMD     : DCD ON
,06-30 12:52:44.605   767  1059 I PowerManagerService: [PWL] Off : 105s ago
,06-30 12:52:45.325   298   298 E SMD     : DCD ON
,06-30 12:52:46.555   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:47.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:48.325   298   298 E SMD     : DCD ON
,06-30 12:52:48.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:49.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:50.035   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 348, CUR = 300
,06-30 12:52:50.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:52:51.325   298   298 E SMD     : DCD ON
,06-30 12:52:51.565   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:52:54.325   298   298 E SMD     : DCD ON
,06-30 12:52:57.325   298   298 E SMD     : DCD ON
,06-30 12:52:57.515   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:52:59.375   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:52:59.385  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:52:59.385  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:52:59.395  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 12:52:59.395  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:52:59.425   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:52:59.425   767  1629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:52:59.425   767  1629 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:52:59.425   767  1629 D BatteryService: stay LED for fully charged
,06-30 12:52:59.425   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:52:59.425   767   767 I MotionRecognitionService: Plugged
,06-30 12:52:59.425   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:52:59.425  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:52:59.435  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:52:59.435  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:52:59.445  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:52:59.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:59.445  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:52:59.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:52:59.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:52:59.455  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:59.465  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:52:59.995   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 12:53:00.035   767  1337 E Watchdog: !@Sync 6
,06-30 12:53:00.095   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 343, CUR = 300
,06-30 12:53:00.325   298   298 E SMD     : DCD ON
,06-30 12:53:03.325   298   298 E SMD     : DCD ON
,06-30 12:53:06.325   298   298 E SMD     : DCD ON
,06-30 12:53:09.335   298   298 E SMD     : DCD ON
,06-30 12:53:09.475   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:09.475   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:53:09.475   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:53:09.475   767  1467 D BatteryService: stay LED for fully charged
,06-30 12:53:09.475   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:09.485  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:09.485  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:53:09.485   767   767 I MotionRecognitionService: Plugged
,06-30 12:53:09.485   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:53:09.485  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:53:09.485  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:53:09.495  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:09.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:09.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:09.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:10.145   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 336, CUR = 300
,06-30 12:53:12.335   298   298 E SMD     : DCD ON
,06-30 12:53:15.335   298   298 E SMD     : DCD ON
,06-30 12:53:16.565   338   338 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:53:16.565   338   338 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:53:17.525   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:18.335   298   298 E SMD     : DCD ON
,06-30 12:53:19.545   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:19.545   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:53:19.555   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:53:19.555   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:19.565  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:19.565  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:19.565   767   767 I MotionRecognitionService: Plugged
06-30 12:53:19.565   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:53:19.565   767   784 D BatteryService: stay LED for fully charged
,06-30 12:53:19.565  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:53:19.565  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:19.575  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:19.575  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:19.575  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:53:19.575  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:19.605   767  1059 I PowerManagerService: [PWL] Off : 140s ago
,06-30 12:53:20.195   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 300
,06-30 12:53:21.335   298   298 E SMD     : DCD ON
,06-30 12:53:24.335   298   298 E SMD     : DCD ON
,06-30 12:53:26.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:27.335   298   298 E SMD     : DCD ON
,06-30 12:53:27.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:28.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:29.565   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:29.615   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:29.615   767  1439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:53:29.625   767  1439 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:53:29.625   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:29.625   767   767 I MotionRecognitionService: Plugged
,06-30 12:53:29.625  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:29.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:53:29.635  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:53:29.635  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:29.635   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:53:29.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:29.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:29.635   767  1439 D BatteryService: stay LED for fully charged
06-30 12:53:29.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:29.635  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:30.045   767  1337 E Watchdog: !@Sync 7
,06-30 12:53:30.235   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 300
,06-30 12:53:30.335   298   298 E SMD     : DCD ON
,06-30 12:53:30.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:31.575   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:53:33.335   298   298 E SMD     : DCD ON
,06-30 12:53:36.335   298   298 E SMD     : DCD ON
,06-30 12:53:36.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:37.525   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:37.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:38.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:39.335   298   298 E SMD     : DCD ON
,06-30 12:53:39.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:39.675   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:39.685   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:53:39.685   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:53:39.685   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:39.685   767   767 I MotionRecognitionService: Plugged
,06-30 12:53:39.685   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:53:39.695   767  1466 D BatteryService: stay LED for fully charged
,06-30 12:53:39.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:39.695  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:39.695  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:53:39.695  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:39.695  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:53:39.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:39.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:53:39.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:40.285   767  3075 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 300
,06-30 12:53:40.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:41.575   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:53:42.335   298   298 E SMD     : DCD ON
,06-30 12:53:45.345   298   298 E SMD     : DCD ON
,06-30 12:53:48.345   298   298 E SMD     : DCD ON
,06-30 12:53:49.735   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:53:49.735   767  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:53:49.745   767  1648 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:53:49.745   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:53:49.755  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:53:49.755  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:53:49.755   767   767 I MotionRecognitionService: Plugged
06-30 12:53:49.755   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:53:49.755  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:53:49.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:49.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:49.765  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:53:49.765  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:53:49.765   767  1648 D BatteryService: stay LED for fully charged
06-30 12:53:49.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:53:50.335   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 321, CUR = 300
,06-30 12:53:51.345   298   298 E SMD     : DCD ON
,06-30 12:53:51.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:52.575   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:53.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:54.345   298   298 E SMD     : DCD ON
,06-30 12:53:54.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:55.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:53:56.585   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:53:57.345   298   298 E SMD     : DCD ON
,06-30 12:53:57.535   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:53:59.615   767  1059 I PowerManagerService: [PWL] Off : 180s ago
,06-30 12:53:59.795   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:00.045   767  1337 E Watchdog: !@Sync 8
,06-30 12:54:00.345   298   298 E SMD     : DCD ON
,06-30 12:54:00.395   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300
,06-30 12:54:03.345   298   298 E SMD     : DCD ON
,06-30 12:54:06.345   298   298 E SMD     : DCD ON
,06-30 12:54:09.345   298   298 E SMD     : DCD ON
,06-30 12:54:09.865   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:09.865   767  1222 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:54:09.865   767  1222 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:54:09.865   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:09.875  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:09.875  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:09.875   767   767 I MotionRecognitionService: Plugged
,06-30 12:54:09.875   767   767 I MotionRecognitionService: setPowerConnected  = true,
,06-30 12:54:09.885   767  1222 D BatteryService: stay LED for fully charged
,06-30 12:54:09.885  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:54:09.885  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:09.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:09.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:09.895  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:54:09.895  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:10.445   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 300
,06-30 12:54:11.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:12.345   298   298 E SMD     : DCD ON
,06-30 12:54:12.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:13.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:14.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:15.345   298   298 E SMD     : DCD ON
,06-30 12:54:15.585   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:16.585   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:54:17.535   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:18.345   298   298 E SMD     : DCD ON
,06-30 12:54:19.925   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:19.925   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:54:19.925   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:54:19.935   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:54:19.945  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:54:19.945  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:54:19.945   767   767 I MotionRecognitionService: Plugged
,06-30 12:54:19.945   767   767 I MotionRecognitionService: setPowerConnected  = true
06-30 12:54:19.945   767  1466 D BatteryService: stay LED for fully charged
,06-30 12:54:19.955  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:54:19.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:19.965  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:19.965  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:54:19.965  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:54:19.965  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:54:20.495   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300
,06-30 12:54:21.355   298   298 E SMD     : DCD ON
,06-30 12:54:24.355   298   298 E SMD     : DCD ON
,06-30 12:54:27.355   298   298 E SMD     : DCD ON
,06-30 12:54:29.985   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:30.045   767  1337 E Watchdog: !@Sync 9
,06-30 12:54:30.355   298   298 E SMD     : DCD ON
,06-30 12:54:30.565   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 300
,06-30 12:54:33.355   298   298 E SMD     : DCD ON
,06-30 12:54:36.355   298   298 E SMD     : DCD ON
,06-30 12:54:36.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:37.535   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:54:37.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:38.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:39.355   298   298 E SMD     : DCD ON
,06-30 12:54:39.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:40.045   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:40.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:54:40.645   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300
,06-30 12:54:41.595   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:54:42.355   298   298 E SMD     : DCD ON
,06-30 12:54:44.615   767  1059 I PowerManagerService: [PWL] Off : 225s ago
,06-30 12:54:45.355   298   298 E SMD     : DCD ON
,06-30 12:54:48.355   298   298 E SMD     : DCD ON
,06-30 12:54:50.105   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:54:50.685   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300
,06-30 12:54:51.355   298   298 E SMD     : DCD ON
,06-30 12:54:54.355   298   298 E SMD     : DCD ON
,06-30 12:54:57.215   767  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:54:57.215   767  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:54:57.225   767  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:54:57.235   767  1100 I TLC_TIMA_PKM_initialize: initializing...
,06-30 12:54:57.235   767  1100 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,06-30 12:54:57.235   767  1100 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,06-30 12:54:57.245   767  1100 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,06-30 12:54:57.245   767  1100 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
06-30 12:54:57.245   767  1100 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
06-30 12:54:57.245   767  1100 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
06-30 12:54:57.245   767  1100 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,06-30 12:54:57.245   767  1100 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
06-30 12:54:57.245   767  1100 D QSEECOMAPI: : App is not loaded in QSEE
,06-30 12:54:57.265   767  1100 D QSEECOMAPI: : Loaded image: APP id = 3
,06-30 12:54:57.275   767  1100 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,06-30 12:54:57.275   767  1100 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,06-30 12:54:57.355   298   298 E SMD     : DCD ON
,06-30 12:54:57.545   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:00.055   767  1337 E Watchdog: !@Sync 10
,06-30 12:55:00.155   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:00.215   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 12:55:00.225   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 12:55:00.225   767  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:00.235   767  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 12:55:00.365   298   298 E SMD     : DCD ON
,06-30 12:55:00.735   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,06-30 12:55:03.365   298   298 E SMD     : DCD ON
,06-30 12:55:06.365   298   298 E SMD     : DCD ON
,06-30 12:55:06.595   338   338 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:55:06.595   338   338 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:55:09.365   298   298 E SMD     : DCD ON
,06-30 12:55:10.785   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,06-30 12:55:12.365   298   298 E SMD     : DCD ON
,06-30 12:55:14.175   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:55:14.185   767   924 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,06-30 12:55:14.185   767   924 D ActivityManager: com.blurb.checkout, Starting
,06-30 12:55:14.185   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:55:14.185   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 12:55:14.195   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:55:14.195   767   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 12:55:14.225   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:14.265   767   924 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7570 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,06-30 12:55:14.275  7570  7570 E Zygote  : MountEmulatedStorage()
,06-30 12:55:14.275  7570  7570 E Zygote  : v2
06-30 12:55:14.275  7570  7570 I libpersona: KNOX_SDCARD checking this for 10096
06-30 12:55:14.275  7570  7570 I libpersona: KNOX_SDCARD not a persona
,06-30 12:55:14.275  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 12:55:14.275  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:55:14.305  7570  7570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,06-30 12:55:14.305  7570  7570 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,06-30 12:55:14.305  7570  7570 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,06-30 12:55:14.305  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 12:55:14.305  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 12:55:14.345  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 12:55:14.355  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
06-30 12:55:14.355  7570  7570 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 12:55:14.355  7570  7570 D ActivityThread: Added TimaKeyStore provider
,06-30 12:55:14.375  7570  7570 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,06-30 12:55:14.395   767  1142 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,06-30 12:55:14.395   767  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@5ccd2a5, r.packageName :com.blurb.checkout
,06-30 12:55:14.455   767  1470 I ActivityManager: Killing 6587:com.wsomacp/u0a29 (adj 15): emptyCount ##41
,06-30 12:55:15.365   298   298 E SMD     : DCD ON
,06-30 12:55:17.545   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:18.365   298   298 E SMD     : DCD ON
,06-30 12:55:20.835   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:55:21.365   298   298 E SMD     : DCD ON
,06-30 12:55:21.595   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:22.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:23.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:24.285   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:24.295   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:55:24.295   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:55:24.295   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:24.305  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:24.315  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:55:24.315  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:55:24.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:24.315   767   767 I MotionRecognitionService: Plugged
06-30 12:55:24.315   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:55:24.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:24.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:55:24.315   767   784 D BatteryService: stay LED for fully charged
,06-30 12:55:24.325  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:55:24.325  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:24.365   298   298 E SMD     : DCD ON
,06-30 12:55:24.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:25.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:26.605   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:55:27.365   298   298 E SMD     : DCD ON
,06-30 12:55:30.055   767  1337 E Watchdog: !@Sync 11
,06-30 12:55:30.365   298   298 E SMD     : DCD ON
,06-30 12:55:30.885   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:55:31.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:32.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:33.365   298   298 E SMD     : DCD ON
,06-30 12:55:33.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:34.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:34.625   767  1059 I PowerManagerService: [PWL] Off : 275s ago
,06-30 12:55:35.505   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 12:55:35.525   767  1439 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:55:35.555   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:35.585   767  1222 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,06-30 12:55:35.585   767  1222 D ActivityManager: caller:android.app.ApplicationThreadProxy@6174288, r.packageName :com.google.android.gms
,06-30 12:55:35.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:35.765   767  3149 I art     : Explicit concurrent mark sweep GC freed 62496(4MB) AllocSpace objects, 74(1184KB) LOS objects, 30% free, 37MB/53MB, paused 1.765ms total 143.635ms
,06-30 12:55:35.765   767  3149 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
06-30 12:55:35.765   767  3149 D ActivityManager: com.google.android.gms, Starting
,06-30 12:55:35.765  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:35.785   767  1365 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:55:35.795  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:35.805  1787  1787 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,06-30 12:55:35.855   767  3149 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,06-30 12:55:35.855  1787  1847 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:35.865  1787  1847 I qtaguid : Tagging socket 67 with tag 1000040100000000{268436481,0} uid 10015, pid: 1787, getuid(): 10015
,06-30 12:55:36.365   298   298 E SMD     : DCD ON
,06-30 12:55:36.595  2520  7613 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
06-30 12:55:36.595  2520  7613 I System.out: (HTTPLog)-Static: isShipBuild true
06-30 12:55:36.595  2520  7613 I System.out: (HTTPLog)-Thread-341-1039434228: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
06-30 12:55:36.595  2520  7613 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,06-30 12:55:36.605   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:55:36.645  2520  7613 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,06-30 12:55:36.645  2520  7613 I qtaguid : Tagging socket 109 with tag 1000010400000000{268435716,0} uid -1, pid: 2520, getuid(): 10015
,06-30 12:55:36.965  2520  7613 I qtaguid : Untagging socket 109
,06-30 12:55:37.045   767   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 12:55:37.555   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:39.375   298   298 E SMD     : DCD ON
,06-30 12:55:40.975   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:55:42.375   298   298 E SMD     : DCD ON
,06-30 12:55:45.375   298   298 E SMD     : DCD ON
,06-30 12:55:45.625   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:45.625   767  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:55:45.625   767  1142 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:55:45.625   767  1142 D BatteryService: stay LED for fully charged
,06-30 12:55:45.625   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:55:45.625  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:55:45.625  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:55:45.625   767   767 I MotionRecognitionService: Plugged
,06-30 12:55:45.625   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:55:45.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:55:45.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:45.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:45.645  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:55:45.645  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:55:45.645  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:55:46.605   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:47.615   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:48.375   298   298 E SMD     : DCD ON
,06-30 12:55:48.615   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:49.615   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:50.615   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:55:51.035   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:55:51.375   298   298 E SMD     : DCD ON
,06-30 12:55:51.615   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:55:54.375   298   298 E SMD     : DCD ON
,06-30 12:55:55.685   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:55:57.375   298   298 E SMD     : DCD ON
,06-30 12:55:57.555   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:55:59.995   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 12:56:00.055   767  1337 E Watchdog: !@Sync 12
,06-30 12:56:00.375   298   298 E SMD     : DCD ON
,06-30 12:56:01.115   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:56:03.375   298   298 E SMD     : DCD ON
,06-30 12:56:05.745   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:05.745   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:05.755   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:56:05.755   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:05.755  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:05.765  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:05.765   767   767 I MotionRecognitionService: Plugged
,06-30 12:56:05.765   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:05.775   767  1466 D BatteryService: stay LED for fully charged
,06-30 12:56:05.775  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:05.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:05.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:05.785  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:05.785  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:05.795  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:06.375   298   298 E SMD     : DCD ON
,06-30 12:56:06.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:07.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:08.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:09.375   298   298 E SMD     : DCD ON
,06-30 12:56:09.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:10.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:11.165   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:56:11.625   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:56:12.385   298   298 E SMD     : DCD ON
,06-30 12:56:15.385   298   298 E SMD     : DCD ON
,06-30 12:56:15.805   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:17.555   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:18.385   298   298 E SMD     : DCD ON
,06-30 12:56:21.215   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:56:21.385   298   298 E SMD     : DCD ON
,06-30 12:56:24.385   298   298 E SMD     : DCD ON
,06-30 12:56:25.865   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:25.865   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:25.875   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:56:25.875   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:25.875  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:25.885  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:25.885   767   767 I MotionRecognitionService: Plugged
,06-30 12:56:25.885   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:25.885   767  1365 D BatteryService: stay LED for fully charged
,06-30 12:56:25.895  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:25.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:25.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:25.915  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:25.915  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:25.915  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:27.385   298   298 E SMD     : DCD ON
,06-30 12:56:29.625   767  1059 I PowerManagerService: [PWL] Off : 330s ago
,06-30 12:56:30.065   767  1337 E Watchdog: !@Sync 13
,06-30 12:56:30.385   298   298 E SMD     : DCD ON
,06-30 12:56:31.255   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:56:31.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:32.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:33.385   298   298 E SMD     : DCD ON
,06-30 12:56:33.625   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:34.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:35.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:56:35.925   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:35.925   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:35.925   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:56:35.925   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:35.935  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:35.935  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:35.945   767   767 I MotionRecognitionService: Plugged
,06-30 12:56:35.945   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:35.945   767  3149 D BatteryService: stay LED for fully charged
,06-30 12:56:35.955  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:35.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:35.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:35.955  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:35.965  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:35.965  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:36.385   298   298 E SMD     : DCD ON
,06-30 12:56:36.635   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:56:37.565   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:56:39.385   298   298 E SMD     : DCD ON
,06-30 12:56:41.315   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,06-30 12:56:42.385   298   298 E SMD     : DCD ON
,06-30 12:56:45.385   298   298 E SMD     : DCD ON
,06-30 12:56:45.985   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:45.985   767  3290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:45.995   767  3290 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:56:45.995   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:45.995   767   767 I MotionRecognitionService: Plugged
,06-30 12:56:46.005   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:56:46.005  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:46.005  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:46.005   767  3290 D BatteryService: stay LED for fully charged
,06-30 12:56:46.015  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:46.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:46.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:46.035  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:46.035  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:46.035  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:48.395   298   298 E SMD     : DCD ON
,06-30 12:56:51.365   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300
,06-30 12:56:51.395   298   298 E SMD     : DCD ON
,06-30 12:56:54.395   298   298 E SMD     : DCD ON
,06-30 12:56:56.045   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:56:56.045   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4337, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:56:56.045   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:56:56.055   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:56:56.055  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:56:56.065  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:56:56.065   767   767 I MotionRecognitionService: Plugged
,06-30 12:56:56.065   767   767 I MotionRecognitionService: setPowerConnected  = true
06-30 12:56:56.065   767  1470 D BatteryService: stay LED for fully charged
,06-30 12:56:56.065  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:56:56.065  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.075  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:56:56.075  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:56:56.075  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:56:57.395   298   298 E SMD     : DCD ON
,06-30 12:56:57.565   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:00.065   767  1337 E Watchdog: !@Sync 14
,06-30 12:57:00.395   298   298 E SMD     : DCD ON
,06-30 12:57:01.415   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300
,06-30 12:57:01.635   338   338 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:57:01.635   338   338 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:57:03.395   298   298 E SMD     : DCD ON
,06-30 12:57:06.105   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:06.115   767  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:06.115   767  1351 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:57:06.115   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:06.125   767   767 I MotionRecognitionService: Plugged
,06-30 12:57:06.135  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:06.135  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:06.135  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:06.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:06.135   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:06.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:06.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:06.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:06.145  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:06.145   767  1351 D BatteryService: stay LED for fully charged
,06-30 12:57:06.395   298   298 E SMD     : DCD ON
,06-30 12:57:09.395   298   298 E SMD     : DCD ON
,06-30 12:57:11.465   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300
,06-30 12:57:12.395   298   298 E SMD     : DCD ON
,06-30 12:57:15.405   298   298 E SMD     : DCD ON
,06-30 12:57:16.175   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:16.185   767  3319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:57:16.185   767  3319 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:57:16.185   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:16.185   767   767 I MotionRecognitionService: Plugged
,06-30 12:57:16.185   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:16.185  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:16.195  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:16.195  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:16.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:16.195   767  3319 D BatteryService: stay LED for fully charged
,06-30 12:57:16.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:16.195  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:16.195  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:57:16.195  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:17.565   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:18.405   298   298 E SMD     : DCD ON
,06-30 12:57:21.405   298   298 E SMD     : DCD ON
,06-30 12:57:21.505   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300
,06-30 12:57:21.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:22.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:23.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:24.405   298   298 E SMD     : DCD ON
,06-30 12:57:24.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:25.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:26.235   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:26.235   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
06-30 12:57:26.245   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:57:26.245   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:26.245   767   767 I MotionRecognitionService: Plugged
,06-30 12:57:26.255   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:26.255   767  1467 D BatteryService: stay LED for fully charged
,06-30 12:57:26.255  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:26.255  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:57:26.255  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:26.255  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:26.265  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:26.265  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:26.265  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:26.265  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:26.635   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,06-30 12:57:27.405   298   298 E SMD     : DCD ON
,06-30 12:57:29.625   767  1059 I PowerManagerService: [PWL] Off : 390s ago
,06-30 12:57:30.065   767  1337 E Watchdog: !@Sync 15
,06-30 12:57:30.405   298   298 E SMD     : DCD ON
,06-30 12:57:31.555   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300
,06-30 12:57:31.635   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:32.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:33.405   298   298 E SMD     : DCD ON
,06-30 12:57:33.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:34.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:35.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:36.295   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:36.305   767  1439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4331, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0,
06-30 12:57:36.305   767  1439 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:57:36.305   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:36.305   767   767 I MotionRecognitionService: Plugged
,06-30 12:57:36.305   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:36.315  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:36.315  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:36.315  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:36.315   767  1439 D BatteryService: stay LED for fully charged
,06-30 12:57:36.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.315  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:57:36.315  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:36.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.325  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:36.405   298   298 E SMD     : DCD ON
,06-30 12:57:36.645   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,06-30 12:57:37.575   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:57:39.405   298   298 E SMD     : DCD ON
,06-30 12:57:41.605   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300
,06-30 12:57:42.405   298   298 E SMD     : DCD ON
,06-30 12:57:45.405   298   298 E SMD     : DCD ON
,06-30 12:57:46.365   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:46.365   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:57:46.365   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:57:46.365   767   782 D BatteryService: stay LED for fully charged
,06-30 12:57:46.365   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:57:46.375   767   767 I MotionRecognitionService: Plugged
,06-30 12:57:46.375   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:57:46.375  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:57:46.375  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:57:46.375  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:57:46.385  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:57:46.385  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:46.385  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:57:46.385  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:57:46.385  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:57:46.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:47.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:47.805   334   334 I bootchecker: bootchecker wake up!!
,06-30 12:57:48.405   298   298 E SMD     : DCD ON
,06-30 12:57:48.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:49.645   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:50.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:57:51.415   298   298 E SMD     : DCD ON
,06-30 12:57:51.655   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,06-30 12:57:51.655   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300
,06-30 12:57:54.415   298   298 E SMD     : DCD ON
,06-30 12:57:56.425   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:57:57.415   298   298 E SMD     : DCD ON
,06-30 12:57:57.575   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:00.075   767  1337 E Watchdog: !@Sync 16
,06-30 12:58:00.415   298   298 E SMD     : DCD ON
,06-30 12:58:01.705   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300
,06-30 12:58:03.415   298   298 E SMD     : DCD ON
,06-30 12:58:06.415   298   298 E SMD     : DCD ON
,06-30 12:58:06.485   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:06.495   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:06.495   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:58:06.495   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:06.505   767   767 I MotionRecognitionService: Plugged
,06-30 12:58:06.515  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 12:58:06.515  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 12:58:06.515  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:06.515  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:06.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:58:06.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:06.515   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:06.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:06.525  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:58:06.525   767  1467 D BatteryService: stay LED for fully charged
,06-30 12:58:06.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:07.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:08.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:09.415   298   298 E SMD     : DCD ON
,06-30 12:58:09.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:10.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:11.655   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,06-30 12:58:11.805   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 12:58:12.415   298   298 E SMD     : DCD ON
,06-30 12:58:15.415   298   298 E SMD     : DCD ON
,06-30 12:58:16.545   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:17.585   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:18.415   298   298 E SMD     : DCD ON
,06-30 12:58:21.425   298   298 E SMD     : DCD ON
,06-30 12:58:21.865   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:58:24.425   298   298 E SMD     : DCD ON
,06-30 12:58:26.605   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:26.605   767  1222 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:26.605   767  1222 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:58:26.605   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:26.615  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:58:26.615  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:26.615   767   767 I MotionRecognitionService: Plugged
,06-30 12:58:26.625   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:26.625   767  1222 D BatteryService: stay LED for fully charged
,06-30 12:58:26.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:26.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:26.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:26.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:26.635  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:58:26.635  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:27.425   298   298 E SMD     : DCD ON
,06-30 12:58:30.075   767  1337 E Watchdog: !@Sync 17
,06-30 12:58:30.425   298   298 E SMD     : DCD ON
,06-30 12:58:31.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:31.915   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:58:32.655   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:33.425   298   298 E SMD     : DCD ON
,06-30 12:58:33.665   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:34.625   767  1059 I PowerManagerService: [PWL] Off : 455s ago
,06-30 12:58:34.665   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:35.665   338   338 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 12:58:36.425   298   298 E SMD     : DCD ON
,06-30 12:58:36.665   338   338 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,06-30 12:58:36.665   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:36.665   767  1439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:58:36.665   767  1439 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:58:36.675   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:58:36.675  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED,
06-30 12:58:36.685  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:58:36.685   767   767 I MotionRecognitionService: Plugged
06-30 12:58:36.685   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:58:36.685   767  1439 D BatteryService: stay LED for fully charged
,06-30 12:58:36.685  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:58:36.685  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:36.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:36.695  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:58:36.695  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:58:36.695  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:58:37.585   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:58:39.425   298   298 E SMD     : DCD ON
,06-30 12:58:41.965   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:58:42.425   298   298 E SMD     : DCD ON
,06-30 12:58:45.435   298   298 E SMD     : DCD ON
,06-30 12:58:46.725   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:48.435   298   298 E SMD     : DCD ON
,06-30 12:58:51.435   298   298 E SMD     : DCD ON
,06-30 12:58:52.035   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:58:54.435   298   298 E SMD     : DCD ON
,06-30 12:58:56.785   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:58:57.435   298   298 E SMD     : DCD ON
,06-30 12:58:57.595   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:00.075   767  1337 E Watchdog: !@Sync 18
,06-30 12:59:00.435   298   298 E SMD     : DCD ON
,06-30 12:59:01.665   338   338 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
06-30 12:59:01.665   338   338 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,06-30 12:59:02.085   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:03.435   298   298 E SMD     : DCD ON
,06-30 12:59:06.435   298   298 E SMD     : DCD ON
,06-30 12:59:06.855   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:09.435   298   298 E SMD     : DCD ON
,06-30 12:59:12.155   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:12.435   298   298 E SMD     : DCD ON
,06-30 12:59:15.445   298   298 E SMD     : DCD ON
,06-30 12:59:16.925   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:16.925   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 12:59:16.925   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 12:59:16.925   767  1470 D BatteryService: stay LED for fully charged
,06-30 12:59:16.925   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:16.925  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:16.925  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:59:16.925   767   767 I MotionRecognitionService: Plugged
,06-30 12:59:16.925   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:16.935  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:16.935  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:16.935  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:16.945  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:16.945  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:16.945  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:17.595   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:18.445   298   298 E SMD     : DCD ON
,06-30 12:59:21.445   298   298 E SMD     : DCD ON
,06-30 12:59:22.205   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:24.445   298   298 E SMD     : DCD ON
,06-30 12:59:26.675   338   338 I Atfwd_Daemon: Stop the daemon....
,06-30 12:59:26.985   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:26.985   767  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:26.985   767  1648 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:59:26.985   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:26.995  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:26.995  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 12:59:26.995   767   767 I MotionRecognitionService: Plugged
,06-30 12:59:26.995   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:27.005   767  1648 D BatteryService: stay LED for fully charged
,06-30 12:59:27.015  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:27.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:27.015  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:27.015  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:27.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:27.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:27.445   298   298 E SMD     : DCD ON
,06-30 12:59:30.085   767  1337 E Watchdog: !@Sync 19
,06-30 12:59:30.445   298   298 E SMD     : DCD ON
,06-30 12:59:32.255   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:33.445   298   298 E SMD     : DCD ON
,06-30 12:59:36.445   298   298 E SMD     : DCD ON
,06-30 12:59:37.035   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:37.595   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 12:59:39.445   298   298 E SMD     : DCD ON
,06-30 12:59:42.325   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:42.445   298   298 E SMD     : DCD ON
,06-30 12:59:44.635   767  1059 I PowerManagerService: [PWL] Off : 525s ago
,06-30 12:59:45.445   298   298 E SMD     : DCD ON
,06-30 12:59:47.105   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:47.105   767  3234 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 12:59:47.105   767  3234 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 12:59:47.105   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 12:59:47.115   767   767 I MotionRecognitionService: Plugged
,06-30 12:59:47.115   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 12:59:47.125  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 12:59:47.125  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 12:59:47.125   767  3234 D BatteryService: stay LED for fully charged
,06-30 12:59:47.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 12:59:47.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 12:59:47.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:47.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 12:59:47.135  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 12:59:47.135  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 12:59:48.445   298   298 E SMD     : DCD ON
,06-30 12:59:51.455   298   298 E SMD     : DCD ON
,06-30 12:59:52.375   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 12:59:54.455   298   298 E SMD     : DCD ON
,06-30 12:59:57.165   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 12:59:57.215   767  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 12:59:57.215   767  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 12:59:57.215   767  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 12:59:57.455   298   298 E SMD     : DCD ON
,06-30 12:59:57.605   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:00.085   767  1337 E Watchdog: !@Sync 20
,06-30 13:00:00.185   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:00:00.185   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:00:00.195   767  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:00:00.205   767  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:00:00.455   298   298 E SMD     : DCD ON
,06-30 13:00:02.465   767  3075 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300
,06-30 13:00:03.455   298   298 E SMD     : DCD ON
,06-30 13:00:06.455   298   298 E SMD     : DCD ON
,06-30 13:00:07.225   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:07.235   767  3290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:00:07.235   767  3290 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:00:07.235   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:00:07.245   767   767 I MotionRecognitionService: Plugged
,06-30 13:00:07.245  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:07.245  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:00:07.245   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:00:07.255  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:00:07.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:07.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:07.255  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:07.255  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:00:07.255  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:00:07.255   767  3290 D BatteryService: stay LED for fully charged
,06-30 13:00:09.455   298   298 E SMD     : DCD ON
,06-30 13:00:12.455   298   298 E SMD     : DCD ON
,06-30 13:00:12.515   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:00:15.455   298   298 E SMD     : DCD ON
,06-30 13:00:17.285   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:17.605   767  3112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:00:18.455   298   298 E SMD     : DCD ON
,06-30 13:00:21.455   298   298 E SMD     : DCD ON
,06-30 13:00:22.575   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:00:24.455   298   298 E SMD     : DCD ON
,06-30 13:00:27.355   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:27.465   298   298 E SMD     : DCD ON
,06-30 13:00:30.085   767  1337 E Watchdog: !@Sync 21
,06-30 13:00:30.465   298   298 E SMD     : DCD ON
,06-30 13:00:32.625   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:00:33.465   298   298 E SMD     : DCD ON
,06-30 13:00:36.465   298   298 E SMD     : DCD ON
,06-30 13:00:37.415   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:37.425   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:00:37.425   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:00:37.425   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:00:37.425   767   767 I MotionRecognitionService: Plugged
,06-30 13:00:37.435   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:00:37.435  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:37.435  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:00:37.435  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:00:37.435  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:00:37.435   767   782 D BatteryService: stay LED for fully charged
,06-30 13:00:37.435  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:00:37.435  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:00:37.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:37.445  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:39.465   298   298 E SMD     : DCD ON
,06-30 13:00:42.465   298   298 E SMD     : DCD ON
,06-30 13:00:42.675   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:00:45.465   298   298 E SMD     : DCD ON
,06-30 13:00:47.475   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:47.485   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:00:47.485   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:00:47.485   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:00:47.495  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:00:47.495  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:00:47.495   767   767 I MotionRecognitionService: Plugged
,06-30 13:00:47.495   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:00:47.495  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:00:47.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:47.495  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:47.495   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:00:47.505  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:00:47.505  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:00:47.505  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:00:48.465   298   298 E SMD     : DCD ON
,06-30 13:00:51.465   298   298 E SMD     : DCD ON
,06-30 13:00:52.735   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:00:54.465   298   298 E SMD     : DCD ON
,06-30 13:00:57.465   298   298 E SMD     : DCD ON
,06-30 13:00:57.535   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:00:59.635   767  1059 I PowerManagerService: [PWL] Off : 600s ago
,06-30 13:01:00.095   767  1337 E Watchdog: !@Sync 22
,06-30 13:01:00.465   298   298 E SMD     : DCD ON
,06-30 13:01:02.785   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:01:03.475   298   298 E SMD     : DCD ON
,06-30 13:01:06.475   298   298 E SMD     : DCD ON
,06-30 13:01:07.605   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:07.605   767  1439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:01:07.605   767  1439 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:01:07.605   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:07.605  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:07.605  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:01:07.605   767   767 I MotionRecognitionService: Plugged
,06-30 13:01:07.605   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:07.615  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:07.615   767  1439 D BatteryService: stay LED for fully charged
,06-30 13:01:07.615  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:07.615  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:07.615  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:07.625  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:07.625  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:09.475   298   298 E SMD     : DCD ON
,06-30 13:01:12.475   298   298 E SMD     : DCD ON
,06-30 13:01:12.835   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:01:15.475   298   298 E SMD     : DCD ON
,06-30 13:01:17.655   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:18.475   298   298 E SMD     : DCD ON
,06-30 13:01:21.475   298   298 E SMD     : DCD ON
,06-30 13:01:22.885   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:01:24.475   298   298 E SMD     : DCD ON
,06-30 13:01:27.475   298   298 E SMD     : DCD ON
,06-30 13:01:27.725   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:27.725   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:01:27.725   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:01:27.725   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:27.725  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:27.725  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:01:27.725   767   767 I MotionRecognitionService: Plugged
,06-30 13:01:27.725   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:27.735  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:27.735  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:27.735  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:27.735   767  1466 D BatteryService: stay LED for fully charged
,06-30 13:01:27.745  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:27.745  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:27.745  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:30.095   767  1337 E Watchdog: !@Sync 23
,06-30 13:01:30.475   298   298 E SMD     : DCD ON
,06-30 13:01:32.945   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,06-30 13:01:33.475   298   298 E SMD     : DCD ON
,06-30 13:01:36.475   298   298 E SMD     : DCD ON
,06-30 13:01:37.785   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:37.785   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:01:37.785   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:01:37.785   767   782 D BatteryService: stay LED for fully charged
06-30 13:01:37.785   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:37.795   767   767 I MotionRecognitionService: Plugged
,06-30 13:01:37.795  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:37.795  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:01:37.795   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:37.795  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:37.795  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:37.805  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:37.805  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:37.805  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:37.805  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:39.485   298   298 E SMD     : DCD ON
,06-30 13:01:42.485   298   298 E SMD     : DCD ON
,06-30 13:01:42.995   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:01:45.485   298   298 E SMD     : DCD ON
,06-30 13:01:47.845   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:01:47.855   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:01:47.855   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:01:47.855   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:01:47.875  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:01:47.875  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:01:47.875  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:01:47.875  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:01:47.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:01:47.875   767   767 I MotionRecognitionService: Plugged
,06-30 13:01:47.875   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:01:47.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:47.885  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:01:47.885  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:01:47.885   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:01:48.485   298   298 E SMD     : DCD ON
,06-30 13:01:51.485   298   298 E SMD     : DCD ON
,06-30 13:01:53.065   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:01:54.485   298   298 E SMD     : DCD ON
,06-30 13:01:57.485   298   298 E SMD     : DCD ON
,06-30 13:01:57.905   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:00.105   767  1337 E Watchdog: !@Sync 24
,06-30 13:02:00.485   298   298 E SMD     : DCD ON
,06-30 13:02:03.145   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:03.485   298   298 E SMD     : DCD ON
,06-30 13:02:06.485   298   298 E SMD     : DCD ON
,06-30 13:02:07.965   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:09.485   298   298 E SMD     : DCD ON
,06-30 13:02:12.485   298   298 E SMD     : DCD ON
,06-30 13:02:13.205   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:15.485   298   298 E SMD     : DCD ON
,06-30 13:02:18.025   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:18.035   767  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:18.035   767  1351 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:02:18.035   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:18.055  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:18.055  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:18.055  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:18.055  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:18.055   767   767 I MotionRecognitionService: Plugged
06-30 13:02:18.055  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:18.055   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:18.065  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:18.065  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:18.065  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:02:18.065   767  1351 D BatteryService: stay LED for fully charged
,06-30 13:02:18.495   298   298 E SMD     : DCD ON
,06-30 13:02:19.645   767  1059 I PowerManagerService: [PWL] Off : 680s ago
,06-30 13:02:21.495   298   298 E SMD     : DCD ON
,06-30 13:02:23.255   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:24.495   298   298 E SMD     : DCD ON
,06-30 13:02:27.495   298   298 E SMD     : DCD ON
,06-30 13:02:28.085   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:28.095   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 284, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:28.095   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:02:28.095   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:28.105  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:28.105  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:28.115  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:28.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:28.115   767   767 I MotionRecognitionService: Plugged
06-30 13:02:28.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:28.115   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:28.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:02:28.115   767  1466 D BatteryService: stay LED for fully charged
,06-30 13:02:28.115  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:28.125  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:30.105   767  1337 E Watchdog: !@Sync 25
,06-30 13:02:30.495   298   298 E SMD     : DCD ON
,06-30 13:02:33.325   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:33.495   298   298 E SMD     : DCD ON
,06-30 13:02:36.495   298   298 E SMD     : DCD ON
,06-30 13:02:38.145   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:38.145   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:38.145   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:02:38.145   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:38.155  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:38.155  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:38.155   767   767 I MotionRecognitionService: Plugged
,06-30 13:02:38.165   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:38.165   767   782 D BatteryService: stay LED for fully charged
,06-30 13:02:38.175  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:38.175  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:38.175  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:38.175  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:38.175  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:38.175  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:39.495   298   298 E SMD     : DCD ON
,06-30 13:02:42.495   298   298 E SMD     : DCD ON
,06-30 13:02:43.375   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:45.495   298   298 E SMD     : DCD ON
,06-30 13:02:48.205   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:02:48.205   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:02:48.205   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:02:48.215   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:02:48.215  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:02:48.225   767   767 I MotionRecognitionService: Plugged
,06-30 13:02:48.225   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:02:48.225  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:02:48.225   767   784 D BatteryService: stay LED for fully charged
,06-30 13:02:48.235  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:02:48.235  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:48.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:48.245  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:02:48.245  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:02:48.245  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:02:48.495   298   298 E SMD     : DCD ON
,06-30 13:02:51.495   298   298 E SMD     : DCD ON
,06-30 13:02:53.435   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:02:54.505   298   298 E SMD     : DCD ON
,06-30 13:02:57.505   298   298 E SMD     : DCD ON
,06-30 13:02:58.265   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:00.115   767  1337 E Watchdog: !@Sync 26
,06-30 13:03:00.505   298   298 E SMD     : DCD ON
,06-30 13:03:03.485   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:03.505   298   298 E SMD     : DCD ON
,06-30 13:03:04.065   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 13:03:06.505   298   298 E SMD     : DCD ON
,06-30 13:03:08.325   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:08.325   767  1439 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:08.325   767  1439 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:03:08.325   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:08.335  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:08.335  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:08.345   767   767 I MotionRecognitionService: Plugged
,06-30 13:03:08.345   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:08.345   767  1439 D BatteryService: stay LED for fully charged
,06-30 13:03:08.355  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:08.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:08.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:08.355  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:08.355  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:08.355  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:09.505   298   298 E SMD     : DCD ON
,06-30 13:03:12.505   298   298 E SMD     : DCD ON
,06-30 13:03:13.535   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:15.505   298   298 E SMD     : DCD ON
,06-30 13:03:18.385   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:18.395   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:18.395   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:03:18.395   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:18.405  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:18.415  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:18.415  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:18.415  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:18.415  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:18.415  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:18.415   767   767 I MotionRecognitionService: Plugged
,06-30 13:03:18.415   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:18.425  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:03:18.425  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:18.425   767  1467 D BatteryService: stay LED for fully charged
,06-30 13:03:18.505   298   298 E SMD     : DCD ON
,06-30 13:03:21.505   298   298 E SMD     : DCD ON
,06-30 13:03:23.605   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:24.505   298   298 E SMD     : DCD ON
,06-30 13:03:27.505   298   298 E SMD     : DCD ON
,06-30 13:03:28.445   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:28.445   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:28.445   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:03:28.445   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:28.455  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:28.455  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:03:28.455   767   767 I MotionRecognitionService: Plugged
,06-30 13:03:28.465   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:28.465   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:03:28.475  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:28.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:28.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:28.475  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:28.475  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:28.475  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:03:30.115   767  1337 E Watchdog: !@Sync 27
,06-30 13:03:30.515   298   298 E SMD     : DCD ON
,06-30 13:03:33.515   298   298 E SMD     : DCD ON
,06-30 13:03:33.665   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:36.515   298   298 E SMD     : DCD ON
,06-30 13:03:38.505   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:39.515   298   298 E SMD     : DCD ON
,06-30 13:03:42.515   298   298 E SMD     : DCD ON
,06-30 13:03:43.705   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:44.645   767  1059 I PowerManagerService: [PWL] Off : 765s ago
,06-30 13:03:45.515   298   298 E SMD     : DCD ON
,06-30 13:03:48.515   298   298 E SMD     : DCD ON
,06-30 13:03:48.555   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:51.515   298   298 E SMD     : DCD ON
,06-30 13:03:53.755   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:03:54.515   298   298 E SMD     : DCD ON
,06-30 13:03:57.515   298   298 E SMD     : DCD ON
,06-30 13:03:58.625   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:03:58.625   767  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:03:58.635   767  1351 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:03:58.635   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:03:58.645  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:03:58.645   767   767 I MotionRecognitionService: Plugged
,06-30 13:03:58.645  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:03:58.645   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:03:58.645   767  1351 D BatteryService: stay LED for fully charged
,06-30 13:03:58.655  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:03:58.655  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:58.665  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:58.665  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:03:58.665  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:03:58.665  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:04:00.115   767  1337 E Watchdog: !@Sync 28
,06-30 13:04:00.515   298   298 E SMD     : DCD ON
,06-30 13:04:03.515   298   298 E SMD     : DCD ON
,06-30 13:04:03.815   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:06.515   298   298 E SMD     : DCD ON
,06-30 13:04:08.685   767  1439 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:09.525   298   298 E SMD     : DCD ON
,06-30 13:04:12.525   298   298 E SMD     : DCD ON
,06-30 13:04:13.855   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:15.525   298   298 E SMD     : DCD ON
,06-30 13:04:18.525   298   298 E SMD     : DCD ON
,06-30 13:04:18.755   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:21.525   298   298 E SMD     : DCD ON
,06-30 13:04:23.905   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:24.525   298   298 E SMD     : DCD ON
,06-30 13:04:27.525   298   298 E SMD     : DCD ON
,06-30 13:04:28.815   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:30.125   767  1337 E Watchdog: !@Sync 29
,06-30 13:04:30.525   298   298 E SMD     : DCD ON
,06-30 13:04:33.525   298   298 E SMD     : DCD ON
,06-30 13:04:33.955   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:36.525   298   298 E SMD     : DCD ON
,06-30 13:04:38.885   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:39.525   298   298 E SMD     : DCD ON
,06-30 13:04:42.525   298   298 E SMD     : DCD ON
,06-30 13:04:44.005   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:45.535   298   298 E SMD     : DCD ON
,06-30 13:04:48.535   298   298 E SMD     : DCD ON
,06-30 13:04:48.945   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:51.535   298   298 E SMD     : DCD ON
,06-30 13:04:54.085   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:04:54.535   298   298 E SMD     : DCD ON
,06-30 13:04:57.215   767  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:04:57.215   767  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:04:57.215   767  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:04:57.535   298   298 E SMD     : DCD ON
,06-30 13:04:58.995   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:04:58.995   767  3319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:04:58.995   767  3319 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:04:58.995   767  3319 D BatteryService: stay LED for fully charged
,06-30 13:04:58.995   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:04:58.995  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:04:59.005  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:04:59.005   767   767 I MotionRecognitionService: Plugged
06-30 13:04:59.005   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:04:59.005  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:04:59.005  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:59.005  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:04:59.015  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:04:59.015  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:04:59.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:00.115   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:05:00.115   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:05:00.125   767  1337 E Watchdog: !@Sync 30
,06-30 13:05:00.135   767  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:00.135   767  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:05:00.535   298   298 E SMD     : DCD ON
,06-30 13:05:03.535   298   298 E SMD     : DCD ON
,06-30 13:05:04.135   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:06.535   298   298 E SMD     : DCD ON
,06-30 13:05:09.065   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:09.535   298   298 E SMD     : DCD ON
,06-30 13:05:12.535   298   298 E SMD     : DCD ON
,06-30 13:05:14.185   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:14.655   767  1059 I PowerManagerService: [PWL] Off : 855s ago
,06-30 13:05:15.535   298   298 E SMD     : DCD ON
,06-30 13:05:18.535   298   298 E SMD     : DCD ON
,06-30 13:05:19.125   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:19.125   767  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:19.125   767  1142 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:05:19.135   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:19.145  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:19.145  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:19.145   767   767 I MotionRecognitionService: Plugged
06-30 13:05:19.145   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:19.145   767  1142 D BatteryService: stay LED for fully charged
,06-30 13:05:19.155  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:19.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.155  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:19.155  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:19.155  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:21.545   298   298 E SMD     : DCD ON
,06-30 13:05:24.245   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:24.545   298   298 E SMD     : DCD ON
,06-30 13:05:27.545   298   298 E SMD     : DCD ON
,06-30 13:05:29.185   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:29.185   767  1222 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:29.185   767  1222 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:05:29.195   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:29.195  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:29.205  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:29.205   767   767 I MotionRecognitionService: Plugged
06-30 13:05:29.205   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:29.205   767  1222 D BatteryService: stay LED for fully charged
,06-30 13:05:29.215  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:29.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:29.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:29.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:29.215  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:29.215  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:30.125   767  1337 E Watchdog: !@Sync 31
,06-30 13:05:30.545   298   298 E SMD     : DCD ON
,06-30 13:05:33.545   298   298 E SMD     : DCD ON
,06-30 13:05:34.305   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:36.545   298   298 E SMD     : DCD ON
,06-30 13:05:39.245   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:39.255   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:39.255   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:05:39.255   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:39.265   767   767 I MotionRecognitionService: Plugged
,06-30 13:05:39.275   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:39.275  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:39.275  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:39.275  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:39.275  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:39.275  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:39.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:39.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:05:39.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:39.285   767  1466 D BatteryService: stay LED for fully charged
,06-30 13:05:39.545   298   298 E SMD     : DCD ON
,06-30 13:05:42.545   298   298 E SMD     : DCD ON
,06-30 13:05:44.355   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:45.545   298   298 E SMD     : DCD ON
,06-30 13:05:48.545   298   298 E SMD     : DCD ON
,06-30 13:05:49.315   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:49.315   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:49.315   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:05:49.325   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:49.335   767   767 I MotionRecognitionService: Plugged
,06-30 13:05:49.335   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:49.335  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:49.335  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:49.335  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:05:49.335  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:49.345  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:49.345  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:05:49.345  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:49.345   767   782 D BatteryService: stay LED for fully charged
06-30 13:05:49.345  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:51.545   298   298 E SMD     : DCD ON
,06-30 13:05:54.415   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:05:54.545   298   298 E SMD     : DCD ON
,06-30 13:05:57.555   298   298 E SMD     : DCD ON
,06-30 13:05:59.375   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:05:59.375   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:05:59.385   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:05:59.385   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:05:59.385   767   767 I MotionRecognitionService: Plugged
,06-30 13:05:59.395  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:05:59.395  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:05:59.395   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:05:59.395  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:05:59.395  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:05:59.405  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:05:59.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:59.405   767   784 D BatteryService: stay LED for fully charged
,06-30 13:05:59.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:05:59.405  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:00.125   767  1337 E Watchdog: !@Sync 32
,06-30 13:06:00.555   298   298 E SMD     : DCD ON
,06-30 13:06:03.555   298   298 E SMD     : DCD ON
,06-30 13:06:04.475   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:06.555   298   298 E SMD     : DCD ON
,06-30 13:06:09.435   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:09.435   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:06:09.435   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:06:09.445   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:09.455  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:09.455   767   767 I MotionRecognitionService: Plugged
,06-30 13:06:09.455   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:09.455  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
06-30 13:06:09.455  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:09.455  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:09.455  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:09.465  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:09.465  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:09.465  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:09.465   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:06:09.555   298   298 E SMD     : DCD ON
,06-30 13:06:12.555   298   298 E SMD     : DCD ON
,06-30 13:06:14.525   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:15.555   298   298 E SMD     : DCD ON
,06-30 13:06:18.555   298   298 E SMD     : DCD ON
,06-30 13:06:19.495   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:21.555   298   298 E SMD     : DCD ON
,06-30 13:06:24.555   298   298 E SMD     : DCD ON
,06-30 13:06:24.605   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:27.555   298   298 E SMD     : DCD ON
,06-30 13:06:29.555   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:29.565   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:06:29.565   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:06:29.565   767  3149 D BatteryService: stay LED for fully charged
06-30 13:06:29.565   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:29.575   767   767 I MotionRecognitionService: Plugged
,06-30 13:06:29.575   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:29.575  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:29.575  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:29.575  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:29.585  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:06:29.585  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:29.585  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:06:29.585  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:29.585  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:30.135   767  1337 E Watchdog: !@Sync 33
,06-30 13:06:30.555   298   298 E SMD     : DCD ON
,06-30 13:06:33.565   298   298 E SMD     : DCD ON
,06-30 13:06:34.665   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:36.565   298   298 E SMD     : DCD ON
,06-30 13:06:39.565   298   298 E SMD     : DCD ON
,06-30 13:06:39.615   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:39.615   767  3234 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:06:39.615   767  3234 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:06:39.615   767  3234 D BatteryService: stay LED for fully charged
,06-30 13:06:39.615   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:39.625  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:39.625  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:06:39.625   767   767 I MotionRecognitionService: Plugged
,06-30 13:06:39.625   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:39.625  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:06:39.625  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:39.625  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:39.635  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:39.635  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:39.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:42.565   298   298 E SMD     : DCD ON
,06-30 13:06:44.715   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:45.565   298   298 E SMD     : DCD ON
,06-30 13:06:48.565   298   298 E SMD     : DCD ON
,06-30 13:06:49.685   767  1059 I PowerManagerService: [PWL] Off : 950s ago
,06-30 13:06:49.685   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:06:49.685   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:06:49.685   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:06:49.695   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:06:49.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:06:49.705  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:06:49.705   767   767 I MotionRecognitionService: Plugged
,06-30 13:06:49.705   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:06:49.705   767  1470 D BatteryService: stay LED for fully charged
,06-30 13:06:49.715  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:06:49.715  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:49.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:49.725  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:06:49.725  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:06:49.725  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:06:51.565   298   298 E SMD     : DCD ON
,06-30 13:06:54.565   298   298 E SMD     : DCD ON
,06-30 13:06:54.775   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:06:57.565   298   298 E SMD     : DCD ON
,06-30 13:06:59.745   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:00.135   767  1337 E Watchdog: !@Sync 34
,06-30 13:07:00.565   298   298 E SMD     : DCD ON
,06-30 13:07:03.565   298   298 E SMD     : DCD ON
,06-30 13:07:04.815   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:06.565   298   298 E SMD     : DCD ON
,06-30 13:07:09.565   298   298 E SMD     : DCD ON
,06-30 13:07:09.805   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:09.815   767  1629 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:09.815   767  1629 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:07:09.815   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:09.825   767   767 I MotionRecognitionService: Plugged
,06-30 13:07:09.825  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:09.825  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:09.835  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:09.835  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:07:09.835  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:07:09.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:09.835   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:09.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:09.835  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:09.845   767  1629 D BatteryService: stay LED for fully charged
,06-30 13:07:12.575   298   298 E SMD     : DCD ON
,06-30 13:07:14.875   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:15.575   298   298 E SMD     : DCD ON
,06-30 13:07:18.575   298   298 E SMD     : DCD ON
,06-30 13:07:19.865   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:19.875   767  3290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:19.875   767  3290 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:07:19.875   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:19.895  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:19.895  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:19.895  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:07:19.895  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:07:19.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:07:19.895   767   767 I MotionRecognitionService: Plugged
,06-30 13:07:19.895   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:19.895  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:19.905  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:19.905   767  3290 D BatteryService: stay LED for fully charged
06-30 13:07:19.905  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:21.575   298   298 E SMD     : DCD ON
,06-30 13:07:24.575   298   298 E SMD     : DCD ON
,06-30 13:07:24.945   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:27.575   298   298 E SMD     : DCD ON
,06-30 13:07:29.925   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:30.135   767  1337 E Watchdog: !@Sync 35
,06-30 13:07:30.575   298   298 E SMD     : DCD ON
,06-30 13:07:33.575   298   298 E SMD     : DCD ON
,06-30 13:07:35.005   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:36.575   298   298 E SMD     : DCD ON
,06-30 13:07:39.575   298   298 E SMD     : DCD ON
,06-30 13:07:39.985   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:39.985   767  3234 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:07:39.985   767  3234 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:07:39.995   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:07:39.995  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:07:40.005  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:07:40.005   767   767 I MotionRecognitionService: Plugged
,06-30 13:07:40.005   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:07:40.005   767  3234 D BatteryService: stay LED for fully charged
,06-30 13:07:40.015  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:07:40.015  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:40.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:40.025  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:07:40.025  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:07:40.025  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:07:42.575   298   298 E SMD     : DCD ON
,06-30 13:07:45.065   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:45.575   298   298 E SMD     : DCD ON
,06-30 13:07:48.585   298   298 E SMD     : DCD ON
,06-30 13:07:50.055   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:07:51.585   298   298 E SMD     : DCD ON
,06-30 13:07:54.585   298   298 E SMD     : DCD ON
,06-30 13:07:55.115   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:07:57.585   298   298 E SMD     : DCD ON
,06-30 13:08:00.115   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:00.115   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:00.125   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:08:00.125   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:00.125   767   767 I MotionRecognitionService: Plugged
,06-30 13:08:00.125   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:00.135  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:00.135  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:00.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:00.135  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:00.135   767  1337 E Watchdog: !@Sync 36
,06-30 13:08:00.145  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:00.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:00.145   767   784 D BatteryService: stay LED for fully charged
,06-30 13:08:00.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:08:00.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:00.585   298   298 E SMD     : DCD ON
,06-30 13:08:03.585   298   298 E SMD     : DCD ON
,06-30 13:08:05.175   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:06.585   298   298 E SMD     : DCD ON
,06-30 13:08:09.585   298   298 E SMD     : DCD ON
,06-30 13:08:10.175   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:10.185   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:10.185   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:08:10.185   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:10.195  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:10.195  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:08:10.195   767   767 I MotionRecognitionService: Plugged
06-30 13:08:10.195   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:10.195  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:10.195  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:10.205  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:10.205   767  1470 D BatteryService: stay LED for fully charged
06-30 13:08:10.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:10.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:10.205  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:12.585   298   298 E SMD     : DCD ON
,06-30 13:08:15.235   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:15.585   298   298 E SMD     : DCD ON
,06-30 13:08:18.585   298   298 E SMD     : DCD ON
,06-30 13:08:20.235   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:20.235   767  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:08:20.245   767  1648 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:08:20.245   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:20.255   767   767 I MotionRecognitionService: Plugged
,06-30 13:08:20.255   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:20.255  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:20.255  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:20.255  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:20.275  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.275  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:20.275  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:08:20.275  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.275  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:20.275   767  1648 D BatteryService: stay LED for fully charged
,06-30 13:08:21.585   298   298 E SMD     : DCD ON
,06-30 13:08:24.595   298   298 E SMD     : DCD ON
,06-30 13:08:25.295   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:27.595   298   298 E SMD     : DCD ON
,06-30 13:08:29.685   767  1059 I PowerManagerService: [PWL] Off : 1050s ago
,06-30 13:08:30.145   767  1337 E Watchdog: !@Sync 37
,06-30 13:08:30.295   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:30.295   767  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:08:30.295   767  1142 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:08:30.295   767  1142 D BatteryService: stay LED for fully charged
,06-30 13:08:30.295   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:08:30.305   767   767 I MotionRecognitionService: Plugged
,06-30 13:08:30.305   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:08:30.305  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:08:30.305  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:08:30.305  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:08:30.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:30.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:30.315  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:08:30.315  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:08:30.315  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:08:30.595   298   298 E SMD     : DCD ON
,06-30 13:08:33.595   298   298 E SMD     : DCD ON
,06-30 13:08:35.365   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:36.595   298   298 E SMD     : DCD ON
,06-30 13:08:39.595   298   298 E SMD     : DCD ON
,06-30 13:08:40.365   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:42.595   298   298 E SMD     : DCD ON
,06-30 13:08:45.405   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:45.595   298   298 E SMD     : DCD ON
,06-30 13:08:48.595   298   298 E SMD     : DCD ON
,06-30 13:08:50.425   767  1629 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:08:51.595   298   298 E SMD     : DCD ON
,06-30 13:08:54.595   298   298 E SMD     : DCD ON
,06-30 13:08:55.485   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:08:57.595   298   298 E SMD     : DCD ON
,06-30 13:09:00.145   767  1337 E Watchdog: !@Sync 38
,06-30 13:09:00.485   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:00.485   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:00.485   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:09:00.485   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:00.495  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:00.495  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:00.495   767   767 I MotionRecognitionService: Plugged
,06-30 13:09:00.495   767   784 D BatteryService: stay LED for fully charged,
06-30 13:09:00.505   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:00.515  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:00.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:00.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:00.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:00.515  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:00.515  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:00.605   298   298 E SMD     : DCD ON
,06-30 13:09:03.605   298   298 E SMD     : DCD ON
,06-30 13:09:05.545   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:06.605   298   298 E SMD     : DCD ON
,06-30 13:09:09.605   298   298 E SMD     : DCD ON
,06-30 13:09:10.545   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:12.605   298   298 E SMD     : DCD ON
,06-30 13:09:15.585   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:15.605   298   298 E SMD     : DCD ON
,06-30 13:09:18.605   298   298 E SMD     : DCD ON
,06-30 13:09:20.605   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:20.605   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:20.605   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:09:20.605   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:20.615  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:20.625  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:20.625   767   767 I MotionRecognitionService: Plugged
,06-30 13:09:20.625   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:20.625   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:09:20.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:20.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:20.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:20.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:20.635  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:20.635  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:21.605   298   298 E SMD     : DCD ON
,06-30 13:09:24.605   298   298 E SMD     : DCD ON
,06-30 13:09:25.635   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:27.605   298   298 E SMD     : DCD ON
,06-30 13:09:30.145   767  1337 E Watchdog: !@Sync 39
,06-30 13:09:30.605   298   298 E SMD     : DCD ON
,06-30 13:09:30.675   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:30.675   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:30.675   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:09:30.685   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:30.695   767   767 I MotionRecognitionService: Plugged
,06-30 13:09:30.695   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:30.695   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:09:30.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:09:30.695  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:30.695  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:09:30.695  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:30.705  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:30.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:30.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:30.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:33.605   298   298 E SMD     : DCD ON
,06-30 13:09:35.685   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:36.605   298   298 E SMD     : DCD ON
,06-30 13:09:39.615   298   298 E SMD     : DCD ON
,06-30 13:09:40.735   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:42.615   298   298 E SMD     : DCD ON
,06-30 13:09:45.615   298   298 E SMD     : DCD ON
,06-30 13:09:45.725   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:48.615   298   298 E SMD     : DCD ON
,06-30 13:09:50.795   767   782 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:09:50.805   767   782 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:09:50.805   767   782 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:09:50.805   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:09:50.805   767   767 I MotionRecognitionService: Plugged
,06-30 13:09:50.805   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:09:50.815  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:09:50.815  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:09:50.815  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:09:50.815  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:50.815  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:09:50.825  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:09:50.825  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:09:50.825   767   782 D BatteryService: stay LED for fully charged
,06-30 13:09:50.825  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:09:51.615   298   298 E SMD     : DCD ON
,06-30 13:09:54.615   298   298 E SMD     : DCD ON
,06-30 13:09:55.775   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:09:57.215   767  1100 D TimaService: TIMA: TimaService scheduler is intialized. 
,06-30 13:09:57.215   767  1100 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,06-30 13:09:57.215   767  1099 D TimaService: TimaServiceHandler.handleMessage what =1
,06-30 13:09:57.615   298   298 E SMD     : DCD ON
,06-30 13:09:57.885   767   918 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:09:57.955   767  1123 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,06-30 13:09:57.955   767  1123 I ApplicationUsage: Updating Usage Statistics in DB @ 1467284997960
,06-30 13:09:57.965   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.965   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.965   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.965   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.965   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 13:09:57.965   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 13:09:57.965   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.965   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.965   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.965   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.975   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.975   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.975   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.975   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.975   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.975   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.975   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
06-30 13:09:57.975   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.985   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.985   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.985   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.985   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.985   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.985   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:57.985   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.985   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.985   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.985   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.985   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.995   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.995   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:57.995   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:57.995   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:57.995   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:57.995   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:57.995   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:57.995   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.005   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.005   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.005   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.005   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.005   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.005   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.005   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.005   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.015   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.015   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.015   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.015   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.015   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.015   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.015   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.015   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.015   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.025   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.025   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.025   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.025   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.025   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.025   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.025   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.025   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.025   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.035   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.035   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.035   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.035   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.035   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.035   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.035   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.045   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.045   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.045   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.045   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.045   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.045   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.045   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.045   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.045   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.045   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.045   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.045   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.055   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.055   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.055   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.055   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.055   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.055   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.055   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.055   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.065   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.065   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.065   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.065   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.065   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.065   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.065   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.065   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.065   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.065   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.065   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.065   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.075   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.075   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.075   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.075   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.075   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.075   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.075   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.075   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.075   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.075   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.075   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.075   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.075   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.075   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.075   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.085   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.085   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.085   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.085   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.085   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.085   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.085   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.085   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.085   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.085   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.085   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.095   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.095   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.095   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.095   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.095   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.095   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.095   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.095   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.095   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.095   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.105   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.105   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.105   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.105   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.105   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.105   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.105   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.105   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.105   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.105   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.105   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.105   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.105   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.115   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.115   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.115   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.115   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.115   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.115   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.115   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.115   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.125   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.125   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.125   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.125   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.125   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.125   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.125   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.125   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.125   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.125   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.125   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.135   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.135   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.135   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.135   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.135   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.135   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.135   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.135   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.135   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.135   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.145   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.145   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.145   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.145   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.145   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.145   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.145   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.145   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.145   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.145   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.145   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.145   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.155   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.155   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.155   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.155   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,06-30 13:09:58.155   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,06-30 13:09:58.155   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.155   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.155   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.155   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.155   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.155   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,06-30 13:09:58.155   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:09:58.165   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.165   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,06-30 13:09:58.165   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.165   767  1123 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
06-30 13:09:58.165   767  1123 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
06-30 13:09:58.165   767  1123 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:09:58.165   767  1123 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:09:58.165   767  1123 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:09:58.165   767  1123 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467284998173
,06-30 13:09:59.995   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,06-30 13:10:00.005   767  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,06-30 13:10:00.015   767  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:10:00.015   767  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,06-30 13:10:00.155   767  1337 E Watchdog: !@Sync 40
,06-30 13:10:00.615   298   298 E SMD     : DCD ON
,06-30 13:10:00.855   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:00.855   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:00.865   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:10:00.865   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:00.865  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:00.865  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:00.875  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:00.875   767   767 I MotionRecognitionService: Plugged
,06-30 13:10:00.875   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:00.875  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:00.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:00.875   767   784 D BatteryService: stay LED for fully charged
,06-30 13:10:00.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:00.885  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:00.885  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:03.615   298   298 E SMD     : DCD ON
,06-30 13:10:05.845   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:06.615   298   298 E SMD     : DCD ON
,06-30 13:10:09.615   298   298 E SMD     : DCD ON
,06-30 13:10:10.915   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:10.915   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:10.925   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:10:10.925   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:10.935   767   767 I MotionRecognitionService: Plugged
,06-30 13:10:10.935   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:10.935   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:10:10.935  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:10.935  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:10.935  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:10.945  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:10.945  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:10.945  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:10.945  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:10.945  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:12.615   298   298 E SMD     : DCD ON
,06-30 13:10:14.685   767  1059 I PowerManagerService: [PWL] Off : 1155s ago
,06-30 13:10:15.615   298   298 E SMD     : DCD ON
,06-30 13:10:15.885   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:18.625   298   298 E SMD     : DCD ON
,06-30 13:10:20.975   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:20.985   767  3290 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:10:20.985   767  3290 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:10:20.985   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:20.985   767   767 I MotionRecognitionService: Plugged
,06-30 13:10:20.995  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:20.995  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:20.995  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:10:20.995   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:20.995  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:20.995  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:20.995  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:21.005   767  3290 D BatteryService: stay LED for fully charged
06-30 13:10:21.005  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:21.005  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:21.625   298   298 E SMD     : DCD ON
,06-30 13:10:24.625   298   298 E SMD     : DCD ON
,06-30 13:10:25.935   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:27.625   298   298 E SMD     : DCD ON
,06-30 13:10:30.155   767  1337 E Watchdog: !@Sync 41
,06-30 13:10:30.625   298   298 E SMD     : DCD ON
,06-30 13:10:31.035   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:33.625   298   298 E SMD     : DCD ON
,06-30 13:10:35.985   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:36.625   298   298 E SMD     : DCD ON
,06-30 13:10:39.625   298   298 E SMD     : DCD ON
,06-30 13:10:41.095   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:42.625   298   298 E SMD     : DCD ON
,06-30 13:10:45.625   298   298 E SMD     : DCD ON
,06-30 13:10:46.025   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:48.625   298   298 E SMD     : DCD ON
,06-30 13:10:51.625   298   298 E SMD     : DCD ON
,06-30 13:10:54.635   298   298 E SMD     : DCD ON
,06-30 13:10:56.085   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:10:57.635   298   298 E SMD     : DCD ON
,06-30 13:10:59.015   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 13:10:59.035  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,06-30 13:10:59.035  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:10:59.035  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
06-30 13:10:59.035  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:10:59.045   767   767 D LightsService: [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,06-30 13:10:59.045   767   767 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,06-30 13:10:59.065   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:10:59.065   767  1648 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:10:59.065   767  1648 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:10:59.065   767  1648 D BatteryService: stay LED for fully charged
,06-30 13:10:59.075  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:10:59.085  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:10:59.085   767   767 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,06-30 13:10:59.095   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:10:59.095  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:10:59.095  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:10:59.105  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:10:59.115  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:10:59.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:59.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:10:59.115  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:10:59.115  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:10:59.115   767   767 I MotionRecognitionService: Plugged
,06-30 13:10:59.115   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:10:59.455   767  1091 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,06-30 13:10:59.465   767  1091 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,06-30 13:10:59.465   767  1091 D SensorManager: unregisterListener ::   
,06-30 13:10:59.465   767  1091 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,06-30 13:10:59.725   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.745   767   918 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
06-30 13:10:59.745   767   918 D ActivityManager: com.google.android.gms, Starting
,06-30 13:10:59.755   767   918 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.apps.plus, action: android.content.SyncAdapter
,06-30 13:10:59.755   767   918 D ActivityManager: com.google.android.apps.plus, Starting
,06-30 13:10:59.775   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.785   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.795   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.795   767  3319 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.805   767  1222 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,06-30 13:10:59.875   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.965   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:10:59.995   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 13:11:00.155   767  1337 E Watchdog: !@Sync 42
,06-30 13:11:00.635   298   298 E SMD     : DCD ON
,06-30 13:11:03.635   298   298 E SMD     : DCD ON
,06-30 13:11:06.135   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:06.635   298   298 E SMD     : DCD ON
,06-30 13:11:09.125   767  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:09.125   767  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:11:09.125   767  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:11:09.125   767  1466 D BatteryService: stay LED for fully charged
,06-30 13:11:09.125   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:09.125   767   767 I MotionRecognitionService: Plugged
,06-30 13:11:09.125   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:09.125  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:11:09.125  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:09.135  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:09.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:09.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:11:09.135  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:09.145  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:09.145  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:09.635   298   298 E SMD     : DCD ON
,06-30 13:11:12.635   298   298 E SMD     : DCD ON
,06-30 13:11:15.635   298   298 E SMD     : DCD ON
,06-30 13:11:16.185   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:18.635   298   298 E SMD     : DCD ON
,06-30 13:11:19.185   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:19.185   767  3319 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:11:19.185   767  3319 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:11:19.195   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:19.195  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:19.195  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:19.205   767   767 I MotionRecognitionService: Plugged
,06-30 13:11:19.205   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:19.215   767  3319 D BatteryService: stay LED for fully charged
,06-30 13:11:19.215  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:19.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:19.215  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:19.225  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:19.225  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:19.225  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:21.635   298   298 E SMD     : DCD ON
,06-30 13:11:24.635   298   298 E SMD     : DCD ON
,06-30 13:11:26.235   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:27.645   298   298 E SMD     : DCD ON
,06-30 13:11:29.775   767  1114 V AlarmManager: waitForAlarm result :4
,06-30 13:11:29.805  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK,
,06-30 13:11:29.805  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:11:29.835   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:29.835   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:11:29.835   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:11:29.835   767  1467 D BatteryService: stay LED for fully charged
,06-30 13:11:29.835  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,06-30 13:11:29.835  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,06-30 13:11:29.845   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:29.845  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:29.855  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:29.855   767   767 I MotionRecognitionService: Plugged
,06-30 13:11:29.855   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:29.855  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:29.865  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:29.865  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:29.865  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:29.865  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:29.865  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:29.885  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:11:29.885  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,06-30 13:11:29.965   767   918 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,06-30 13:11:30.155   767  1337 E Watchdog: !@Sync 43
,06-30 13:11:30.645   298   298 E SMD     : DCD ON
,06-30 13:11:33.645   298   298 E SMD     : DCD ON
,06-30 13:11:36.305   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:36.645   298   298 E SMD     : DCD ON
,06-30 13:11:39.645   298   298 E SMD     : DCD ON
,06-30 13:11:39.895   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:39.905   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:11:39.905   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:11:39.905   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:11:39.905  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:11:39.905  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:11:39.905   767   767 I MotionRecognitionService: Plugged
06-30 13:11:39.905   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:11:39.915   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:11:39.915  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:11:39.915  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:39.915  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:39.915  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:11:39.915  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:11:39.925  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:11:42.645   298   298 E SMD     : DCD ON
,06-30 13:11:45.645   298   298 E SMD     : DCD ON
,06-30 13:11:46.375   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:48.645   298   298 E SMD     : DCD ON
,06-30 13:11:49.965   767  1648 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:11:51.645   298   298 E SMD     : DCD ON
,06-30 13:11:54.645   298   298 E SMD     : DCD ON
,06-30 13:11:56.465   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:11:57.645   298   298 E SMD     : DCD ON
,06-30 13:12:00.005   767  1114 V AlarmManager: waitForAlarm result :8
,06-30 13:12:00.065   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:00.065   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:12:00.065   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:12:00.065   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:12:00.065   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:00.075  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:00.075  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:00.075  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:00.075  2971  3065 D HeadsetStateMachine: Disconnected process message: 10,
,06-30 13:12:00.085  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:00.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:00.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:00.085   767   767 I MotionRecognitionService: Plugged
06-30 13:12:00.085   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:00.085  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:00.165   767  1337 E Watchdog: !@Sync 44
,06-30 13:12:00.645   298   298 E SMD     : DCD ON
,06-30 13:12:03.655   298   298 E SMD     : DCD ON
,06-30 13:12:04.685   767  1059 I PowerManagerService: [PWL] Off : 1265s ago
,06-30 13:12:06.545   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:12:06.655   298   298 E SMD     : DCD ON
,06-30 13:12:09.655   298   298 E SMD     : DCD ON
,06-30 13:12:10.125   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:10.125   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
06-30 13:12:10.125   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
06-30 13:12:10.125   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:12:10.125   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:10.135  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:10.135  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:12:10.135   767   767 I MotionRecognitionService: Plugged
,06-30 13:12:10.135   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:10.145  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:10.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:12:10.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:10.145  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:10.145  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:10.145  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:12.655   298   298 E SMD     : DCD ON
,06-30 13:12:15.655   298   298 E SMD     : DCD ON
,06-30 13:12:16.595   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:12:18.655   298   298 E SMD     : DCD ON
,06-30 13:12:20.185   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:21.655   298   298 E SMD     : DCD ON
,06-30 13:12:24.655   298   298 E SMD     : DCD ON
,06-30 13:12:26.645   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:12:27.655   298   298 E SMD     : DCD ON
,06-30 13:12:30.165   767  1337 E Watchdog: !@Sync 45
,06-30 13:12:30.245   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:30.255   767  1351 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:12:30.255   767  1351 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:12:30.255   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:12:30.265  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:12:30.265   767   767 I MotionRecognitionService: Plugged
,06-30 13:12:30.265  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:12:30.265   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:12:30.265   767  1351 D BatteryService: stay LED for fully charged
,06-30 13:12:30.275  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:12:30.275  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:30.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:30.285  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:12:30.285  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:12:30.285  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:12:30.655   298   298 E SMD     : DCD ON
,06-30 13:12:33.655   298   298 E SMD     : DCD ON
,06-30 13:12:36.655   298   298 E SMD     : DCD ON
,06-30 13:12:36.705   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:12:39.665   298   298 E SMD     : DCD ON
,06-30 13:12:40.305   767  3319 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:42.665   298   298 E SMD     : DCD ON
,06-30 13:12:45.665   298   298 E SMD     : DCD ON
,06-30 13:12:46.755   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,06-30 13:12:48.665   298   298 E SMD     : DCD ON
,06-30 13:12:50.365   767  1222 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:12:51.665   298   298 E SMD     : DCD ON
,06-30 13:12:54.665   298   298 E SMD     : DCD ON
,06-30 13:12:56.795   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 299, CUR = 300
,06-30 13:12:57.665   298   298 E SMD     : DCD ON
,06-30 13:13:00.165   767  1337 E Watchdog: !@Sync 46
,06-30 13:13:00.425   767  1470 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:00.425   767  1470 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:00.435   767  1470 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:13:00.435   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:00.445  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:00.445  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:00.445   767   767 I MotionRecognitionService: Plugged
06-30 13:13:00.445   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:00.445   767  1470 D BatteryService: stay LED for fully charged
,06-30 13:13:00.455  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:00.455  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:00.455  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:00.455  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:00.455  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:00.455  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:00.665   298   298 E SMD     : DCD ON
,06-30 13:13:03.665   298   298 E SMD     : DCD ON
,06-30 13:13:06.675   298   298 E SMD     : DCD ON
,06-30 13:13:06.875   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 299, CUR = 300
,06-30 13:13:09.675   298   298 E SMD     : DCD ON
,06-30 13:13:10.485   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:10.495   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:10.495   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:13:10.495   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:10.505   767   767 I MotionRecognitionService: Plugged
,06-30 13:13:10.505   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:10.515  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:10.515  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:10.515  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:10.515  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:10.515  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:10.525  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:10.525  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:10.525  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:10.525   767  1467 D BatteryService: stay LED for fully charged
,06-30 13:13:12.675   298   298 E SMD     : DCD ON
,06-30 13:13:15.675   298   298 E SMD     : DCD ON
,06-30 13:13:16.935   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 299, CUR = 300
,06-30 13:13:18.675   298   298 E SMD     : DCD ON
,06-30 13:13:20.555   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:21.675   298   298 E SMD     : DCD ON
,06-30 13:13:24.675   298   298 E SMD     : DCD ON
,06-30 13:13:26.985   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 298, CUR = 300
,06-30 13:13:27.675   298   298 E SMD     : DCD ON
,06-30 13:13:30.175   767  1337 E Watchdog: !@Sync 47
,06-30 13:13:30.615   767   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:30.625   767   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:30.625   767   784 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:13:30.625   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:30.635  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:30.635  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:13:30.635   767   767 I MotionRecognitionService: Plugged
,06-30 13:13:30.635   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:30.635  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:30.635   767   784 D BatteryService: stay LED for fully charged
,06-30 13:13:30.635  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:30.645  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:30.645  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:30.645  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:13:30.645  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:30.675   298   298 E SMD     : DCD ON
,06-30 13:13:33.675   298   298 E SMD     : DCD ON
,06-30 13:13:36.675   298   298 E SMD     : DCD ON
,06-30 13:13:37.045   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 297, CUR = 300
,06-30 13:13:39.675   298   298 E SMD     : DCD ON
,06-30 13:13:40.675   767  1142 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:40.685   767  1142 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:40.685   767  1142 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:13:40.685   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:40.695  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:40.695  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:13:40.695   767   767 I MotionRecognitionService: Plugged
,06-30 13:13:40.695   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:40.695  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:40.695  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:40.705  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:40.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:40.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:40.705  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:13:40.705   767  1142 D BatteryService: stay LED for fully charged
,06-30 13:13:42.675   298   298 E SMD     : DCD ON
,06-30 13:13:45.675   298   298 E SMD     : DCD ON
,06-30 13:13:47.115   767  3075 D SSRM:n  : SIOP:: AP = 300, PST = 297, CUR = 300
,06-30 13:13:48.685   298   298 E SMD     : DCD ON
,06-30 13:13:50.735   767  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:13:50.745   767  1467 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:13:50.745   767  1467 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:13:50.745   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:13:50.755   767   767 I MotionRecognitionService: Plugged
,06-30 13:13:50.755   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:13:50.755  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:13:50.755  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:13:50.755  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:50.755   767  1467 D BatteryService: stay LED for fully charged
,06-30 13:13:50.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:50.765  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:13:50.765  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:13:50.765  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:13:50.765  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:13:51.685   298   298 E SMD     : DCD ON
,06-30 13:13:54.685   298   298 E SMD     : DCD ON
,06-30 13:13:57.175   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 296, CUR = 300
,06-30 13:13:57.685   298   298 E SMD     : DCD ON
,06-30 13:13:59.695   767  1059 I PowerManagerService: [PWL] Off : 1380s ago
,06-30 13:14:00.175   767  1337 E Watchdog: !@Sync 48
,06-30 13:14:00.685   298   298 E SMD     : DCD ON
,06-30 13:14:00.795   767  3149 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:00.795   767  3149 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:14:00.805   767  3149 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:14:00.805   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:00.815   767   767 I MotionRecognitionService: Plugged
,06-30 13:14:00.815   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:14:00.815  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:00.815  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:00.815  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:14:00.815  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:14:00.815  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:00.825  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,06-30 13:14:00.825  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
06-30 13:14:00.825   767  3149 D BatteryService: stay LED for fully charged
,06-30 13:14:00.825  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:03.685   298   298 E SMD     : DCD ON
,06-30 13:14:06.685   298   298 E SMD     : DCD ON
,06-30 13:14:07.235   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 295, CUR = 300
,06-30 13:14:09.685   298   298 E SMD     : DCD ON
,06-30 13:14:10.855   767  1365 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:10.855   767  1365 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,06-30 13:14:10.865   767  1365 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,06-30 13:14:10.865   767   767 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,06-30 13:14:10.875   767   767 I MotionRecognitionService: Plugged
,06-30 13:14:10.875   767   767 I MotionRecognitionService: setPowerConnected  = true
,06-30 13:14:10.875  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,06-30 13:14:10.875  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,06-30 13:14:10.875  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,06-30 13:14:10.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:14:10.875  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:10.875   767  1365 D BatteryService: stay LED for fully charged
,06-30 13:14:10.885  2971  2971 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
06-30 13:14:10.885  2971  3065 D HeadsetStateMachine: Disconnected process message: 10
,06-30 13:14:10.885  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,06-30 13:14:12.685   298   298 E SMD     : DCD ON
,06-30 13:14:15.685   298   298 E SMD     : DCD ON
,06-30 13:14:17.295   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 294, CUR = 300
,06-30 13:14:18.685   298   298 E SMD     : DCD ON
,06-30 13:14:20.915   767  3290 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:21.695   298   298 E SMD     : DCD ON
,06-30 13:14:24.695   298   298 E SMD     : DCD ON
,06-30 13:14:27.345   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300
,06-30 13:14:27.695   298   298 E SMD     : DCD ON
,06-30 13:14:30.175   767  1337 E Watchdog: !@Sync 49
,06-30 13:14:30.695   298   298 E SMD     : DCD ON
,06-30 13:14:30.975   767  1351 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:33.695   298   298 E SMD     : DCD ON
,06-30 13:14:36.695   298   298 E SMD     : DCD ON
,06-30 13:14:37.385   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 293, CUR = 300
,06-30 13:14:39.695   298   298 E SMD     : DCD ON
,06-30 13:14:41.035   767  3234 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:14:42.695   298   298 E SMD     : DCD ON
,06-30 13:14:45.695   298   298 E SMD     : DCD ON
,06-30 13:14:47.435   767  3075 D SSRM:n  : SIOP:: AP = 290, PST = 292, CUR = 300
,TIME-OUT KILL (timeout was 1400000ms),06-30 13:14:48.695   298   298 E SMD     : DCD ON
06-30 13:14:48.935  7736  7736 D AndroidRuntime: 
06-30 13:14:48.935  7736  7736 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:14:48.945  7736  7736 D AndroidRuntime: CheckJNI is OFF
06-30 13:14:48.945  7736  7736 D AndroidRuntime: readGMSProperty: start
06-30 13:14:48.945  7736  7736 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:14:48.945  7736  7736 D AndroidRuntime: readGMSProperty: end
06-30 13:14:48.945  7736  7736 D AndroidRuntime: addProductProperty: start
06-30 13:14:49.135  7736  7736 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:14:49.155  7736  7736 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
06-30 13:14:49.175   767  1466 D PackageManager: START PACKAGE DELETE: observer{1657254}
06-30 13:14:49.175   767  1466 D PackageManager: pkg{<packageName>}
06-30 13:14:49.175   767  1466 D PackageManager: user{0}
06-30 13:14:49.175   767  1466 D PackageManager: caller{2000}
06-30 13:14:49.175   767  1466 D PackageManager: flags{2}
06-30 13:14:49.185   767  1466 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:14:49.185   767  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:14:49.185   767  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:14:49.185   767  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:14:49.185   767  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:14:49.185   767  1063 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:14:49.185   767  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:14:49.185   767  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:14:49.185   767  1063 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:14:49.185   767  1063 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
06-30 13:14:49.185   767  1063 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
06-30 13:14:49.185   767   924 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
06-30 13:14:49.195   767   924 I ActivityManager: Killing 7111:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
06-30 13:14:49.195   767   924 I ActivityManager:   Force finishing activity ActivityRecord{265460e3 u0 com.test.thalitest/.MainActivity t41}
06-30 13:14:49.195   767   924 D FocusedStackFrame: Set to : 0
06-30 13:14:49.205   266   416 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
06-30 13:14:49.205   266  1492 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
06-30 13:14:49.205   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:14:49.205   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:14:49.205   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
06-30 13:14:49.205   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:14:49.315   767  1063 W PackageSettings: Skipping PackageSetting{3606eaa4 com.example.hello/10078} due to missing metadata
06-30 13:14:49.335   767  3075 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:14:49.355   767  1063 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
06-30 13:14:49.385  5412  5412 I art     : Explicit concurrent mark sweep GC freed 107(16KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 380us total 28.649ms
06-30 13:14:49.405  4980  4980 I art     : Explicit concurrent mark sweep GC freed 7998(487KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 470us total 38.348ms
06-30 13:14:49.405  1503  1503 I art     : Explicit concurrent mark sweep GC freed 11321(678KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 20MB/33MB, paused 615us total 52.625ms
06-30 13:14:49.415  3707  3707 I art     : Explicit concurrent mark sweep GC freed 5386(298KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 485us total 23.843ms
06-30 13:14:49.415   767  1055 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
06-30 13:14:49.415   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
06-30 13:14:49.435   767  3445 E libprocessgroup: failed to kill 1 processes for processgroup 7111
06-30 13:14:49.445  1691  1691 E SamsungIME: mOCRHelper is null
06-30 13:14:49.445   767  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
06-30 13:14:49.455  1787  2236 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
06-30 13:14:49.455  6649  6649 I art     : Explicit concurrent mark sweep GC freed 6923(330KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 445us total 87.228ms
06-30 13:14:49.475  3992  3992 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
06-30 13:14:49.475  3992  3992 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467285289480
06-30 13:14:49.485  1420  1420 D RegisteredServicesCache: empty dynamic service
06-30 13:14:49.485  2520  2520 I art     : Explicit concurrent mark sweep GC freed 43022(2MB) AllocSpace objects, 24(827KB) LOS objects, 24% free, 24MB/32MB, paused 922us total 119.024ms
06-30 13:14:49.485   767  1144 V NetworkStats: removeUidsLocked() for UIDs [10079]
06-30 13:14:49.485   767  1144 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:14:49.485   767  1144 V NetworkStats: performPollLocked(flags=0x3)
06-30 13:14:49.485   767  1144 D NetworkStatsFactory: UpdateStatsForKnox
06-30 13:14:49.485   767  1144 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
06-30 13:14:49.495  3992  3992 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
06-30 13:14:49.505   767  1144 V NetworkStats: performPollLocked() took 18ms
06-30 13:14:49.505   767  1144 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:14:49.505   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:14:49.505   767  1145 D NtpTrustedTime: currentTimeMillis() cache hit
06-30 13:14:49.505  3992  3992 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
06-30 13:14:49.545   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
06-30 13:14:49.615   767   767 I art     : Explicit concurrent mark sweep GC freed 112650(10MB) AllocSpace objects, 359(5MB) LOS objects, 29% free, 37MB/53MB, paused 3.203ms total 224.710ms
06-30 13:14:49.615   767   779 I art     : WaitForGcToComplete blocked for 200.395ms for cause Background
06-30 13:14:49.615   767  1063 I art     : WaitForGcToComplete blocked for 94.426ms for cause Explicit
06-30 13:14:49.615   767   767 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
06-30 13:14:49.655   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
06-30 13:14:49.655   767  3149 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 13:14:49.655   767  3149 D SecContentProvider2: mCursor = null
06-30 13:14:49.665   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
06-30 13:14:49.675   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
06-30 13:14:49.675   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
06-30 13:14:49.685   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
06-30 13:14:49.695   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 13:14:49.695   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
06-30 13:14:49.695   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
06-30 13:14:49.705  3992  3992 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
06-30 13:14:49.705   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
06-30 13:14:49.715   767   918 D EnterpriseDeviceManagerService: Package has changed for user 0
06-30 13:14:49.715   767   918 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 13:14:49.715   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
06-30 13:14:49.715   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
06-30 13:14:49.715   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
06-30 13:14:49.725  3992  3992 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
06-30 13:14:49.725   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
06-30 13:14:49.725  6939  6939 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
06-30 13:14:49.725   767  1629 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 13:14:49.725   767  1629 D ActivityManager: caller:android.app.ApplicationThreadProxy@87e9306, r.packageName :com.sec.esdk.elm
06-30 13:14:49.735   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 13:14:49.735  6939  6939 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
06-30 13:14:49.735   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
06-30 13:14:49.735  3671  3671 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
06-30 13:14:49.735  3671  3671 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:14:49.735   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
06-30 13:14:49.735  3671  3671 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
06-30 13:14:49.735  3671  3671 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:14:49.735  3671  3671 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
06-30 13:14:49.735  3671  3671 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:14:49.735  3671  3671 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:14:49.735  3671  3671 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
06-30 13:14:49.735  3671  3671 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
06-30 13:14:49.735  6939  6939 D elm:14491: ElmAgentService : onCreate()
06-30 13:14:49.735   767   782 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
06-30 13:14:49.735  6939  7763 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 13:14:49.735   767   782 D ActivityManager: com.sec.android.service.health, Starting
06-30 13:14:49.735   767   767 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
06-30 13:14:49.735  6939  7763 D elm:14491: MainReceiver.listeningToPackageRemoved()
06-30 13:14:49.735  6939  7763 D elm:14491: MDMBridge.getInstance()
06-30 13:14:49.735  6939  7763 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:14:49.745  6939  7763 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:14:49.745   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.745   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.745   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.745   767   782 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.745   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
06-30 13:14:49.745   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
06-30 13:14:49.755   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
06-30 13:14:49.755   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
06-30 13:14:49.755   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
06-30 13:14:49.765   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
06-30 13:14:49.765   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
06-30 13:14:49.765   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
06-30 13:14:49.775   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
06-30 13:14:49.775   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
06-30 13:14:49.785  7764  7764 E Zygote  : MountEmulatedStorage()
06-30 13:14:49.785  7764  7764 E Zygote  : v2
06-30 13:14:49.785  7764  7764 I libpersona: KNOX_SDCARD checking this for 10021
06-30 13:14:49.785  7764  7764 I libpersona: KNOX_SDCARD not a persona
06-30 13:14:49.785   767   767 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
06-30 13:14:49.795   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.795  7764  7764 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:14:49.795  7764  7764 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:14:49.795  7764  7764 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:14:49.795   767   782 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=7764 uid=10021 gids={50021, 9997} abi=armeabi-v7a
06-30 13:14:49.795  6939  6939 D elm:14491: ElmAgentService : onDestroy().
06-30 13:14:49.805   767   767 D RCPManagerService: PackageReceiver onReceive()
06-30 13:14:49.805   767   767 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
06-30 13:14:49.805   767   767 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 13:14:49.805   767   767 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
06-30 13:14:49.805   767   767 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicy: uID is 10079
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
06-30 13:14:49.805   767   767 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
06-30 13:14:49.805   767  1177 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
06-30 13:14:49.805   767  3075 D SSRM:aY : MSG_TYPE_APP_REMOVED::
06-30 13:14:49.815   767   767 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
06-30 13:14:49.815  7764  7764 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:14:49.815   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.825  7764  7764 D ActivityThread: Added TimaKeyStore provider
06-30 13:14:49.825   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
06-30 13:14:49.825   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.825   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
06-30 13:14:49.835   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.835   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
06-30 13:14:49.835  7764  7764 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
06-30 13:14:49.845   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.845   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.845   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.845   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
06-30 13:14:49.855  1432  1432 D SurfaceWidgetView: destroyHardwareResources():1014931735
06-30 13:14:49.855   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.855   767  3319 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
06-30 13:14:49.855   767  3319 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
06-30 13:14:49.855   767  3319 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-30 13:14:49.855   767  3319 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
06-30 13:14:49.855   767  3319 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
06-30 13:14:49.855   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
06-30 13:14:49.855  1432  1432 D Launcher: onRestart, Launcher: 681776949
06-30 13:14:49.865  1432  1432 D Launcher: onStart, Launcher: 681776949
06-30 13:14:49.865  1432  1432 D Launcher.HomeView: onStart
06-30 13:14:49.865  1432  1432 V ActivityThread: updateVisibility : ActivityRecord{bfb58d8 token=android.os.BinderProxy@3b50ded6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
06-30 13:14:49.865  1735  1752 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
06-30 13:14:49.865  1735  2114 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
06-30 13:14:49.865  1735  2114 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
06-30 13:14:49.865  7764  7764 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
06-30 13:14:49.865  7764  7764 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
06-30 13:14:49.865  7764  7764 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
06-30 13:14:49.875   767  1439 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
06-30 13:14:49.875   767  1439 D ActivityManager: com.sec.pcw.device, Starting
06-30 13:14:49.875   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.875   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.875   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.875   767  1439 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:49.885   266   266 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
06-30 13:14:49.885   767  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:14:49.885   767  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:14:49.885   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.885   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.885   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
06-30 13:14:49.885   767  1055 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:14:49.885   767  1055 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:14:49.885   767  1055 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
06-30 13:14:49.885   767  1055 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
06-30 13:14:49.895   767   918 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 13:14:49.895   767   918 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:14:49.895   767   918 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:14:49.895   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.895   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
06-30 13:14:49.895   767   918 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
06-30 13:14:49.895   767  3290 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 13:14:49.895   767   918 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
06-30 13:14:49.895   767  3290 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7111 uid 10079
06-30 13:14:49.905   767  7783 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 13:14:49.905   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
06-30 13:14:49.915  7785  7785 E Zygote  : MountEmulatedStorage()
06-30 13:14:49.915  7785  7785 E Zygote  : v2
06-30 13:14:49.915  7785  7785 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:14:49.915  7785  7785 I libpersona: KNOX_SDCARD not a persona
06-30 13:14:49.915   767  1063 I art     : Explicit concurrent mark sweep GC freed 22392(1218KB) AllocSpace objects, 3(48KB) LOS objects, 29% free, 37MB/53MB, paused 3.766ms total 297.815ms
06-30 13:14:49.925   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
06-30 13:14:49.925   767  1439 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7785 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:14:49.925   767  1439 I ActivityManager: Killing 6604:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
06-30 13:14:49.935   331   331 I art     : Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 348us total 14.150ms
06-30 13:14:49.945   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.916ms
06-30 13:14:49.945   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.945   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
06-30 13:14:49.955  7785  7785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:14:49.955  7785  7785 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:14:49.955  7785  7785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:14:49.955   331   331 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 277us total 10.143ms
06-30 13:14:49.965   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.965   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
06-30 13:14:49.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.975   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 13:14:49.975   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
06-30 13:14:49.985   767  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{28de4f09 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t40} time:1508990
06-30 13:14:49.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.985   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
06-30 13:14:49.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 13:14:49.985   767   918 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
06-30 13:14:49.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.985   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
06-30 13:14:49.985   767   918 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
06-30 13:14:49.995  7785  7785 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:14:49.995   767   918 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:14:49.995  7785  7785 D ActivityThread: Added TimaKeyStore provider
06-30 13:14:49.995   767   918 D UsbSettingsManager: clearDefaults: com.test.thalitest
06-30 13:14:49.995   767   918 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
06-30 13:14:50.005  7785  7785 D ResourcesManager: creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
06-30 13:14:50.025  7785  7785 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-30 13:14:50.025  7785  7785 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-30 13:14:50.025  7785  7785 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
06-30 13:14:50.025   767  1063 D PackageManager: delete codoeFile: 
06-30 13:14:50.025   767  1063 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
06-30 13:14:50.025   767  1063 I AASA_removePackage: UID=10079 Target=com.test.thalitest
06-30 13:14:50.025   767  1063 D PackageManager: result of delete: 1{1657254}
06-30 13:14:50.035  7736  7736 D AndroidRuntime: Shutting down VM
06-30 13:14:50.035  7785  7785 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 13:14:50.035  7785  7785 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:14:50.035  7785  7785 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 13:14:50.035  7785  7785 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
06-30 13:14:50.045   767  1063 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 13:14:50.045   767  1063 D PackageManager: userId{-1}
06-30 13:14:50.045   767  1063 D PackageManager: andCode{true}
06-30 13:14:50.045   767  1063 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
06-30 13:14:50.055   767  1222 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
06-30 13:14:50.055   767  1222 D ActivityManager: caller:android.app.ApplicationThreadProxy@2465cd8b, r.packageName :com.sec.android.app.shealth
06-30 13:14:50.055   767  3319 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-30 13:14:50.055   767  3319 D ActivityManager: com.sec.spp.push, Starting
06-30 13:14:50.055   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.055   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.055   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.055   767  3319 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.095  7802  7802 E Zygote  : MountEmulatedStorage()
06-30 13:14:50.095  7802  7802 E Zygote  : v2
06-30 13:14:50.095  7802  7802 I libpersona: KNOX_SDCARD checking this for 10043
06-30 13:14:50.095  7802  7802 I libpersona: KNOX_SDCARD not a persona
06-30 13:14:50.095   767  3319 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7802 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:14:50.105  7802  7802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:14:50.105  7802  7802 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:14:50.105  7802  7802 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-30 13:14:50.105   767  1467 I ActivityManager: Killing 6649:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
06-30 13:14:50.115   767  3319 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
06-30 13:14:50.115   767  3319 D ActivityManager: caller:android.app.ApplicationThreadProxy@27390281, r.packageName :com.samsung.android.app.galaxyfinder
06-30 13:14:50.125  7802  7802 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:14:50.135  7802  7802 D ActivityThread: Added TimaKeyStore provider
06-30 13:14:50.145  7802  7802 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
06-30 13:14:50.175  7802  7802 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 13:14:50.175  7802  7802 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 13:14:50.185  7802  7802 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:14:50.185  7802  7802 D SPPClientService: PushLog.txt file is not deleted.
06-30 13:14:50.185  7802  7802 D SPPClientService: ============PushLog. stop!
06-30 13:14:50.195   767  1222 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
06-30 13:14:50.195   767  1222 D ActivityManager: com.sec.spp.push, Starting
06-30 13:14:50.195   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.195   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.195   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.195   767  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:14:50.255  7819  7819 E Zygote  : MountEmulatedStorage()
06-30 13:14:50.255  7819  7819 E Zygote  : v2
06-30 13:14:50.255  7819  7819 I libpersona: KNOX_SDCARD checking this for 10043
06-30 13:14:50.255  7819  7819 I libpersona: KNOX_SDCARD not a persona
06-30 13:14:50.265  7819  7819 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
06-30 13:14:50.265  7819  7819 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
06-30 13:14:50.265  7819  7819 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
06-30 13:14:50.265   767  1222 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7819 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:14:50.275   767  1222 I ActivityManager: Killing 6667:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
06-30 13:14:50.285  7819  7819 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:14:50.295  7819  7819 D ActivityThread: Added TimaKeyStore provider
06-30 13:14:50.315  7819  7819 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
06-30 13:14:50.345  7819  7819 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
06-30 13:14:50.345  7819  7819 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
06-30 13:14:50.345  7819  7819 D SPPClientService: PushLog.txt file is not deleted.

```
