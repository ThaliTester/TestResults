#### Test 7214543196063dc_thali07_samsung-SM-N9005 Logs


```
--------- beginning of system
07-05 14:03:49.490   907   994 W ProcessCpuTracker: Skipping unknown process pid 7094
07-05 14:03:49.550   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,--------- beginning of main
07-05 14:03:49.820   305   305 E SMD     : DCD ON
07-05 14:03:50.020  7098  7098 D AndroidRuntime: 
07-05 14:03:50.020  7098  7098 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:03:50.020  7098  7098 D AndroidRuntime: CheckJNI is OFF
07-05 14:03:50.020  7098  7098 D AndroidRuntime: readGMSProperty: start
07-05 14:03:50.020  7098  7098 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:03:50.030  7098  7098 D AndroidRuntime: readGMSProperty: end
07-05 14:03:50.030  7098  7098 D AndroidRuntime: addProductProperty: start
07-05 14:03:50.280  7098  7098 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:03:50.310  7098  7098 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-05 14:03:50.320   907  1468 E PersonaManagerService: inState():  stateMachine is null !!
07-05 14:03:50.320   907  1468 I PersonaManagerService: PersonaId don't exist
07-05 14:03:50.320   907  1468 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-05 14:03:50.320   907  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-05 14:03:50.320   907  1468 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 14:03:50.320   907  1468 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-05 14:03:50.330   907  1468 W ActivityManager: mDVFSHelper.acquire()
07-05 14:03:50.330   907  1468 D FocusedStackFrame: Set to : 0
07-05 14:03:50.340   907  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:50.340   907  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:50.340   907  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:50.340   907  1468 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:50.400   907  1468 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7114 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-05 14:03:50.400  7114  7114 E Zygote  : MountEmulatedStorage()
07-05 14:03:50.400  7114  7114 E Zygote  : v2
07-05 14:03:50.400  7114  7114 I libpersona: KNOX_SDCARD checking this for 10079
07-05 14:03:50.400  7114  7114 I libpersona: KNOX_SDCARD not a persona
07-05 14:03:50.420  7098  7098 D AndroidRuntime: Shutting down VM
07-05 14:03:50.420  7114  7114 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:03:50.420  7114  7114 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:03:50.420  7114  7114 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-05 14:03:50.440   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:03:50.440   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:03:50.440   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:03:50.440   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:03:50.460  7114  7114 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:03:50.460  7114  7114 D ActivityThread: Added TimaKeyStore provider
07-05 14:03:50.470   907  1689 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-05 14:03:50.470   907  1689 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-05 14:03:50.470   907  1689 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 14:03:50.470   907  1689 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-05 14:03:50.470   907  1689 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-05 14:03:50.480   907   907 V ActivityManager: Display changed displayId=0
07-05 14:03:50.510  1431  1431 D SurfaceWidgetView: destroyHardwareResources():981562756
07-05 14:03:50.530   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:03:50.530  7114  7114 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-05 14:03:50.610   267   971 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-05 14:03:50.610   267   318 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-05 14:03:50.620  1755  1768 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-05 14:03:50.620  1431  1431 V ActivityThread: updateVisibility : ActivityRecord{2d062f96 token=android.os.BinderProxy@3a6ebb2e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-05 14:03:50.620  1431  1431 D Launcher: onTrimMemory. Level: 20
,07-05 14:03:50.690  7114  7114 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-05 14:03:50.700  7114  7114 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-05 14:03:50.720  7114  7114 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8170-8174)
07-05 14:03:50.720  7114  7114 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:03:50.750  7114  7114 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {13d0263e}
07-05 14:03:50.750  7114  7114 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-05 14:03:50.750  7114  7114 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-05 14:03:50.790  7114  7114 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-05 14:03:50.790  7114  7114 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:03:50.800  7114  7114 E SysUtils: ApplicationContext is null in ApplicationStatus
07-05 14:03:50.840  7114  7114 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-05 14:03:50.840  7114  7114 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-05 14:03:50.840  7114  7114 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
07-05 14:03:50.850  7114  7114 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 14:03:50.850  7114  7114 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 14:03:50.850  7114  7114 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 14:03:50.850  7114  7114 I Adreno-EGL: Local Branch: mybranch5813579
07-05 14:03:50.850  7114  7114 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 14:03:50.850  7114  7114 I Adreno-EGL: Local Patches: NONE
07-05 14:03:50.850  7114  7114 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
07-05 14:03:51.020   907   994 W ActivityManager: Activity pause timeout for ActivityRecord{3673af94 u0 com.test.thalitest/.MainActivity t41}
07-05 14:03:51.190  7114  7160 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
07-05 14:03:51.280  7114  7114 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:03:51.310  7114  7114 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-05 14:03:51.370  7114  7114 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
07-05 14:03:51.390  7114  7114 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:03:51.390  7114  7114 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-05 14:03:51.560  7114  7114 D Activity: performCreate Call secproduct feature valuefalse
07-05 14:03:51.560  7114  7114 D Activity: performCreate Call debug elastic valuetrue
07-05 14:03:51.600  7114  7186 D OpenGLRenderer: Render dirty regions requested: true
07-05 14:03:51.600   907  1689 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:03:51.600   907  1689 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:03:51.600   907  1689 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:03:51.600   907   907 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:03:51.600   907   907 D PersonaManagerService: getPersonasForUser(): returning null!
07-05 14:03:51.610  7114  7114 V ActivityThread: updateVisibility : ActivityRecord{8d4b008 token=android.os.BinderProxy@364f77fa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:03:51.650   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
07-05 14:03:51.650   907  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:03:51.660   907  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:03:51.690   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:03:51.690   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:03:51.690   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:03:51.690   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:03:51.700  7114  7186 I OpenGLRenderer: Initialized EGL, version 1.4
07-05 14:03:51.710  7114  7186 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cc7c68 ,&mEglDisplay = 1 , &mEglConfig = 8 
07-05 14:03:51.720  7114  7186 D OpenGLRenderer: Enabling debug mode 0
07-05 14:03:51.770   907  1093 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:03:51.790   907  7189 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 14:03:51.800   907  1058 W ActivityManager: mDVFSHelper.release()
07-05 14:03:51.800   907  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3673af94 u0 com.test.thalitest/.MainActivity t41} time:99250
07-05 14:03:51.820  7114  7114 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
07-05 14:03:51.820  1725  1725 I SamsungIME: getCurrentCandidateView
07-05 14:03:51.850  7114  7114 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364f77fa time:99301
07-05 14:03:51.870   907  3328 D SSRM:n  : SIOP:: AP = 360, PST = 414, CUR = 300
07-05 14:03:51.910  7114  7114 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7114
07-05 14:03:51.960  1725  1725 D SamsungIME: Dismiss ExpandCandiate
07-05 14:03:52.060  1725  1725 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:03:52.100  1725  1725 I SamsungIME: getDebugLevel  : 0x4f4c
,07-05 14:03:52.120  1725  1725 I SamsungIME: KeybaordView init() : load resources
,07-05 14:03:52.140  1725  1725 I SamsungIME: getCurrentKeyboard
07-05 14:03:52.140  1725  1725 I SamsungIME: getTextKeyboard
,07-05 14:03:52.150  7114  7114 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-05 14:03:52.170  1725  1725 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 14:03:52.280  7114  7191 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1358211456
,07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-05 14:03:52.300  7114  7191 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20182b38 added. We now have 1 listener(s)
,07-05 14:03:52.310  7114  7191 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,07-05 14:03:52.310  7114  7191 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-05 14:03:52.310  7114  7191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-05 14:03:52.310  7114  7191 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-05 14:03:52.310  7114  7191 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@322fd677 added. We now have 1 listener(s)
,07-05 14:03:52.310  7114  7191 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-05 14:03:52.340  7114  7191 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,07-05 14:03:52.340  7114  7191 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
,07-05 14:03:52.340  7114  7191 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,07-05 14:03:52.350  7114  7191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-05 14:03:52.350  7114  7191 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,07-05 14:03:52.370   907  3589 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:03:52.380  7114  7191 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-05 14:03:52.380  7114  7191 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-05 14:03:52.380  7114  7191 D io.jxcore.node.ConnectivityMonitor: start: OK
07-05 14:03:52.380   907   922 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:52.380  7114  7114 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-05 14:03:52.380   907  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:52.390  7114  7114 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,07-05 14:03:52.390  7114  7191 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-05 14:03:52.450  7114  7114 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-05 14:03:52.600  1725  7208 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-05 14:03:52.820   305   305 E SMD     : DCD ON
,07-05 14:03:53.440  7114  7214 W jxcore-log: Initializing JXcore engine
,07-05 14:03:53.440  7114  7214 W jxcore-log: JXcore engine is ready
,07-05 14:03:53.500  1788  1788 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-05 14:03:53.500  1788  1788 E audit   : type=1400 msg=audit(1467720233.500:203): avc:  denied  { ioctl } for  pid=7214 comm="Thread-1179" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-05 14:03:53.500  1788  1788 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-05 14:03:53.500  1788  1788 E audit   : 
07-05 14:03:53.500  1788  1788 E audit   : type=1300 msg=audit(1467720233.500:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9a6008d8 items=0 ppid=348 ppcomm=main pid=7214 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1179" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,07-05 14:03:53.500  1788  1788 E audit   : type=1320 msg=audit(1467720233.500:203): 
07-05 14:03:53.500   907  1041 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-05 14:03:53.500   907  1041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-05 14:03:53.500   907   994 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
07-05 14:03:53.500   907   994 D ActivityManager: com.samsung.android.securitylogagent, Starting
,07-05 14:03:53.510   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:53.510   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:53.510   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:53.510   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:03:53.510   907  1041 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-05 14:03:53.520  7114  7214 W jxcore-log: Starting JXcore engine
,07-05 14:03:53.540   907   994 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,07-05 14:03:53.550  7219  7219 E Zygote  : MountEmulatedStorage()
,07-05 14:03:53.550  7219  7219 E Zygote  : v2
07-05 14:03:53.550  7219  7219 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:03:53.550  7219  7219 I libpersona: KNOX_SDCARD not a persona
,07-05 14:03:53.570   348   348 I art     : Explicit concurrent mark sweep GC freed 8763(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 11.796ms total 27.115ms
,07-05 14:03:53.580  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:03:53.580  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:03:53.580  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:03:53.580   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.274ms
,07-05 14:03:53.590   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 9.397ms
,07-05 14:03:53.620  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:03:53.620  7219  7219 D ActivityThread: Added TimaKeyStore provider
,07-05 14:03:53.640  7219  7219 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-05 14:03:53.660  7219  7219 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-05 14:03:53.660  7219  7219 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-05 14:03:53.660   907  1468 I ActivityManager: Killing 5963:com.sec.providers.settingsearch/u0a191 (adj 15): emptyCount ##41
,07-05 14:03:53.660  7114  7214 W jxcore-log: Platform android
07-05 14:03:53.660  7114  7214 W jxcore-log: 
,07-05 14:03:53.660  7114  7214 W jxcore-log: Process ARCH arm
07-05 14:03:53.660  7114  7214 W jxcore-log: 
,07-05 14:03:53.860  7114  7214 I jxcore-log: JXcore Cordova bridge is ready!
07-05 14:03:53.860  7114  7214 I jxcore-log: 
,07-05 14:03:53.860  7114  7214 W jxcore-log: JXcore engine is started
,07-05 14:03:53.870  7114  7191 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-05 14:03:53.870  7114  7114 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-05 14:03:55.820   305   305 E SMD     : DCD ON
,07-05 14:03:56.330   907   922 I art     : Explicit concurrent mark sweep GC freed 69283(4MB) AllocSpace objects, 17(566KB) LOS objects, 29% free, 37MB/53MB, paused 1.340ms total 116.188ms
,07-05 14:03:57.380   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:03:57.380   907   994 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
07-05 14:03:57.380   907   994 D ActivityManager: com.sec.enterprise.knox.cloudmdm.smdms, Starting
,07-05 14:03:57.380   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:57.380   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:57.380   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:03:57.380   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:03:57.430   907   994 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler: pid=7257 uid=10201 gids={50201, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,07-05 14:03:57.440   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:03:57.440   907  1240 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4292, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:03:57.440   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:03:57.440   907  1240 D BatteryService: stay LED for charging
07-05 14:03:57.440   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:03:57.450  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:03:57.450  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:03:57.450  7257  7257 E Zygote  : MountEmulatedStorage()
07-05 14:03:57.450  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:03:57.450  7257  7257 I libpersona: KNOX_SDCARD checking this for 10201
07-05 14:03:57.450  7257  7257 E Zygote  : v2
07-05 14:03:57.450  7257  7257 I libpersona: KNOX_SDCARD not a persona
,07-05 14:03:57.450   907   907 I MotionRecognitionService: Plugged
,07-05 14:03:57.450   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:03:57.470  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:03:57.470  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 14:03:57.470  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:03:57.470  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:03:57.470  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:03:57.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:03:57.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
07-05 14:03:57.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:03:57.510  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:03:57.510  7257  7257 D ActivityThread: Added TimaKeyStore provider
,07-05 14:03:57.520  7257  7257 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,07-05 14:03:57.520  7257  7257 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-05 14:03:57.540  7257  7257 D UMC:Core: onCreate(): 
,07-05 14:03:57.600  7257  7257 D USER_AGENT: UMC/1.1.40 (SM-N9005) SAFE-5.3 KNOX-2.3
,07-05 14:03:57.680  7257  7257 D [SAMSUNG SMARCART NATIVE]: initialize...
07-05 14:03:57.680  7257  7257 D [SAMSUNG SMARCART NATIVE]: DEBUG: connect to PKCS#11 module: libtlc_tz_ccm.so 
,07-05 14:03:57.690  7257  7257 I CSTORAGE: ================================================
07-05 14:03:57.690  7257  7257 I CSTORAGE:  CSTORAGE_SKM_LIB, v1.0.22, MSM8974|MSM8x26|MSM8x10
07-05 14:03:57.690  7257  7257 I CSTORAGE: ================================================
,07-05 14:03:57.690  7257  7257 I TZ_CCM_C_GetFunctionList: : TZ_CCM_C_GetFunctionList was called
07-05 14:03:57.690  7257  7257 D [SAMSUNG SMARCART NATIVE]: FINISHED: initialize rv:0
,07-05 14:03:57.750  7257  7257 D UMC:SecurityUtils: Loaded server certificates: 0
,07-05 14:03:57.750  7257  7257 D UMC:SecurityUtils: Loaded server certificates: 0
07-05 14:03:57.750  7257  7257 D UMC:SecurityUtils: timaVersion on the device: 3.0
,07-05 14:03:57.750  7257  7257 D UMC:CloudMDMSecurity: New Flow
,07-05 14:03:57.750   907  1459 D TimaService: TIMA3: in ccmRegisterForDefaultCertificate
07-05 14:03:57.750   907  1459 D TimaService: TIMA: in getTimaVersion
07-05 14:03:57.750   907  1459 I         : CCM JNI: In ccm_register_for_default_cert
07-05 14:03:57.750   907  1459 I         : CCM JNI: In ccm_create_slot
07-05 14:03:57.750   907  1459 I TZ_CCM_C_Initialize: : DEBUG_CONTAINER_PROBLEM Enter TZ_CCM_C_Initialize_TLC!
07-05 14:03:57.750   907  1459 I TZ_CCM_C_Initialize: : pInitArgs 0x95701814 has not called C_Init before.
07-05 14:03:57.750   907  1459 I TZ_CCM_C_Initialize: : &ctx = 0x9ffb0c1c
07-05 14:03:57.750   907  1459 I TLC_TZ_CCM: : creating new ccm context...
07-05 14:03:57.750   907  1459 I TLC_TZ_CCM: : initializing ccm context...
07-05 14:03:57.750   907  1459 I TLC_TZ_CCM: : root = /firmware/image, root_strlen = 15
07-05 14:03:57.750   907  1459 I TLC_TZ_CCM: : process = tz_ccm, process_strlen = 6
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: input max_sendmsg_size = 19420
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: input max_recvmsg_size = 19420
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: root = /firmware/image, root_len = 15
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: process = tz_ccm, process_strlen = 6
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: aligned max_sendmsg_size = 19456
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: aligned max_recvmsg_size = 19456
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: Client_Server_Open was called
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: IClientServer::IClientServer()
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: BpClientServer::BpClientServer()
07-05 14:03:57.750   907  1459 I TZ: client_server_communication: IClientServer::~IClientServer()
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: BnCCM::onTransact(0) 16
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: OPENSWCONN
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: creating new ccm context...
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: initializing ccm context...
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: root = /firmware/image, root_strlen = 15
07-05 14:03:57.750  1103  1107 I TZ_CCM_SERVER: process = tz_ccm, process_strlen = 6
07-05 14:03:57.750  1103  1107 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
07-05 14:03:57.750  1103  1107 I TZ: qc_tlc_communication: process = tz_ccm, process_strlen = 6
07-05 14:03:57.750  1103  1107 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 19456 = 0x4c00
07-05 14:03:57.750  1103  1107 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 19456 = 0x4c00
07-05 14:03:57.750  1103  1107 I TZ: qc_tlc_communication: max_message_size = 38912 = 0x9800
07-05 14:03:57.750  1103  1107 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x9800
07-05 14:03:57.750  1103  1107 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:03:57.770  1103  1107 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 14:03:57.770  1103  1107 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tz_ccm, tzapp is loaded
,07-05 14:03:57.770   907  1459 I TZ: client_server_communication: OpenSWConn(CCM) is successful
07-05 14:03:57.770   907  1459 I TZ: client_server_communication: Client_Server_Open succeeded, serverName = CCM
07-05 14:03:57.770   907  1459 I TZ_CCM_C_Initialize: : ctx = 0x93ba0140, comm = 0x922e7328, sendmsg = 0x9102c000, recvmsg = 0x91030c00
07-05 14:03:57.770   907  1459 I TZ_init: : TZ_init: sending initialization request...
07-05 14:03:57.770   907  1459 I TZ: client_server_communication: Cmd id = 2, len = 19456
,07-05 14:03:57.770   907  1459 I TZ: client_server_communication: Calling Communicate()
07-05 14:03:57.770  1103  1103 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
07-05 14:03:57.770  1103  1103 I TZ_CCM_SERVER: COMM
,07-05 14:03:57.770   907  1459 I TZ_init: : TZ_init: successful initialization
,07-05 14:03:57.770   907  1459 I TLC_TZ_COMMON: key_db_init: : Exercising TZ_DB_INIT in TLC
07-05 14:03:57.770   907  1459 I TZ: client_server_communication: Cmd id = 17, len = 19456
07-05 14:03:57.770   907  1459 I TZ: client_server_communication: Calling Communicate()
,07-05 14:03:57.770  1103  4307 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
07-05 14:03:57.770  1103  4307 I TZ_CCM_SERVER: COMM
,07-05 14:03:57.780   907  1459 I TZ_COMMON: tlc_key_db_util: : DB Operation suceeded
,07-05 14:03:57.780   907  1459 I TLC_TZ_CCM: register for default cert: : Exercising TZ_CCM_register_default_TLC
07-05 14:03:57.780   907  1459 I TZ: client_server_communication: Cmd id = 25, len = 19456
07-05 14:03:57.780   907  1459 I TZ: client_server_communication: Calling Communicate()
,07-05 14:03:57.780  1103  1107 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
07-05 14:03:57.780  1103  1107 I TZ_CCM_SERVER: COMM
,07-05 14:03:57.780   907  1459 I TLC_TZ_CCM: register for default cert: : TZ_CCM_register_default_TLC_END: DB file size to update is 0
,07-05 14:03:57.780   907  1459 I TLC_TZ_CCM: register for default cert: : TZ_CCM_register_default_TLC: Slot ID 0 allocated for cid: 0
07-05 14:03:57.780   907  1459 I TZ_CCM_C_Finalize: : DEBUG_CONTAINER_PROBLEM Exercising TZ_CCM_C_Finalize_TLC
07-05 14:03:57.780   907  1459 I TZ: client_server_communication: Cmd id = 41, len = 19456
07-05 14:03:57.780   907  1459 I TZ: client_server_communication: Calling Communicate()
,07-05 14:03:57.780  1103  1103 I TZ_CCM_SERVER: BnCCM::onTransact(2) 16
,07-05 14:03:57.780  1103  1103 I TZ_CCM_SERVER: COMM
,07-05 14:03:57.780   907  1459 I TZ: client_server_communication: Client_Server_Close was called
,07-05 14:03:57.790  1103  7282 I TZ_CCM_SERVER: BnCCM::onTransact(1) 16
07-05 14:03:57.790  1103  7282 I TZ_CCM_SERVER: CLOSESWCONN
07-05 14:03:57.790  1103  7282 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:03:57.790  1103  7282 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,07-05 14:03:57.790   907  1459 I TZ: client_server_communication: Client_Server_Close succeeded
,07-05 14:03:57.790  7257  7257 D UMC:CloudMDMSecurity: ccmRegisterForDefaultCertificate: 0
07-05 14:03:57.790  7257  7257 D UMC:CloudMDMSecurity: TIMA service call for password change success!!
,07-05 14:03:57.790  7257  7257 D UMC:AdminManager: init - start
,07-05 14:03:57.810  7257  7257 D UMC:AdminManager: loadAdmins
,07-05 14:03:57.820  7257  7257 D UMC:AdminManager: startPolicyHandlers
,07-05 14:03:57.820  7257  7257 I UMC:TestPolicyHandler: Setup is called in testpolicyhandler
,07-05 14:03:57.820  7257  7257 D UMC:AdminManager: init - end
,07-05 14:03:57.830  7257  7257 V UMC:AlarmHandler: Enter loadList
,07-05 14:03:57.850  7257  7257 D GSLBManager: migrateStoredUrlFromOldPref
,07-05 14:03:57.860  7257  7257 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,07-05 14:03:57.860  7257  7257 D UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,07-05 14:03:57.860  7257  7257 E UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,07-05 14:03:57.860  7257  7257 D UMC:UMCAdmin: deactivateUMCAdmin : -1
,07-05 14:03:57.860  7257  7257 D UMC:UMCAdmin: isContainer : 0
,07-05 14:03:57.860   907  1093 W LicenseLogService: log() failed
,07-05 14:03:57.870   907  1636 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,07-05 14:03:57.870  7257  7257 E UMC:UMCAdmin: No active admin owned by uid 10201
,07-05 14:03:57.870  7257  7257 D UMC:UMCAdmin: isContainer : 0
,07-05 14:03:57.870  7257  7257 D UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,07-05 14:03:57.870  7257  7257 V UMC:AlarmHandler: onReceive :Intent { flg=0x14 cmp=com.sec.enterprise.knox.cloudmdm.smdms/.core.AlarmHandler (has extras) }
,07-05 14:03:57.870   907  1655 I ActivityManager: Killing 6560:flipboard.app/u0a125 (adj 15): emptyCount ##41
,07-05 14:03:57.880   907   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:57.900   907  1733 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:03:57.900   907  1733 D ActivityManager: caller:android.app.ApplicationThreadProxy@202626bf, r.packageName :com.google.android.gms
,07-05 14:03:57.920  7257  7257 D QuickStartReceiver: Msg Id : 2
,07-05 14:03:57.920  7257  7257 D QuickStartReceiver: model : SM-N9005
07-05 14:03:57.920  7257  7257 D QuickStartReceiver: id : 100
,07-05 14:03:57.960   907  3589 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 14:03:57.970  1870  1870 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:03:57.970  1870  1870 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:03:58.020   907  3589 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 14:03:58.020  1870  2436 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:03:58.030  1870  2436 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-05 14:03:58.030  1870  2436 I qtaguid : Tagging socket 42 with tag 1000040100000000{268436481,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:03:58.070  1870  2436 I qtaguid : Tagging socket 74 with tag 1000040100000000{268436481,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:03:58.250   907  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:58.290   907   922 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:03:58.290   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@2563558d, r.packageName :com.google.android.gms
,07-05 14:03:58.320  2452  3796 D NetworkUsageDbReporter: Started reporting usage
,07-05 14:03:58.320   907  1459 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 14:03:58.320   907  1093 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:03:58.320   907  1093 D ActivityManager: caller:android.app.ApplicationThreadProxy@2312a18e, r.packageName :com.google.android.gms
,07-05 14:03:58.340  1870  7305 D GCM     : GcmService start Intent { act=com.google.android.gcm.intent.SEND flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.gcm.intent.SEND
,07-05 14:03:58.340   907   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 52646
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: keeping row: 263
,07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7676
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: keeping row: 262
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 76715
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: keeping row: 256
,07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 18059
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: keeping row: 278
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 13948
07-05 14:03:58.370  2452  3796 D NetworkUsageDbReporter: keeping row: 255
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 7149
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 275
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 41222
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 264
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 4361
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 260
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 10069
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 259
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 15178
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 258
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 89257
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 257
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 30440
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 265
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 277940
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 254
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 1025206
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 253
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 9982
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 220
,07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 2246
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 214
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: groudData rxBackgroundBytes: 83586
07-05 14:03:58.380  2452  3796 D NetworkUsageDbReporter: keeping row: 213
,07-05 14:03:58.400  2452  3796 D NetworkUsageDbReporter: Finished reporting usage.
,07-05 14:03:58.410   907  1093 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:03:58.820   305   305 E SMD     : DCD ON
,07-05 14:03:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:04:00.380   907  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-05 14:04:01.240   907  1333 E Watchdog: !@Sync 3
,07-05 14:04:01.710   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:04:01.730   907   907 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-05 14:04:01.730   907   907 V AlarmManagerEXT: <AppSync3 Whitelist>
07-05 14:04:01.730   907   907 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-05 14:04:01.730  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:04:01.730  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:04:01.730  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:04:01.730  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:04:01.740   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:01.750   907  3589 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:01.780  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:04:01.780  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:04:01.800   907  1429 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:01.800   907  1429 D ActivityManager: caller:android.app.ApplicationThreadProxy@42aa945, r.packageName :com.google.android.gms
07-05 14:04:01.800   907  1060 I PowerManagerService: [PWL] Off : 30s ago
07-05 14:04:01.800   907  1060 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-05 14:04:01.810   907  1060 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-05 14:04:01.810   907  1060 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.notifications.GunsService' (uid=10015, pid=1870, ws=null) (elapsedTime=52556)
07-05 14:04:01.810   907  1060 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10015, pid=1870, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=56)
07-05 14:04:01.810   907  1060 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*net_scheduler*' (uid=10015, pid=1870, ws=WorkSource{10015 com.google.android.gms}) (elapsedTime=18)
,07-05 14:04:01.820   907  1359 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
07-05 14:04:01.820   907  1359 D ActivityManager: com.google.android.gms, Starting
,07-05 14:04:01.820   305   305 E SMD     : DCD ON
,07-05 14:04:01.840   907   924 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:01.840   907   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@257033a7, r.packageName :com.google.android.gms
,07-05 14:04:01.860  2452  7318 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,07-05 14:04:01.860  2452  7318 D SchedPeriodicTask: Scheduled AdAttestation task.
,07-05 14:04:01.870  1870  1870 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-05 14:04:01.890   907  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:01.930   907  3328 D SSRM:n  : SIOP:: AP = 400, PST = 412, CUR = 300
,07-05 14:04:01.930   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:01.960   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:01.960  1870  1870 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,07-05 14:04:01.990   907  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:01.990   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ba1bbfd, r.packageName :com.google.android.gms
,07-05 14:04:02.020   907  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:02.020   907  1472 D ActivityManager: caller:android.app.ApplicationThreadProxy@34626343, r.packageName :com.google.android.gms
,07-05 14:04:02.060   907  1733 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:02.110   907  1733 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:02.110   907  1733 D ActivityManager: caller:android.app.ApplicationThreadProxy@232a15ec, r.packageName :com.google.android.gms
,07-05 14:04:02.200   907  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:02.200   907  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:02.200   907  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:02.200   907  1733 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:02.240  7325  7325 E Zygote  : MountEmulatedStorage()
07-05 14:04:02.240  7325  7325 E Zygote  : v2
07-05 14:04:02.240  7325  7325 I libpersona: KNOX_SDCARD checking this for 10015
07-05 14:04:02.240  7325  7325 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:02.250   907  1733 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7325 uid=10015 gids={50015, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,07-05 14:04:02.290  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:04:02.290  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 14:04:02.290  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-05 14:04:02.310  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:02.320  7325  7325 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:02.330  7325  7325 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-05 14:04:02.330  7325  7325 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-05 14:04:02.330  7325  7325 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-05 14:04:02.370  7325  7325 I MultiDex: VM with version 2.1.0 has multidex support
,07-05 14:04:02.370  7325  7325 I MultiDex: install
07-05 14:04:02.370  7325  7325 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-05 14:04:02.400  7325  7325 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-05 14:04:02.460   907  1733 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-05 14:04:02.460  7325  7325 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-05 14:04:02.460  7325  7325 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@4827b5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-05 14:04:02.460  7325  7325 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-05 14:04:02.470  7325  7325 D ChimeraCfgMgr: Reading stored module config
,07-05 14:04:02.490  1870  1870 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=054d7814-6584-4108-9925-ab15a70bc4e9
,07-05 14:04:02.560  7325  7347 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,07-05 14:04:02.560  7325  7325 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 14:04:02.560  7325  7325 I art     : Rejecting re-init on previously-failed class java.lang.Class<inz>
,07-05 14:04:02.640   310  2435 D WVCdm   : Instantiating CDM.
,07-05 14:04:02.640   310   310 I WVCdm   : CdmEngine::OpenSession
07-05 14:04:02.640   310   310 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,07-05 14:04:02.650  1870  2277 W GCoreFlp: No location to return for getLastLocation()
,07-05 14:04:02.650   310   310 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,07-05 14:04:02.670   907  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@240aea77, r.packageName :com.google.android.gms
,07-05 14:04:02.670   907  1655 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b2046e4, r.packageName :com.google.android.gms
,07-05 14:04:02.680   310   310 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x13
07-05 14:04:02.680   310   310 D DrmWidevineDash: Service_Initialize: starts!
07-05 14:04:02.680   310   310 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,07-05 14:04:02.680   310   310 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:02.680   310   310 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
07-05 14:04:02.680   310   310 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 14:04:02.680   310   310 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:02.680   310   310 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:02.680   310   310 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
07-05 14:04:02.680   310   310 E QSEECOMAPI: : Error::Loading image failed with ret = -1
07-05 14:04:02.680   310   310 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
07-05 14:04:02.680   310   310 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:04:02.680   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aafd74d, r.packageName :com.google.android.gms
,07-05 14:04:02.700   310   310 D QSEECOMAPI: : Loaded image: APP id = 2
07-05 14:04:02.700  7325  7337 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:02.700  7325  7337 I System.out: (HTTPLog)-Static: isShipBuild true
07-05 14:04:02.700  7325  7337 I System.out: (HTTPLog)-Thread-1170-604539564: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
07-05 14:04:02.700  7325  7337 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:02.700   310   310 D DrmWidevineDash: Service_Initialize: ends! returns 0
07-05 14:04:02.700   310   310 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb18e6000
07-05 14:04:02.700   310   310 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb18e6000
,07-05 14:04:02.710  7325  7337 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-05 14:04:02.710  7325  7337 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} uid -1, pid: 7325, getuid(): 10015
,07-05 14:04:02.720   310   310 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
07-05 14:04:02.720   310   310 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:02.720   310   310 D DrmWidevineDash: hlos api version =  9
07-05 14:04:02.720   310   310 D DrmWidevineDash: tz api version =  8
07-05 14:04:02.720   310   310 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 14:04:02.720   310   310 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
,07-05 14:04:02.720  2452  7322 D UdcContextInitService: registered all accounts: true
,07-05 14:04:02.730  1870  2326 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
07-05 14:04:02.730   310   310 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xbeb361b0
,07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb191a070, dataLength=8
,07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts!SID=1, wrapped_rsa_key=0xb265b000, wrapped_rsa_key_length=1280
,07-05 14:04:02.730   310   310 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
07-05 14:04:02.730   310   310 I WVCdm   : CdmEngine::QueryKeyControlInfo
,07-05 14:04:02.730   310   677 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
07-05 14:04:02.730   310   677 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
07-05 14:04:02.730   310   677 I WVCdm   : CdmEngine::GenerateKeyRequest
07-05 14:04:02.730   310   677 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb0676740, idLength=0xb1eff710
,07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 25
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0x0
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!
,07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0x0
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
,07-05 14:04:02.740   310   677 D DrmWidevineDash: hlos api version =  9
07-05 14:04:02.740   310   677 D DrmWidevineDash: tz api version =  8
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1
,07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
07-05 14:04:02.740   310   677 D WVCdm   : PrepareKeyRequest: nonce=2778503591
07-05 14:04:02.740   310   677 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb0345600
07-05 14:04:02.740   310   677 D DrmWidevineDash: message_length=1587, signature=0xb001b680, signature_length=2985293556
,07-05 14:04:02.750  1870  2392 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,07-05 14:04:02.820   907  1093 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:02.820   310   677 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,07-05 14:04:02.820   310  6322 I WVCdm   : CdmEngine::CloseSession
,07-05 14:04:02.820   310  6322 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
07-05 14:04:02.820   310  6322 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
07-05 14:04:02.820   310  6322 I WVCdm   : L3 Terminate.
07-05 14:04:02.820   310  6322 D DrmWidevineDash: OEMCrypto_Terminate: starts!
,07-05 14:04:02.820   310  6322 D DrmWidevineDash: Service_Uninitialize: starts!
07-05 14:04:02.820   310  6322 D QSEECOMAPI: : QSEECom_dealloc_memory 
07-05 14:04:02.820   310  6322 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 2
,07-05 14:04:02.820   310  6322 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
07-05 14:04:02.820   310  6322 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,07-05 14:04:02.870   907  1359 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,07-05 14:04:02.890  1870  2392 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:02.890  1870  2392 I qtaguid : Tagging socket 42 with tag 1000040100000000{268436481,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:04:03.000  7325  7337 I qtaguid : Untagging socket 30
,07-05 14:04:03.050  7325  7337 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
,07-05 14:04:03.050  7325  7337 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
,07-05 14:04:03.060  7325  7337 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
,07-05 14:04:03.060  7325  7337 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000003@DynamiteModulesA_GmsCore_prodlmp_xxhdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000003/DynamiteModulesA_GmsCore_prodlmp_xxhdpi_release.apk': Failed to open oat filename for reading: No such file or directory
,07-05 14:04:03.070  7325  7337 D ChimeraFileApk: Classloading successful. Optimized code found.
,07-05 14:04:03.070  7325  7337 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
,07-05 14:04:03.120   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:04:03.120   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:04:03.150  7325  7337 D GoogleCertificatesImpl: Fetched 163 Google release certificates
,07-05 14:04:03.280  7357  7357 I dex2oat : ----------------------------------------------------
07-05 14:04:03.280  7357  7357 I dex2oat : <SS>: S T A R T I N G . . .
07-05 14:04:03.280  7357  7357 I dex2oat : <SS>: Zip is absent. Canceled.
,07-05 14:04:03.280  7357  7357 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/the.apk --oat-fd=37 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_dg_cache/042D5D9E998807924918C70C2492E0203B21CB19/opt/the.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 14:04:03.300  7357  7357 I dex2oat : dex2oat took 24.860ms (threads: 4)
,07-05 14:04:03.610  7363  7363 I dex2oat : ----------------------------------------------------
07-05 14:04:03.610  7363  7363 I dex2oat : <SS>: S T A R T I N G . . .
07-05 14:04:03.610  7363  7363 I dex2oat : <SS>: Zip is absent. Canceled.
07-05 14:04:03.610  7363  7363 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=45 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,07-05 14:04:03.650  7363  7363 I dex2oat : dex2oat took 36.847ms (threads: 4)
,07-05 14:04:03.660  7325  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 14:04:03.660  7325  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 14:04:03.660  7325  7337 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 14:04:03.660  7325  7337 I Adreno-EGL: Local Branch: mybranch5813579
07-05 14:04:03.660  7325  7337 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 14:04:03.660  7325  7337 I Adreno-EGL: Local Patches: NONE
07-05 14:04:03.660  7325  7337 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 14:04:03.790  7325  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 14:04:03.790  7325  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 14:04:03.790  7325  7337 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 14:04:03.790  7325  7337 I Adreno-EGL: Local Branch: mybranch5813579
07-05 14:04:03.790  7325  7337 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 14:04:03.790  7325  7337 I Adreno-EGL: Local Patches: NONE
07-05 14:04:03.790  7325  7337 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 14:04:03.830  7325  7337 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-05 14:04:03.830  7325  7337 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-05 14:04:03.830  7325  7337 I Adreno-EGL: Build Date: 11/19/14 Wed
07-05 14:04:03.830  7325  7337 I Adreno-EGL: Local Branch: mybranch5813579
07-05 14:04:03.830  7325  7337 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-05 14:04:03.830  7325  7337 I Adreno-EGL: Local Patches: NONE
07-05 14:04:03.830  7325  7337 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-05 14:04:03.940  1870  7321 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:03.940  1870  7321 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-05 14:04:03.940  1870  7321 I qtaguid : Tagging socket 78 with tag 1000040100000000{268436481,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:04:03.980  1870  7321 I qtaguid : Tagging socket 81 with tag 1000040100000000{268436481,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:04:04.130  7114  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-05 14:04:04.130  7114  7214 I jxcore-log: 
,07-05 14:04:04.130  1870  2392 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-07-05 14:04:02.823+0200, stopTime=2016-07-05 14:04:04.138+0200, duration=1315ms
,07-05 14:04:04.130  7114  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-05 14:04:04.130  7114  7214 I jxcore-log: 
,07-05 14:04:04.140   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-05 14:04:04.140  7114  7214 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-05 14:04:04.140  1870  6235 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:04.140  1870  6235 I qtaguid : Tagging socket 70 with tag 1000310500000000{268448005,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:04:04.140  7114  7214 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-05 14:04:04.140  7114  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-05 14:04:04.140  7114  7214 I jxcore-log: 
,07-05 14:04:04.150  7114  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-05 14:04:04.150  7114  7214 I jxcore-log: 
,07-05 14:04:04.170   907  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.280   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.280  1870  6235 I qtaguid : Untagging socket 70
,07-05 14:04:04.310   907   922 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:04.310   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@167eb16f, r.packageName :com.google.android.gms
,07-05 14:04:04.330  1870  2392 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,07-05 14:04:04.370   907  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.380   907  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.380   907  3589 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.380   907  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.400   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@7911668, r.packageName :com.google.android.gms
,07-05 14:04:04.430   907  1359 D ActivityManager: caller:android.app.ApplicationThreadProxy@33a8d726, r.packageName :com.google.android.gms
,07-05 14:04:04.430  1870  7373 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 14:04:04.430  1870  7371 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:04:04.430   907  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@3dd55f67, r.packageName :com.google.android.gms
,07-05 14:04:04.460   907   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@7953114, r.packageName :com.google.android.gms
,07-05 14:04:04.460  1870  7373 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 14:04:04.460  1870  7371 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,07-05 14:04:04.460   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@38f22dbd, r.packageName :com.google.android.gms
,07-05 14:04:04.490   907  1429 D ActivityManager: caller:android.app.ApplicationThreadProxy@263b3fb2, r.packageName :com.google.android.gms
,07-05 14:04:04.490  1870  7373 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,07-05 14:04:04.490  1870  7371 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
07-05 14:04:04.490  1870  7371 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,07-05 14:04:04.510  1870  7371 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,07-05 14:04:04.530  7114  7214 I jxcore-log: Unit Test app is loaded
07-05 14:04:04.530  7114  7214 I jxcore-log: 
,07-05 14:04:04.540  7114  7214 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-05 14:04:04.540  7114  7214 I jxcore-log: 
,07-05 14:04:04.540  7114  7114 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-05 14:04:04.540   907   924 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:04.540  7114  7214 I jxcore-log: My device name is: samsung-SM-N9005
07-05 14:04:04.540  7114  7214 I jxcore-log: 
,07-05 14:04:04.550   907  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.570   907  1733 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.580  1870  7371 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:04.580  1870  7371 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-05 14:04:04.580  1870  7371 I qtaguid : Tagging socket 87 with tag 11065c0800000000{285629448,0} uid -1, pid: 1870, getuid(): 10015
,07-05 14:04:04.620  1870  7371 I qtaguid : Tagging socket 90 with tag 11065c0800000000{285629448,0} uid -1, pid: 1870, getuid(): 10015
,07-05 14:04:04.820   305   305 E SMD     : DCD ON
,07-05 14:04:04.840   907  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.840   907  1636 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.840   907  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.850   907  1459 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:04.850   907  1689 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.850   907  1466 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:04.850  1870  7371 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:04.850  1870  7371 I qtaguid : Tagging socket 87 with tag 1106583100000000{285628465,0} uid -1, pid: 1870, getuid(): 10015
,07-05 14:04:05.010   907  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.020   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.020   907  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.020   907  1468 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:05.040   907  1636 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.050   907  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.060   907  3589 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.060  1870  7371 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:05.060  1870  7371 I qtaguid : Tagging socket 87 with tag fffffca200000000{4294966434,0} uid -1, pid: 1870, getuid(): 10015
,07-05 14:04:05.210   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.220   907   922 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.230   907  1655 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.230   907  3589 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,07-05 14:04:05.230   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.230   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.240  1870  7371 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-05 14:04:05.240  1870  7371 I qtaguid : Tagging socket 87 with tag 11065fff00000000{285630463,0} uid -1, pid: 1870, getuid(): 10015
,07-05 14:04:05.360   907  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.370   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.380   907  1377 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:05.420   907  1093 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:06.240   907   922 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:06.270  1870  6236 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-05 14:04:06.270  1870  6236 I qtaguid : Tagging socket 70 with tag 1000310200000000{268448002,0} uid 10015, pid: 1870, getuid(): 10015
,07-05 14:04:06.470  1870  6236 I qtaguid : Untagging socket 70
,07-05 14:04:06.480  1870  2392 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,07-05 14:04:06.510   907  1359 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-05 14:04:06.530  2452  3796 V UdcCtxListenerSrv: handle intent
,07-05 14:04:07.820   305   305 E SMD     : DCD ON
,07-05 14:04:07.890   907  1064 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,07-05 14:04:07.900   907   907 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-05 14:04:07.910   907  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-05 14:04:07.920   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-05 14:04:07.930   907  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-05 14:04:07.930   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-05 14:04:07.940   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-05 14:04:07.940   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-05 14:04:07.950   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-05 14:04:07.950   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-05 14:04:07.950   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-05 14:04:07.960   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-05 14:04:07.960   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-05 14:04:07.960  1409  1409 D RegisteredServicesCache: empty dynamic service
,07-05 14:04:07.960  1431  1431 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-05 14:04:07.970  1431  1431 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:07.970  1431  1431 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-05 14:04:07.970  3954  3954 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_CHANGED, package = com.sec.enterprise.knox.cloudmdm.smdms, uid = -1
,07-05 14:04:07.970   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-05 14:04:07.970  1431  1431 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-05 14:04:07.980  1431  1431 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:07.980  1431  1431 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:07.980  1431  1431 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-05 14:04:07.980  1431  1431 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-05 14:04:07.980  1431  1431 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:04:07.980  1431  1431 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-05 14:04:07.980   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-05 14:04:07.990   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-05 14:04:08.000   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-05 14:04:08.030   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-05 14:04:08.040   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-05 14:04:08.040   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-05 14:04:08.040   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-05 14:04:08.040   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-05 14:04:08.050   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-05 14:04:08.070   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-05 14:04:08.070   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.070   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-05 14:04:08.080   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-05 14:04:08.080   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-05 14:04:08.080   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-05 14:04:08.090   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-05 14:04:08.100   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-05 14:04:08.100   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-05 14:04:08.110   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-05 14:04:08.110   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-05 14:04:08.110   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-05 14:04:08.120   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-05 14:04:08.120   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.120   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-05 14:04:08.120   907   907 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-05 14:04:08.120   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:08.130   907  1689 I art     : Explicit concurrent mark sweep GC freed 42767(2MB) AllocSpace objects, 8(128KB) LOS objects, 30% free, 37MB/53MB, paused 1.746ms total 122.425ms
,07-05 14:04:08.130   907  1689 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 14:04:08.130   907  1689 D SecContentProvider2: mCursor = null
,07-05 14:04:08.140   907   907 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.sec.enterprise.knox.cloudmdm.smdms flg=0x4000010 (has extras) }
,07-05 14:04:08.140   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-05 14:04:08.150   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.150   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-05 14:04:08.160   907  3589 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,07-05 14:04:08.160   907  3589 D ActivityManager: caller:android.app.ApplicationThreadProxy@132f8346, r.packageName :com.google.android.googlequicksearchbox
,07-05 14:04:08.170   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:08.170   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-05 14:04:08.170  1492  7395 I UpdateIcingCorporaServi: Updating corpora: APPS=com.sec.enterprise.knox.cloudmdm.smdms, CONTACTS=MAYBE
,07-05 14:04:08.170   907  1689 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
07-05 14:04:08.170   907  1689 D ActivityManager: com.samsung.android.app.FileShareServer, Starting
,07-05 14:04:08.170   907  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.170   907  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.170   907  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.170   907  1689 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:08.170   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.170   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.170   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-05 14:04:08.180   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.180   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-05 14:04:08.180   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-05 14:04:08.190   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-05 14:04:08.190   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-05 14:04:08.190   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.190   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-05 14:04:08.190   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-05 14:04:08.200   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-05 14:04:08.210  7397  7397 E Zygote  : MountEmulatedStorage()
,07-05 14:04:08.210  7397  7397 E Zygote  : v2
07-05 14:04:08.210  7397  7397 I libpersona: KNOX_SDCARD checking this for 10088
07-05 14:04:08.210  7397  7397 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:08.220   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.220   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.220   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-05 14:04:08.220   907   991 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-05 14:04:08.220   907   991 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:04:08.220   907  1689 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=7397 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 14:04:08.220   907   991 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:08.220   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.220   907   991 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
,07-05 14:04:08.230   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-05 14:04:08.230  1492  7395 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 61 ms] updated apps [took 61 ms] 
,07-05 14:04:08.230   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-05 14:04:08.240   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.240   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-05 14:04:08.240   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.240   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-05 14:04:08.240   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.240   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:04:08.240   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-05 14:04:08.250   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.250   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-05 14:04:08.250   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.250   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:04:08.250   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-05 14:04:08.250   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-05 14:04:08.250   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:04:08.250   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-05 14:04:08.260   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:04:08.260  7397  7397 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:04:08.260  7397  7397 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 14:04:08.260  7397  7397 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:08.280  7397  7397 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:08.280  7397  7397 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:08.290  7397  7397 D ResourcesManager: creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,07-05 14:04:08.310  7397  7397 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.sec.enterprise.knox.cloudmdm.smdms
,07-05 14:04:08.310   907  1093 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
07-05 14:04:08.310   907  1093 D ActivityManager: com.sec.knox.bridge, Starting
,07-05 14:04:08.310   907  1093 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.310   907  1093 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.310   907  1093 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.310   907  1093 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:08.350  7413  7413 E Zygote  : MountEmulatedStorage()
,07-05 14:04:08.350  7413  7413 E Zygote  : v2
07-05 14:04:08.350  7413  7413 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:08.350  7413  7413 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:08.360   907  1093 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7413 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-05 14:04:08.360   907  1093 I ActivityManager: Killing 5997:com.google.android.gm/u0a128 (adj 15): emptyCount ##41
,07-05 14:04:08.410  7413  7413 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:04:08.410  7413  7413 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:04:08.410  7413  7413 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:08.440   907  1733 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-05 14:04:08.440   907  1733 D ActivityManager: caller:android.app.ApplicationThreadProxy@1717a1ce, r.packageName :com.samsung.android.app.galaxyfinder
,07-05 14:04:08.440  7413  7413 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:08.440  7413  7413 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:08.450  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-05 14:04:08.450  7114  7214 I jxcore-log: 
,07-05 14:04:08.450  7413  7413 D ResourcesManager: creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,07-05 14:04:08.450  7413  7413 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:08.480   907  1240 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,07-05 14:04:08.480   907  1240 D ActivityManager: com.sec.knox.knoxsetupwizardclient, Starting
07-05 14:04:08.480   907  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:08.480   907  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.480   907  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:04:08.480   907  1240 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:04:08.520  7428  7428 E Zygote  : MountEmulatedStorage()
07-05 14:04:08.520  7428  7428 E Zygote  : v2
07-05 14:04:08.520  7428  7428 I libpersona: KNOX_SDCARD checking this for 1000
07-05 14:04:08.520  7428  7428 I libpersona: KNOX_SDCARD not a persona
,07-05 14:04:08.530   907  1240 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=7428 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
07-05 14:04:08.530   907  1240 I ActivityManager: Killing 5761:com.sec.android.app.music:service/u0a49 (adj 15): emptyCount ##41
,07-05 14:04:08.570  7428  7428 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:04:08.570  7428  7428 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 14:04:08.570  7428  7428 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-05 14:04:08.590  7428  7428 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:04:08.590  7428  7428 D ActivityThread: Added TimaKeyStore provider
,07-05 14:04:08.600  7428  7428 D ResourcesManager: creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,07-05 14:04:08.620  7428  7428 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,07-05 14:04:08.630   907   922 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,07-05 14:04:08.630   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bb0d8ef, r.packageName :com.google.android.apps.plus
,07-05 14:04:08.630   907  3589 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,07-05 14:04:08.630   907  3589 D ActivityManager: caller:android.app.ApplicationThreadProxy@1722d685, r.packageName :com.google.android.apps.plus
,07-05 14:04:08.650   907  1429 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.650   907  1429 D ActivityManager: caller:android.app.ApplicationThreadProxy@105c150b, r.packageName :com.google.android.gms
,07-05 14:04:08.660  2452  7446 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,07-05 14:04:08.660   907  1636 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.660   907  1636 D ActivityManager: caller:android.app.ApplicationThreadProxy@153f5601, r.packageName :com.google.android.gms
,07-05 14:04:08.660   907  1468 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.660   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@1334f6e7, r.packageName :com.google.android.gms
,07-05 14:04:08.670   907   924 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.670   907   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d4a513d, r.packageName :com.google.android.gms
,07-05 14:04:08.670   907  1359 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.670   907  1359 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ed01a83, r.packageName :com.google.android.gms
07-05 14:04:08.670   907  1733 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.670   907  1733 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b016400, r.packageName :com.google.android.gms
,07-05 14:04:08.670  2452  7446 D WearableController: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.sec.enterprise.knox.cloudmdm.smdms
,07-05 14:04:08.670   907  1240 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:08.670   907  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@5961a7e, r.packageName :com.google.android.gms
,07-05 14:04:08.680   907   924 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:04:08.680   907   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a18c02c, r.packageName :com.google.android.gms
,07-05 14:04:08.690   907  1472 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.690   907  1472 D ActivityManager: caller:android.app.ApplicationThreadProxy@1267b318, r.packageName :com.google.android.gms
,07-05 14:04:08.700   907   922 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.700   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@750fb56, r.packageName :com.google.android.gms
,07-05 14:04:08.710   907   924 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.710   907   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b0e8c4, r.packageName :com.google.android.gms
,07-05 14:04:08.730  2452  7451 W IcingInternalCorpora: getNumBytesRead when not calculated.
,07-05 14:04:08.790  1870  2436 I art     : Explicit concurrent mark sweep GC freed 114339(6MB) AllocSpace objects, 69(3MB) LOS objects, 39% free, 23MB/39MB, paused 718us total 48.888ms
,07-05 14:04:08.790   907  1636 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.800   907  1636 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f8d2da9, r.packageName :com.google.android.gms
,07-05 14:04:08.800   907  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:04:08.800   907  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@92d7acf, r.packageName :com.google.android.gms
,07-05 14:04:08.890  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-05 14:04:08.890  7114  7214 I jxcore-log: 
,07-05 14:04:08.910  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-05 14:04:08.910  7114  7214 I jxcore-log: 
,07-05 14:04:08.910  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-05 14:04:08.910  7114  7214 I jxcore-log: 
,07-05 14:04:08.930  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-05 14:04:08.930  7114  7214 I jxcore-log: 
,07-05 14:04:08.930   907  1636 I ActivityManager: Killing 5801:com.sec.android.app.myfiles/u0a56 (adj 15): emptyCount ##41
,07-05 14:04:08.940  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-05 14:04:08.940  7114  7214 I jxcore-log: 
,07-05 14:04:09.120   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:09.560   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:09.810  2452  2725 I Icing   : Indexing F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9 from com.google.android.gms
,07-05 14:04:09.830  2452  2725 I Icing   : Indexing done F944DC6DBF38E5B5A54FB3560A7505412CF0FFB9
,07-05 14:04:10.120   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:10.820   305   305 E SMD     : DCD ON
,07-05 14:04:10.850  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-05 14:04:10.850  7114  7214 I jxcore-log: 
,07-05 14:04:10.860  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-05 14:04:10.860  7114  7214 I jxcore-log: 
,07-05 14:04:10.870  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-05 14:04:10.870  7114  7214 I jxcore-log: 
,07-05 14:04:11.020  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-05 14:04:11.020  7114  7214 I jxcore-log: 
,07-05 14:04:11.100  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-05 14:04:11.100  7114  7214 I jxcore-log: 
,07-05 14:04:11.120   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:11.160  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-05 14:04:11.160  7114  7214 I jxcore-log: 
,07-05 14:04:11.160  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-05 14:04:11.160  7114  7214 I jxcore-log: 
,07-05 14:04:11.350  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-05 14:04:11.350  7114  7214 I jxcore-log: 
,07-05 14:04:11.370  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-05 14:04:11.370  7114  7214 I jxcore-log: 
,07-05 14:04:11.370  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-05 14:04:11.370  7114  7214 I jxcore-log: 
,07-05 14:04:11.380  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-05 14:04:11.380  7114  7214 I jxcore-log: 
,07-05 14:04:11.390  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-05 14:04:11.390  7114  7214 I jxcore-log: 
,07-05 14:04:11.410  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-05 14:04:11.410  7114  7214 I jxcore-log: 
,07-05 14:04:11.500  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-05 14:04:11.500  7114  7214 I jxcore-log: 
,07-05 14:04:11.500  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-05 14:04:11.500  7114  7214 I jxcore-log: 
,07-05 14:04:11.530  7114  7214 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-05 14:04:11.530  7114  7214 I jxcore-log: 
,07-05 14:04:11.540  7114  7214 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,07-05 14:04:11.540  7114  7214 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
07-05 14:04:11.540  7114  7214 I jxcore-log: 
,07-05 14:04:11.990   907  3328 D SSRM:n  : SIOP:: AP = 410, PST = 411, CUR = 300
,07-05 14:04:12.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:12.570   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:04:12.570   907  1113 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,07-05 14:04:12.630   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:12.630   907  1240 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4322, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:04:12.630   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:04:12.640   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:12.640   907   907 I MotionRecognitionService: Plugged
,07-05 14:04:12.640   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:04:12.640   907  1240 D BatteryService: stay LED for charging
,07-05 14:04:12.650  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:12.650  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:12.650  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:12.650  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:12.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:12.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:12.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:12.660  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:13.020  6516  6516 D FactoryTest: Not factory mode
,07-05 14:04:13.020  6516  6516 D FactoryTest: Not factory mode. isFactoryMode() returend false
,07-05 14:04:13.030  6516  6516 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
,07-05 14:04:13.040  6516  6516 D MTPRx   : still no open session command from host, so toast
,07-05 14:04:13.040  6516  6516 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1583 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,07-05 14:04:13.050  6516  6516 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.app.ContextImpl.startActivity:1584 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
,07-05 14:04:13.050  6516  6516 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:120505
,07-05 14:04:13.050   907  1468 E PersonaManagerService: inState():  stateMachine is null !!
,07-05 14:04:13.060   907  1468 I PersonaManagerService: PersonaId don't exist
,07-05 14:04:13.060   907  1468 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,07-05 14:04:13.070   907  1468 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,07-05 14:04:13.080   907  1468 I ActivityManager: START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,07-05 14:04:13.080   907  1468 W ActivityManager: mDVFSHelper.acquire()
,07-05 14:04:13.110   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-05 14:04:13.110   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
,07-05 14:04:13.110   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:04:13.110   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 14:04:13.120   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:13.130  6516  6516 E MTPRx   : started activity for popup
,07-05 14:04:13.130   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:04:13.150  6516  6516 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-05 14:04:13.160  6516  6516 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-05 14:04:13.180  6516  6516 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,07-05 14:04:13.200   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-05 14:04:13.200   907  1240 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:04:13.200   907  1240 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@2d3ce606 attribute=null, token = android.os.BinderProxy@35b71465
,07-05 14:04:13.200   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:04:13.200   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:04:13.200   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-05 14:04:13.220  6516  6516 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,07-05 14:04:13.230  6516  6516 D Activity: performCreate Call secproduct feature valuefalse
07-05 14:04:13.230  6516  6516 D Activity: performCreate Call debug elastic valuetrue
,07-05 14:04:13.240  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:04:13.240  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:04:13.240  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-05 14:04:13.240  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 14:04:13.240   907  1472 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:04:13.240   907  1472 D KnoxTimeoutHandler: postActiveUserChange for user 0
,07-05 14:04:13.240   907  1472 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:04:13.240   907   907 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:04:13.240   907   907 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 14:04:13.260  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:04:13.260  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:04:13.260  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f1b4069 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2cb03ed3, 16908290=android.view.AbsSavedState$1@2cb03ed3}, android:focusedViewId=100}]}]
,07-05 14:04:13.260  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:04:13.260  7114  7114 V ActivityThread: updateVisibility : ActivityRecord{8d4b008 token=android.os.BinderProxy@364f77fa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:04:13.260  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:04:13.260  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:04:13.260  7114  7114 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364f77fa time:120719
,07-05 14:04:13.590   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:13.680   907   994 W ProcessCpuTracker: Skipping unknown process pid 7463
,07-05 14:04:13.680   907   994 W ProcessCpuTracker: Skipping unknown process pid 7464
,07-05 14:04:13.680   907   994 W ProcessCpuTracker: Skipping unknown process pid 7467
07-05 14:04:13.680   907   994 W ProcessCpuTracker: Skipping unknown process pid 7477
,07-05 14:04:13.690   907   994 W ProcessCpuTracker: Skipping unknown process pid 7485
,07-05 14:04:13.820   305   305 E SMD     : DCD ON
,07-05 14:04:15.050   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:04:15.060   907   991 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:04:15.710   907  1093 I ActivityManager: Killing 5265:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,07-05 14:04:16.080   907   994 W ActivityManager: mDVFSHelper.release()
,07-05 14:04:16.820   305   305 E SMD     : DCD ON
,07-05 14:04:18.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:19.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:19.830   305   305 E SMD     : DCD ON
,07-05 14:04:20.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:21.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:21.810   907  1060 I PowerManagerService: [PWL] Off : 50s ago
,07-05 14:04:22.030   907  3328 D SSRM:n  : SIOP:: AP = 360, PST = 402, CUR = 300
,07-05 14:04:22.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:22.690   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:22.700   907  1377 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4325, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:04:22.700   907  1377 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:04:22.700   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:22.710  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:22.720  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:22.720  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:22.710  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:22.720   907   907 I MotionRecognitionService: Plugged
,07-05 14:04:22.720   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:04:22.720  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:22.720  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:22.720  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:22.720  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:22.730   907  1377 D BatteryService: stay LED for charging
,07-05 14:04:22.830   305   305 E SMD     : DCD ON
,07-05 14:04:23.130   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:04:25.830   305   305 E SMD     : DCD ON
,07-05 14:04:28.830   305   305 E SMD     : DCD ON
,07-05 14:04:29.570   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:31.240   907  1333 E Watchdog: !@Sync 4
,07-05 14:04:31.830   305   305 E SMD     : DCD ON
,07-05 14:04:32.080   907  3328 D SSRM:n  : SIOP:: AP = 350, PST = 393, CUR = 300
,07-05 14:04:32.750   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:32.750   907  1468 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:04:32.760   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:04:32.760   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:32.770  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:32.770  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:32.770   907   907 I MotionRecognitionService: Plugged
,07-05 14:04:32.770   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:04:32.770   907  1468 D BatteryService: stay LED for charging
,07-05 14:04:32.780  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:32.780  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:32.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:32.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:32.800  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:32.800  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:33.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:34.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:34.280   907  1905 V SAMP_SPCM_test: CSC File load.. 
,07-05 14:04:34.310   907  1905 D ResourcesManager: creating new AssetManager and set to /system/app/UniversalMDMClient/UniversalMDMClient.apk
,07-05 14:04:34.330   907  1905 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-05 14:04:34.360   907  1905 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-05 14:04:34.390   907  1905 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,07-05 14:04:34.830   305   305 E SMD     : DCD ON
,07-05 14:04:35.130   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:36.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:37.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:37.830   305   305 E SMD     : DCD ON
,07-05 14:04:38.140   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:04:40.830   305   305 E SMD     : DCD ON
,07-05 14:04:42.130   907  3328 D SSRM:n  : SIOP:: AP = 340, PST = 382, CUR = 300
,07-05 14:04:42.810   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:42.820   907  3589 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4328, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:04:42.820   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:04:42.820   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:04:42.830  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:04:42.830  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:04:42.830   907   907 I MotionRecognitionService: Plugged
,07-05 14:04:42.830   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:04:42.840  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:04:42.840  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:04:42.840  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:04:42.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:42.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:42.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:04:42.840   907  3589 D BatteryService: stay LED for charging
,07-05 14:04:43.830   305   305 E SMD     : DCD ON
,07-05 14:04:46.810   907  1060 I PowerManagerService: [PWL] Off : 75s ago
,07-05 14:04:46.830   305   305 E SMD     : DCD ON
,07-05 14:04:49.570   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:04:49.830   305   305 E SMD     : DCD ON
,07-05 14:04:52.180   907  3328 D SSRM:n  : SIOP:: AP = 340, PST = 373, CUR = 300
,07-05 14:04:52.840   305   305 E SMD     : DCD ON
,07-05 14:04:52.870   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:04:53.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:54.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:55.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:55.840   305   305 E SMD     : DCD ON
,07-05 14:04:56.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:57.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:04:58.140   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:04:58.840   305   305 E SMD     : DCD ON
,07-05 14:04:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:05:01.240   907  1333 E Watchdog: !@Sync 5
,07-05 14:05:01.840   305   305 E SMD     : DCD ON
,07-05 14:05:02.220   907  3328 D SSRM:n  : SIOP:: AP = 340, PST = 367, CUR = 300
,07-05 14:05:02.730  1870  3200 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:05:02.930   907  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:02.930   907  1472 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4330, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:05:02.930   907  1472 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:05:02.940   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:02.940  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:02.940  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:02.950   907   907 I MotionRecognitionService: Plugged
,07-05 14:05:02.950   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:02.950  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:02.950   907  1472 D BatteryService: stay LED for charging
,07-05 14:05:02.950  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:02.960  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:02.960  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:02.960  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:02.960  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:04.840   305   305 E SMD     : DCD ON
,07-05 14:05:07.840   305   305 E SMD     : DCD ON
,07-05 14:05:09.570   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:10.840   305   305 E SMD     : DCD ON
,07-05 14:05:12.270   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 360, CUR = 300
,07-05 14:05:12.990   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:12.990   907  1359 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4332, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:05:13.000   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:05:13.000   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:13.010  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:13.010  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:13.010   907   907 I MotionRecognitionService: Plugged
,07-05 14:05:13.010   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:13.010  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:13.020  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:13.020   907  1359 D BatteryService: stay LED for charging
,07-05 14:05:13.020  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:13.020  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:13.020  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:13.020  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:13.840   305   305 E SMD     : DCD ON
,07-05 14:05:16.810   907  1060 I PowerManagerService: [PWL] Off : 105s ago
,07-05 14:05:16.840   305   305 E SMD     : DCD ON
,07-05 14:05:18.140   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:19.150   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:19.840   305   305 E SMD     : DCD ON
,07-05 14:05:20.150   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:21.150   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:22.150   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:22.320   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 356, CUR = 300
,07-05 14:05:22.840   305   305 E SMD     : DCD ON
,07-05 14:05:23.150   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:05:25.840   305   305 E SMD     : DCD ON
,07-05 14:05:28.850   305   305 E SMD     : DCD ON
,07-05 14:05:29.580   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:31.250   907  1333 E Watchdog: !@Sync 6
,07-05 14:05:31.620   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:05:31.650  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:05:31.650  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:05:31.650  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:05:31.650  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:05:31.670   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:31.670   907  1459 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4327, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:05:31.670   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:05:31.670   907  1459 D BatteryService: stay LED for charging
,07-05 14:05:31.680   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:31.690   907   907 I MotionRecognitionService: Plugged
,07-05 14:05:31.690   907   907 I MotionRecognitionService: setPowerConnected  = true
07-05 14:05:31.690  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:31.690  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:31.690  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:31.700  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:31.700  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:31.700  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:31.700  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,07-05 14:05:31.700  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:31.710  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:05:31.720  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:05:31.850   305   305 E SMD     : DCD ON
,07-05 14:05:32.360   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 353, CUR = 300
,07-05 14:05:34.850   305   305 E SMD     : DCD ON
,07-05 14:05:37.850   305   305 E SMD     : DCD ON
,07-05 14:05:40.850   305   305 E SMD     : DCD ON
,07-05 14:05:41.750   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:41.750   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:05:41.750   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:05:41.750   907  1240 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 907) 
,07-05 14:05:41.750   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:41.750  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:41.750   907   907 I MotionRecognitionService: Plugged
,07-05 14:05:41.760   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:41.760   907  1240 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x12 -> 0x42 | SvcLED(id=3) set On
,07-05 14:05:41.760   907  1472 D SecContentProvider2: uri = 14 selection = getSealedState
07-05 14:05:41.760   907  1472 D SecContentProvider2: mCursor = null
,07-05 14:05:41.770   907  1240 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:05:41.780  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:41.780  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:41.790   907  1636 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
,07-05 14:05:41.790   907  1636 V ApplicationPolicy: isApplicationStateBlocked userId -2 pkgname com.android.systemui
,07-05 14:05:41.790   907   907 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
,07-05 14:05:41.790   907  1240 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-05 14:05:41.800   907  1240 D BatteryService: turn on LED for fully charged
,07-05 14:05:41.800   907  1093 D PowerManagerService: [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1189
,07-05 14:05:41.800   907  1093 I PowerManagerService: !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
,07-05 14:05:41.800   907  1093 I PowerManagerService: Waking up from sleep (uid 10067)...
,07-05 14:05:41.800   907  1170 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1495b8f0)
,07-05 14:05:41.800   907  1093 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 14:05:41.800  1189  1207 D KeyguardViewMediator: onScreenTurnedOn, seq = 2
,07-05 14:05:41.800  1189  1207 D KeyguardViewMediator: notifyScreenOnLocked
,07-05 14:05:41.810   907  1093 D PowerManagerService: [s] UserActivityState : 0 -> 1
,07-05 14:05:41.810   907  1060 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-05 14:05:41.810   907  1093 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
,07-05 14:05:41.810  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:05:41.820   907  1056 D SContextService: 	.registerCallback : 1, client=
,07-05 14:05:41.820   907  1056 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,07-05 14:05:41.820  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:41.820   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
,07-05 14:05:41.820   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:05:41.820   907  1175 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
,07-05 14:05:41.830   907  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
,07-05 14:05:41.830   907  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 14:05:41.830   907  1175 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:05:41.830   907  1056 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,07-05 14:05:41.830  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:41.830   907  1056 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
,07-05 14:05:41.830   907  1056 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
,07-05 14:05:41.830   267   267 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a62000
,07-05 14:05:41.830   267   267 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:05:41.840   907  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 14:05:41.840   907   907 V ActivityManager: Display changed displayId=0
,07-05 14:05:41.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:41.840   907  1056 D SContextService: sendAttribute() : service = Auto Rotation
,07-05 14:05:41.840   907  1056 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:05:41.850  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:41.850   907  1056 V CAE     : start(ContextProvider.java:126)
,07-05 14:05:41.850   907  1056 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:05:41.850   907  1056 V CAE     : enable(AutoRotationRunner.java:158)
,07-05 14:05:41.850   907  1056 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
,07-05 14:05:41.850   907  1056 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
,07-05 14:05:41.860   322   322 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-05 14:05:41.890   907  1056 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:05:41.890   907  1056 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:05:41.890  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:05:41.890  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
07-05 14:05:41.890  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-05 14:05:41.890  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,07-05 14:05:41.900   907  1170 D InputManager-JNI: setDeviceInteractive: 1
,07-05 14:05:41.900   907  1689 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:05:41.900   907  1689 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:05:41.900   907  1689 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-05 14:05:41.900   907   907 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:05:41.900   907   907 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 14:05:41.900   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-05 14:05:41.900  1409  1409 D NativeNfcManager: power state=4
07-05 14:05:41.900  1409  1409 D BrcmNfcJni: PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x4; screen on unlocked
,07-05 14:05:41.910   907  7521 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-05 14:05:41.910   907  7519 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-05 14:05:41.910   907  7520 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-05 14:05:41.910   907  7520 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
,07-05 14:05:41.910   907  1472 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:05:41.910  1409  1605 D NfcService: call the applyRouting
,07-05 14:05:41.910   907   907 D PalmMotion: 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
07-05 14:05:41.910   907   907 D PalmMotion: SURFACE_PALM_SWIPE: 1
07-05 14:05:41.910   907   907 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
07-05 14:05:41.910   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 907) 
07-05 14:05:41.910   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,07-05 14:05:41.910   907  3328 D SSRM:a  : DeviceInfo:: 000000100000
07-05 14:05:41.910   907  3328 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 14:05:41.910  1725  1725 D SamsungIME: showDlgMsgBox : false true true
,07-05 14:05:41.920   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 907) 
07-05 14:05:41.920   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
,07-05 14:05:41.920   907  1092 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 14:05:41.920   907   907 D BatteryService: turn off LED
07-05 14:05:41.920   907  1092 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:05:41.920   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:05:41.920   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:05:41.920   907   907 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 14:05:41.920   907   907 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,07-05 14:05:41.920   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-05 14:05:41.920   907   907 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
,07-05 14:05:41.930   322   578 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-05 14:05:41.930   907  1092 D SensorManager: unregisterListener ::   
07-05 14:05:41.930   907  1092 D lights  : led_pattern : 0 +
,07-05 14:05:41.930   907  1092 D lights  : led_pattern : 0 -
07-05 14:05:41.930   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,07-05 14:05:41.940   907   907 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-05 14:05:41.940   907  1056 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 14:05:41.940   907  1056 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-05 14:05:41.940   907  1056 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-05 14:05:41.940   907  1056 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@3aba9d78, Service : AUTO_ROTATION(1)
07-05 14:05:41.940   907   907 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
07-05 14:05:41.940   907  1056 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:05:41.940   907  1056 D SContextService: addSContextService() : service = Auto Rotation
07-05 14:05:41.940   907  1056 D SContextService: ===== SContext Service List =====
07-05 14:05:41.940   907  1056 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@203fcc51, Service : Auto Rotation
07-05 14:05:41.940   907  1056 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1bb90e69, service=Auto Rotation
,07-05 14:05:41.940  1189  1189 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
07-05 14:05:41.940   907  1126 E MotionRecognitionService:  handler : SCREEN_ON end
07-05 14:05:41.940   907   907 D NotificationService: ACTION_SCREEN_ON
07-05 14:05:41.940   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 907) 
07-05 14:05:41.940   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
07-05 14:05:41.940   907  1092 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 14:05:41.940   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
07-05 14:05:41.950   907  1148 E native  : do suspend false
07-05 14:05:41.950   310   687 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:05:41.950   310   687 V voice   : voice_set_parameters: enter: screen_state=on
07-05 14:05:41.950   310   687 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:05:41.950   310   687 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 14:05:41.950   310   687 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:05:41.950   310   687 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:05:41.950   310   687 V audio_hw_primary: adev_set_parameters: exit
07-05 14:05:41.950  1299  1299 I wpa_supplicant: reset timer : RESET_TIMER 1
07-05 14:05:41.950  1299  1299 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 14:05:41.950  1299  1299 I wpa_supplicant: P2P: Current p2p state = IDLE
07-05 14:05:41.960  1299  1299 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-05 14:05:41.960   907  1377 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:05:41.960   907  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@310dcb6, r.packageName :com.google.android.gms
07-05 14:05:41.960  1189  1189 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
07-05 14:05:41.970   907   907 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
07-05 14:05:41.970  1189  1189 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
07-05 14:05:41.970  1189  1189 D PhoneStatusBar: tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@20e45e5f
,07-05 14:05:41.980  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:05:41.980  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:05:41.980  1189  1189 I PhoneStatusBar: Icon Only
07-05 14:05:41.980  1189  1189 I StatusBar: Icon Only
07-05 14:05:41.980  1189  1189 D PanelView: There is/are notification(s) 
07-05 14:05:41.980  1189  1189 D PanelView: There is/are notification(s) 
07-05 14:05:41.980  1189  1189 D KeyguardViewMediator: handleNotifyScreenOn
07-05 14:05:41.980  1189  1189 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-05 14:05:41.980  1870  1870 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
07-05 14:05:41.980  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:05:41.980  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 14:05:41.980  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-05 14:05:41.980  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:05:41.980  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:05:41.990  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:05:41.990  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 14:05:41.990  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-05 14:05:41.990  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:05:41.990  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:05:41.990   295   295 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
07-05 14:05:41.990   295   295 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
07-05 14:05:41.990   295   295 I rmt_storage: wakelock acquired: 1, error no: 42
07-05 14:05:41.990   295   668 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1229454592)
07-05 14:05:42.000  1189  1189 D StatusBarKeyguardViewManager: callback.onShown()
07-05 14:05:42.000   907  3589 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:05:42.010   907  1056 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 14:05:42.010   907  1060 I DisplayPowerController: Unblocked screen on after 193 ms
07-05 14:05:42.010   907  1060 D DisplayPowerState: !@ ColorFade exit
,07-05 14:05:42.020   907  7519 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
07-05 14:05:42.020   907  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-05 14:05:42.020   907  1058 D IpRemoteDisplayController: Bridge Server is not available
07-05 14:05:42.030  1189  1189 D BatteryMeterView: onDraw batteryColor : -1
07-05 14:05:42.040   267   318 I SurfaceFlinger: id=11 Removed DolorFade (8/8)
07-05 14:05:42.040   267   971 I SurfaceFlinger: id=11 Removed DolorFade (-2/8)
07-05 14:05:42.040   907  1060 E libEGL  : call to OpenGL ES API with no current context (logged once per thread)
07-05 14:05:42.040   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:05:42.040   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:05:42.040   907  1174 D lights  : lcd : 162 +
07-05 14:05:42.040   907  1174 D lights  : lcd : 162 -
07-05 14:05:42.040   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:05:42.040   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:05:42.040   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:05:42.040   907  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
07-05 14:05:42.040   907  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-05 14:05:42.040   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOn
07-05 14:05:42.040   907  1171 D lights  : button : 1 +
07-05 14:05:42.040   907  1171 D lights  : button : 1 -
07-05 14:05:42.050   907   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 14:05:42.050   907   907 D PersonaManagerService: ACTION_SCREEN_ON onReceive
07-05 14:05:42.050   907  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
07-05 14:05:42.050   907  1093 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:05:42.060   295   668 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 1572864
07-05 14:05:42.060   295   668 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
07-05 14:05:42.060   295   668 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1229454592) wakelock released: 1, error no: 0
07-05 14:05:42.060   295   668 I rmt_storage: 
,07-05 14:05:42.060  1409  1409 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-05 14:05:42.060   295   295 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,07-05 14:05:42.070  7114  7114 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364f77fa time:209524
,07-05 14:05:42.070  1409  1783 D NfcService: call the applyRouting
,07-05 14:05:42.070   267   525 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 14:05:42.070   267   267 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-05 14:05:42.070   267   267 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-05 14:05:42.070   907  1175 D SurfaceControl: Excessive delay in setPowerMode(): 242ms
,07-05 14:05:42.080   907  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 251ms
,07-05 14:05:42.100  1755  1755 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,07-05 14:05:42.100  1755  1755 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,07-05 14:05:42.130  1725  1725 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-05 14:05:42.150  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,07-05 14:05:42.150  2915  2915 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-05 14:05:42.150  2915  2915 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25140236k
,07-05 14:05:42.160  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
,07-05 14:05:42.160  2915  2915 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
07-05 14:05:42.160  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
,07-05 14:05:42.160  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
07-05 14:05:42.160   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:05:42.160  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1467720342163
,07-05 14:05:42.160   907  1733 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:05:42.200   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 346, CUR = 300
,07-05 14:05:42.200  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-05 14:05:42.210  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,07-05 14:05:42.210  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
07-05 14:05:42.210  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 14:05:42.210  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,07-05 14:05:42.210  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:05:42.210  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:05:42.210  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:05:42.220  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:05:42.220  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:05:42.220  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:05:42.230  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-05 14:05:42.230  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,07-05 14:05:42.230  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:05:42.240  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 14:05:42.240  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/05/2016 04:42 PM
,07-05 14:05:42.240  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/05/2016 02:05 PM
,07-05 14:05:42.240  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:05:42.240  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:05:42.260   907  7536 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:05:42.260   907  7536 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:05:42.290   907  7521 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 14:05:42.290   907  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:05:42.310   907  7536 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:05:42.360   907  7536 I BatteryStatsDumper: Screen bin #0: time=5 power=3.1666666666666666E-5
07-05 14:05:42.360   907  7536 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 14:05:42.370   907  7536 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 14:05:42.370   907  7536 I BatteryStatsDumper: Screen bin #3: time=9018 power=0.399798
07-05 14:05:42.370   907  7536 I BatteryStatsDumper: Screen bin #4: time=0 power=0.0
07-05 14:05:42.370   907  7536 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:05:42.550   907  7536 I BatteryStatsDumper: Writing to database completed
,07-05 14:05:42.700  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:05:42.700  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:05:42.700  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:42.700  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:42.720  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:42.720  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:42.720  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:42.730  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:42.730  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:42.730  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:42.960   907  3328 D SSRM:a  : DeviceInfo:: 000000100000
,07-05 14:05:42.960   907  3328 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 14:05:43.540   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 14:05:43.540   907  1171 D lights  : button : 0 +
,07-05 14:05:43.590   907  1171 D lights  : button : 0 -
,07-05 14:05:43.730  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:43.740  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:43.740  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:43.740  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:43.750  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:43.850   305   305 E SMD     : DCD ON
,07-05 14:05:45.960  1299  1299 I wpa_supplicant: nl80211: Received scan results (10 BSSes)
,07-05 14:05:45.980   907  1147 D WifiP2pService: InactiveState{ what=147461 }
,07-05 14:05:45.980   907  1147 D WifiP2pService: P2pEnabledState{ what=147461 }
,07-05 14:05:45.990   907  1147 D WifiP2pService: DefaultState{ what=147461 }
,07-05 14:05:46.770  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:46.770  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:46.780  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:46.780  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:46.780  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:46.790  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:46.790  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:46.790  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:46.790  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:46.790  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:46.850   305   305 E SMD     : DCD ON
,07-05 14:05:48.150   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:05:48.150   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:05:48.800  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:48.800  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:48.810  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:48.810  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:48.820  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:49.580   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:05:49.850   305   305 E SMD     : DCD ON
,07-05 14:05:50.850  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:50.850  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:50.860  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:50.860  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:50.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:51.810   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:05:51.820   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4317, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:05:51.820   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:05:51.820   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:05:51.820  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:05:51.820  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:05:51.820   907   907 I MotionRecognitionService: Plugged
,07-05 14:05:51.820   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:05:51.830  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:05:51.830  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:51.830  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:51.830  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:05:51.840  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:05:51.840  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:05:51.840  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:05:51.840  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
07-05 14:05:51.840  1189  1189 I PhoneStatusBar: Icon Only
07-05 14:05:51.840  1189  1189 I StatusBar: Icon Only
,07-05 14:05:51.850  1189  1189 D PanelView: There is/are notification(s) 
07-05 14:05:51.850  1189  1189 D PanelView: There is/are notification(s) 
,07-05 14:05:51.870  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:51.880  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:51.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:52.240   907  3328 D SSRM:n  : SIOP:: AP = 340, PST = 339, CUR = 300
,07-05 14:05:52.850   305   305 E SMD     : DCD ON
,07-05 14:05:53.890  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:53.890  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:53.890  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:53.890  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:53.900  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:53.910  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:53.930  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:53.930  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:53.930  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:53.930  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:54.940  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:54.940  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:54.940  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:54.940  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:54.960  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:55.850   305   305 E SMD     : DCD ON
,07-05 14:05:56.970  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:56.970  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:56.980  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:57.990  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:58.000  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:58.000  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:58.000  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:58.020  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:58.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:58.850   305   305 E SMD     : DCD ON
,07-05 14:05:59.030  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:05:59.030  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:05:59.040  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:59.040  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:59.050  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:59.060  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:59.060  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:05:59.060  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:05:59.060  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:05:59.060  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:05:59.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:05:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:06:00.010  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:06:00.010  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:06:00.020  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:06:00.020  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:00.070  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:00.070  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:00.100  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:06:00.100  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:06:00.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:01.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:01.250   907  1333 E Watchdog: !@Sync 7
,07-05 14:06:01.830   907  3589 D PowerManagerService: [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10067 pid=1189 (0x0)
,07-05 14:06:01.850   305   305 E SMD     : DCD ON
,07-05 14:06:01.870   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:01.870   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:06:01.870   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:06:01.870   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:01.880  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:01.880  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:06:01.880   907   907 I MotionRecognitionService: Plugged
07-05 14:06:01.880   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:01.880  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:01.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:01.890  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:01.890  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:06:01.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:01.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:02.080  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:02.080  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:06:02.080  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:02.090  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:02.100  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:02.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:02.300   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 336, CUR = 300
,07-05 14:06:03.160   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:06:04.860   305   305 E SMD     : DCD ON
,07-05 14:06:05.800   907  1060 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-05 14:06:05.800   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:06:05.800   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:05.810   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-05 14:06:05.820   907  1174 D lights  : lcd : 153 +
,07-05 14:06:05.850   907  1174 D lights  : lcd : 153 -
,07-05 14:06:05.850   907  1174 D lights  : lcd : 86 +
,07-05 14:06:05.880   907  1174 D lights  : lcd : 86 -
,07-05 14:06:05.880   907  1174 D lights  : lcd : 53 +
,07-05 14:06:05.880   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:06:05.880   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:05.900   907  1174 D lights  : lcd : 53 -
,07-05 14:06:05.900   907  1174 D lights  : lcd : 20 +
,07-05 14:06:05.920   907  1174 D lights  : lcd : 20 -
,07-05 14:06:05.930   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:06:05.930   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:06.140  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:06.140  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:07.860   305   305 E SMD     : DCD ON
,07-05 14:06:08.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:08.170  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:08.180  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:06:08.180  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:08.180  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:08.190  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:08.200  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:08.200  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:08.200  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:06:08.200  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:08.200  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:09.160   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:09.210  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:09.210  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:06:09.210  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:09.210  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:09.220  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:09.220  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:09.230  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:09.230  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:09.230  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:09.230  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:09.590   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:10.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:10.860   305   305 E SMD     : DCD ON
,07-05 14:06:11.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:11.230  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:06:11.230  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:06:11.240  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:11.240  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:11.250  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:06:11.260  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:11.260  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:11.260  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:11.260  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:06:11.260  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:06:11.800   907  1060 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-05 14:06:11.800   907  1060 I PowerManagerService: !@[ps] Screen__Off - 1 : timeout (0x4) (2)
,07-05 14:06:11.800   907  1060 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:06:11.810   907  1170 D InputManager-JNI: setDeviceInteractive: 0
,07-05 14:06:11.810   907  1060 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 14:06:11.810   907  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-05 14:06:11.820   907  1060 D PowerManagerService: handleSandman : startDream()
,07-05 14:06:11.820   907  1060 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
,07-05 14:06:11.820   907  1060 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:06:11.820   907  1060 D PowerManagerService: [s] UserActivityState : 4 -> 0
,07-05 14:06:11.820   907  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0,
,07-05 14:06:11.830   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 14:06:11.830   267   267 I SurfaceFlinger: id=13 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 14:06:11.840   907  7572 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,07-05 14:06:11.840   907  7573 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
07-05 14:06:11.840   907  7571 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
,07-05 14:06:11.840   907  7572 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,07-05 14:06:11.840   907  7571 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0
,07-05 14:06:11.840   907  7573 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
07-05 14:06:11.840   907  1170 D SContextService: 	.unregisterCallback : 1, client=
,07-05 14:06:11.840   907  1170 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@203fcc51, Service = Auto Rotation, used = 1
07-05 14:06:11.840   907  1170 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:06:11.850   907  1170 V CAE     : stop(ContextProvider.java:149)
,07-05 14:06:11.850   907  1170 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:06:11.850   907  1170 V CAE     : disable(AutoRotationRunner.java:171)
07-05 14:06:11.850   907  1170 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,07-05 14:06:11.850   907  1170 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
07-05 14:06:11.850   322   322 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 14:06:11.900   907  1170 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:06:11.900   907  1170 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:06:11.930   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:11.930   907  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4330, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:06:11.930   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:06:11.930   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:11.930   907   907 I MotionRecognitionService: Plugged
,07-05 14:06:11.930   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:11.940  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:11.940  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:11.940  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:11.940  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:11.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:11.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:11.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:11.940  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:11.950   907  1060 D DisplayPowerController: ColorFade: onAnimationStart
,07-05 14:06:11.950   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 0
07-05 14:06:11.950   907  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:11.950   907  1170 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 14:06:11.950   907  1170 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,07-05 14:06:11.950   907  1170 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
07-05 14:06:11.950   907  1170 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
,07-05 14:06:11.950   907  1170 D SContextService: removeSContextService() : service = Auto Rotation
07-05 14:06:11.950   907  1170 D SContextService: ===== SContext Service List =====
07-05 14:06:11.950   907  1170 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1bb90e69, service=Auto Rotation
,07-05 14:06:11.950  1189  4042 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 14:06:11.950  1189  4042 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
07-05 14:06:11.950  1189  4042 D KeyguardEffectViewController: changeWallpaperByScreenOff()
,07-05 14:06:11.950  1189  4042 D KeyguardViewMediator: notifyScreenOffLocked
,07-05 14:06:11.960  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
07-05 14:06:11.960  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:06:11.970   907  1174 D lights  : lcd : 17 +
,07-05 14:06:11.970  1189  4042 D KeyguardViewMediator: timeout : 5000
,07-05 14:06:11.970   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 0
,07-05 14:06:11.970   907  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:12.000   907  1174 D lights  : lcd : 17 -
07-05 14:06:12.000   907  1174 D lights  : lcd : 0 +
,07-05 14:06:12.020  1189  4042 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 2
07-05 14:06:12.020  1189  1189 D KeyguardViewMediator: handleNotifyScreenOff
,07-05 14:06:12.020   907  1174 D lights  : lcd : 0 -
07-05 14:06:12.020  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f1b4069 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2cb03ed3, 16908290=android.view.AbsSavedState$1@2cb03ed3}, android:focusedViewId=100}]}]
07-05 14:06:12.020  7114  7114 V ActivityThread: updateVisibility : ActivityRecord{8d4b008 token=android.os.BinderProxy@364f77fa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:06:12.020  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:06:12.020  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:06:12.020  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:06:12.030   907   907 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 907) 
07-05 14:06:12.030   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,07-05 14:06:12.030   907   907 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:06:12.040   907   907 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
07-05 14:06:12.040   907   907 D BatteryService: turn on LED for fully charged
,07-05 14:06:12.040   907   907 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-05 14:06:12.040   907   907 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
07-05 14:06:12.040   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
07-05 14:06:12.040   907   907 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
,07-05 14:06:12.040   322   578 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-05 14:06:12.050   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 6, 12,
,07-05 14:06:12.050   907   907 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 6, 12
07-05 14:06:12.050   322   322 D Sensorhubs: sendContextData: -63, 14, 12, 6, 12
,07-05 14:06:12.060   907   907 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 14:06:12.060   907  1126 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 14:06:12.070   907   907 D NotificationService: ACTION_SCREEN_OFF
07-05 14:06:12.070   907   907 D LightsService: [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 907) 
07-05 14:06:12.070   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,07-05 14:06:12.070   310   310 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 14:06:12.070   310   310 V voice   : voice_set_parameters: enter: screen_state=off
07-05 14:06:12.070   310   310 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:06:12.070   310   310 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 14:06:12.070   310   310 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:06:12.070   310   310 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:06:12.070   310   310 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:06:12.070   907  1148 E native  : do suspend true
,07-05 14:06:12.090   907   907 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-05 14:06:12.090   907   907 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 14:06:12.100   907  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
07-05 14:06:12.100   907  1058 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:06:12.110  1189  1189 D VolumePanel.2cc5a711: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-05 14:06:12.110  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
07-05 14:06:12.110  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-05 14:06:12.110  1189  1189 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
07-05 14:06:12.110  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
07-05 14:06:12.110  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 14:06:12.120   907   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 14:06:12.120   907   907 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
07-05 14:06:12.120   907  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-05 14:06:12.130  1409  1409 D NativeNfcManager: power state=2
07-05 14:06:12.130  1409  1409 D BrcmNfcJni: PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x2; screen off
,07-05 14:06:12.130  1409  3264 D NfcService: call the applyRouting
,07-05 14:06:12.140  1189  1189 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-05 14:06:12.160  1755  1755 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-05 14:06:12.170   907  1060 D DisplayPowerState: !@ ColorFade entry
,07-05 14:06:12.170   907  1060 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:06:12.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:12.170   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:06:12.170   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:06:12.170   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:06:12.180   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:06:12.180   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:06:12.180   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:06:12.180   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:06:12.180   907  1060 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-05 14:06:12.180   907  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
07-05 14:06:12.180   907   907 V ActivityManager: Display changed displayId=0
,07-05 14:06:12.180   267   267 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a62000
07-05 14:06:12.180   267   267 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 14:06:12.210  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:06:12.210  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 14:06:12.210  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-05 14:06:12.210   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:06:12.210  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:06:12.210  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:06:12.220   907  1240 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:06:12.220   907  1472 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:06:12.220   907  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:06:12.240   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 334, CUR = 300
,07-05 14:06:12.330   907  7592 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:06:12.340   907  7592 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:06:12.370   907  7592 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:06:12.410   907  1092 D LightsService: [SvcLED]  onSensorChanged::light value = 0
,07-05 14:06:12.410   907  1092 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:06:12.420   907  1092 D SensorManager: unregisterListener ::   
07-05 14:06:12.420   907  1092 D lights  : led_pattern : 3 +
,07-05 14:06:12.420   907  1092 D lights  : led_pattern : 3 -
07-05 14:06:12.420   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Screen bin #0: time=5 power=3.1666666666666666E-5
07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Screen bin #3: time=9018 power=0.399798
07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Screen bin #4: time=0 power=0.0
07-05 14:06:12.430   907  7592 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:06:12.450   267   525 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 14:06:12.450   267   267 D qdhwcomposer: hwc_blank: Done blanking display: 0
,07-05 14:06:12.450   907  1175 D SurfaceControl: Excessive delay in setPowerMode(): 274ms
07-05 14:06:12.450   907  1175 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,07-05 14:06:12.450   907  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 14:06:12.450   907  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 14:06:12.450   907  1175 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:06:12.460   907  1060 I PowerManagerService: [PWL] Off : 0s ago
07-05 14:06:12.460   907  1060 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-05 14:06:12.460   907  1060 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-05 14:06:12.460   907  1060 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'SmartManager Framework Thread' (uid=1000, pid=907, ws=null) (elapsedTime=140)
07-05 14:06:12.460   907  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 289ms
,07-05 14:06:12.590   907  7592 I BatteryStatsDumper: Writing to database completed
,07-05 14:06:13.170   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:06:13.860   305   305 E SMD     : DCD ON
,07-05 14:06:16.860   305   305 E SMD     : DCD ON
,07-05 14:06:16.970   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:06:16.980  1189  1189 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,07-05 14:06:16.990  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:06:17.000  1189  1189 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 14:06:17.470   907  1060 I PowerManagerService: [PWL] Off : 5s ago
,07-05 14:06:19.860   305   305 E SMD     : DCD ON
,07-05 14:06:22.100   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:06:22.140   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:22.140   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:06:22.140   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:06:22.140   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:06:22.140   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:06:22.140   907   907 I MotionRecognitionService: Plugged
,07-05 14:06:22.140   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:22.150  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:22.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:22.150  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:22.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:22.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:22.160  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:22.160  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:22.160  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:22.290   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 333, CUR = 300
,07-05 14:06:22.860   305   305 E SMD     : DCD ON
,07-05 14:06:23.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:24.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:25.090   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:06:25.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:25.860   305   305 E SMD     : DCD ON
,07-05 14:06:26.170   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:27.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:27.470   907  1060 I PowerManagerService: [PWL] Off : 15s ago
,07-05 14:06:28.180   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:06:28.860   305   305 E SMD     : DCD ON
,07-05 14:06:29.590   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:31.250   907  1333 E Watchdog: !@Sync 8
,07-05 14:06:31.860   305   305 E SMD     : DCD ON
,07-05 14:06:32.200   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:32.210   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:06:32.210   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:06:32.210   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:32.220  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:32.220  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:32.230   907   907 I MotionRecognitionService: Plugged
,07-05 14:06:32.230   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:32.240   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:06:32.240  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:32.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:32.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:32.260  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:32.270  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:06:32.270  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:32.340   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 332, CUR = 300
,07-05 14:06:34.860   305   305 E SMD     : DCD ON
,07-05 14:06:37.860   305   305 E SMD     : DCD ON
,07-05 14:06:40.870   305   305 E SMD     : DCD ON
,07-05 14:06:42.210   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:06:42.230   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:06:42.290   907   907 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-05 14:06:42.290   907   907 I BackgroundCompactionService: onStart. jobID=801
,07-05 14:06:42.290   907   907 I BackgroundCompactionService: onStart done. jobID=801
,07-05 14:06:42.290   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:42.290   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:06:42.300   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:06:42.300   907  1636 D BatteryService: stay LED for fully charged
07-05 14:06:42.300   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:06:42.300  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:06:42.310  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:06:42.310  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:06:42.310  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:06:42.310  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:42.310  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:06:42.310  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:06:42.310  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:06:42.310   907   907 I MotionRecognitionService: Plugged
,07-05 14:06:42.310   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:06:42.320   907  7605 I BackgroundCompactionService: Execute BGCompaction (type1). (1 times)
,07-05 14:06:42.330   907  7605 I BackgroundCompactionService: compact_memory command done
,07-05 14:06:42.450   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 331, CUR = 300
,07-05 14:06:42.470   907  1060 I PowerManagerService: [PWL] Off : 30s ago
,07-05 14:06:43.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:43.870   305   305 E SMD     : DCD ON
,07-05 14:06:44.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:45.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:46.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:46.870   305   305 E SMD     : DCD ON
,07-05 14:06:47.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:06:48.180   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:06:49.590   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:06:49.870   305   305 E SMD     : DCD ON
,07-05 14:06:52.330   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:06:52.500   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 331, CUR = 300
,07-05 14:06:52.870   305   305 E SMD     : DCD ON
,07-05 14:06:55.870   305   305 E SMD     : DCD ON
,07-05 14:06:58.870   305   305 E SMD     : DCD ON
,07-05 14:06:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:07:01.260   907  1333 E Watchdog: !@Sync 9
,07-05 14:07:01.870   305   305 E SMD     : DCD ON
,07-05 14:07:02.390   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:02.390   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:02.390   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:07:02.400   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:02.400  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:02.410  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:02.410   907   907 I MotionRecognitionService: Plugged
,07-05 14:07:02.410   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:02.420   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:07:02.430  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:02.430  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:02.430  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:02.430  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:02.440  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:02.440  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:02.470   907  1060 I PowerManagerService: [PWL] Off : 50s ago
,07-05 14:07:02.540   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 330, CUR = 300
,07-05 14:07:04.870   305   305 E SMD     : DCD ON
,07-05 14:07:07.870   305   305 E SMD     : DCD ON
,07-05 14:07:08.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:09.180   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:09.600   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:10.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:10.870   305   305 E SMD     : DCD ON
,07-05 14:07:11.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:12.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:12.450   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:12.460   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:12.460   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:07:12.470   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:12.480  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:12.480  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:12.480   907   907 I MotionRecognitionService: Plugged
,07-05 14:07:12.480   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:12.490   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:07:12.500  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:12.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:12.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:12.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:12.520  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:12.520  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:12.590   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 329, CUR = 300
,07-05 14:07:13.190   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:07:13.870   305   305 E SMD     : DCD ON
,07-05 14:07:16.870   305   305 E SMD     : DCD ON
,07-05 14:07:19.880   305   305 E SMD     : DCD ON
,07-05 14:07:22.510   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:22.520   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:22.520   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:07:22.520   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:22.530  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:22.530  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:22.540   907   907 I MotionRecognitionService: Plugged
,07-05 14:07:22.540   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:22.540   907  1655 D BatteryService: stay LED for fully charged
,07-05 14:07:22.560  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:22.570  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:22.580  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:22.580  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:22.580  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:22.580  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:22.620   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 328, CUR = 300
,07-05 14:07:22.880   305   305 E SMD     : DCD ON
,07-05 14:07:25.880   305   305 E SMD     : DCD ON
,07-05 14:07:27.470   907  1060 I PowerManagerService: [PWL] Off : 75s ago
,07-05 14:07:28.880   305   305 E SMD     : DCD ON
,07-05 14:07:29.260   907  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:07:29.260   907  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:07:29.270   907  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:07:29.280   907  1102 I TLC_TIMA_PKM_initialize: initializing...
,07-05 14:07:29.290   907  1102 I TLC_TIMA_PKM_initialize: root = /firmware/image, root_strlen = 15
,07-05 14:07:29.290   907  1102 I TLC_TIMA_PKM_initialize: process = tima_pkm, process_strlen = 8
,07-05 14:07:29.290   907  1102 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
,07-05 14:07:29.290   907  1102 I TZ: qc_tlc_communication: process = tima_pkm, process_strlen = 8
,07-05 14:07:29.290   907  1102 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 262208 = 0x40040
,07-05 14:07:29.300   907  1102 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 262208 = 0x40040
,07-05 14:07:29.300   907  1102 I TZ: qc_tlc_communication: max_message_size = 524416 = 0x80080
,07-05 14:07:29.300   907  1102 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x80080
,07-05 14:07:29.300   907  1102 D QSEECOMAPI: : App is not loaded in QSEE
,07-05 14:07:29.340   907  1102 D QSEECOMAPI: : Loaded image: APP id = 2
,07-05 14:07:29.350   907  1102 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_pkm, tzapp is loaded
,07-05 14:07:29.360   907  1102 I TLC_TIMA_PKM_initialize: Trustlet response is completed
,07-05 14:07:29.600   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:31.260   907  1333 E Watchdog: !@Sync 10
,07-05 14:07:31.880   305   305 E SMD     : DCD ON
,07-05 14:07:32.260   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:07:32.260   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:07:32.270   907  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:32.280   907  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:07:32.570   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:32.570   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:32.570   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:07:32.580   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:32.590   907   907 I MotionRecognitionService: Plugged
,07-05 14:07:32.600  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:32.600  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:32.600   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:32.610   907  1240 D BatteryService: stay LED for fully charged
,07-05 14:07:32.630  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:32.630  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:32.630  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:32.630  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:32.640  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:32.640  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:32.680   907  3328 D SSRM:n  : SIOP:: AP = 330, PST = 327, CUR = 300
,07-05 14:07:34.880   305   305 E SMD     : DCD ON
,07-05 14:07:37.880   305   305 E SMD     : DCD ON
,07-05 14:07:38.190   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:07:38.190   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:07:40.880   305   305 E SMD     : DCD ON
,07-05 14:07:42.040  1870  3200 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:07:42.740   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 326, CUR = 300
,07-05 14:07:43.880   305   305 E SMD     : DCD ON
,07-05 14:07:46.580   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:07:46.610   907   994 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-05 14:07:46.610   907   994 D ActivityManager: com.blurb.checkout, Starting
,07-05 14:07:46.630   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:07:46.630   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:07:46.630   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:07:46.630   907   994 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-05 14:07:46.650   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:46.700   907   994 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7632 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-05 14:07:46.710  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:07:46.710  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:07:46.710  7632  7632 E Zygote  : MountEmulatedStorage()
,07-05 14:07:46.710  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:07:46.720  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:07:46.720  7632  7632 E Zygote  : v2
07-05 14:07:46.720  7632  7632 I libpersona: KNOX_SDCARD checking this for 10096
07-05 14:07:46.720  7632  7632 I libpersona: KNOX_SDCARD not a persona
,07-05 14:07:46.730  7632  7632 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:07:46.730  7632  7632 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-05 14:07:46.740  7632  7632 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-05 14:07:46.780  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:07:46.780  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:07:46.790  7632  7632 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-05 14:07:46.800  7632  7632 D ActivityThread: Added TimaKeyStore provider
,07-05 14:07:46.810  7632  7632 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-05 14:07:46.850   907  1466 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
07-05 14:07:46.850   907  1466 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ac0d1f9, r.packageName :com.blurb.checkout
,07-05 14:07:46.880   305   305 E SMD     : DCD ON
,07-05 14:07:46.920   907  1093 I ActivityManager: Killing 5592:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,07-05 14:07:49.610   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:07:49.880   305   305 E SMD     : DCD ON
,07-05 14:07:52.810   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 325, CUR = 300
,07-05 14:07:52.890   305   305 E SMD     : DCD ON
,07-05 14:07:53.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:54.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:55.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:55.890   305   305 E SMD     : DCD ON
,07-05 14:07:56.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:56.710   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:07:56.720   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:07:56.720   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:07:56.720   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:07:56.730  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:07:56.740  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:07:56.740   907   907 I MotionRecognitionService: Plugged
,07-05 14:07:56.740   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:07:56.740   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:07:56.760  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:07:56.770  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:56.780  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:07:56.780  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:07:56.780  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:56.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:07:57.190   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:07:57.480   907  1060 I PowerManagerService: [PWL] Off : 105s ago
,07-05 14:07:58.190   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:07:58.890   305   305 E SMD     : DCD ON
,07-05 14:07:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:08:01.260   907  1333 E Watchdog: !@Sync 11
,07-05 14:08:01.890   305   305 E SMD     : DCD ON
,07-05 14:08:02.860   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 324, CUR = 300
,07-05 14:08:03.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:04.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:04.890   305   305 E SMD     : DCD ON
,07-05 14:08:05.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:06.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:07.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:07.890   305   305 E SMD     : DCD ON
,07-05 14:08:08.200   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:08:09.610   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:10.890   305   305 E SMD     : DCD ON
,07-05 14:08:12.110   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:08:12.130  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:08:12.130  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:08:12.140  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:08:12.140  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:08:12.180   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:12.180   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:08:12.180   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:08:12.180   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:08:12.190   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:12.210  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:12.210  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:12.220  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:12.220   907   907 I MotionRecognitionService: Plugged
,07-05 14:08:12.220   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:12.220  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:12.220  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:12.220  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:12.220  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:12.230  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:12.240  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:08:12.240  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:08:12.910   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 323, CUR = 300
,07-05 14:08:13.890   305   305 E SMD     : DCD ON
,07-05 14:08:16.890   305   305 E SMD     : DCD ON
,07-05 14:08:18.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:19.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:19.890   305   305 E SMD     : DCD ON
,07-05 14:08:20.200   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:21.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:22.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:22.230   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:22.240   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:22.240   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:08:22.240   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:22.250  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:22.260  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:22.260   907   907 I MotionRecognitionService: Plugged
,07-05 14:08:22.260   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:22.260   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:08:22.280  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:22.280  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:22.290  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:22.290  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:22.300  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:22.300  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:22.890   305   305 E SMD     : DCD ON
,07-05 14:08:22.960   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 322, CUR = 300
,07-05 14:08:23.210   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:08:25.890   305   305 E SMD     : DCD ON
,07-05 14:08:28.900   305   305 E SMD     : DCD ON
,07-05 14:08:29.620   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:31.270   907  1333 E Watchdog: !@Sync 12
,07-05 14:08:31.900   305   305 E SMD     : DCD ON
,07-05 14:08:32.300   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:32.300   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:32.300   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:08:32.310   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:32.310  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:32.320  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:32.320   907   907 I MotionRecognitionService: Plugged
,07-05 14:08:32.320   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:32.330   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:08:32.340  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:32.350  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:32.360  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:32.360  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:32.360  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:32.360  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:32.480   907  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-05 14:08:33.010   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300
,07-05 14:08:34.900   305   305 E SMD     : DCD ON
,07-05 14:08:37.900   305   305 E SMD     : DCD ON
,07-05 14:08:38.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:39.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:40.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:40.900   305   305 E SMD     : DCD ON
,07-05 14:08:41.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:42.210   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:08:42.360   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:42.360   907  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:42.370   907  1377 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:08:42.370   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:42.380  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:42.380  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:42.390   907   907 I MotionRecognitionService: Plugged
,07-05 14:08:42.390   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:42.390   907  1377 D BatteryService: stay LED for fully charged
,07-05 14:08:42.410  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:42.410  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:08:42.410  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:42.410  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:42.420  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:42.420  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:43.050   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300
,07-05 14:08:43.210   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:08:43.900   305   305 E SMD     : DCD ON
,07-05 14:08:46.900   305   305 E SMD     : DCD ON
,07-05 14:08:49.620   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:08:49.900   305   305 E SMD     : DCD ON
,07-05 14:08:52.420   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:08:52.430   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:08:52.430   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:08:52.430   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:08:52.440  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:08:52.440  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:08:52.450   907   907 I MotionRecognitionService: Plugged
,07-05 14:08:52.450   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:08:52.460   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:08:52.460  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:08:52.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:52.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:52.470  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:08:52.470  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:08:52.470  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:08:52.900   305   305 E SMD     : DCD ON
,07-05 14:08:53.100   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300
,07-05 14:08:55.900   305   305 E SMD     : DCD ON
,07-05 14:08:58.900   305   305 E SMD     : DCD ON
,07-05 14:08:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:09:01.270   907  1333 E Watchdog: !@Sync 13
,07-05 14:09:01.900   305   305 E SMD     : DCD ON
,07-05 14:09:02.480   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:03.150   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 321, CUR = 300
,07-05 14:09:03.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:04.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:04.910   305   305 E SMD     : DCD ON
,07-05 14:09:05.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:06.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:07.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:07.910   305   305 E SMD     : DCD ON
,07-05 14:09:08.220   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:09:09.630   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:10.910   305   305 E SMD     : DCD ON
,07-05 14:09:12.490   907  1060 I PowerManagerService: [PWL] Off : 180s ago
,07-05 14:09:12.540   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:12.550   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:12.550   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:09:12.550   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:12.560  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:12.570  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:12.570   907   907 I MotionRecognitionService: Plugged
,07-05 14:09:12.570   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:12.580   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:09:12.590  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:12.600  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:12.600  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:12.610  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:12.610  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:12.610  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:13.200   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300
,07-05 14:09:13.910   305   305 E SMD     : DCD ON
,07-05 14:09:16.910   305   305 E SMD     : DCD ON
,07-05 14:09:19.910   305   305 E SMD     : DCD ON
,07-05 14:09:22.610   907  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:22.610   907  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:22.620   907  1472 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:09:22.620   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:22.630  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:22.630  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:22.640   907   907 I MotionRecognitionService: Plugged
,07-05 14:09:22.640   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:22.640   907  1472 D BatteryService: stay LED for fully charged
,07-05 14:09:22.660  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:22.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:22.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:22.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:22.670  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:22.670  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:22.910   305   305 E SMD     : DCD ON
,07-05 14:09:23.240   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 320, CUR = 300
,07-05 14:09:25.910   305   305 E SMD     : DCD ON
,07-05 14:09:28.910   305   305 E SMD     : DCD ON
,07-05 14:09:29.630   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:31.270   907  1333 E Watchdog: !@Sync 14
,07-05 14:09:31.910   305   305 E SMD     : DCD ON
,07-05 14:09:32.670   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:33.220   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:09:33.220   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:09:33.290   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 319, CUR = 300
,07-05 14:09:34.910   305   305 E SMD     : DCD ON
,07-05 14:09:37.910   305   305 E SMD     : DCD ON
,07-05 14:09:40.920   305   305 E SMD     : DCD ON
,07-05 14:09:42.730   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:43.340   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 318, CUR = 300
,07-05 14:09:43.920   305   305 E SMD     : DCD ON
,07-05 14:09:46.920   305   305 E SMD     : DCD ON
,07-05 14:09:49.630   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:09:49.920   305   305 E SMD     : DCD ON
,07-05 14:09:52.790   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:09:52.800   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:09:52.800   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:09:52.800   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:09:52.810  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:09:52.820  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:09:52.820   907   907 I MotionRecognitionService: Plugged
,07-05 14:09:52.820   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:09:52.830   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:09:52.840  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:09:52.850  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:52.860  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:52.860  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:09:52.860  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:09:52.860  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:09:52.920   305   305 E SMD     : DCD ON
,07-05 14:09:53.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:53.440   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 317, CUR = 300
,07-05 14:09:54.220   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:55.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:55.920   305   305 E SMD     : DCD ON
,07-05 14:09:56.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:57.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:09:57.500   907  1060 I PowerManagerService: [PWL] Off : 225s ago
,07-05 14:09:58.230   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-05 14:09:58.920   305   305 E SMD     : DCD ON
,07-05 14:10:01.270   907  1333 E Watchdog: !@Sync 15
,07-05 14:10:01.920   305   305 E SMD     : DCD ON
,07-05 14:10:02.860   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:03.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:03.490   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 316, CUR = 300
,07-05 14:10:04.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:04.920   305   305 E SMD     : DCD ON
,07-05 14:10:05.230   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:06.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:07.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:07.920   305   305 E SMD     : DCD ON
,07-05 14:10:08.240   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-05 14:10:09.640   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:10.920   305   305 E SMD     : DCD ON
,07-05 14:10:12.920   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:12.930   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:12.930   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:10:12.930   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:12.940  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:12.940  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:12.950   907   907 I MotionRecognitionService: Plugged
,07-05 14:10:12.950   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:12.960   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:10:12.960  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:12.960  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:12.960  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:12.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:12.970  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:12.970  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:13.540   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 315, CUR = 300
,07-05 14:10:13.920   305   305 E SMD     : DCD ON
,07-05 14:10:16.930   305   305 E SMD     : DCD ON
,07-05 14:10:18.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:19.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:19.480   353   353 I bootchecker: bootchecker wake up!!
,07-05 14:10:19.930   305   305 E SMD     : DCD ON
,07-05 14:10:20.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:21.240   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:22.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:22.930   305   305 E SMD     : DCD ON
,07-05 14:10:22.990   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:22.990   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:23.000   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:10:23.000   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:23.010  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:23.010  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:23.020   907   907 I MotionRecognitionService: Plugged
,07-05 14:10:23.020   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:23.030   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:10:23.040  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:23.050  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:23.060  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:23.060  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:23.060  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:23.060  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:23.250   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,07-05 14:10:23.590   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 314, CUR = 300
,07-05 14:10:25.930   305   305 E SMD     : DCD ON
,07-05 14:10:28.930   305   305 E SMD     : DCD ON
,07-05 14:10:29.640   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:31.280   907  1333 E Watchdog: !@Sync 16
,07-05 14:10:31.930   305   305 E SMD     : DCD ON
,07-05 14:10:33.050   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:33.060   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:33.060   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:10:33.060   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:33.070  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:33.070  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:33.080   907   907 I MotionRecognitionService: Plugged
,07-05 14:10:33.080   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:33.090   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:10:33.100  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:33.110  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:33.110  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:33.110  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:33.110  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:33.110  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:33.630   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 313, CUR = 300
,07-05 14:10:34.930   305   305 E SMD     : DCD ON
,07-05 14:10:37.930   305   305 E SMD     : DCD ON
,07-05 14:10:38.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:39.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:40.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:40.930   305   305 E SMD     : DCD ON
,07-05 14:10:41.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:42.250   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:10:43.110   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:43.120   907  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:10:43.120   907  1377 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:10:43.120   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:10:43.130  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:10:43.130  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:10:43.140   907   907 I MotionRecognitionService: Plugged
,07-05 14:10:43.140   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:10:43.150   907  1377 D BatteryService: stay LED for fully charged
,07-05 14:10:43.160  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:10:43.160  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:43.160  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:43.160  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:10:43.170  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:10:43.170  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:10:43.250   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-05 14:10:43.680   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:10:43.930   305   305 E SMD     : DCD ON
,07-05 14:10:46.930   305   305 E SMD     : DCD ON
,07-05 14:10:47.500   907  1060 I PowerManagerService: [PWL] Off : 275s ago
,07-05 14:10:49.650   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:10:49.930   305   305 E SMD     : DCD ON
,07-05 14:10:52.940   305   305 E SMD     : DCD ON
,07-05 14:10:53.730   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:10:55.940   305   305 E SMD     : DCD ON
,07-05 14:10:58.940   305   305 E SMD     : DCD ON
,07-05 14:10:59.010   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:10:59.030  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:10:59.040  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:10:59.040  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:10:59.040  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:10:59.080   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:10:59.120  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:10:59.120  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:10:59.240   907   991 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:10:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:11:01.280   907  1333 E Watchdog: !@Sync 17
,07-05 14:11:01.940   305   305 E SMD     : DCD ON
,07-05 14:11:03.260   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:03.780   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:04.260   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:04.940   305   305 E SMD     : DCD ON
,07-05 14:11:05.260   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:06.260   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:07.260   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,07-05 14:11:07.940   305   305 E SMD     : DCD ON
,07-05 14:11:08.260   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-05 14:11:09.130   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:09.140   907  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 292, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:11:09.140   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:11:09.140   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:11:09.150  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:11:09.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:11:09.160   907   907 I MotionRecognitionService: Plugged
,07-05 14:11:09.160   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:11:09.170   907  1359 D BatteryService: stay LED for fully charged
,07-05 14:11:09.170  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:11:09.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:09.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:09.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:11:09.180  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:11:09.180  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:11:09.650   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:10.940   305   305 E SMD     : DCD ON
,07-05 14:11:13.830   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:13.940   305   305 E SMD     : DCD ON
,07-05 14:11:16.940   305   305 E SMD     : DCD ON
,07-05 14:11:19.190   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:19.940   305   305 E SMD     : DCD ON
,07-05 14:11:22.940   305   305 E SMD     : DCD ON
,07-05 14:11:23.910   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:25.940   305   305 E SMD     : DCD ON
,07-05 14:11:28.950   305   305 E SMD     : DCD ON
,07-05 14:11:29.250   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:29.650   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:31.280   907  1333 E Watchdog: !@Sync 18
,07-05 14:11:31.950   305   305 E SMD     : DCD ON
,07-05 14:11:33.260   357   357 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
07-05 14:11:33.260   357   357 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-05 14:11:33.970   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:34.950   305   305 E SMD     : DCD ON
,07-05 14:11:37.950   305   305 E SMD     : DCD ON
,07-05 14:11:39.310   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:40.950   305   305 E SMD     : DCD ON
,07-05 14:11:42.500   907  1060 I PowerManagerService: [PWL] Off : 330s ago
,07-05 14:11:43.950   305   305 E SMD     : DCD ON
,07-05 14:11:44.050   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:46.950   305   305 E SMD     : DCD ON
,07-05 14:11:49.370   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:11:49.660   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:11:49.950   305   305 E SMD     : DCD ON
,07-05 14:11:52.950   305   305 E SMD     : DCD ON
,07-05 14:11:54.120   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:11:55.950   305   305 E SMD     : DCD ON
,07-05 14:11:58.270   357   357 I Atfwd_Daemon: Stop the daemon....
,07-05 14:11:58.950   305   305 E SMD     : DCD ON
,07-05 14:11:59.430   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:01.280   907  1333 E Watchdog: !@Sync 19
,07-05 14:12:01.950   305   305 E SMD     : DCD ON
,07-05 14:12:04.170   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:04.960   305   305 E SMD     : DCD ON
,07-05 14:12:07.960   305   305 E SMD     : DCD ON
,07-05 14:12:09.490   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:09.500   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:09.500   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:12:09.500   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:09.510  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:09.520   907   907 I MotionRecognitionService: Plugged
,07-05 14:12:09.520  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:09.520   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:09.520   907  1240 D BatteryService: stay LED for fully charged
,07-05 14:12:09.550  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:09.550  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:09.560  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:09.560  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:09.570  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:09.570  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:09.660   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:10.960   305   305 E SMD     : DCD ON
,07-05 14:12:13.960   305   305 E SMD     : DCD ON
,07-05 14:12:14.220   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:16.960   305   305 E SMD     : DCD ON
,07-05 14:12:19.560   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:19.960   305   305 E SMD     : DCD ON
,07-05 14:12:22.960   305   305 E SMD     : DCD ON
,07-05 14:12:24.280   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:25.960   305   305 E SMD     : DCD ON
,07-05 14:12:28.960   305   305 E SMD     : DCD ON
,07-05 14:12:29.260   907  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:12:29.260   907  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:12:29.260   907  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:12:29.630   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:29.630   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:29.640   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:12:29.640   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:29.650  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:29.650  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:29.660   907   907 I MotionRecognitionService: Plugged
,07-05 14:12:29.660   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:29.660   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:29.670   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:12:29.680  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:29.680  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:29.680  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:29.680  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:29.680  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:29.690  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:31.290   907  1333 E Watchdog: !@Sync 20
,07-05 14:12:31.960   305   305 E SMD     : DCD ON
,07-05 14:12:32.300   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:12:32.300   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:12:32.310   907  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:32.310   907  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:12:34.360   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:34.960   305   305 E SMD     : DCD ON
,07-05 14:12:37.960   305   305 E SMD     : DCD ON
,07-05 14:12:39.690   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:40.960   305   305 E SMD     : DCD ON
,07-05 14:12:42.510   907  1060 I PowerManagerService: [PWL] Off : 390s ago
,07-05 14:12:43.970   305   305 E SMD     : DCD ON
,07-05 14:12:44.400   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:46.970   305   305 E SMD     : DCD ON
,07-05 14:12:49.700   907  3372 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-05 14:12:49.760   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:12:49.760   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:12:49.760   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:12:49.770   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:12:49.770  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:12:49.780  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:12:49.780   907   907 I MotionRecognitionService: Plugged
,07-05 14:12:49.790   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:12:49.790   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:12:49.810  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:12:49.810  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:49.820  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:49.820  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:12:49.820  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:12:49.830  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:12:49.970   305   305 E SMD     : DCD ON
,07-05 14:12:52.970   305   305 E SMD     : DCD ON
,07-05 14:12:54.450   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:12:55.970   305   305 E SMD     : DCD ON
,07-05 14:12:58.970   305   305 E SMD     : DCD ON
,07-05 14:12:59.820   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:01.290   907  1333 E Watchdog: !@Sync 21
,07-05 14:13:01.970   305   305 E SMD     : DCD ON
,07-05 14:13:04.500   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:04.970   305   305 E SMD     : DCD ON
,07-05 14:13:07.970   305   305 E SMD     : DCD ON
,07-05 14:13:09.890   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:10.980   305   305 E SMD     : DCD ON
,07-05 14:13:13.980   305   305 E SMD     : DCD ON
,07-05 14:13:14.550   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:16.980   305   305 E SMD     : DCD ON
,07-05 14:13:19.950   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:19.980   305   305 E SMD     : DCD ON
,07-05 14:13:22.980   305   305 E SMD     : DCD ON
,07-05 14:13:24.640   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:25.980   305   305 E SMD     : DCD ON
,07-05 14:13:28.980   305   305 E SMD     : DCD ON
,07-05 14:13:30.000   907   922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:31.290   907  1333 E Watchdog: !@Sync 22
,07-05 14:13:31.980   305   305 E SMD     : DCD ON
,07-05 14:13:34.690   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:34.980   305   305 E SMD     : DCD ON
,07-05 14:13:37.980   305   305 E SMD     : DCD ON
,07-05 14:13:40.060   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:40.070   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:40.070   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:13:40.070   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:40.080   907   907 I MotionRecognitionService: Plugged
,07-05 14:13:40.080  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:40.090  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:40.090   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:40.100   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:13:40.110  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:40.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:40.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:40.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:40.120  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:40.120  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:40.980   305   305 E SMD     : DCD ON
,07-05 14:13:43.980   305   305 E SMD     : DCD ON
,07-05 14:13:44.740   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:46.980   305   305 E SMD     : DCD ON
,07-05 14:13:47.510   907  1060 I PowerManagerService: [PWL] Off : 455s ago
,07-05 14:13:49.990   305   305 E SMD     : DCD ON
,07-05 14:13:50.120   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:13:50.130   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:13:50.130   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:13:50.130   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:13:50.140  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:13:50.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:13:50.150   907   907 I MotionRecognitionService: Plugged
,07-05 14:13:50.150   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:13:50.160   907  1240 D BatteryService: stay LED for fully charged
,07-05 14:13:50.170  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:13:50.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:50.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:50.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:13:50.180  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:13:50.180  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:13:52.990   305   305 E SMD     : DCD ON
,07-05 14:13:54.780   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:13:55.990   305   305 E SMD     : DCD ON
,07-05 14:13:58.990   305   305 E SMD     : DCD ON
,07-05 14:14:00.000   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:14:00.020  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:14:00.020  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:14:00.020  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:14:00.030  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:14:00.100  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:14:00.110  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:14:00.170   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:00.170   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:14:00.170   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:14:00.170   907  1655 D BatteryService: stay LED for fully charged
07-05 14:14:00.170   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:00.170  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:00.170  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:14:00.170   907   907 I MotionRecognitionService: Plugged
07-05 14:14:00.170   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:00.170  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:00.180  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:00.180  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:00.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:00.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:00.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:01.300   907  1333 E Watchdog: !@Sync 23
,07-05 14:14:01.990   305   305 E SMD     : DCD ON
,07-05 14:14:04.830   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:14:04.990   305   305 E SMD     : DCD ON
,07-05 14:14:07.990   305   305 E SMD     : DCD ON
,07-05 14:14:10.230   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:10.230   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:10.230   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:14:10.240   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:10.250   907   907 I MotionRecognitionService: Plugged
,07-05 14:14:10.250   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:10.250   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:14:10.260  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:10.270  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:10.270  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:10.280  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:10.280  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:10.280  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:10.280  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:10.280  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:10.990   305   305 E SMD     : DCD ON
,07-05 14:14:13.990   305   305 E SMD     : DCD ON
,07-05 14:14:14.880   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:14:17.000   305   305 E SMD     : DCD ON
,07-05 14:14:20.000   305   305 E SMD     : DCD ON
,07-05 14:14:20.290   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:20.300   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:20.300   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:14:20.300   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:20.310  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:20.310  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:20.320   907   907 I MotionRecognitionService: Plugged
,07-05 14:14:20.320   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:20.320   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:14:20.340  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:20.340  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:20.350  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:20.350  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:20.360  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:20.360  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:23.000   305   305 E SMD     : DCD ON
,07-05 14:14:24.930   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:14:26.000   305   305 E SMD     : DCD ON
,07-05 14:14:29.000   305   305 E SMD     : DCD ON
,07-05 14:14:30.350   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:31.300   907  1333 E Watchdog: !@Sync 24
,07-05 14:14:32.000   305   305 E SMD     : DCD ON
,07-05 14:14:35.000   305   305 E SMD     : DCD ON
,07-05 14:14:35.020   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:14:38.000   305   305 E SMD     : DCD ON
,07-05 14:14:38.550   907  1122 D InputReader: Input event: value=1
,07-05 14:14:38.550   907  1122 D InputReader: !@notifyKey(172), action=0
,07-05 14:14:38.550   907  1122 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=0
,07-05 14:14:38.550   907  1122 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  pkgName : WAKEUP_BOOSTER@32
,07-05 14:14:38.550   907  1122 E SamsungWindowManager: mCoreNumLockHelper.acquire
,07-05 14:14:38.550   907  1122 D PowerManagerService: [api] [s] wakeUpWithReason (uid: 1000 pid: 907) eventTime = 746000 event = 1
,07-05 14:14:38.560   907  1122 I PowerManagerService: !@[ps] Screen__On  - 2 :  wakeUpWithReason: 1 (uid: 1000 pid: 907)
07-05 14:14:38.560   907  1122 I PowerManagerService: Waking up from sleep (uid 1000)...
07-05 14:14:38.560   907  1122 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
07-05 14:14:38.560   907  1122 D PowerManagerService: [s] UserActivityState : 0 -> 1
07-05 14:14:38.560   907  1122 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Display
07-05 14:14:38.560   907  1122 D InputManager-JNI: !@handleInterceptActions(172), action=0, wmActions=0
07-05 14:14:38.560   907  1122 D InputManager-JNI: Disable repeat for home key when device wake up
,07-05 14:14:38.560   907  1170 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@1495b8f0)
07-05 14:14:38.560   907  1060 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
07-05 14:14:38.560   907  1056 D SContextService: 	.registerCallback : 1, client=
07-05 14:14:38.560   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:14:38.560   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:38.560   907  1056 W CAE     : setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
07-05 14:14:38.560  1189  1205 D KeyguardViewMediator: onScreenTurnedOn, seq = 3
07-05 14:14:38.560  1189  1205 D KeyguardViewMediator: notifyScreenOnLocked
07-05 14:14:38.560  1189  1189 D KeyguardViewMediator: handleNotifyScreenOn
,07-05 14:14:38.560   907  1175 D PowerManagerService: !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
07-05 14:14:38.560   907  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 1
07-05 14:14:38.560   907  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 1
07-05 14:14:38.560   907  1175 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:14:38.560   907  1056 I CAE     : setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
07-05 14:14:38.560   907  1056 I CAE     : setCAProperty(ContextAwareService.java:469) - result : true
07-05 14:14:38.560   907  1056 W CAE     : setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:14:38.560   907  1056 D SContextService: sendAttribute() : service = Auto Rotation
,07-05 14:14:38.560   907  1056 W CAE     : registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
07-05 14:14:38.560  1189  1189 D StatusBarKeyguardViewManager: onScreenTurnedOn()
07-05 14:14:38.560   907  1056 V CAE     : start(ContextProvider.java:126)
07-05 14:14:38.560   907  1359 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-05 14:14:38.560   907  1056 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:14:38.560  1189  1189 D StatusBarKeyguardViewManager: callback.onShown()
07-05 14:14:38.560   907  1056 V CAE     : enable(AutoRotationRunner.java:158)
07-05 14:14:38.560   907  1056 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
07-05 14:14:38.560   907  1056 D SensorHubManager: SendSensorHubData: send data = -79, 7, 0, 0
07-05 14:14:38.560   322   578 D Sensorhubs: sendContextData: -79, 7, 0, 0
,07-05 14:14:38.560   267   267 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6a62000
07-05 14:14:38.560   267   267 D qdhwcomposer: hwc_blank: Unblanking display: 0
,07-05 14:14:38.570   907  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 14:14:38.580   907  1056 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
07-05 14:14:38.580   907  1056 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:14:38.630   907  1056 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 14:14:38.630   907  1056 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
07-05 14:14:38.630   907  1056 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-05 14:14:38.630   907  1056 I CAE     : showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@41237d8, Service : AUTO_ROTATION(1)
07-05 14:14:38.630   907  1056 W CAE     : registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:14:38.630   907  1056 D SContextService: addSContextService() : service = Auto Rotation
07-05 14:14:38.630   907  1056 D SContextService: ===== SContext Service List =====
07-05 14:14:38.630   907  1056 D SContextService: Listener : android.hardware.scontext.SContextService$Listener@11d5c731, Service : Auto Rotation
07-05 14:14:38.630   907  1056 D SContextManager:   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1bb90e69, service=Auto Rotation
,07-05 14:14:38.630   907  1056 D DisplayPowerController: [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
07-05 14:14:38.630   907   907 V ActivityManager: Display changed displayId=0
07-05 14:14:38.630   907  1060 I DisplayPowerController: Unblocked screen on after 76 ms
07-05 14:14:38.630   907  1060 D DisplayPowerState: !@ ColorFade exit
,07-05 14:14:38.650   267  1437 I SurfaceFlinger: id=13 Removed DolorFade (8/8)
,07-05 14:14:38.650   267   318 I SurfaceFlinger: id=13 Removed DolorFade (-2/8)
,07-05 14:14:38.650   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:14:38.650   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:38.650   907  1174 D lights  : lcd : 121 +
07-05 14:14:38.650   907  1174 D lights  : lcd : 121 -
07-05 14:14:38.660   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
,07-05 14:14:38.660   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:14:38.660   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:14:38.660   907  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : true
07-05 14:14:38.660   907  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 1
07-05 14:14:38.660   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOn
,07-05 14:14:38.660   907  1171 D lights  : button : 1 +
07-05 14:14:38.660   907  1171 D lights  : button : 1 -
,07-05 14:14:38.670  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-05 14:14:38.670  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-05 14:14:38.670   907  1170 D InputManager-JNI: setDeviceInteractive: 1
,07-05 14:14:38.670   907  7750 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 1
07-05 14:14:38.670   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:14:38.670   907  7749 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 1
07-05 14:14:38.670   907  7749 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 1
07-05 14:14:38.670   907  7748 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 1
,07-05 14:14:38.670   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
,07-05 14:14:38.680   907   907 D PalmMotion: 2013 - SURFACE_MOTION_ENGINE: 1 SURFACE_PALM_TOUCH: 1
,07-05 14:14:38.680   907  1174 D lights  : lcd : 162 +
07-05 14:14:38.680   907  1174 D lights  : lcd : 162 -
07-05 14:14:38.680   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:38.680   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 162
07-05 14:14:38.680   907  1060 D DisplayPowerController: animation target = 162, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:14:38.680   907   907 D PalmMotion: SURFACE_PALM_SWIPE: 1
07-05 14:14:38.680   907   907 E MotionRecognitionService:   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,07-05 14:14:38.680   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 907) 
07-05 14:14:38.680   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x42 -> 0x40 | SvcLED(id=4) set Off
,07-05 14:14:38.680   907   907 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:14:38.680  1409  1409 D NativeNfcManager: power state=4
07-05 14:14:38.680  1409  1409 D BrcmNfcJni: PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x4; screen on unlocked
,07-05 14:14:38.690   907   907 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
,07-05 14:14:38.690  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-05 14:14:38.690  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:14:38.690  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-05 14:14:38.690  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 14:14:38.690  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-05 14:14:38.690  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:38.690  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:38.690   907  3328 D SSRM:a  : DeviceInfo:: 000000100000
07-05 14:14:38.690   907  3328 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 14:14:38.700   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 907) 
,07-05 14:14:38.700   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
07-05 14:14:38.700   907  1092 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,07-05 14:14:38.700   907  1092 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
07-05 14:14:38.700  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:14:38.700  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-05 14:14:38.700  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-05 14:14:38.700  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:38.700  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:38.700   907   907 D BatteryService: turn off LED
07-05 14:14:38.700   907  1468 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-05 14:14:38.700   907  1468 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-05 14:14:38.700   907  1468 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,07-05 14:14:38.700  1725  1725 D SamsungIME: showDlgMsgBox : false true true
07-05 14:14:38.700  7114  7114 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@364f77fa time:746158
,07-05 14:14:38.700   907   907 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-05 14:14:38.700   907   907 D PersonaManagerService: getPersonasForUser(): returning null!
,07-05 14:14:38.710   907  1092 D SensorManager: unregisterListener ::   
,07-05 14:14:38.710   907  1092 D lights  : led_pattern : 0 +
07-05 14:14:38.710  1409  7041 D NfcService: call the applyRouting
07-05 14:14:38.710   907  1092 D lights  : led_pattern : 0 -
07-05 14:14:38.710   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,07-05 14:14:38.720   907  1122 D InputReader: Input event: value=0
07-05 14:14:38.720   907  1122 D InputReader: !@notifyKey(172), action=1
07-05 14:14:38.720   907  1122 D InputManager-JNI: !@interceptKeyBeforeQueueing(172), action=1
07-05 14:14:38.720   907  1122 D InputManager-JNI: !@handleInterceptActions(172), action=1, wmActions=0
,07-05 14:14:38.720   907   907 I CAE     : handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,07-05 14:14:38.720   907   907 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
07-05 14:14:38.720   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
07-05 14:14:38.720   907   907 D SensorHubManager: SendSensorHubData: send data = -76, 13, -47, 0
07-05 14:14:38.720   907  1429 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-05 14:14:38.720   907  1429 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b9cee16, r.packageName :com.google.android.gms
,07-05 14:14:38.730   322   322 D Sensorhubs: sendContextData: -76, 13, -47, 0
,07-05 14:14:38.730   907   907 D InputMethodManagerService: [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,07-05 14:14:38.740  1870  1870 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.trustagent.UserPresentBroadcastReceiver }.
,07-05 14:14:38.740   907   907 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_ON
,07-05 14:14:38.740   907  1126 E MotionRecognitionService:  handler : SCREEN_ON end
,07-05 14:14:38.750   907   907 D NotificationService: ACTION_SCREEN_ON
07-05 14:14:38.750   907   907 D LightsService: [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 907) 
07-05 14:14:38.750   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
07-05 14:14:38.750   907  1092 D LightsService: [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
07-05 14:14:38.750   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,07-05 14:14:38.750   310   677 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
07-05 14:14:38.750   310   677 V voice   : voice_set_parameters: enter: screen_state=on
07-05 14:14:38.750   310   677 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:14:38.750   310   677 V msm8974_platform: platform_set_parameters: enter: screen_state=on
07-05 14:14:38.750   310   677 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-05 14:14:38.750   310   677 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:14:38.750   310   677 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:14:38.750   907   907 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,07-05 14:14:38.750   907  1148 E native  : do suspend false
,07-05 14:14:38.760  1299  1299 I wpa_supplicant: reset timer : RESET_TIMER 1
07-05 14:14:38.760  1299  1299 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-05 14:14:38.760  1299  1299 I wpa_supplicant: P2P: Current p2p state = IDLE
,07-05 14:14:38.760  1299  1299 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-05 14:14:38.760   907  1359 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:14:38.770   907  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_ON
07-05 14:14:38.770   907  1058 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:14:38.800   907  7748 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 1
,07-05 14:14:38.800   267   525 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-05 14:14:38.800   267   267 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-05 14:14:38.800   267   267 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-05 14:14:38.800   907  1175 D SurfaceControl: Excessive delay in setPowerMode(): 240ms
07-05 14:14:38.800   907  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 245ms
,07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020507/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:14:38.820  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:38.820  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.070   907  7750 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 1
,07-05 14:14:39.550   907   907 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1958400  uid : 1000  pid : 907  tag : WAKEUP_BOOSTER@32
,07-05 14:14:39.820  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:39.830  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:39.830  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.830  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.830  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.830  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:39.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:39.840  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:39.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:39.840  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:40.030   907   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_ON
07-05 14:14:40.030   907   907 D PersonaManagerService: ACTION_SCREEN_ON onReceive
,07-05 14:14:40.030   907  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_ON called
,07-05 14:14:40.040  1409  1409 I NfcService: When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,07-05 14:14:40.040  1409  7045 D NfcService: call the applyRouting
,07-05 14:14:40.050  1755  1755 D accuweather: [Accuweather J]>>> SWW:67 [0:0] =============== BR act = androidintentactionSCREEN_ON
,07-05 14:14:40.050  1755  1755 D accuweather: [Accuweather J]>>> SWW:70 [0:0] =============== androidintentactionSCREEN_ON instance : [0]1
,07-05 14:14:40.060  1725  1725 I SamsungIME: getNextShiftState() cursorCapsMode : 0
,07-05 14:14:40.080  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:43 [0:0] onReceive() action : androidintentactionSCREEN_ON
,07-05 14:14:40.080  2915  2915 E com.samsung.app: [MSC]>>>News_Daemon(E) DR:71 [0:0] [NameNotFoundException] process restart With Widget !!!!!
,07-05 14:14:40.080  2915  2915 W com.samsung.app: [MSC]>>>News_Daemon(E) U:95 [0:0]  ::::::::: Available Internal MemorySize ::::::::: = 25140228k
,07-05 14:14:40.090   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:14:40.090  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:104 [0:0] checkPackageNameList is Empty
07-05 14:14:40.090  2915  2915 I com.samsung.app: [MSC]>>>News_Daemon(E) DR:110 [0:0] serviceStatus = 0 checkPackageNameList = 0
,07-05 14:14:40.090  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:145 [0:0] [CARS][AUTOREFRESHKEY] --> 0
07-05 14:14:40.090  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:146 [0:0] [CARS][NRT] = 0
07-05 14:14:40.090  2915  2915 D com.samsung.app: [MSC]>>>News_Daemon(E) DR:147 [0:0] [CARS][DT] = 1467720880094
,07-05 14:14:40.090   907  1093 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:14:40.100   907  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:14:40.120   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 311, CUR = 300
,07-05 14:14:40.130  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,07-05 14:14:40.130  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 14:14:40.130  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
,07-05 14:14:40.130  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
07-05 14:14:40.130  2915  2915 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
07-05 14:14:40.130  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:14:40.130  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:14:40.130  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:616 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
07-05 14:14:40.140  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,07-05 14:14:40.150  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:618 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,07-05 14:14:40.150  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:619 [0:0] [ASO][NUT] = 07/05/2016 04:42 PM
,07-05 14:14:40.150  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:620 [0:0] [ASO][CT] = 07/05/2016 02:14 PM
,07-05 14:14:40.150  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,07-05 14:14:40.150  2915  2915 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,07-05 14:14:40.160   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
07-05 14:14:40.160   907  1171 D lights  : button : 0 +
,07-05 14:14:40.180   907  7771 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:14:40.190   907  7771 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:14:40.200   907  1171 D lights  : button : 0 -
,07-05 14:14:40.210   907  7771 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Screen bin #0: time=5 power=3.1666666666666666E-5
,07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Screen bin #3: time=9018 power=0.399798
07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Screen bin #4: time=0 power=0.0
07-05 14:14:40.250   907  7771 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:14:40.390   907  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:14:40.390   907  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4272, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:14:40.390   907  1472 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:14:40.390   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:40.390   907   907 I MotionRecognitionService: Plugged
07-05 14:14:40.390   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:40.390  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:40.400  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:40.400  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:14:40.400  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:40.400  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:40.400  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:40.400  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:14:40.400  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:40.470   907  7771 I BatteryStatsDumper: Writing to database completed
,07-05 14:14:40.890   907  3328 D SSRM:a  : DeviceInfo:: 000000100000
,07-05 14:14:40.890   907  3328 D SSRM:a  : SettingsAirViewInfo:: 010100000
,07-05 14:14:41.000   305   305 E SMD     : DCD ON
,07-05 14:14:42.780  1299  1299 I wpa_supplicant: nl80211: Received scan results (17 BSSes)
,07-05 14:14:42.810   907  1147 D WifiP2pService: InactiveState{ what=147461 }
,07-05 14:14:42.810   907  1147 D WifiP2pService: P2pEnabledState{ what=147461 }
07-05 14:14:42.810   907  1147 D WifiP2pService: DefaultState{ what=147461 }
,07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:42.840  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:42.840  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:43.840  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:43.840  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:43.850  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:43.860  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:44.000   305   305 E SMD     : DCD ON
,07-05 14:14:45.860  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:45.860  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:45.860  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:45.860  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:45.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:45.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:45.880  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:45.880  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:45.890  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:45.890  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:47.000   305   305 E SMD     : DCD ON
,07-05 14:14:49.910  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:49.910  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:49.910  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:49.920  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:49.930  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:50.010   305   305 E SMD     : DCD ON
,07-05 14:14:50.170   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:14:50.450   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:14:50.460   907   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:14:50.460   907   924 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:14:50.460   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:14:50.470  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:14:50.470  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:14:50.470  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:14:50.470   907   907 I MotionRecognitionService: Plugged
07-05 14:14:50.470   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:14:50.480  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:50.480  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:50.480  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:14:50.480  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:14:50.480  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:14:51.940  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:51.940  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:51.950  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:51.950  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:51.970  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:52.970  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:52.970  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:52.980  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:52.980  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:52.990  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:53.010   305   305 E SMD     : DCD ON
,07-05 14:14:55.000  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:55.000  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:55.010  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:55.010  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:55.030  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:56.010   305   305 E SMD     : DCD ON
,07-05 14:14:56.040  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:56.040  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:56.040  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:56.040  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:56.060  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:56.060  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:56.060  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:56.060  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:56.070  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:56.070  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:58.070  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:58.080  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:58.080  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:58.080  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:58.090  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:59.010   305   305 E SMD     : DCD ON
,07-05 14:14:59.100  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:14:59.100  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:14:59.110  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:59.110  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:59.120  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:14:59.130  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:59.130  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:59.130  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:59.130  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:14:59.130  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:14:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:15:00.010  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:15:00.010  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:15:00.020  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:15:00.020  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:15:00.080  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:15:00.080  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:15:00.220   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:15:00.510   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:00.510   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4297, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:15:00.510   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:15:00.510   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:00.510   907   907 I MotionRecognitionService: Plugged
07-05 14:15:00.510   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:00.510  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:00.510  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:00.510  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:15:00.510  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 14:15:00.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:00.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:00.510  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:15:00.510  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:01.140  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:15:01.140  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:01.140  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:01.150  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:01.160  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:01.160  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:01.160  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:01.170  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:01.170  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:01.170  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:01.300   907  1333 E Watchdog: !@Sync 25
,07-05 14:15:02.010   305   305 E SMD     : DCD ON
,07-05 14:15:02.170  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:15:02.170  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:02.170  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:02.170  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:02.190  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:02.550   907  1060 D PowerManagerService: [s] UserActivityState : 1 -> 2
,07-05 14:15:02.550   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:15:02.550   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:15:02.560   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,07-05 14:15:02.560   907  1174 D lights  : lcd : 144 +
,07-05 14:15:02.620   907  1174 D lights  : lcd : 144 -
,07-05 14:15:02.630   907  1174 D LightsService: Excessive delay setting light: 61ms
,07-05 14:15:02.630   907  1174 D lights  : lcd : 45 +
,07-05 14:15:02.630   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
,07-05 14:15:02.630   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:15:02.640   907  1174 D lights  : lcd : 45 -
,07-05 14:15:02.640   907  1174 D lights  : lcd : 20 +
,07-05 14:15:02.670   907  1174 D lights  : lcd : 20 -
,07-05 14:15:02.670   907  1060 D DisplayPowerController: getFinalBrightness : 20 -> 20
07-05 14:15:02.670   907  1060 D DisplayPowerController: animation target = 20, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:15:03.200  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:15:03.200  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:03.200  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:03.210  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:03.220  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:03.220  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:03.230  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:03.230  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:15:03.230  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:03.230  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:05.010   305   305 E SMD     : DCD ON
,07-05 14:15:05.240  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:15:05.240  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:05.240  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:05.250  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:05.260  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:05.260  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:05.260  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:05.260  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:05.270  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:05.270  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:07.280  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-05 14:15:07.290  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:07.290  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:07.290  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: applyOpen
07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-05 14:15:07.310  1189  1189 D StatusBar.NetworkController: applyOpen
,07-05 14:15:08.010   305   305 E SMD     : DCD ON
,07-05 14:15:08.550   907  1060 D PowerManagerService: [s] UserActivityState : 2 -> 4
,07-05 14:15:08.550   907  1060 I PowerManagerService: !@[ps] Screen__Off - 2 : timeout (0x4) (2)
,07-05 14:15:08.550   907  1060 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-05 14:15:08.550   907  1170 D InputManager-JNI: setDeviceInteractive: 0
,07-05 14:15:08.560   907  1060 D PowerManagerService: [PWL] sb acquire: PowerManagerService.Broadcasts
,07-05 14:15:08.560   907  1060 D PowerManagerService: SecHardwareInterface.setBatteryADC : false
,07-05 14:15:08.560   907  1060 D PowerManagerService: handleSandman : startDream()
,07-05 14:15:08.570   907  1060 E PowerManagerService: handleSandman : startDreaming, but isDreaming false
,07-05 14:15:08.570   907  1060 I PowerManagerService: Sleeping (uid 1000)...
,07-05 14:15:08.570   907  1060 D PowerManagerService: [s] UserActivityState : 4 -> 0
,07-05 14:15:08.570   907  1060 D PowerManagerService: [input device light] setInputDeviceLightOn is called : 0
,07-05 14:15:08.570   907  1171 D PowerManagerService: [input device light] handleInputDeviceLightOff
,07-05 14:15:08.580   267   267 I SurfaceFlinger: id=14 createSurf (1080x1920),2 flag=404, DolorFade
,07-05 14:15:08.580   907  7796 D InputManager-JNI: sysfs_write +: /sys/class/input/event2/device/enabled: 0
,07-05 14:15:08.610   907  7795 D InputManager-JNI: sysfs_write +: /sys/class/input/event3/device/enabled: 0
,07-05 14:15:08.610   907  7796 D InputManager-JNI: sysfs_write -: /sys/class/input/event2/device/enabled: 0
,07-05 14:15:08.610   907  7794 D InputManager-JNI: sysfs_write +: /sys/class/input/event4/device/enabled: 0
,07-05 14:15:08.610   907  7795 D InputManager-JNI: sysfs_write -: /sys/class/input/event3/device/enabled: 0
,07-05 14:15:08.620   907  7794 D InputManager-JNI: sysfs_write -: /sys/class/input/event4/device/enabled: 0
,07-05 14:15:08.620   907  1170 D SContextService: 	.unregisterCallback : 1, client=
,07-05 14:15:08.630   907  1170 D SContextService: unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@11d5c731, Service = Auto Rotation, used = 1
,07-05 14:15:08.630   907  1170 W CAE     : unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,07-05 14:15:08.630   907  1170 V CAE     : stop(ContextProvider.java:149)
,07-05 14:15:08.630   907  1170 V CAE     : clear(AutoRotationRunner.java:182)
,07-05 14:15:08.640   907  1170 V CAE     : disable(AutoRotationRunner.java:171)
,07-05 14:15:08.640   907  1170 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,07-05 14:15:08.640   907  1170 D SensorHubManager: SendSensorHubData: send data = -78, 7, 0, 0
,07-05 14:15:08.640   322   578 D Sensorhubs: sendContextData: -78, 7, 0, 0
,07-05 14:15:08.660   907  1170 D CAE     : getFaultDetectionResult(AutoRotationRunner.java:195) - true
,07-05 14:15:08.660   907  1170 I CAE     : notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,07-05 14:15:08.680   907  1060 D DisplayPowerController: ColorFade: onAnimationStart
,07-05 14:15:08.680   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 0
07-05 14:15:08.680   907  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:15:08.700   907  1174 D lights  : lcd : 16 +
,07-05 14:15:08.720   907  1170 D CAE     : doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,07-05 14:15:08.720   907  1170 I CAE     : displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
07-05 14:15:08.720   907  1170 D CAE     : showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,07-05 14:15:08.720   907  1170 W CAE     : unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
07-05 14:15:08.720   907  1170 D SContextService: removeSContextService() : service = Auto Rotation
07-05 14:15:08.720   907  1170 D SContextService: ===== SContext Service List =====
07-05 14:15:08.720   907  1170 D SContextManager:   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1bb90e69, service=Auto Rotation
,07-05 14:15:08.720  1189  1207 D KeyguardViewMediator: onScreenTurnedOff(3)
07-05 14:15:08.720  1189  1207 I KeyguardEffectViewController: *** KeyguardEffectView getInstanceIfExists ***
,07-05 14:15:08.720  1189  1207 D KeyguardEffectViewController: changeWallpaperByScreenOff()
07-05 14:15:08.720  1189  1207 D KeyguardViewMediator: notifyScreenOffLocked
,07-05 14:15:08.730  1189  1207 D KeyguardViewMediator: timeout : 5000
,07-05 14:15:08.730  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-05 14:15:08.730  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-05 14:15:08.740   907  1174 D lights  : lcd : 16 -
,07-05 14:15:08.750  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f1b4069 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@2cb03ed3, 16908290=android.view.AbsSavedState$1@2cb03ed3}, android:focusedViewId=100}]}]
,07-05 14:15:08.750  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-05 14:15:08.750  7114  7114 V ActivityThread: updateVisibility : ActivityRecord{8d4b008 token=android.os.BinderProxy@364f77fa {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
07-05 14:15:08.750   907  1060 D DisplayPowerController: getFinalBrightness : 162 -> 0
,07-05 14:15:08.750   907  1060 D DisplayPowerController: animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:15:08.750  7114  7114 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-05 14:15:08.750  7114  7114 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-05 14:15:08.760   907  1174 D lights  : lcd : 0 +
,07-05 14:15:08.760  1189  1207 D KeyguardViewMediator: setting alarm to turn off keyguard, seq = 3
07-05 14:15:08.760  1189  1189 D KeyguardViewMediator: handleNotifyScreenOff
,07-05 14:15:08.770   907   907 D LightsService: [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 907) 
,07-05 14:15:08.770   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,07-05 14:15:08.770   907   907 E LightSensor: Light old sensor_state 0, new sensor_state : 512 en : 1
,07-05 14:15:08.780   907   907 D SensorManager: registerListener :: 6, MAX88921 RGB Sensor, 200000, 0,  
07-05 14:15:08.780   907   907 D BatteryService: turn on LED for fully charged
,07-05 14:15:08.780   907   907 I CAE     : handleMessage(CaPowerManager.java:182) - AP_SLEEP
,07-05 14:15:08.780   907   907 I CAE     : updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
07-05 14:15:08.780   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
07-05 14:15:08.780   907   907 D SensorHubManager: SendSensorHubData: send data = -76, 13, -46, 0
07-05 14:15:08.780   322   322 D Sensorhubs: sendContextData: -76, 13, -46, 0
,07-05 14:15:08.790   907  1174 D lights  : lcd : 0 -
,07-05 14:15:08.790   907   907 I CAE     : sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 12, 15, 8,
,07-05 14:15:08.790   907   907 D SensorHubManager: SendSensorHubData: send data = -63, 14, 12, 15, 8
07-05 14:15:08.790   322   578 D Sensorhubs: sendContextData: -63, 14, 12, 15, 8
,07-05 14:15:08.800   907   907 D MotionRecognitionService:   mReceiver.onReceive : ACTION_SCREEN_OFF
,07-05 14:15:08.810   907  1126 E MotionRecognitionService:  handler : SCREEN_OFF end 
,07-05 14:15:08.810   907   907 D NotificationService: ACTION_SCREEN_OFF
,07-05 14:15:08.810   907   907 D LightsService: [api] [SvcLED] setFlashing :: id = 4, color = ffffffff, mode = 12, onMS = 500, offMS = 2000,  (uid: 1000 pid: 907) 
07-05 14:15:08.810   907   907 D LightsService: [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x42 | SvcLED(id=4) set On
,07-05 14:15:08.820   907  1148 E native  : do suspend true
,07-05 14:15:08.820   310  6322 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
07-05 14:15:08.820   310  6322 V voice   : voice_set_parameters: enter: screen_state=off
07-05 14:15:08.820   310  6322 V voice   : voice_set_parameters: exit with code(-2)
07-05 14:15:08.820   310  6322 V msm8974_platform: platform_set_parameters: enter: screen_state=off
07-05 14:15:08.820   310  6322 V msm8974_platform: platform_set_parameters: exit with code(-2)
,07-05 14:15:08.820   310  6322 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-05 14:15:08.820   310  6322 V audio_hw_primary: adev_set_parameters: exit
,07-05 14:15:08.840   907   907 I SecExternalDisplayIntents_Java: Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,07-05 14:15:08.840   907   907 I BackgroundCompactionService: Schedule Type1 BGCompaction
,07-05 14:15:08.860   907  1058 D IpRemoteDisplayController: intent received android.intent.action.SCREEN_OFF
,07-05 14:15:08.860   907  1058 D IpRemoteDisplayController: Bridge Server is not available
,07-05 14:15:08.870  1189  1189 D VolumePanel.2cc5a711: forceTimeout delay=0 callers=com.android.systemui.volume.VolumePanel.postDismiss:2103 com.android.systemui.volume.VolumePanel$8.onReceive:1167 android.app.LoadedApk$ReceiverDispatcher$Args.run:923 
,07-05 14:15:08.870  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 14:15:08.870  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF start
07-05 14:15:08.870  1189  1189 D VolumePanel: mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,07-05 14:15:08.870  1189  1189 D VolumePanel: mCoverBroadcastReceiver: Screen OFF end
,07-05 14:15:08.870  1189  1189 D VolumePanel: mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,07-05 14:15:08.900   907  1060 D DisplayPowerState: !@ ColorFade entry
,07-05 14:15:08.900   907  1060 D DisplayPowerController: ColorFade: onAnimationEnd
,07-05 14:15:08.900   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:15:08.900   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,07-05 14:15:08.900   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:15:08.900   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:15:08.900   907  1060 D DisplayPowerController: getFinalBrightness : 0 -> 0
07-05 14:15:08.900   907  1060 D DisplayPowerController: animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
07-05 14:15:08.900   907  1060 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
07-05 14:15:08.900   907  1060 D PowerManagerService: [PWL] sb release: PowerManagerService.Display
,07-05 14:15:08.910   907  1058 I DisplayManagerService: Display device changed: DisplayDeviceInfo{"Built-in Screen": 1080 x 1920, 60.0 fps, supportedRefreshRates [60.0], density 480, 386.366 x 387.047 dpi, appVsyncOff 0, presDeadline 17666667, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,07-05 14:15:08.910   907   907 V ActivityManager: Display changed displayId=0
,07-05 14:15:08.910   267   267 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6a62000
07-05 14:15:08.910   267   267 D qdhwcomposer: hwc_blank: Blanking display: 0
,07-05 14:15:08.930  1189  1189 D StatusBar.NetworkController: onSignalStrengthsChanged signalStrength=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte level=0
07-05 14:15:08.930  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-05 14:15:08.930  1189  1189 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-05 14:15:08.930  1189  1189 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-05 14:15:08.930  1189  1189 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-05 14:15:09.150   907  1092 D LightsService: [SvcLED]  onSensorChanged::light value = 40
,07-05 14:15:09.150   907  1092 E LightSensor: Light old sensor_state 512, new sensor_state : 0 en : 0
,07-05 14:15:09.160   907  1092 D SensorManager: unregisterListener ::   
,07-05 14:15:09.160   907  1092 D lights  : led_pattern : 3 +
,07-05 14:15:09.160   907  1092 D lights  : led_pattern : 3 -
,07-05 14:15:09.160   907  1092 D LightsService: [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=4) maintains its priority right
,07-05 14:15:09.180   267   525 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-05 14:15:09.180   267   267 D qdhwcomposer: hwc_blank: Done blanking display: 0
07-05 14:15:09.180   907  1175 D SurfaceControl: Excessive delay in setPowerMode(): 277ms
07-05 14:15:09.180   907  1175 D PowerManagerService: !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
07-05 14:15:09.180   907  1175 D MISC PowerHAL: sysfs_write +: /sys/class/power_supply/battery/lcd: 0
07-05 14:15:09.180   907  1175 D MISC PowerHAL: sysfs_write -: /sys/class/power_supply/battery/lcd: 0
07-05 14:15:09.180   907  1175 I QCOM PowerHAL: Got set_interactive hint
,07-05 14:15:09.180   907  1175 D PowerManagerService: Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 280ms
07-05 14:15:09.180   907  1060 I PowerManagerService: [PWL] Off : 0s ago
,07-05 14:15:09.180   907  1060 I PowerManagerService: [PWL]   PowerManagerService.Broadcasts: ref count=1
,07-05 14:15:09.810   907   991 D GpsLocationProvider: receive broadcast intent, action: android.intent.action.SCREEN_OFF
,07-05 14:15:09.810   907   907 D PersonaManagerService: ACTION_SCREEN_OFF onReceive
07-05 14:15:09.810   907  1067 D PersonaManagerServiceHandler: MSG_ACTION_SCREEN_OFF called
,07-05 14:15:09.810  1409  1409 D NativeNfcManager: power state=2
07-05 14:15:09.810  1409  1409 D BrcmNfcJni: PowerSwitch::com_android_nfc_NativeNfcManager_doSetPowerMode: mode=0x2; screen off
,07-05 14:15:09.820  1189  1189 D STATUSBAR-PhoneStatusBar:      ACTION_SCREEN_OFF is finished!!!! 
,07-05 14:15:09.820  1409  1605 D NfcService: call the applyRouting
,07-05 14:15:09.850  1755  1755 D accuweather: [Accuweather J]>>> SWW:81 [0:0] =============== BR act = androidintentactionSCREEN_OFF
,07-05 14:15:09.890   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:15:09.910   907  1655 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:15:09.910   907  1093 W ActivityManager: getTasks: caller 10102 does not hold GET_TASKS; limiting output
,07-05 14:15:09.910   907  1170 D PowerManagerService: [PWL] sb release: PowerManagerService.Broadcasts
,07-05 14:15:09.930   907  3328 D SSRM:n  : SIOP:: AP = 320, PST = 312, CUR = 300
,07-05 14:15:10.020   907  7832 I BatteryStatsDumper: In refreshStats isReason Screen ON/OFF: true
,07-05 14:15:10.060   907  7832 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:15:10.110   907  7832 D NetworkStatsFactory: UpdateStatsForKnox
,07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Screen bin #0: time=5 power=3.1666666666666666E-5
07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Screen bin #1: time=0 power=0.0
07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Screen bin #2: time=0 power=0.0
07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Screen bin #3: time=9018 power=0.399798
07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Screen bin #4: time=0 power=0.0
07-05 14:15:10.170   907  7832 I BatteryStatsDumper: Previous Battery Level: 100 Current Level: 100 Delta: 0
,07-05 14:15:10.340   907  7832 I BatteryStatsDumper: Writing to database completed
,07-05 14:15:11.010   305   305 E SMD     : DCD ON
,07-05 14:15:13.760   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:15:13.810   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:13.810   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 291, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:15:13.810   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:15:13.810   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:15:13.810   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:15:13.840   907   907 I MotionRecognitionService: Plugged
,07-05 14:15:13.840   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:13.840  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:13.840  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:13.850  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:15:13.850  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:13.850  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:13.850  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:13.850  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:13.850  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:15:13.860  1189  1189 D KeyguardViewMediator: received DELAYED_KEYGUARD_ACTION with seq = 3, mDelayedShowingSequence = 3
,07-05 14:15:13.860  1189  1189 D PersonaManager: isKioskContainerExistOnDevice
,07-05 14:15:13.860  1189  1189 D KeyguardViewMediator: doKeyguard: not showing because lockscreen is off
,07-05 14:15:14.010   305   305 E SMD     : DCD ON
,07-05 14:15:14.180   907  1060 I PowerManagerService: [PWL] Off : 5s ago
,07-05 14:15:17.010   305   305 E SMD     : DCD ON
,07-05 14:15:18.840   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:15:18.880   907  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-05 14:15:18.890   907  1466 D ActivityManager: caller:android.app.ApplicationThreadProxy@4cb08c6, r.packageName :com.google.android.gms
,07-05 14:15:18.940  2452  7838 I EventLogChimeraService: Aggregate from 1467718787870 (log), 1467718787870 (data)
,07-05 14:15:19.040   907  1466 D ActivityManager: caller:android.app.ApplicationThreadProxy@13095e23, r.packageName :com.google.android.gms
,07-05 14:15:19.070   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d7ac0d9, r.packageName :com.google.android.gms
,07-05 14:15:19.130  2452  7839 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 14:15:19.140  2452  7839 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,07-05 14:15:19.980   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:15:20.010   305   305 E SMD     : DCD ON
,07-05 14:15:21.840   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:15:23.010   305   305 E SMD     : DCD ON
,07-05 14:15:23.890   907   922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:24.190   907  1060 I PowerManagerService: [PWL] Off : 15s ago
,07-05 14:15:26.010   305   305 E SMD     : DCD ON
,07-05 14:15:29.020   305   305 E SMD     : DCD ON
,07-05 14:15:30.030   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:15:31.130   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:15:31.310   907  1333 E Watchdog: !@Sync 26
,07-05 14:15:32.020   305   305 E SMD     : DCD ON
,07-05 14:15:35.020   305   305 E SMD     : DCD ON
,07-05 14:15:38.020   305   305 E SMD     : DCD ON
,07-05 14:15:39.190   907  1060 I PowerManagerService: [PWL] Off : 30s ago
,07-05 14:15:39.890   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:15:39.920   907  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-05 14:15:39.950   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:39.950   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:15:39.950   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:15:39.950   907  1655 D BatteryService: stay LED for fully charged
,07-05 14:15:39.950   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:39.960  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:39.960  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:39.960   907   907 I MotionRecognitionService: Plugged
07-05 14:15:39.960   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:39.960  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:15:39.960  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:39.970  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:39.970  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:15:39.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:39.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:39.980   907   907 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
,07-05 14:15:39.990   907   907 I BackgroundCompactionService: onStart. jobID=801
,07-05 14:15:39.990   907   907 I BackgroundCompactionService: onStart done. jobID=801
,07-05 14:15:40.000   907  7859 I BackgroundCompactionService: Execute BGCompaction (type1). (2 times)
,07-05 14:15:40.000   907  7859 I BackgroundCompactionService: compact_memory command done
,07-05 14:15:40.100   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:15:41.020   305   305 E SMD     : DCD ON
,07-05 14:15:44.020   305   305 E SMD     : DCD ON
,07-05 14:15:47.020   305   305 E SMD     : DCD ON
,07-05 14:15:50.010   907   922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:15:50.010   907   922 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:15:50.020   907   922 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:15:50.020   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:15:50.020   305   305 E SMD     : DCD ON
,07-05 14:15:50.030   907   907 I MotionRecognitionService: Plugged
,07-05 14:15:50.030   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:15:50.040  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:15:50.040  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:15:50.040   907   922 D BatteryService: stay LED for fully charged
,07-05 14:15:50.060  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:15:50.060  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:50.070  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:50.070  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:15:50.080  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:15:50.080  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:15:50.140   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:15:53.020   305   305 E SMD     : DCD ON
,07-05 14:15:56.020   305   305 E SMD     : DCD ON
,07-05 14:15:59.020   305   305 E SMD     : DCD ON
,07-05 14:15:59.200   907  1060 I PowerManagerService: [PWL] Off : 50s ago
,07-05 14:15:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:16:00.070   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:00.190   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:16:01.310   907  1333 E Watchdog: !@Sync 27
,07-05 14:16:02.030   305   305 E SMD     : DCD ON
,07-05 14:16:05.030   305   305 E SMD     : DCD ON
,07-05 14:16:08.030   305   305 E SMD     : DCD ON
,07-05 14:16:10.130   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:10.240   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 312, CUR = 300
,07-05 14:16:11.030   305   305 E SMD     : DCD ON
,07-05 14:16:14.030   305   305 E SMD     : DCD ON
,07-05 14:16:17.030   305   305 E SMD     : DCD ON
,07-05 14:16:20.030   305   305 E SMD     : DCD ON
,07-05 14:16:20.190   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:20.190   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:20.200   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:16:20.200   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:20.210  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:20.210  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:20.220   907   907 I MotionRecognitionService: Plugged
,07-05 14:16:20.220   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:20.230   907  1655 D BatteryService: stay LED for fully charged
,07-05 14:16:20.240  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:20.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:20.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:20.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:20.250  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:20.250  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:20.290   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:16:23.030   305   305 E SMD     : DCD ON
,07-05 14:16:24.200   907  1060 I PowerManagerService: [PWL] Off : 75s ago
,07-05 14:16:26.030   305   305 E SMD     : DCD ON
,07-05 14:16:29.030   305   305 E SMD     : DCD ON
,07-05 14:16:30.250   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:30.260   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:30.260   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:16:30.260   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:30.270  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:30.270  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:30.280   907   907 I MotionRecognitionService: Plugged
,07-05 14:16:30.280   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:30.290   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:16:30.290  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:30.290  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.290  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.300  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:30.300  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:30.300  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:30.340   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:16:31.310   907  1333 E Watchdog: !@Sync 28
,07-05 14:16:32.030   305   305 E SMD     : DCD ON
,07-05 14:16:35.030   305   305 E SMD     : DCD ON
,07-05 14:16:38.040   305   305 E SMD     : DCD ON
,07-05 14:16:38.750  1870  3200 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-05 14:16:40.310   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:40.310   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:40.320   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:16:40.320   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:40.330  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:40.330  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:40.340   907   907 I MotionRecognitionService: Plugged
,07-05 14:16:40.340   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:40.340   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:16:40.360  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:40.360  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:40.370  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:40.370  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:40.380  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:40.380  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:40.400   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 311, CUR = 300
,07-05 14:16:41.040   305   305 E SMD     : DCD ON
,07-05 14:16:44.040   305   305 E SMD     : DCD ON
,07-05 14:16:47.040   305   305 E SMD     : DCD ON
,07-05 14:16:50.040   305   305 E SMD     : DCD ON
,07-05 14:16:50.370   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:16:50.380   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:16:50.380   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:16:50.380   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:16:50.390  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:16:50.400  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:16:50.400   907   907 I MotionRecognitionService: Plugged
,07-05 14:16:50.400   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:16:50.410   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:16:50.430  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:16:50.430  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:50.440  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:50.440  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:16:50.440  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:16:50.440  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:16:50.460   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:16:53.040   305   305 E SMD     : DCD ON
,07-05 14:16:54.200   907  1060 I PowerManagerService: [PWL] Off : 105s ago
,07-05 14:16:56.040   305   305 E SMD     : DCD ON
,07-05 14:16:59.040   305   305 E SMD     : DCD ON
,07-05 14:17:00.500   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:01.320   907  1333 E Watchdog: !@Sync 29
,07-05 14:17:02.040   305   305 E SMD     : DCD ON
,07-05 14:17:05.040   305   305 E SMD     : DCD ON
,07-05 14:17:08.040   305   305 E SMD     : DCD ON
,07-05 14:17:08.870   907  1113 V AlarmManager: waitForAlarm result :4
,07-05 14:17:08.890  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:17:08.900  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:17:08.900  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:17:08.910  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:17:08.940   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:08.940   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:17:08.940   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:17:08.940   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:17:08.950   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:08.960  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:08.960  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:08.960  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:08.970  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:08.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:17:08.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:08.970   907   907 I MotionRecognitionService: Plugged
07-05 14:17:08.970   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:08.970  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:08.980  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:08.990  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:17:09.000  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:17:10.550   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:11.040   305   305 E SMD     : DCD ON
,07-05 14:17:14.050   305   305 E SMD     : DCD ON
,07-05 14:17:17.050   305   305 E SMD     : DCD ON
,07-05 14:17:19.000   907  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:20.050   305   305 E SMD     : DCD ON
,07-05 14:17:20.610   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:23.050   305   305 E SMD     : DCD ON
,07-05 14:17:26.050   305   305 E SMD     : DCD ON
,07-05 14:17:29.050   305   305 E SMD     : DCD ON
,07-05 14:17:29.060   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:29.060   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:17:29.070   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:17:29.070   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:29.080  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:29.080  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:29.090   907   907 I MotionRecognitionService: Plugged
,07-05 14:17:29.090   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:29.090   907  1636 D BatteryService: stay LED for fully charged
,07-05 14:17:29.090  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:29.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:29.100  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:29.100  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:29.100  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:29.100  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:29.210   907  1060 I PowerManagerService: [PWL] Off : 140s ago
,07-05 14:17:29.260   907  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:17:29.260   907  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:17:29.270   907  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:17:30.670   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:31.320   907  1333 E Watchdog: !@Sync 30
,07-05 14:17:32.050   305   305 E SMD     : DCD ON
,07-05 14:17:32.290   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:17:32.290   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:17:32.310   907  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:32.310   907  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:17:35.050   305   305 E SMD     : DCD ON
,07-05 14:17:38.050   305   305 E SMD     : DCD ON
,07-05 14:17:39.120   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:39.130   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:17:39.130   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:17:39.130   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:39.140  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:39.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:39.150   907   907 I MotionRecognitionService: Plugged
,07-05 14:17:39.150   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:39.160   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:17:39.160  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:39.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:39.170  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:39.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:39.190  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:39.190  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:40.720   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:41.050   305   305 E SMD     : DCD ON
,07-05 14:17:44.050   305   305 E SMD     : DCD ON
,07-05 14:17:47.050   305   305 E SMD     : DCD ON
,07-05 14:17:49.190   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:17:49.190   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:17:49.190   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:17:49.200   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:17:49.210  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:17:49.210  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:17:49.210   907   907 I MotionRecognitionService: Plugged
,07-05 14:17:49.220   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:17:49.230   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:17:49.240  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:17:49.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:49.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:49.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:17:49.250  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:17:49.250  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:17:50.060   305   305 E SMD     : DCD ON
,07-05 14:17:50.760   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:17:53.060   305   305 E SMD     : DCD ON
,07-05 14:17:56.060   305   305 E SMD     : DCD ON
,07-05 14:17:59.060   305   305 E SMD     : DCD ON
,07-05 14:18:00.010   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:18:00.060   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:00.060   907   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 289, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:00.070   907   924 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:18:00.070   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:00.080  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:00.080  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:00.090   907   907 I MotionRecognitionService: Plugged
,07-05 14:18:00.090   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:00.100   907   924 D BatteryService: stay LED for fully charged
,07-05 14:18:00.110  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:00.110  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:00.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:00.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:00.130  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:00.130  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:00.810   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:18:01.320   907  1333 E Watchdog: !@Sync 31
,07-05 14:18:02.060   305   305 E SMD     : DCD ON
,07-05 14:18:05.060   305   305 E SMD     : DCD ON
,07-05 14:18:08.060   305   305 E SMD     : DCD ON
,07-05 14:18:09.210   907  1060 I PowerManagerService: [PWL] Off : 180s ago
,07-05 14:18:10.120   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:10.130   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:18:10.130   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:18:10.130   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:18:10.140   907   907 I MotionRecognitionService: Plugged
,07-05 14:18:10.140  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:18:10.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:18:10.150   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:18:10.160   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:18:10.170  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:18:10.180  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:10.190  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:10.190  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:18:10.190  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:18:10.190  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:18:10.860   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:18:11.060   305   305 E SMD     : DCD ON
,07-05 14:18:14.060   305   305 E SMD     : DCD ON
,07-05 14:18:17.060   305   305 E SMD     : DCD ON
,07-05 14:18:20.060   305   305 E SMD     : DCD ON
,07-05 14:18:20.180   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:20.910   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 300
,07-05 14:18:23.060   305   305 E SMD     : DCD ON
,07-05 14:18:26.070   305   305 E SMD     : DCD ON
,07-05 14:18:29.070   305   305 E SMD     : DCD ON
,07-05 14:18:30.260   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:30.950   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 309, CUR = 300
,07-05 14:18:31.330   907  1333 E Watchdog: !@Sync 32
,07-05 14:18:32.070   305   305 E SMD     : DCD ON
,07-05 14:18:35.070   305   305 E SMD     : DCD ON
,07-05 14:18:38.070   305   305 E SMD     : DCD ON
,07-05 14:18:40.320   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:41.000   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 308, CUR = 300
,07-05 14:18:41.070   305   305 E SMD     : DCD ON
,07-05 14:18:44.070   305   305 E SMD     : DCD ON
,07-05 14:18:47.070   305   305 E SMD     : DCD ON
,07-05 14:18:50.070   305   305 E SMD     : DCD ON
,07-05 14:18:50.390   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:18:51.040   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 307, CUR = 300
,07-05 14:18:53.070   305   305 E SMD     : DCD ON
,07-05 14:18:54.210   907  1060 I PowerManagerService: [PWL] Off : 225s ago
,07-05 14:18:56.070   305   305 E SMD     : DCD ON
,07-05 14:18:59.070   305   305 E SMD     : DCD ON
,07-05 14:19:00.460   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:00.460   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:00.460   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:00.470   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:00.470  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:00.480  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:00.480   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:00.490   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:00.490   907  1240 D BatteryService: stay LED for fully charged
,07-05 14:19:00.490  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:00.490  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:00.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:00.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:00.500  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:00.500  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:01.100   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 306, CUR = 300
,07-05 14:19:01.330   907  1333 E Watchdog: !@Sync 33
,07-05 14:19:02.080   305   305 E SMD     : DCD ON
,07-05 14:19:05.080   305   305 E SMD     : DCD ON
,07-05 14:19:08.080   305   305 E SMD     : DCD ON
,07-05 14:19:10.520   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:10.530   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:10.530   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:10.530   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:10.540  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:10.540  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:10.550   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:10.550   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:10.560   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:19:10.570  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:10.590  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:10.590  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:10.590  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:10.590  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:10.590  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:11.080   305   305 E SMD     : DCD ON
,07-05 14:19:11.150   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 305, CUR = 300
,07-05 14:19:14.080   305   305 E SMD     : DCD ON
,07-05 14:19:17.080   305   305 E SMD     : DCD ON
,07-05 14:19:20.080   305   305 E SMD     : DCD ON
,07-05 14:19:20.590   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:20.590   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:20.590   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:20.600   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:20.610  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:20.610  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:20.610   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:20.620   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:20.620   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:19:20.640  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:20.640  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:20.640  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:20.640  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:20.650  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:20.650  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:21.190   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 304, CUR = 300
,07-05 14:19:23.080   305   305 E SMD     : DCD ON
,07-05 14:19:26.080   305   305 E SMD     : DCD ON
,07-05 14:19:29.080   305   305 E SMD     : DCD ON
,07-05 14:19:30.650   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:30.660   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:30.660   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:30.660   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:30.670  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:30.670  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:30.680   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:30.690   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:30.690   907  1636 D BatteryService: stay LED for fully charged
,07-05 14:19:30.690  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:30.690  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:30.690  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:30.700  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:30.700  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:30.700  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:31.240   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 303, CUR = 300
,07-05 14:19:31.330   907  1333 E Watchdog: !@Sync 34
,07-05 14:19:32.080   305   305 E SMD     : DCD ON
,07-05 14:19:35.080   305   305 E SMD     : DCD ON
,07-05 14:19:38.090   305   305 E SMD     : DCD ON
,07-05 14:19:40.710   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:40.720   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:40.720   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:40.720   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:40.730   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:40.730  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:40.740  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:40.740   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:40.740   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:19:40.760  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:40.760  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:40.770  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:40.770  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:40.780  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:40.780  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:41.090   305   305 E SMD     : DCD ON
,07-05 14:19:41.290   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 302, CUR = 300
,07-05 14:19:44.090   305   305 E SMD     : DCD ON
,07-05 14:19:44.210   907  1060 I PowerManagerService: [PWL] Off : 275s ago
,07-05 14:19:47.090   305   305 E SMD     : DCD ON
,07-05 14:19:50.090   305   305 E SMD     : DCD ON
,07-05 14:19:50.770   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:19:50.780   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:19:50.780   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:19:50.780   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:19:50.790  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:19:50.790  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:19:50.800   907   907 I MotionRecognitionService: Plugged
,07-05 14:19:50.800   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:19:50.810   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:19:50.830  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:19:50.830  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:50.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:50.840  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:19:50.850  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:19:50.850  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:19:51.340   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:19:53.090   305   305 E SMD     : DCD ON
,07-05 14:19:56.090   305   305 E SMD     : DCD ON
,07-05 14:19:59.090   305   305 E SMD     : DCD ON
,07-05 14:20:00.830   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:00.840   907   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:00.840   907   924 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:20:00.840   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:00.850  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:00.850  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:00.860   907   907 I MotionRecognitionService: Plugged
,07-05 14:20:00.860   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:00.870   907   924 D BatteryService: stay LED for fully charged
,07-05 14:20:00.890  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:00.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:00.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:00.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:00.890  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:00.900  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:01.340   907  1333 E Watchdog: !@Sync 35
,07-05 14:20:01.390   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:02.090   305   305 E SMD     : DCD ON
,07-05 14:20:05.090   305   305 E SMD     : DCD ON
,07-05 14:20:08.090   305   305 E SMD     : DCD ON
,07-05 14:20:10.900   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:10.900   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:10.900   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:20:10.910   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:10.920  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:10.920  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:10.920   907   907 I MotionRecognitionService: Plugged
,07-05 14:20:10.930   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:10.940   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:20:10.940  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:10.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:10.950  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:10.950  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:10.950  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:10.950  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:11.090   305   305 E SMD     : DCD ON
,07-05 14:20:11.430   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:14.100   305   305 E SMD     : DCD ON
,07-05 14:20:17.100   305   305 E SMD     : DCD ON
,07-05 14:20:20.100   305   305 E SMD     : DCD ON
,07-05 14:20:20.960   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:21.510   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:23.100   305   305 E SMD     : DCD ON
,07-05 14:20:26.100   305   305 E SMD     : DCD ON
,07-05 14:20:29.100   305   305 E SMD     : DCD ON
,07-05 14:20:31.030   907  1093 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:31.030   907  1093 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:31.030   907  1093 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:20:31.040   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:31.040  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:31.050  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:31.060   907   907 I MotionRecognitionService: Plugged
,07-05 14:20:31.060   907  1093 D BatteryService: stay LED for fully charged
,07-05 14:20:31.070  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:31.080   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:31.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:31.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:31.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:31.100  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:31.100  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:31.340   907  1333 E Watchdog: !@Sync 36
,07-05 14:20:31.560   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:32.100   305   305 E SMD     : DCD ON
,07-05 14:20:35.100   305   305 E SMD     : DCD ON
,07-05 14:20:38.100   305   305 E SMD     : DCD ON
,07-05 14:20:39.220   907  1060 I PowerManagerService: [PWL] Off : 330s ago
,07-05 14:20:41.090   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:41.100   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:20:41.100   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:20:41.100   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:20:41.110   305   305 E SMD     : DCD ON
,07-05 14:20:41.110  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:20:41.120  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:20:41.130   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:20:41.140   907   907 I MotionRecognitionService: Plugged
,07-05 14:20:41.140  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:20:41.140   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:20:41.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:41.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:41.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:20:41.150  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:20:41.150  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:20:41.600   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:44.110   305   305 E SMD     : DCD ON
,07-05 14:20:47.110   305   305 E SMD     : DCD ON
,07-05 14:20:50.110   305   305 E SMD     : DCD ON
,07-05 14:20:51.150   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:20:51.670   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:20:51.920   907   919 I art     : Background partial concurrent mark sweep GC freed 124374(8MB) AllocSpace objects, 118(2MB) LOS objects, 29% free, 37MB/53MB, paused 1.877ms total 232.242ms
,07-05 14:20:53.110   305   305 E SMD     : DCD ON
,07-05 14:20:56.110   305   305 E SMD     : DCD ON
,07-05 14:20:59.110   305   305 E SMD     : DCD ON
,07-05 14:21:00.010   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:21:00.020  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-05 14:21:00.030  1189  1189 D KeyguardUpdateMonitor: handleTimeUpdate
,07-05 14:21:00.030  1189  1189 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-05 14:21:00.030  1189  1189 I KeyguardEffectViewController: *** don't update sliding image ***
,07-05 14:21:00.120  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:21:00.120  1189  1189 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-05 14:21:01.210   907  1472 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:01.220   907  1472 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:01.220   907  1472 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:21:01.220   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:01.230  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:01.230  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:01.240   907   907 I MotionRecognitionService: Plugged
,07-05 14:21:01.240   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:01.250   907  1472 D BatteryService: stay LED for fully charged
,07-05 14:21:01.260  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:01.270  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:01.270  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:01.280  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:01.280  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:01.280  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:01.340   907  1333 E Watchdog: !@Sync 37
,07-05 14:21:01.730   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:02.110   305   305 E SMD     : DCD ON
,07-05 14:21:05.110   305   305 E SMD     : DCD ON
,07-05 14:21:08.110   305   305 E SMD     : DCD ON
,07-05 14:21:11.110   305   305 E SMD     : DCD ON
,07-05 14:21:11.270   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:11.280   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:11.280   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:21:11.280   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:11.300  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:11.300  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:11.300   907   907 I MotionRecognitionService: Plugged
,07-05 14:21:11.310   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:11.310   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:21:11.330  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:11.340  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:11.340  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:21:11.340  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:11.340  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:11.340  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:11.830   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:14.110   305   305 E SMD     : DCD ON
,07-05 14:21:17.120   305   305 E SMD     : DCD ON
,07-05 14:21:20.120   305   305 E SMD     : DCD ON
,07-05 14:21:21.330   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:21.340   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:21.340   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:21:21.340   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:21.350  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:21.350  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:21.360   907   907 I MotionRecognitionService: Plugged
,07-05 14:21:21.360   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:21.370   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:21:21.380  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:21.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:21.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:21.390  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:21.390  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:21.400  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:21.880   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:23.120   305   305 E SMD     : DCD ON
,07-05 14:21:26.120   305   305 E SMD     : DCD ON
,07-05 14:21:29.120   305   305 E SMD     : DCD ON
,07-05 14:21:31.340   907  1333 E Watchdog: !@Sync 38
,07-05 14:21:31.410   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:31.920   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:32.120   305   305 E SMD     : DCD ON
,07-05 14:21:35.120   305   305 E SMD     : DCD ON
,07-05 14:21:38.120   305   305 E SMD     : DCD ON
,07-05 14:21:39.220   907  1060 I PowerManagerService: [PWL] Off : 390s ago
,07-05 14:21:41.120   305   305 E SMD     : DCD ON
,07-05 14:21:41.470   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:41.470   907  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:41.470   907  1377 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:21:41.480   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:41.490   907   907 I MotionRecognitionService: Plugged
,07-05 14:21:41.500  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:41.500  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:41.500   907  1377 D BatteryService: stay LED for fully charged
,07-05 14:21:41.520   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:41.520  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:41.530  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:41.540  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:41.540  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:41.550  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:41.550  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:41.970   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:44.120   305   305 E SMD     : DCD ON
,07-05 14:21:47.120   305   305 E SMD     : DCD ON
,07-05 14:21:50.120   305   305 E SMD     : DCD ON
,07-05 14:21:51.530   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:21:51.540   907  1240 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:21:51.540   907  1240 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:21:51.550   907  1240 D BatteryService: stay LED for fully charged
,07-05 14:21:51.550   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:21:51.560  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:21:51.560  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:21:51.570   907   907 I MotionRecognitionService: Plugged
,07-05 14:21:51.580   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:21:51.590  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:21:51.590  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:51.600  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:51.600  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:21:51.600  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:21:51.600  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:21:52.020   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:21:53.130   305   305 E SMD     : DCD ON
,07-05 14:21:56.130   305   305 E SMD     : DCD ON
,07-05 14:21:59.130   305   305 E SMD     : DCD ON
,07-05 14:21:59.990   907  1113 V AlarmManager: waitForAlarm result :8
,07-05 14:22:01.350   907  1333 E Watchdog: !@Sync 39
,07-05 14:22:01.590   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:01.600   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:01.620   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:01.630   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:22:01.640   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:01.640  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:01.650  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:01.650  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:22:01.650  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:01.650  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:01.650  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:01.650  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:22:01.650  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:01.650   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:01.650   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:02.070   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:22:02.130   305   305 E SMD     : DCD ON
,07-05 14:22:05.130   305   305 E SMD     : DCD ON
,07-05 14:22:08.130   305   305 E SMD     : DCD ON
,07-05 14:22:11.130   305   305 E SMD     : DCD ON
,07-05 14:22:11.670   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:11.670   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:11.680   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:11.680   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:11.690  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:11.690  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:11.700   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:22:11.700   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:11.710  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:11.710   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:11.720  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:11.720  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:11.730  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:11.740  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:11.740  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:12.120   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:22:14.130   305   305 E SMD     : DCD ON
,07-05 14:22:17.130   305   305 E SMD     : DCD ON
,07-05 14:22:20.130   305   305 E SMD     : DCD ON
,07-05 14:22:21.730   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:21.740   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:21.740   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:21.740   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:21.750  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:21.760  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:21.770   907  1636 D BatteryService: stay LED for fully charged
,07-05 14:22:21.780   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:21.790  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:21.790   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:21.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:21.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:21.790  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:21.800  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:21.800  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:22.170   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:22:23.130   305   305 E SMD     : DCD ON
,07-05 14:22:26.130   305   305 E SMD     : DCD ON
,07-05 14:22:29.130   305   305 E SMD     : DCD ON
,07-05 14:22:29.140   907   991 I UsageStatsService: User[0] Flushing usage stats to disk
,07-05 14:22:29.220   907  1125 I ApplicationUsage: handleMessage : MSG_UPDATE_USAGE_DB
,07-05 14:22:29.220   907  1125 I ApplicationUsage: Updating Usage Statistics in DB @ 1467721349227
,07-05 14:22:29.230   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.230   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.240   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.240   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 14:22:29.240   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,07-05 14:22:29.240   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 14:22:29.240   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.240   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.240   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.240   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.240   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.240   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.250   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.250   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 14:22:29.250   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
,07-05 14:22:29.250   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 14:22:29.250   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.250   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.250   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.250   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.250   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.250   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.260   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.260   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
07-05 14:22:29.260   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
,07-05 14:22:29.260   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
07-05 14:22:29.260   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.260   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.260   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.260   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.260   907  1102 D TimaService: TIMA: TimaService scheduler is intialized. 
,07-05 14:22:29.260   907  1101 D TimaService: TimaServiceHandler.handleMessage what =1
,07-05 14:22:29.270   907  1102 D TimaService: TIMA: checkEvent, operation: 50000 subject: 10000
,07-05 14:22:29.270   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.270   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.270   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.270   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:29.280   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:29.280   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.280   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.280   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.280   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.280   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.290   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.290   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.290   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:29.290   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.290   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.290   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.290   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.290   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.300   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.300   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.300   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.300   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.310   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.310   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.310   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.310   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.310   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.310   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.310   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.310   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.320   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.320   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.320   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.320   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.320   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.320   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.330   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.330   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.330   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.330   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.330   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.330   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.340   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.340   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.340   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.340   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.340   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.340   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.340   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.340   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.350   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.350   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.350   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.350   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.350   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.350   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.350   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.350   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.360   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.360   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.360   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.360   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.360   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.360   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.360   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.360   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.370   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.370   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.370   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.370   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.370   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.370   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.370   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.370   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.370   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.380   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.380   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.380   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.380   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.380   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.380   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.390   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.390   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.390   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.390   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.390   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.390   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.390   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.390   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.400   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.400   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.400   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.400   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.400   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.400   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.410   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.410   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.410   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.410   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.410   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.410   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.410   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.410   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.410   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.410   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.410   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.410   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.410   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.420   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.420   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.420   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.420   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.420   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.420   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.430   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.430   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.430   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.430   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.430   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.430   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.440   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.440   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.440   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.440   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.440   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.440   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.450   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.450   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.450   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.450   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.450   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.450   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.450   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.450   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-05 14:22:29.460   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.460   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.460   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.460   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.460   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.460   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.460   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.460   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.460   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.460   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.470   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.470   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.470   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.470   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.470   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.470   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.470   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.470   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.470   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.Applicatio,nUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.470   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.470   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.480   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.480   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.480   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.480   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.480   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.480   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.480   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.480   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.480   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.480   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.480   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.490   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.490   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.490   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.490   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.490   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.490   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.490   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.490   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.490   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.500   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.500   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.500   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.500   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.500   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.500   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
,07-05 14:22:29.500   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.500   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.500   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.510   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.510   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.510   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.510   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:22:29.510   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-05 14:22:29.510   907  1125 I ApplicationUsageDb: ::getAppControlDB: Exception to create DB
07-05 14:22:29.510   907  1125 W System.err: java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
,07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
07-05 14:22:29.510   907  1125 W System.err: 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
07-05 14:22:29.510   907  1125 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:22:29.510   907  1125 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,07-05 14:22:29.510   907  1125 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-05 14:22:29.510   907  1125 I ApplicationUsage: Done Updating Usage Statistics in DB @ 1467721349517
,07-05 14:22:31.350   907  1333 E Watchdog: !@Sync 40
,07-05 14:22:31.810   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:31.820   907  1466 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:31.830   907  1466 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:31.830   907  1466 D BatteryService: stay LED for fully charged
,07-05 14:22:31.830   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:31.850  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:31.850  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:31.860  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:31.860   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:31.870  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:31.870   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:31.870  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:31.880  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:31.880  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:31.890  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:32.140   305   305 E SMD     : DCD ON
,07-05 14:22:32.150   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
,07-05 14:22:32.160   907  1102 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,07-05 14:22:32.170   907  1102 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:32.170   907  1102 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,07-05 14:22:32.220   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300
,07-05 14:22:35.140   305   305 E SMD     : DCD ON
,07-05 14:22:38.140   305   305 E SMD     : DCD ON
,07-05 14:22:41.140   305   305 E SMD     : DCD ON
,07-05 14:22:41.870   907  3589 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:41.870   907  3589 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:41.870   907  3589 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:41.880   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:41.880  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:41.890  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:41.900   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:41.900   907  3589 D BatteryService: stay LED for fully charged
,07-05 14:22:41.920  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:22:41.920   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:41.930  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:41.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:41.940  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:41.940  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:41.940  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:42.270   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:22:44.140   305   305 E SMD     : DCD ON
,07-05 14:22:44.230   907  1060 I PowerManagerService: [PWL] Off : 455s ago
,07-05 14:22:47.140   305   305 E SMD     : DCD ON
,07-05 14:22:50.140   305   305 E SMD     : DCD ON
,07-05 14:22:51.930   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:22:51.940   907   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:22:51.940   907   924 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:22:51.940   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:22:51.950  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:22:51.950  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:22:51.960   907   907 I MotionRecognitionService: Plugged
,07-05 14:22:51.970   907   924 D BatteryService: stay LED for fully charged
,07-05 14:22:51.980   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:22:51.980  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,07-05 14:22:51.990  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:52.000  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:22:52.000  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:22:52.000  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:52.000  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:22:52.310   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:22:53.140   305   305 E SMD     : DCD ON
,07-05 14:22:56.140   305   305 E SMD     : DCD ON
,07-05 14:22:59.140   305   305 E SMD     : DCD ON
,07-05 14:23:01.350   907  1333 E Watchdog: !@Sync 41
,07-05 14:23:01.990   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:02.000   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:02.000   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:23:02.000   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:02.010  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:02.020  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:02.020   907   907 I MotionRecognitionService: Plugged
,07-05 14:23:02.020   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:02.030   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:23:02.040  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:02.040  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:02.040  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:02.050  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:02.050  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:02.050  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:02.140   305   305 E SMD     : DCD ON
,07-05 14:23:02.360   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:05.150   305   305 E SMD     : DCD ON
,07-05 14:23:08.150   305   305 E SMD     : DCD ON
,07-05 14:23:11.150   305   305 E SMD     : DCD ON
,07-05 14:23:12.050   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:12.060   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:12.060   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:23:12.060   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:12.070  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:12.080  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:12.080   907   907 I MotionRecognitionService: Plugged
,07-05 14:23:12.080   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:12.090   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:23:12.090  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:12.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:12.090  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:12.100  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:12.100  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:12.100  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:12.410   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:14.150   305   305 E SMD     : DCD ON
,07-05 14:23:17.150   305   305 E SMD     : DCD ON
,07-05 14:23:20.150   305   305 E SMD     : DCD ON
,07-05 14:23:22.120   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:22.130   907  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:22.130   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:23:22.130   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:22.140  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:22.140  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:22.150   907   907 I MotionRecognitionService: Plugged
,07-05 14:23:22.150   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:22.160   907  1359 D BatteryService: stay LED for fully charged
,07-05 14:23:22.180  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:22.190  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:22.190  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:22.190  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:22.190  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:22.200  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:22.460   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:23.150   305   305 E SMD     : DCD ON
,07-05 14:23:26.150   305   305 E SMD     : DCD ON
,07-05 14:23:29.150   305   305 E SMD     : DCD ON
,07-05 14:23:31.360   907  1333 E Watchdog: !@Sync 42
,07-05 14:23:32.150   305   305 E SMD     : DCD ON
,07-05 14:23:32.190   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:32.200   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:32.200   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:23:32.200   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:32.210  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:32.210  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:32.220   907   907 I MotionRecognitionService: Plugged
,07-05 14:23:32.220   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:32.230   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:23:32.240  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:32.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:32.240  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:32.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:32.250  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:32.250  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:32.510   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:35.150   305   305 E SMD     : DCD ON
,07-05 14:23:38.150   305   305 E SMD     : DCD ON
,07-05 14:23:41.160   305   305 E SMD     : DCD ON
,07-05 14:23:42.260   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:42.570   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:44.160   305   305 E SMD     : DCD ON
,07-05 14:23:47.160   305   305 E SMD     : DCD ON
,07-05 14:23:50.160   305   305 E SMD     : DCD ON
,07-05 14:23:52.320   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:23:52.330   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:23:52.330   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:23:52.330   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:23:52.340  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:23:52.340  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:23:52.350   907   907 I MotionRecognitionService: Plugged
,07-05 14:23:52.350   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:23:52.370   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:23:52.380  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:23:52.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:52.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:52.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:23:52.400  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:23:52.400  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:23:52.620   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:23:53.160   305   305 E SMD     : DCD ON
,07-05 14:23:54.230   907  1060 I PowerManagerService: [PWL] Off : 525s ago
,07-05 14:23:56.160   305   305 E SMD     : DCD ON
,07-05 14:23:59.160   305   305 E SMD     : DCD ON
,07-05 14:24:01.360   907  1333 E Watchdog: !@Sync 43
,07-05 14:24:02.160   305   305 E SMD     : DCD ON
,07-05 14:24:02.380   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:02.670   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 301, CUR = 300
,07-05 14:24:05.160   305   305 E SMD     : DCD ON
,07-05 14:24:08.160   305   305 E SMD     : DCD ON
,07-05 14:24:11.160   305   305 E SMD     : DCD ON
,07-05 14:24:12.440   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:12.450   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:12.450   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:24:12.450   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:12.460  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:12.460  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:12.470   907   907 I MotionRecognitionService: Plugged
,07-05 14:24:12.470   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:12.480   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:24:12.490  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:12.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:12.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:12.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:12.500  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:12.500  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:12.720   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:24:14.160   305   305 E SMD     : DCD ON
,07-05 14:24:17.170   305   305 E SMD     : DCD ON
,07-05 14:24:20.170   305   305 E SMD     : DCD ON
,07-05 14:24:22.500   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:22.510   907  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:22.520   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:24:22.520   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:22.530  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:22.530  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:22.540   907   907 I MotionRecognitionService: Plugged
,07-05 14:24:22.540   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:22.540   907  1359 D BatteryService: stay LED for fully charged
,07-05 14:24:22.540  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:22.550  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:22.550  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:22.550  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:22.560  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:22.560  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:22.770   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:24:23.170   305   305 E SMD     : DCD ON
,07-05 14:24:26.170   305   305 E SMD     : DCD ON
,07-05 14:24:29.170   305   305 E SMD     : DCD ON
,07-05 14:24:31.360   907  1333 E Watchdog: !@Sync 44
,07-05 14:24:32.170   305   305 E SMD     : DCD ON
,07-05 14:24:32.570   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:32.570   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:32.570   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:24:32.580   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:32.590  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:32.590  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:32.590   907   907 I MotionRecognitionService: Plugged
,07-05 14:24:32.600   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:32.600   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:24:32.620  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:32.620  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:32.620  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:32.630  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:32.640  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:32.640  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:32.820   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:24:35.170   305   305 E SMD     : DCD ON
,07-05 14:24:38.170   305   305 E SMD     : DCD ON
,07-05 14:24:41.170   305   305 E SMD     : DCD ON
,07-05 14:24:42.630   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:42.640   907  1655 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:24:42.640   907  1655 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:24:42.640   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:24:42.650  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:24:42.660  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:24:42.660   907   907 I MotionRecognitionService: Plugged
,07-05 14:24:42.660   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:24:42.680   907  1655 D BatteryService: stay LED for fully charged
,07-05 14:24:42.690  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:24:42.690  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:42.690  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:42.690  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:24:42.700  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:24:42.700  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:24:42.870   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:24:44.170   305   305 E SMD     : DCD ON
,07-05 14:24:47.170   305   305 E SMD     : DCD ON
,07-05 14:24:50.170   305   305 E SMD     : DCD ON
,07-05 14:24:52.700   907   922 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:24:52.910   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:24:53.180   305   305 E SMD     : DCD ON
,07-05 14:24:56.180   305   305 E SMD     : DCD ON
,07-05 14:24:59.180   305   305 E SMD     : DCD ON
,07-05 14:25:01.370   907  1333 E Watchdog: !@Sync 45
,07-05 14:25:02.180   305   305 E SMD     : DCD ON
,07-05 14:25:02.760   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:02.770   907  1429 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:02.770   907  1429 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:25:02.770   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:02.780  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:02.780  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:02.790   907   907 I MotionRecognitionService: Plugged
,07-05 14:25:02.790   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:02.790   907  1429 D BatteryService: stay LED for fully charged
,07-05 14:25:02.800  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:02.810  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:02.810  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:02.820  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:02.830  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:02.840  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:02.960   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:05.180   305   305 E SMD     : DCD ON
,07-05 14:25:08.180   305   305 E SMD     : DCD ON
,07-05 14:25:09.230   907  1060 I PowerManagerService: [PWL] Off : 600s ago
,07-05 14:25:11.180   305   305 E SMD     : DCD ON
,07-05 14:25:12.820   907  1636 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:12.820   907  1636 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:12.820   907  1636 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:25:12.830   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:12.830  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:12.840  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:12.850   907   907 I MotionRecognitionService: Plugged
,07-05 14:25:12.850   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:12.850   907  1636 D BatteryService: stay LED for fully charged
,07-05 14:25:12.870  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:12.880  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:12.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:12.890  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:12.890  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:12.890  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:13.010   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:14.180   305   305 E SMD     : DCD ON
,07-05 14:25:17.180   305   305 E SMD     : DCD ON
,07-05 14:25:20.180   305   305 E SMD     : DCD ON
,07-05 14:25:22.880   907  1466 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:23.050   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:23.180   305   305 E SMD     : DCD ON
,07-05 14:25:26.180   305   305 E SMD     : DCD ON
,07-05 14:25:29.190   305   305 E SMD     : DCD ON
,07-05 14:25:31.370   907  1333 E Watchdog: !@Sync 46
,07-05 14:25:32.190   305   305 E SMD     : DCD ON
,07-05 14:25:32.940   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:33.100   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:35.190   305   305 E SMD     : DCD ON
,07-05 14:25:38.190   305   305 E SMD     : DCD ON
,07-05 14:25:41.190   305   305 E SMD     : DCD ON
,07-05 14:25:43.000   907  1240 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:43.180   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:44.190   305   305 E SMD     : DCD ON
,07-05 14:25:47.190   305   305 E SMD     : DCD ON
,07-05 14:25:50.190   305   305 E SMD     : DCD ON
,07-05 14:25:53.070   907   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:25:53.070   907   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:25:53.070   907   924 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:25:53.080   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:25:53.090  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:25:53.090  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:25:53.090   907   907 I MotionRecognitionService: Plugged
,07-05 14:25:53.100   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:25:53.100   907   924 D BatteryService: stay LED for fully charged
,07-05 14:25:53.120  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:25:53.120  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:53.140  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:53.150  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:25:53.150  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:25:53.150  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:25:53.190   305   305 E SMD     : DCD ON
,07-05 14:25:53.220   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:25:56.190   305   305 E SMD     : DCD ON
,07-05 14:25:59.190   305   305 E SMD     : DCD ON
,07-05 14:26:01.370   907  1333 E Watchdog: !@Sync 47
,07-05 14:26:02.190   305   305 E SMD     : DCD ON
,07-05 14:26:03.130   907  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:03.140   907  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:03.140   907  1468 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:26:03.140   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:03.150  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:03.150  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:03.160   907   907 I MotionRecognitionService: Plugged
,07-05 14:26:03.160   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:03.170   907  1468 D BatteryService: stay LED for fully charged
,07-05 14:26:03.180  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:03.190  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:03.200  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:03.200  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:03.200  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:03.200  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:03.260   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:05.200   305   305 E SMD     : DCD ON
,07-05 14:26:08.200   305   305 E SMD     : DCD ON
,07-05 14:26:11.200   305   305 E SMD     : DCD ON
,07-05 14:26:13.190   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:13.190   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:13.200   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:26:13.200   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:13.210  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:13.210  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:13.220   907   907 I MotionRecognitionService: Plugged
,07-05 14:26:13.220   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:13.230   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:26:13.240  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:13.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:13.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:13.250  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:13.250  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:13.250  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:13.300   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:14.200   305   305 E SMD     : DCD ON
,07-05 14:26:17.200   305   305 E SMD     : DCD ON
,07-05 14:26:20.200   305   305 E SMD     : DCD ON
,07-05 14:26:23.200   305   305 E SMD     : DCD ON
,07-05 14:26:23.260   907  1359 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:23.260   907  1359 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:23.260   907  1359 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:26:23.270   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:23.280  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:23.280  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:23.280   907   907 I MotionRecognitionService: Plugged
,07-05 14:26:23.290   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:23.290   907  1359 D BatteryService: stay LED for fully charged
,07-05 14:26:23.310  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:23.320  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:23.320  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:23.330  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:23.330  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:23.330  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:23.370   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:26.200   305   305 E SMD     : DCD ON
,07-05 14:26:29.200   305   305 E SMD     : DCD ON
,07-05 14:26:29.240   907  1060 I PowerManagerService: [PWL] Off : 680s ago
,07-05 14:26:31.370   907  1333 E Watchdog: !@Sync 48
,07-05 14:26:32.200   305   305 E SMD     : DCD ON
,07-05 14:26:33.320   907  1689 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:33.330   907  1689 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:33.330   907  1689 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:26:33.330   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:33.340  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:33.340  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:33.350   907   907 I MotionRecognitionService: Plugged
,07-05 14:26:33.350   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:33.360   907  1689 D BatteryService: stay LED for fully charged
,07-05 14:26:33.380  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:33.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:33.390  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:33.390  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:33.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:33.390  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:33.440   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:35.200   305   305 E SMD     : DCD ON
,07-05 14:26:38.200   305   305 E SMD     : DCD ON
,07-05 14:26:41.210   305   305 E SMD     : DCD ON
,07-05 14:26:43.390   907  1655 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:43.480   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:44.210   305   305 E SMD     : DCD ON
,07-05 14:26:47.210   305   305 E SMD     : DCD ON
,07-05 14:26:50.210   305   305 E SMD     : DCD ON
,07-05 14:26:53.210   305   305 E SMD     : DCD ON
,07-05 14:26:53.450   907  1733 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:26:53.450   907  1733 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:26:53.460   907  1733 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:26:53.460   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:26:53.470  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:26:53.470  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:26:53.470   907   907 I MotionRecognitionService: Plugged
,07-05 14:26:53.480   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:26:53.490   907  1733 D BatteryService: stay LED for fully charged
,07-05 14:26:53.490  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:26:53.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:53.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:53.500  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:26:53.500  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:26:53.500  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:26:53.540   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:26:56.210   305   305 E SMD     : DCD ON
,07-05 14:26:59.210   305   305 E SMD     : DCD ON
,07-05 14:27:01.380   907  1333 E Watchdog: !@Sync 49
,07-05 14:27:02.210   305   305 E SMD     : DCD ON
,07-05 14:27:03.520   907  1429 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:03.590   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:27:05.210   305   305 E SMD     : DCD ON
,07-05 14:27:08.210   305   305 E SMD     : DCD ON
,07-05 14:27:11.210   305   305 E SMD     : DCD ON
,07-05 14:27:13.580   907  1459 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-05 14:27:13.580   907  1459 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,07-05 14:27:13.580   907  1459 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
,07-05 14:27:13.590   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-05 14:27:13.600  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-05 14:27:13.600  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-05 14:27:13.610   907   907 I MotionRecognitionService: Plugged
,07-05 14:27:13.610   907   907 I MotionRecognitionService: setPowerConnected  = true
,07-05 14:27:13.620   907  1459 D BatteryService: stay LED for fully charged
,07-05 14:27:13.640  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-05 14:27:13.640  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:13.650  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:13.650  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-05 14:27:13.650  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-05 14:27:13.650  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
,07-05 14:27:13.670   907  3328 D SSRM:n  : SIOP:: AP = 300, PST = 300, CUR = 300
,07-05 14:27:14.210   305   305 E SMD     : DCD ON
,07-05 14:27:17.220   305   305 E SMD     : DCD ON
,07-05 14:27:20.220   305   305 E SMD     : DCD ON
,TIME-OUT KILL (timeout was 1400000ms),07-05 14:27:22.510  7919  7919 D AndroidRuntime: 
07-05 14:27:22.510  7919  7919 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-05 14:27:22.510  7919  7919 D AndroidRuntime: CheckJNI is OFF
07-05 14:27:22.510  7919  7919 D AndroidRuntime: readGMSProperty: start
07-05 14:27:22.510  7919  7919 D AndroidRuntime: readGMSProperty: already setted!!
07-05 14:27:22.510  7919  7919 D AndroidRuntime: readGMSProperty: end
07-05 14:27:22.510  7919  7919 D AndroidRuntime: addProductProperty: start
07-05 14:27:22.750  7919  7919 E AffinityControl: AffinityControl: registerfunction enter
07-05 14:27:22.790  7919  7919 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
07-05 14:27:22.810   907  1429 D PackageManager: START PACKAGE DELETE: observer{818329422}
07-05 14:27:22.810   907  1429 D PackageManager: pkg{<packageName>}
07-05 14:27:22.810   907  1429 D PackageManager: user{0}
07-05 14:27:22.810   907  1429 D PackageManager: caller{2000}
07-05 14:27:22.810   907  1429 D PackageManager: flags{2}
07-05 14:27:22.820   907  1429 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-05 14:27:22.820   907  1429 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-05 14:27:22.820   907  1429 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-05 14:27:22.820   907  1429 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:22.820   907  1429 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-05 14:27:22.820   907  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-05 14:27:22.820   907  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-05 14:27:22.820   907  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-05 14:27:22.820   907  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
07-05 14:27:22.820   907  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
07-05 14:27:22.820   907  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
07-05 14:27:22.820   907   994 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-05 14:27:22.820   907   994 I ActivityManager: Killing 7114:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-05 14:27:22.830   907   994 I ActivityManager:   Force finishing activity ActivityRecord{3673af94 u0 com.test.thalitest/.MainActivity t41}
07-05 14:27:22.830   907   994 D FocusedStackFrame: Set to : 0
07-05 14:27:22.850   267   330 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
07-05 14:27:22.850   267  1437 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
07-05 14:27:22.850   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:27:22.850   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:27:22.850   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:27:22.850   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:27:22.940   907  1064 W PackageSettings: Skipping PackageSetting{1bcaeac7 com.example.hello/10078} due to missing metadata
07-05 14:27:22.960   907  3328 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:27:22.970   907  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-05 14:27:23.030  1492  1492 I art     : Explicit concurrent mark sweep GC freed 11317(678KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 20MB/33MB, paused 668us total 59.236ms
07-05 14:27:23.080   907  3180 E libprocessgroup: failed to kill 1 processes for processgroup 7114
07-05 14:27:23.080  6821  6821 I art     : Explicit concurrent mark sweep GC freed 487(53KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 15MB/20MB, paused 444us total 95.354ms
07-05 14:27:23.100  6874  6874 I art     : Explicit concurrent mark sweep GC freed 4548(230KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 583us total 35.422ms
07-05 14:27:23.100   907  1058 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
07-05 14:27:23.110   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 14:27:23.110  3901  3901 I art     : Explicit concurrent mark sweep GC freed 5386(298KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 491us total 28.880ms
07-05 14:27:23.120   907  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-05 14:27:23.120  1870  2326 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-05 14:27:23.120  1725  1725 E SamsungIME: mOCRHelper is null
07-05 14:27:23.120   907  1145 V NetworkStats: performPollLocked(flags=0x3)
07-05 14:27:23.120   907  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:27:23.130   907  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-05 14:27:23.130   907  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-05 14:27:23.130   907  1145 V NetworkStats: performPollLocked() took 12ms
07-05 14:27:23.130   907  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:27:23.130  1409  1409 D RegisteredServicesCache: empty dynamic service
07-05 14:27:23.130   907  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-05 14:27:23.140  2523  2523 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
07-05 14:27:23.140  2523  2523 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1467721643142
07-05 14:27:23.150  2523  2523 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
07-05 14:27:23.170   907  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:27:23.170   907  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-05 14:27:23.170  2523  2523 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
07-05 14:27:23.220   305   305 E SMD     : DCD ON
07-05 14:27:23.230  5212  5212 I art     : Explicit concurrent mark sweep GC freed 829(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 26.292ms total 184.867ms
07-05 14:27:23.230  2452  2452 I art     : Explicit concurrent mark sweep GC freed 35250(2024KB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 24MB/32MB, paused 851us total 235.178ms
07-05 14:27:23.240   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
07-05 14:27:23.250   907   907 I art     : Explicit concurrent mark sweep GC freed 63389(5MB) AllocSpace objects, 126(2017KB) LOS objects, 30% free, 37MB/53MB, paused 1.835ms total 163.150ms
07-05 14:27:23.250   907  1064 I art     : WaitForGcToComplete blocked for 147.122ms for cause Explicit
07-05 14:27:23.250   907   907 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
07-05 14:27:23.250  2452  2461 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-05 14:27:23.260   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
07-05 14:27:23.270   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
07-05 14:27:23.280   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 14:27:23.280   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 14:27:23.290   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
07-05 14:27:23.290   907  1655 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-05 14:27:23.290   907  1655 D SecContentProvider2: mCursor = null
07-05 14:27:23.290   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
07-05 14:27:23.300   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 14:27:23.310   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
07-05 14:27:23.320   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
07-05 14:27:23.330   907   991 D EnterpriseDeviceManagerService: Package has changed for user 0
07-05 14:27:23.330   907   991 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
07-05 14:27:23.330   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
07-05 14:27:23.330   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 14:27:23.330  2523  2523 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
07-05 14:27:23.340   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
07-05 14:27:23.340  2523  2523 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
07-05 14:27:23.340   907  3589 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
07-05 14:27:23.340   907  3589 D ActivityManager: com.sec.esdk.elm, Starting
07-05 14:27:23.340   907  3589 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.340   907  3589 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.340   907  3589 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.340   907  3589 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.350   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
07-05 14:27:23.350   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 14:27:23.350   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
07-05 14:27:23.350   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.350   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 14:27:23.350   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
07-05 14:27:23.360   907   907 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
07-05 14:27:23.360   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
07-05 14:27:23.360   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 14:27:23.360   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 14:27:23.370   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
07-05 14:27:23.370   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
07-05 14:27:23.370   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
07-05 14:27:23.380   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 14:27:23.380   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
07-05 14:27:23.390  7948  7948 E Zygote  : MountEmulatedStorage()
07-05 14:27:23.390  7948  7948 I libpersona: KNOX_SDCARD checking this for 10116
07-05 14:27:23.390  7948  7948 E Zygote  : v2
07-05 14:27:23.390  7948  7948 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:23.390   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 14:27:23.400   907  3589 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7948 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
07-05 14:27:23.400   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-05 14:27:23.410   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.410   907   907 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-05 14:27:23.410   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-05 14:27:23.410  7948  7948 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:27:23.410  7948  7948 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:27:23.410  7948  7948 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-05 14:27:23.430  7948  7948 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:23.430  7948  7948 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:23.440   907   907 D RCPManagerService: PackageReceiver onReceive()
07-05 14:27:23.440   907   907 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
07-05 14:27:23.440   907   907 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.450   907   907 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
07-05 14:27:23.450   907   907 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicy: uID is 10079
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicy: Removed Packageuid is0
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-05 14:27:23.450   907   907 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
07-05 14:27:23.450   907  3328 D SSRM:aY : MSG_TYPE_APP_REMOVED::
07-05 14:27:23.450   907  1177 D TaskPersister: removeObsoleteFile: deleting file=41_task.xml
07-05 14:27:23.450   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
07-05 14:27:23.450   907   907 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
07-05 14:27:23.460  1431  1431 D SurfaceWidgetView: destroyHardwareResources():981562756
07-05 14:27:23.460   907  1359 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-05 14:27:23.460   907  1359 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-05 14:27:23.460   907  1359 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-05 14:27:23.460   907  1359 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-05 14:27:23.460   907  1359 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-05 14:27:23.460   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.460   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
07-05 14:27:23.460   907  1064 I art     : Explicit concurrent mark sweep GC freed 9582(482KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 37MB/53MB, paused 15.564ms total 211.941ms
07-05 14:27:23.460  1431  1431 D Launcher: onRestart, Launcher: 831175093
07-05 14:27:23.460  7948  7948 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
07-05 14:27:23.460  1431  1431 D Launcher: onStart, Launcher: 831175093
07-05 14:27:23.460  1431  1431 D Launcher.HomeView: onStart
07-05 14:27:23.460  1431  1431 V ActivityThread: updateVisibility : ActivityRecord{2d062f96 token=android.os.BinderProxy@3a6ebb2e {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-05 14:27:23.470  1755  1768 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-05 14:27:23.470  1755  2065 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
07-05 14:27:23.470  1755  2065 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
07-05 14:27:23.480   267   267 I SurfaceFlinger: id=15 createSurf (1080x1920),1 flag=4, Mauncher
07-05 14:27:23.480   907  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:27:23.480   907  1056 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
07-05 14:27:23.490   907  1058 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-05 14:27:23.490   907  1058 D PointerIcon: setMouseCustomIcon IconType is same.101
07-05 14:27:23.490   907  1058 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-05 14:27:23.490   907  1058 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-05 14:27:23.490   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.490   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
07-05 14:27:23.500   907   922 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
07-05 14:27:23.500   907   922 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7114 uid 10079
07-05 14:27:23.500  7948  7948 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
07-05 14:27:23.500   907  7965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-05 14:27:23.510  7948  7948 D elm:14491: ELMEngine.ELMEngine( context ).
07-05 14:27:23.510   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.510  7948  7948 D elm:14491: MDMBridge.setEnterpriseBridge()
07-05 14:27:23.510   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.510   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
07-05 14:27:23.510   907  1472 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
07-05 14:27:23.510   907  1472 D ActivityManager: caller:android.app.ApplicationThreadProxy@1201f088, r.packageName :com.sec.esdk.elm
07-05 14:27:23.520  7948  7948 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
07-05 14:27:23.520   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.520   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
07-05 14:27:23.520  3954  3954 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-05 14:27:23.530  7948  7948 D elm:14491: ElmAgentService : onCreate()
07-05 14:27:23.530  3954  3954 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-05 14:27:23.530  3954  3954 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-05 14:27:23.530  3954  3954 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-05 14:27:23.530  3954  3954 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-05 14:27:23.530  3954  3954 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-05 14:27:23.530  3954  3954 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-05 14:27:23.530  3954  3954 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-05 14:27:23.530  3954  3954 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-05 14:27:23.530  7948  7967 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-05 14:27:23.530  7948  7967 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-05 14:27:23.530  7948  7967 D elm:14491: MDMBridge.getInstance()
07-05 14:27:23.530  7948  7967 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 14:27:23.530  6058  6058 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-05 14:27:23.530  6058  6058 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-05 14:27:23.530  6058  6058 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
07-05 14:27:23.530  7948  7967 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
07-05 14:27:23.550  6714  6714 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-05 14:27:23.550  6714  6714 I PCWCLIENTTRACE_PushUtil: sales region : global
07-05 14:27:23.550  6714  6714 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-05 14:27:23.550  6714  6714 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.550   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
07-05 14:27:23.560  7948  7948 D elm:14491: ElmAgentService : onDestroy().
07-05 14:27:23.560   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
07-05 14:27:23.570   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
07-05 14:27:23.570   907  1468 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
07-05 14:27:23.570   907  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ddb2da3, r.packageName :com.sec.android.app.shealth
07-05 14:27:23.570   907  1058 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4a811c7 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t40} time:1511025
07-05 14:27:23.570   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.570   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
07-05 14:27:23.580   907  1064 D PackageManager: delete codoeFile: 
07-05 14:27:23.580   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
07-05 14:27:23.580   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
07-05 14:27:23.580   907  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-05 14:27:23.580   907  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
07-05 14:27:23.580   907  1459 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-05 14:27:23.580   907  1459 D ActivityManager: com.sec.spp.push, Starting
07-05 14:27:23.580   907  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.580   907  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.580   907  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.580   907  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-05 14:27:23.590   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.590   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.590   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
07-05 14:27:23.590   907  1064 D PackageManager: result of delete: 1{818329422}
07-05 14:27:23.590  7919  7919 D AndroidRuntime: Shutting down VM
07-05 14:27:23.600   907   991 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-05 14:27:23.600   907   991 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-05 14:27:23.600   907   991 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-05 14:27:23.600   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.600   907   991 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-2/base.apk
07-05 14:27:23.610   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-05 14:27:23.610   907  1064 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-05 14:27:23.610   907  1064 D PackageManager: userId{-1}
07-05 14:27:23.610   907  1064 D PackageManager: andCode{true}
07-05 14:27:23.610   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
07-05 14:27:23.610   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.610   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
07-05 14:27:23.620   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.620   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
07-05 14:27:23.630   907  1377 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-05 14:27:23.630   907  1377 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4276, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-05 14:27:23.630   907  1377 D BatteryService: online:4, current avg:300, charge type:2, power sharing:false, high voltage charger:false, capacity:280000, current_now:300
07-05 14:27:23.630   907  1377 D BatteryService: stay LED for fully charged
07-05 14:27:23.630   907   907 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-05 14:27:23.630  7970  7970 E Zygote  : MountEmulatedStorage()
07-05 14:27:23.630  7970  7970 E Zygote  : v2
07-05 14:27:23.630  7970  7970 I libpersona: KNOX_SDCARD checking this for 10043
07-05 14:27:23.630  7970  7970 I libpersona: KNOX_SDCARD not a persona
07-05 14:27:23.630   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.630   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:27:23.630   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
07-05 14:27:23.630   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.630   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-05 14:27:23.640   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.640   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:27:23.640   907   991 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
07-05 14:27:23.640   907  1459 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7970 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-05 14:27:23.640   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.640   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-05 14:27:23.640   907   991 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
07-05 14:27:23.640   907  1064 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
07-05 14:27:23.640   907   991 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-05 14:27:23.650  7970  7970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-05 14:27:23.650  7970  7970 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-05 14:27:23.650  7970  7970 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-05 14:27:23.650   907   991 D UsbSettingsManager: clearDefaults: com.test.thalitest
07-05 14:27:23.650   907   991 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
07-05 14:27:23.660   907   907 I MotionRecognitionService: Plugged
07-05 14:27:23.660   907   907 I MotionRecognitionService: setPowerConnected  = true
07-05 14:27:23.660  3237  3237 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-05 14:27:23.660  1189  1189 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-05 14:27:23.660  3237  3321 D HeadsetStateMachine: Disconnected process message: 10
07-05 14:27:23.660  1189  1189 D KeyguardUpdateMonitor: handleBatteryUpdate
07-05 14:27:23.660  1189  1189 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-05 14:27:23.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:23.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:23.660  1189  1189 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-05 14:27:23.670   907  1466 I ActivityManager: Killing 5607:com.android.calendar/u0a172 (adj 15): emptyCount ##41
07-05 14:27:23.680  7970  7970 D TimaKeyStoreProvider: TimaSignature is unavailable
07-05 14:27:23.690  7970  7970 D ActivityThread: Added TimaKeyStore provider
07-05 14:27:23.700  7970  7970 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
07-05 14:27:23.710   907  3328 D SSRM:n  : SIOP:: AP = 310, PST = 301, CUR = 300
07-05 14:27:23.730  7970  7970 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
07-05 14:27:23.730  7970  7970 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
07-05 14:27:23.740   907   922 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-05 14:27:23.740   907   922 D ActivityManager: caller:android.app.ApplicationThreadProxy@149f8dc9, r.packageName :com.samsung.android.app.galaxyfinder
07-05 14:27:23.740  7970  7970 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:27:23.740  7970  7970 D SPPClientService: PushLog.txt file is not deleted.
07-05 14:27:23.740  7970  7970 D SPPClientService: ============PushLog. stop!
07-05 14:27:23.760  6782  6782 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
07-05 14:27:23.760  6782  6782 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
07-05 14:27:23.760   907  1377 I ActivityManager: Killing 6678:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
07-05 14:27:23.770   907  1459 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
07-05 14:27:23.770   907  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@1798ccce, r.packageName :com.android.providers.contacts
07-05 14:27:23.820  5854  5854 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.820   907  1733 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
07-05 14:27:23.820   907  1733 D ActivityManager: caller:android.app.ApplicationThreadProxy@231802fc, r.packageName :com.android.mms
07-05 14:27:23.820   907  1429 I TactileAssist: enable value -1
07-05 14:27:23.820   907  1429 I TactileAssist: internal enable value -1
07-05 14:27:23.820   907  1429 I TactileAssist: intensity value -1
07-05 14:27:23.820   907  1429 I TactileAssist: saveAppList value true
07-05 14:27:23.830  5854  7988 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
07-05 14:27:23.830  5854  7988 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
07-05 14:27:23.830   907  1429 I TactileAssist: List of disabled apps :
07-05 14:27:23.830   907  1468 D SettingsProvider: name = reading_mode_app_list
07-05 14:27:23.830  6803  6803 D Compatibility: onReceive() it will make start service
07-05 14:27:23.830   907  1459 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
07-05 14:27:23.830   907  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@5f8e7da, r.packageName :com.sec.android.app.soundalive
07-05 14:27:23.840   907  1240 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox

```
